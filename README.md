# cookbook

`cookbook` is a collection of re-usable GitHub workflows for your [actions](https://docs.github.com/en/actions)
To add your own workflows, open a [PR](https://github.com/catto-oss/cookbook/pulls)!

## Workflows

| Workflow     | Description     | Supports     |
| ------------ | --------------- | ------------ |
| [`crystal-release.yml`](https://github.com/catto-oss/cookbook/blob/main/workflows/crystal-release.yml) | A configurable workflow for building and releasing Crystal-based applications using `crystal build`. | Linux, Macintosh (M-series), Macintosh (Intel)  |
| [`rust-release.yml`](https://github.com/catto-oss/cookbook/blob/main/workflows/rust-release.yml) | A configurable workflow for building and releasing Rust-based applications | Linux, Macintosh (M-series) |

## Instructions
To apply a workflow to your own projects, copy and paste a file from the [`workflows/`](https://github.com/catto-oss/cookbook/blob/main/workflows) and replace every instance of `__BINARY__` and replace it with your binary/application name.
