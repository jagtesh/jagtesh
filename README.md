# Hi, I'm Jag

I build native apps, developer tools, and libraries across Rust, Swift, Python, and Dart. My projects range from GPU charting and real-time collaboration to language and compiler experiments.

## Selected projects

- **[Lumen Charts](https://github.com/jagtesh/lumen-charts)** - GPU-accelerated charting built on Vello and wgpu, with Rust, Swift, and WebAssembly APIs. Inspired by Lightweight Charts.
- **[ApplePy](https://github.com/jagtesh/ApplePy)** - Build native Python extensions in Swift using macros, with access to Apple frameworks.
  - [PyCoreML](https://github.com/jagtesh/pycoreml), [PyNatural](https://github.com/jagtesh/pynatural), and [SwiftKeychain](https://github.com/jagtesh/swiftkeychain) bring Core ML inference, on-device language processing, and macOS Keychain access to Python.
- **[Superlemon](https://github.com/jagtesh/superlemon)** - A native macOS app built around Neovim, with file navigation, Quick Open, tabs, and a minimap.
- **[Zatara](https://github.com/jagtesh/zatara)** - A mouse-driven desktop inside a graphics-capable terminal, with floating windows, independent shells, and Pixel applications.
- **Real-time collaboration** - [hocuspocus-rs](https://github.com/jagtesh/hocuspocus-rs) implements the Hocuspocus V2 protocol in Rust for personal and embedded use. [yjs-dart](https://github.com/jagtesh/yjs-dart) and [hocuspocus-dart](https://github.com/jagtesh/hocuspocus-dart) port Yjs and its Hocuspocus WebSocket provider to Dart.

## More projects

### Developer tools and utilities

- **[Guise](https://github.com/jagtesh/guise)** - Switch profiles and configurations across Codex, Gemini, Claude, and GitHub Copilot.
- **[Squashbox](https://github.com/jagtesh/squashbox)** - Mount SquashFS images with on-demand decompression using Windows ProjFS or an embedded NFS server on macOS and Linux.
- **[Emuscribe](https://github.com/jagtesh/emuscribe)** - Local video transcription on macOS, with speaker diarization, frame capture, and Markdown, HTML, and PDF exports.
- **[TG Channel Archiver](https://github.com/jagtesh/tg-channel-archiver)** - A local-first Telegram channel archiver with message and media storage, incremental syncing, and a searchable web interface.
- **[unbun](https://github.com/jagtesh/unbun)** - Extract bundled code, assets, sourcemaps, and metadata from Bun standalone executables.
- **[GorillaTSZ](https://github.com/jagtesh/gorilla-tsz-swift)** - Gorilla time-series compression in Swift, ported from dgryski/go-tsz, with Python bindings.

### Language and compiler experiments

- **[Darcy](https://github.com/jagtesh/darcy-lang)** - A small typed Lisp that compiles to Rust, with Cargo integration and editor tooling.
- **[Elevate](https://github.com/quichelang/elevate)** - An experimental compiler framework that generates Rust while inferring ownership, borrowing, and mutability.
- **[Quiche](https://github.com/quichelang/quiche)** - A Python-inspired language that compiles to Rust through Elevate.
- **[Rustdex](https://github.com/quichelang/rustdex)** - Build and query compact indexes of Rust standard-library trait implementations from rustdoc JSON.
- **[elevate-types](https://github.com/quichelang/elevate-types)** - Shared index data structures and persistence for Rustdex and Elevate.

## Forks and adaptations

- **[lucebox](https://github.com/jagtesh/lucebox/tree/serving-resilience)** - A serving-resilience fork of Luce-Org's Lucebox, adding cache reclamation, memory admission, a bounded model gateway, and cancellation/recovery.
- **[simdcsv](https://github.com/jagtesh/simdcsv)** - A Rust port of Geoff Langdale's SIMD CSV parser, with AVX2 and ARM NEON paths.
- **[backhand](https://github.com/jagtesh/backhand)** - SquashFS tooling with Windows filename handling fixes.
- **[Tab Group Manager Plus](https://github.com/jagtesh/Tab-Group-Manager-Plus)** - A Tab Manager Plus fork that uses Chrome's native Tab Groups.
- **[SyncedStore](https://github.com/jagtesh/SyncedStore)** - A dependency-maintenance fork of YousefED's collaborative state library.
- **[winformsx](https://github.com/jagtesh/winformsx)** - An experimental cross-platform adaptation of .NET Windows Forms using Silk.NET and Impeller.
