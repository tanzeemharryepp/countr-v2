# countr-v2

Fast line/byte counter written in Rust

## Install

```bash
cargo build --release
```

## What it does

- Counts lines, words and bytes like wc
- Zero dependencies outside std
- Reads stdin or multiple files
- Parallel over files with std threads

## Examples

```bash
./target/release/countr-v2 src/*.rs
cat README.md | ./target/release/countr-v2
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── development.md
│   └── faq.md
├── src/
│   └── main.rs
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── Cargo.toml
└── LICENSE
```

## License

MIT. Do whatever you want.
