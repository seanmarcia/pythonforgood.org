# Codeforgood.org

This repository holds [Codeforgood.org](http://Codeforgood.org), a site built on [GitHub Pages](https://pages.github.com/).

## Running Locally for Development

First, install dependencies with bundler:

```
bundle install
```

Then, run the site with `jekyll`:

```
jekyll serve
```

The site will be available at [http://localhost:4000](http://localhost:4000).

## Team Leads: Add or Update your project in the Yearbook

Add or update your project on this page by submitting a pull request to the Codeforgood.org repository:

* Pull down or fork the repository
* Create a branch with the year and your team name
* Add the project information to `yearbook.md` according to the template. Be sure to place it under the project's year.
* Push and make a pull request


```
##### Title of the Project

Description of the project and the organization the project was built for. If
possible, mention the impact the project has had for the original organization
or others who have begun using it.

{% include github-block.html
  href="url-to-repository"
  team="team-lead-github-username|pipe-separated|team-member|github|usernames"
%}
```
