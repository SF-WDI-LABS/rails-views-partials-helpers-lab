# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> Rails Views & Helpers Training

**Objective:** Refactor forms, links, and redirects in this application to take advantage of Rails partials, view helpers (`form_for` and `link_to`), and path prefixes.

## Getting Started

1. Fork this repo, and clone it to your local machine.  

2. Change directories into `rails-views-helpers-training`, and `bundle install`.  

3. Run `rails db:create db:migrate db:seed` (or `rails db:setup`).  

4. Start your Rails server, and you're ready to go!

## Steps to Refactor

1. Find two `<a></a>` tags in the views, and refactor them to use the <a href="http://apidock.com/rails/ActionView/Helpers/UrlHelper/link_to" target="_blank">`link_to` helper</a>.
  > Tip: Use Command + Shift + F to bring up an interface to search all project files in Atom or Sublime.

2. Find one form in this application, and refactor it to use the <a href="http://guides.rubyonrails.org/form_helpers.html#binding-a-form-to-an-object" target="_blank">`form_for` helper</a>.

3. Refactor othe recipes new and edit forms to use a <a href="http://guides.rubyonrails.org/layouts_and_rendering.html#using-partials" target="_blank">partial</a>.

4. While you're at it, refactor the Bootstrap navbar in the application layout to use a partial (or named yield).

5. Find one redirect (`redirect_to`) in the **controller methods**, and refactor it to use <a href="http://guides.rubyonrails.org/routing.html#prefixing-the-named-route-helpers" target="_blank">path prefixes</a>.

Refer to the [solution branch](/../../tree/solution) if needed for guidance.
