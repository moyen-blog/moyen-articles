There is (intentionally) little configuration to tweak with Moyen. For more information on Moyen's design philosophy, see [this article](/Why.md). With that said, here are some ways to improve your experience with Moyen once you've got the basics configured.

## Ignoring Articles

If you'd like to ignore certain files, or directories, create a file named *.moyenconfig* within your article directory. Within this file, add a list of ignore patterns as follows.

```
ignore:
  - my_ignored_file.md
  - *_test.md
```

The configuration file you just created is in YAML format. The list of ignore patterns follows basic [glob pattern matching](https://en.wikipedia.org/wiki/Glob_(programming)).

## Article Metadata

Moyen automatically assigns a title and other metadata to the articles you publish. These are derived from the article's file name, text, etc. Article metadata can be set explicitly by including **YAML front matter** in your article.

YAML front matter is defined at the top of a markdown article. The following example shows the YAML properties supported by Moyen in a valid markdown article.

```
---
title: My Custom Article Title
---

Here is the rest of your article markdown content.
```
