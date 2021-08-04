## What Isn't Working

 A blogging platform or framework should provide the following benefits.

1. Authors should be presented with a simple, managed solution. Dependencies, hosting, configuration, etc. should not be the author's concern.
1. Too much customizability distracts authors from writing. The important thing is to simply get content published.
1. Authors should be able to write in a familiar, simple format. The workflow and organization of files should be up to the author.
1. Prompts to login, signup, subscribe, etc. should not be shoved in readers' faces.
1. Readers should not have advertisements detract from the content they wish to read. Internal ads e.g. suggested articles are no exception.
1. Readers should not have to pay to read articles.
1. Readers' privacy should be valued.

| | Simple | Content-centric | Familiar format | No prompts | Ad-free | No paywalls | Privacy
--------- |:-:|:-:|:-:|:-:|:-:|:-:|:-:
**Moyen** | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓
SSG*      |   |   | ✓ | ✓ | ✓ | ✓ | ✓
Medium    | ✓ | ✓ |   |   |   |   |
Substack  | ✓ | ✓ |   | ✓ | ✓ | ✓ |
Ghost     | ✓ |   |   |   | ✓ |   |
Blogger   | ✓ |   |   |   | ✓ | ✓ |
Wordpress |   |   |   | ✓ | ✓ | ✓ | ✓

&ast; Static site generators (SSG) create fully static sites from template files. This allows identical files to be served to each client and requires no server-side logic. Popular static site generators include Hugo, Jekyll, Gatsby, and [many more](https://jamstack.org/generators/).

## Website Usability

For frequent readers of Internet articles and blogs, one of the above criteria is particularly important. Websites are becoming larger. This is no secret as has been covered many times before (see [this](https://idlewords.com/talks/website_obesity.htm), [this](https://httparchive.org/reports/state-of-the-web?start=earliest&end=latest&view=list), [this](https://motherfuckingwebsite.com/), and [this](https://medium.com/hackernoon/on-the-web-size-matters-e52ac0f5fdbe)). Ironically, that last article, hosted on Medium, downloads over 4MB worth of resources. That's considerably larger than Leo Tolstoy's masterpiece [War and Peace](https://en.wikipedia.org/wiki/War_and_Peace), clocking in at roughly 3MB.

In addition to websites becoming larger, they are becoming less user-friendly. Often, before being able to read an article, one has to wade through a barrage of cookie acceptance modals, prompts to login, signup, or subscribe, paywalls blocking content, banners promoting suggested articles, and advertisements. The web is indeed in a sad state.

## Values

1. ### Passive, augmentative; not onerous, supervised

    Moyen should be an addition to one's local documentation. Documents are written, owned, and updated as the author sees fit without the involvement of Moyen. Publishing via Moyen should be a simple, near-effortless afterthought.

1. ### Simple, austere; not decorative

    Moyen should be a simple means of publishing one's work. As such, minimal time and effort should be spent customizing aesthetics and function of the resultant website. For readers, the website should be lightweight and fast meaning minimal downloaded resources and JavaScript.

1. ### Compatible, generalized; not bespoke

    Moyen should work with as many pre-existing workflows as possible. Moyen should require as little setup as possible and include minimal bespoke syntax or configuration.

1. ### Private, unintrusive; not invasive

    Moyen should value the privacy of its authors and readers alike. No third party cookies, no social authentication, minimal analytics.

## Features

1. Upload from a directory of existing markdown files and images
1. Simple, functional styling means blogs are readable on mobile and desktop
1. No third party script or cookies, ads, trackers, etc.
1. Minimally customizable; focus on simply writing
1. What you see in a local editor or file browser is what is published

## Pricing

I would, ideally, like to keep this free. If costs exceed a nominal fee each month, I'll look into monetization. Options, in order of preference, include the following.

1. Accept donations.
1. Limit future features (custom theme, custom domain) to paid authors.
1. Limit storage space (documents & images) for free accounts and charge monthly for tiers of storage.
1. Limit writes (creating, updating, and deleting articles) for free accounts and charge monthly for unlimited writes.

## Open Source

While I gauge interest and costs, Moyen will remain closed source. If a business model is required (see above), closed source keeps my options open.

Most peripheral tools e.g. clients developed for Moyen are open source. See the [Moyen GitHub organization](https://github.com/moyen-blog) for examples.
