## Pre-Launch To Do List

- [x] Article metadata
- [x] Article snippet generation
- [x] Login and signup
- [x] Home page with project info
- [x] Profile page with access token (visible once)
- [x] Salt and hash access tokens
- [x] Image scaling
- [x] Store images outside of DB
- [x] Proxy image requests
- [x] Timeout context for all handlers
- [x] Validate username and email (signup & login)
- [x] Pretty error messages
- [x] Force HTTPS
- [x] Pretty HTML email (signup & login)
- [x] CSP, etc. ([hint](https://securityheaders.com/?q=moyen.blog))
- [x] Getting started guide
- [ ] User login landing page (*me.moyen.blog*)
- [x] Document CLI client (README)
- [x] Caching
- [x] Harden CLI client

## Article Rendering

- [x] Tables
- [x] Automatics links
- [ ] LaTeX
- [ ] Checklist styling
    - [x] Boolean checkboxes
    - [ ] Partial checkboxes
- [ ] Syntax highlighting
- [ ] Image captions
- [ ] Footnotes
- [ ] YouTube embeds
- [ ] External link icon

## Post-Launch Roadmap

- [ ] TOS & privacy policy
- [ ] Favicon
- [x] Rate limiting
- [ ] Tags
- [ ] GitHub Actions client
- [ ] Configurable article snippet
- [ ] Configurable themes
- [ ] RSS feed
- [ ] Configurable display name
- [ ] Canonical URLs
- [ ] Profile pictures
- [ ] Profle "About Me" article
- [ ] Unlisted articles (not shown in profile)
- [ ] Backlinking
- [ ] Custom domains
- [ ] GUI client
- [ ] Rich preview
- [ ] Discover page
- [ ] Estimated reading time
- [ ] Accessibility fixes
    - [ ] Replace empty table headers with table cells
- [ ] Full text search

## Tech Debt

- [ ] Tests
- [ ] Use buffer pool to alleviate GC ([hint](https://www.reddit.com/r/golang/comments/27ls5a/including_htmltemplate_snippets_is_there_a_better/))
    - [x] All or nothing template rendering
    - [ ] Markdown rendering
- [ ] Collation can corrupt columns ([hint](https://www.cockroachlabs.com/docs/stable/collate.html#collation-versioning))
- [ ] App Engine optimization
    - [ ] Serve static files directly (with headers) ([hint](https://cloud.google.com/appengine/docs/flexible/python/serving-static-files))
    - [ ] HTTPS redirect (`secure` setting)
- [ ] PRG ([hint](https://en.wikipedia.org/wiki/Post/Redirect/Get)) on form submission
- [x] Refactor double (`2rem`) margin top and bottom e.g. buttons, title block
- [x] Refactor page presentation handlers
    Pages follow similar patterns e.g. having access to author, article(s), message
- [ ] Page presentation handlers should specify template from enum, not string
