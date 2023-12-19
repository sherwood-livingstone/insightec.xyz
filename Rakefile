# frozen_string_literal: true

require 'html-proofer'

task :test do
  sh 'bundle exec jekyll build'
  proofer = HTMLProofer.check_directory(
    './_site/',
    check_html: true,
    check_external_hash: false,
    hydra: { max_concurrency: 10 },
    url_ignore: [%r{https://developer.insightec.xyz}, %r{https://docs.insightec.xyz}, %r{https://help.insightec.xyz}],
    ignore_files: [%r{/community/}, %r{/stories/}],
    ignore_status_codes: [429]
  )
  token = ENV.fetch('GITHUB_TOKEN', nil)
  unless token.nil?
    proofer.before_request do |request|
      request.options[:headers]['Authorization'] = "Bearer #{token}" if request.base_url == 'https://insightec.xyz'
    end
  end
  proofer.run
end
