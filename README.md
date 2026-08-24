# xinzhirao.github.io

Personal academic website of **Xinzhi Rao** (Ph.D. candidate in Information Systems and Operations Management, Warrington College of Business, University of Florida), built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and hosted on GitHub Pages.

## Where to edit

| What | File |
|------|------|
| Site title, sidebar (name, bio, location, employer, email, Google Scholar / LinkedIn / GitHub links) | `_config.yml` (the `author:` block) |
| Home page: bio and the Research section (papers with collapsible abstracts) | `_pages/about.md` |
| CV page | `_pages/cv.md` |
| Downloadable CV (replace the file with a new version to update the download button) | `files/CV_Xinzhi_Rao.pdf` |
| Sidebar photo | `images/profile.jpg` |
| Top navigation menu | `_data/navigation.yml` |
| Favicon (initials "XR") | `images/favicon*.png`, `images/favicon.svg`, `images/favicon.ico` |

Every push to the default branch is rebuilt automatically by GitHub Pages (usually within a minute or two).

## Adding a paper

In `_pages/about.md`, copy one of the existing `<div class="paper"> ... </div>` blocks and edit the title, coauthors, status, venue line, link, and abstract. Then add a matching bullet to `_pages/cv.md`.

## Local preview (optional)

Follow the [Academic Pages instructions](https://github.com/academicpages/academicpages.github.io#running-locally): install Ruby and Bundler, then run `bundle install` and `bundle exec jekyll serve -l -H localhost` and open <http://localhost:4000>. A Docker setup (`docker-compose up`) is also included.

## Credits

Theme: [Academic Pages](https://github.com/academicpages/academicpages.github.io), a fork of [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) (MIT License, see `LICENSE`).
