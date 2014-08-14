---
title: gum
go:
  pkg: willnorris.com/go/gum
  vcs: git
  src: https://github.com/willnorris/gum
excerpt: Personal short URL resolver
---
Gum is a personal short URL resolver written in Go.

Gum is a short URL resolver for personal content (blog posts, photos, checkins,
etc).  Short URLs typically consist of a content type (normally a single
letter) plus an identifier for the resource (often a date-based encoded ID).
Exact content types and identifier format are configurable, but the overall
design is strongly modelled after [Whistle][].

This is the URL resolver I run behind <https://willnorris.com/>.  While I'll
probably do my best to keep things configurable, reusability is not a primary
goal for now.  I'm primarily developing it for use on my personal website, so
may occasionally hardcode some things that limit others' use.

[Whistle]: http://tantek.com/w/Whistle

## License ##

Gum is copyright Google, but is not an official Google product.  It is
available under a [BSD License][].

[BSD License]: https://github.com/willnorris/gum/blob/master/LICENSE
