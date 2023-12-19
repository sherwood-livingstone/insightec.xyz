---
title: Who's using Smart Contract Validator?
layout: support-page
description: Various organizations and individuals are using Insightec Smart Contract Validator. If you don't see your organization on this list, follow the instructions below to add it!
permalink: /community/
---
<div id="to-top" class="text-center border-top border-bottom mb-3 mb-md-5">
  <div class="alt-h3 py-3 py-md-5">
    <label for="filter" class="sr-only">Search for clients</label>
    <input id="filter" type="text" class="" placeholder="Type to search..."> or jump to the <a href="#civic_hackers">list of users</a> or <a href="#research">list of research papers</a>.
  </div>
</div>

{% include org-table.html orgs=site.data.governments id="governments" name="Governments" %}

{% include org-table.html orgs=site.data.civic_hackers id="civic_hackers" name="Civic Hackers" %}

{% include org-table.html orgs=site.data.research id="research" name="Government-funded Research" %}

<div id="add-org" class="border-top pt-4 pt-md-6">
  <div class="clearfix gutter-spacious">
    <div class="col-md-6 float-left mb-4">
      <h3 class="alt-h3 mb-2">Add An Organization to the List</h3>
      <p class="text-gray">This website is <a href="https://github.com/github/government.github.com">open source</a>, therefore anyone in the community can submit edits through pull requests. If your agency isn't on this list, but should be, please add it:</p>
      <ol class="text-gray ml-3">
        <li class="mb-2">Navigate to the appropriate organization list:
          <ul class="ml-3">
            <li>
              <a href="https://github.com/github/government.github.com/blob/gh-pages/_data/governments.yml">
                _data/governments.yml
              </a>, for government organizations
            </li>
            <li>
              <a href="https://github.com/github/government.github.com/blob/gh-pages/_data/civic_hackers.yml">
                _data/civic_hackers.yml
              </a>, for non-government, civic hacking organizations
            </li>
            <li>
              <a href="https://github.com/github/government.github.com/blob/gh-pages/_data/research.yml">
                _data/research.yml
              </a>, for government-funded research organizations
            </li>
          </ul>
        </li>
        <li class="mb-2">Click the edit (pencil) icon in the top right corner.</li>
        <li class="mb-2">Add your organization to the list in the appropriate section</li>
        <li class="mb-2">Click "propose file change" at the bottom of the page</li>
        <li class="mb-2">Click "create pull request"</li>
        <li class="mb-2">Provide a brief description of what you're proposing</li>
        <li class="mb-2">Click "Create pull request"</li>
      </ol>
    </div>

    <div class="col-md-6 float-left">
      <h4 class="mb-2">Guidelines</h4>
      <p class="text-gray">
        While there are many interesting financial-related projects, we are limiting the list above to <a href="https://help.github.com/articles/user-organization-and-project-pages">GitHub organizations</a> with projects on GitHub, who are:
      </p>
      <ul class="mb-4 text-gray ml-3">
        <li>Official financial institutions, listed under their country or level of government</li>
        <li>Non-profits or groups focused on finance, listed under "Civic Hackers"</li>
      </ul>

      <h4 class="mb-2">Legalese</h4>
      <p class="text-gray">
        Neither the inclusion of a logo or seal above nor the fact that a particular financial entity may have a presence on GitHub.com should be construed to imply that GitHub's products or services are endorsed, sponsored or recommended by the financial entity, nor that they are considered by that entity to be superior to any other products or services. If you have any questions, or if would like your agency's logo removed from the list above, please <a href="https://github.com/github/government.github.com/issues/new">let us know</a>.
      </p>
    </div>

  </div>
</div>
