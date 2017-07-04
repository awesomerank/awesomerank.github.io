---
layout: default
title: Awesome Rank for nikgraf/awesome-draft-js
---

<p align="center">
	This list is a copy of <a href="https://github.com/nikgraf/awesome-draft-js">nikgraf/awesome-draft-js</a> with ranks
</p>
---
# Awesome Draft.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★60916](https://github.com/sindresorhus/awesome)

[Draft.js](https://facebook.github.io/draft-js/) is a framework for building rich text editors in React.

**Table of Contents**

- [Community ★869](https://github.com/nikgraf/awesome-draft-js#community)
- [Presentations ★869](https://github.com/nikgraf/awesome-draft-js#presentations)
- [Projects on Top of Draft.js ★869](https://github.com/nikgraf/awesome-draft-js#standalone-editors-built-on-draftjs)
- [Common Utilities ★869](https://github.com/nikgraf/awesome-draft-js#common-utilities)
- [Blog Posts & Articles ★869](https://github.com/nikgraf/awesome-draft-js#blog-posts--articles)
- [Live Demos ★869](https://github.com/nikgraf/awesome-draft-js#live-demos)
- [Usage in Production ★869](https://github.com/nikgraf/awesome-draft-js#usage-in-production)
- [License ★869](https://github.com/nikgraf/awesome-draft-js#license)

## Community

* [Slack channel](https://draftjs.herokuapp.com/)

## Presentations
* [Rich Text Editing with React @ React.js Conf 2016 by Isaac Salier-Hellendag ](https://www.youtube.com/watch?v=feUYwoLhE_4)
* [Rich text editing with Draft.js & DraftJS Plugins by Nik Graf](https://www.youtube.com/watch?v=gxNuHZXZMgs)
* [React Ep. 37: Draftjs by What I Learned Today – Atomic Jolt](https://www.youtube.com/watch?v=0k9suXgCtTA)
* [008 - Draft.js Plugins @ React30](https://www.youtube.com/watch?v=w-PqnpMizcQ)
* [Draft.js at HubSpot by Ben Briggs](http://product.hubspot.com/blog/tech-talk-at-night-react-meetup)
* [Draft.js under the hood - React Melbourne meetup](https://www.youtube.com/watch?feature=player_embedded&v=vOZAO3jFSHI)

## Standalone Editors Built on Draft.js

* [Draft WYSIWYG ★323](https://github.com/bkniffler/draft-wysiwyg) - WYSIWYG editor that with drag&drop, resizing & tooltips.
* [Draft.js Editor ★83](https://github.com/AlastairTaft/draft-js-editor) - A Rich text editor inspired by Medium & Facebook Notes.
* [React-RTE ★1285](https://github.com/sstur/react-rte) - A full-featured textarea replacement similar to CKEditor or TinyMCE.
* [Facebook Notes Clone(ish) ★183 ⏳1Y](https://github.com/andrewcoelho/react-text-editor) - Rich text editor similar to Facebook notes.
* [Megadraft ★375](https://github.com/globocom/megadraft) - A rich text editor with a nice default base of plugins and extensibility.
* [Medium Draft ★820](https://github.com/brijeshb42/medium-draft) - Medium-like rich text editor with a focus on keyboard shortcuts.
* [React-Draft-Wyiswyg](https://github.com/jpuri/react-draft-wysiwyg.git) - A WYISWYG editor, with various text editing options and corresponding HTML generation.
* [Dante 2 ★292](https://github.com/michelson/dante2) - Just another Medium clone built on top of DraftJs.
* [Last Draft ★113](https://github.com/vacenz/last-draft) - A Draft editor built with Draft.js plugins.

## Plugins and Decorators Built for Draft.js

* [Draft.js Plugins ★2058](https://github.com/draft-js-plugins/draft-js-plugins) - A Plugin architecture on top of Draft.js
  - [Emoji](https://www.draft-js-plugins.com/plugin/emoji) - Slack-like emoji support
  - [Stickers](https://www.draft-js-plugins.com/plugin/sticker) - Facebook-like sticker support
  - [Hashtags](https://www.draft-js-plugins.com/plugin/hashtag) - Twitter-like hashtag support
  - [Linkify](https://www.draft-js-plugins.com/plugin/linkify) - Automatically turn links into anchor-tags.
  - [Mentions](https://www.draft-js-plugins.com/plugin/mention) - Twitter-like mention support
  - [Undo](https://www.draft-js-plugins.com/plugin/undo) - Undo & Redo button.
  - [Counter](https://www.draft-js-plugins.com/plugin/counter) - Character, word & line counting.
  - [Autolist ★41](https://github.com/icelab/draft-js-autolist-plugin) - Automatic unordered/ordered list creation.
  - [Block Breakout ★22](https://github.com/icelab/draft-js-block-breakout-plugin) - Break out of block types as you type.
  - [Markdown Shortcuts ★74](https://github.com/ngs/draft-js-markdown-shortcuts-plugin) - Markdown syntax shortcuts.
  - [Single Line ★13](https://github.com/icelab/draft-js-single-line-plugin) - Restrict to a single line of input.
  - [RichButtons ★30](https://github.com/jasonphillips/draft-js-richbuttons-plugin) - Add and customize rich formatting buttons.
  - [Katex ★5](https://github.com/letranloc/draft-js-katex-plugin) - Insert and render LaTeX using Katex.
  - [Mathjax ★12](https://github.com/efloti/draft-js-mathjax-plugin) - Edit math using (La)TeX rendered by Mathjax.
  - [Buttons ★25](https://github.com/vacenz/last-draft-js-plugins)
  - [Color Picker ★25](https://github.com/vacenz/last-draft-js-plugins)
  - [Embed ★25](https://github.com/vacenz/last-draft-js-plugins)
  - [EmojiPicker ★25](https://github.com/vacenz/last-draft-js-plugins)
  - [GifPicker ★25](https://github.com/vacenz/last-draft-js-plugins)
  - [Link ★25](https://github.com/vacenz/last-draft-js-plugins)
  - [Modal ★25](https://github.com/vacenz/last-draft-js-plugins)
  - [Sidebar ★25](https://github.com/vacenz/last-draft-js-plugins)
  - [Toolbar ★25](https://github.com/vacenz/last-draft-js-plugins)
* [Draft.js Gutter](https://github.com/yepnamesjames/draft-js-gutter) - Compliments line number gutter.
* [Draft.js Basic HTML Editor ★61](https://github.com/dburrows/draft-js-basic-html-editor) - Accept html as its input format, and return html to an onChange.
* [Draft.js Prism](https://github.com/SamyPesse/draftjs-prism)- Highlight code blocks using Prism.
* [Draft.js Typeahead ★87](https://github.com/dooly-ai/draft-js-typeahead) - Support for typeahead functionality.
* [Draft Extend ★44](https://github.com/HubSpot/draft-extend) - Build extensible Draft.js editors with configurable plugins and integrated serialization.

## Common Utilities

* [BackDraft.js ★35 ⏳1Y](https://github.com/evanc/backdraft-js) - Function to turn a rawContentBlock into a marked-up string.
* [Draft.js Exporter ★24](https://github.com/rkpasia/draft-js-exporter) - Export and format the content from Draft.js.
* [Draft.js: Export ContentState to HTML ★304](https://github.com/sstur/draft-js-export-html) - Export ContentState to HTML.
* [Redraft ★56](https://github.com/lokiuz/redraft) - Renders the result of Draft.js convertToRaw using provided callbacks, works well with React
* [Draft.js exporter (Ruby) ★4](https://github.com/ignitionworks/draftjs_exporter) - Export Draft.js content state into HTML.
* [Draft.js exporter (Python) ★15](https://github.com/springload/draftjs_exporter) - Library to convert Draft.js raw ContentState to HTML
* [Draft.js AST Exporter ★21](https://github.com/icelab/draft-js-ast-exporter) - Export content into an abstract syntax tree (AST).
* [Draft.js AST Importer ★3](https://github.com/icelab/draft-js-ast-importer)- Emport an abstract syntax tree (AST) output from the companion draft-js-ast-exporter.
* [Draft.js Multidecorators](https://github.com/SamyPesse/draftjs-multidecorators) - Combine multiple decorators.
* [Draft.js SimpleDecorator ★13](https://github.com/Soreine/draft-js-simpledecorator) - Easily create flexible decorators.
* [DraftJS Utils](https://github.com/jpuri/draftjs-utils.git) - Set of utility functions for DraftJS.
* [DraftJs to HTML](https://github.com/jpuri/draftjs-to-html.git) - Library for generating HTML for DraftJS editor content.
* [Draft Convert ★144](https://github.com/HubSpot/draft-convert) - Extensibly serialize & deserialize Draft.js ContentState with HTML.
* [HTML to DraftJS ★23](https://github.com/jpuri/html-to-draftjs) - Convert plain HTML to DraftJS Editor content.
* [Draft.js Exporter (Go) ★12](https://github.com/ejilay/draftjs) - Export Draft.js content state into HTML.
* [React Native Draft.js Render ★106](https://github.com/globocom/react-native-draftjs-render) - A React Native render for Draft.js model.

## Blog Posts & Articles

* [Facebook open sources rich text editor framework Draft.js](https://code.facebook.com/posts/1684092755205505/facebook-open-sources-rich-text-editor-framework-draft-js/)
* [This Blog Post Was Written Using Draft.js](https://dev.to/ben/this-blog-post-was-written-using-draftjs)
* [How Draft.js Represents Rich Text Data](https://medium.com/@rajaraodv/how-draft-js-represents-rich-text-data-eeabb5f25cf2#.7gd8psdvi)
* [A Beginner’s Guide to Draft.js](https://medium.com/@adrianli/a-beginner-s-guide-to-draft-js-d1823f58d8cc#.uufeulpl5)
* [Implementing todo list in Draft.js](http://bitwiser.in/2016/08/31/implementing-todo-list-in-draft-js.html)
* [Draft.js Pieces](https://cannibalcoder.com/2016/12/02/draft-js-pieces/)
* [Learning Draft.js](https://reactrocket.com/series/learning-draft-js/) - Series of blog posts on how to develop with draft.js

## Live Demos

* [REACTing Codepen Comment Editor - Draft.js](http://codepen.io/rkpasia/full/jqbrpq)
* [Draft.js Examples - A Heroku app w/ several example Draft.js Editors from different projects](http://draftjs-examples.herokuapp.com/)
* [Draft-js Samples - An app with examples and code explanations ★14](https://github.com/Mair/react-meetup-draftjs)

## Playgrounds for Examples from Official Repository (v.0.10.0)
* [Rich Text Editor](http://codepen.io/Kiwka/pen/YNYvyG)
* [Color Editor](http://codepen.io/Kiwka/pen/oBpVve)
* [Convert from HTML Editor](http://codepen.io/Kiwka/pen/YNYgWa)
* [Entity Editor](http://codepen.io/Kiwka/pen/wgpOoZ)
* [Link Editor](http://codepen.io/Kiwka/pen/ZLvPeO)
* [Media Editor](http://codepen.io/Kiwka/pen/rjpRzj)
* [Plain Text Editor](http://codepen.io/Kiwka/pen/jyYJzb)
* [Decorators Editor - Tweet example](http://codepen.io/Kiwka/pen/KaZERV)

## Usage in Production
* [Small Teaser](https://www.smallteaser.com/articles/write)
* [HKW Technosphere Magazine](http://technosphere-magazine.hkw.de/)
* [Douban Read](https://read.douban.com/editor_ng)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Nikolaus Graf](https://github.com/nikgraf/) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="https://github.com/nikgraf/awesome-draft-js">nikgraf/awesome-draft-js</a> with ranks
</p>
