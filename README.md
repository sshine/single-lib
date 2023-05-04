# {{project-name}}

[![Rust CI](https://github.com/{{github-username}}/{{project-name}}/actions/workflows/main.yml/badge.svg)](https://github.com/{{github-username}}/{{project-name}}/actions)

{{description}}

## Getting started

To contribute, install the Rust toolchain, e.g. using [rustup][rustup]:

```sh
curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```

[rustup]: https://rustup.rs/

You can run the test suite like so:

```sh
cargo test --all-targets
```

{% if false %}

## This is a `cargo generate` template

*(This section won't occur when using this template.)*

To install `cargo generate`, run:

```sh
cargo install cargo-generate
```

Create new template, either from GitHub, or from a local path:

```sh
cargo generate --git https://github.com/sshine/workspace-template
cargo generate --path $HOME/Projects/workspace-template
```

Create a `cargo gen` shortcut by adding a section to ~/.cargo/config.toml:

```toml
[alias]
gen = "generate"
```

Add your `github-username` to ~/.cargo/cargo-generate.toml:

```toml
[values]
github-username = "sshine"
```

{% endif %}