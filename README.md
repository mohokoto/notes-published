# notes-published

Public intermediate artifact holding rendered, published Notes as
static HTML (`notes/{slug}/index.html`). Rendering happens once, at
publish time — nothing downstream of this repo does Markdown parsing.

Not meant to be browsed directly. `mohokoto.github.io` syncs from here
and is the actual public site. The canonical source (including Drafts
and revision history) lives in the private
[`content-drafts`](https://github.com/mohokoto/content-drafts) repo —
this repo only ever contains currently-Published content.

## Context

- [Technical design](https://github.com/mohokoto/mohokoto.github.io/issues/1)
- [Implementation tracking](https://github.com/mohokoto/mohokoto.github.io/issues/2)
- [This repo's setup](https://github.com/mohokoto/mohokoto.github.io/issues/3)
