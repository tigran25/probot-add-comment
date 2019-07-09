# Add Comment Bot

[![Downloads][npm-downloads]][npm-url] [![version][npm-version]][npm-url]
[![Build Status][travis-status]][travis-url]

A [Probot](https://probot.github.io) bot to add/remove a comment to issues when a label is present/removed.

## Setup

Add a `.github/comment.yml` file to your repository and then run the bot against it.

If the config is empty or doesn't exist, the bot will not run.

```yml

# Config

comments:
  - label: needs-area
    comment: |
      Please add an `area:<team>` label to this issue.
```

## Contribute

If you have suggestions for how this bot could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

[travis-status]: https://travis-ci.org/lswith/probot-add-comment.svg?branch=master
[travis-url]: https://travis-ci.org/lswith/probot-add-comment
[npm-downloads]: https://img.shields.io/npm/dm/probot-add-comment.svg?style=flat
[npm-version]: https://img.shields.io/npm/v/probot-add-comment.svg?style=flat
[npm-url]: https://www.npmjs.com/package/probot-add-comment
