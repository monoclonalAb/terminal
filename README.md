<div align="center">

# terminal

**A native macOS terminal with the multiplexer built in, where coding agents draw real UI.**

<img alt="Status: design phase" src="https://img.shields.io/badge/status-design%20phase-ca9ee6?style=flat-square" />
<img alt="Platform: macOS" src="https://img.shields.io/badge/platform-macOS-8caaee?style=flat-square&logo=apple&logoColor=white" />
<img alt="Built with Rust and GPUI" src="https://img.shields.io/badge/Rust-GPUI-ef9f76?style=flat-square&logo=rust&logoColor=white" />
<a href="LICENSE"><img alt="Licence: MIT" src="https://img.shields.io/badge/licence-MIT-a6d189?style=flat-square" /></a>

<img src="docs/assets/readme-hero.png" width="900" alt="Static GPUI mock-up of the target window: an agent transcript with diff and test cards and an emoji popup, typeset math, a context meter, and a zsh pane" />

<sub>An early visual prototype: a static mock-up with hard-coded content, not a working terminal.</sub>

</div>

> [!NOTE]
> Design phase: no production code and nothing to install yet. `terminal` is a
> placeholder name.

## Planned features

- **Native agent UI.** Programs that speak the Tern Surface Protocol (TSP), omp
  today and pi later, draw transcripts, diffs, editors, and math as native
  views.
- **A terminal first.** Everything else runs unmodified on a grid driven by
  Ghostty's VT core.
- **Multiplexer built in.** Workspaces, tabs, and splits with herdr's key map.
- **Agent attention.** A sidebar dot per agent, and one key to jump to the one
  that needs you.
- **No webview.** Rust on GPUI, Zed's GPU UI framework.

## Status

A visual prototype confirmed GPUI can produce the look. A single-pane terminal
is next.

## Licence

[MIT](LICENSE)
