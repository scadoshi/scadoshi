### Hey!

🦀 I'm **Scotty**. A Rust engineer in Washington state.

⚙️ I build systems from the bottom up: [**chickadee**](https://github.com/scadoshi/chickadee), an LSM-tree storage engine, and [**steller**](https://github.com/scadoshi/steller), a Redis-compatible server that talks to real `redis-cli`. Both hand-written, no frameworks.

📱 I also built [**Zwipe**](https://zwipe.net) ([source](https://github.com/scadoshi/zwipe)), a swipe-first MTG deck builder, live on the iOS and Android app stores with ~1,000 users. Over 100,000 lines of Rust across 6 workspace crates, 700+ tests, self-hosted, built and operated by me.

🔨 I build things from scratch to understand how they actually work.

[**scottyfermo.com**](https://scottyfermo.com) · [LinkedIn](https://www.linkedin.com/in/scotty-fermo-41a35b141)

#### ⚡ Stats

I joined GitHub **2** years ago and have since pushed **5,178** commits across **56** personal projects, with contributions to **35** public repositories.

![Rust](https://img.shields.io/static/v1?style=flat-square&label=%E2%A0%80&color=555&labelColor=dea584&message=Rust%EF%B8%B158.9%25)
![HTML](https://img.shields.io/static/v1?style=flat-square&label=%E2%A0%80&color=555&labelColor=e34c26&message=HTML%EF%B8%B131.5%25)
![CSS](https://img.shields.io/static/v1?style=flat-square&label=%E2%A0%80&color=555&labelColor=663399&message=CSS%EF%B8%B14.0%25)
![C#](https://img.shields.io/static/v1?style=flat-square&label=%E2%A0%80&color=555&labelColor=178600&message=C%23%EF%B8%B11.9%25)

<sub>Counted by hand on 23 Sep 2026.</sub>

#### 🌀 Projects

| **Databases & Systems**                                                                                                                                                                                                                                                                                                                                     | **Apps & Tools**                                                                                                                                                                                                                                                                                                                                                                     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| • [chickadee](https://github.com/scadoshi/chickadee) - A key-value storage engine, evolved from Bitcask to an LSM-tree: WAL, memtables, SSTable compaction, bloom filters, CRC32 corruption recovery<br>• [steller](https://github.com/scadoshi/steller) - A Redis-compatible server in std-only Rust: hand-written RESP parser, snapshot + append-only durability, works with real `redis-cli`<br>• [gotcha](https://github.com/scadoshi/gotcha) - Cross-platform security camera: raw evdev with nix::poll on Linux, Accessibility API callbacks on macOS, releases photos only with a secret key | • [Zwipe](https://zwipe.net) - Full-stack MTG deck builder (Axum + Dioxus + PostgreSQL), live on both app stores ([source](https://github.com/scadoshi/zwipe))<br>• [halo_action_importer](https://github.com/scadoshi/halo_action_importer) - Production CLI that bulk-imports actions into Halo from CSV/Excel: runs unattended for hours against unreliable APIs, per-failure retry logic. Weeks of manual work, automated<br>• [halo_custom_field_builder](https://github.com/scadoshi/halo_custom_field_builder) - Production CLI that bulk-creates custom fields across Halo products: OAuth2 with cached tokens, type-safe domain modeling. Hours to minutes, used across Fortune 500 client implementations<br>• [marvin](https://github.com/scadoshi/marvin) - Interactive CLI chatbot built on Rig with Claude: streaming responses, web + math tools, chat persistence, dynamic model discovery. Found deprecated model constants in Rig, filed the issue and a 17-file fix<br>• [upsee](https://github.com/scadoshi/upsee) - ONNX inference in Rust<br>• [cairn](https://github.com/scadoshi/cairn) - Lifetime rep counter for iOS in Rust and Dioxus: local SQLite, no server, no account. On my phone daily with 97,600 reps across 224 days<br>• [rustmas](https://github.com/scadoshi/rustmas) - Advent of Code client: input fetcher and solutions<br>• [sharpmas](https://github.com/scadoshi/sharpmas) - rustmas ported to C#, same tooling rebuilt on .NET<br>• [portfolio](https://github.com/scadoshi/portfolio) - [scottyfermo.com](https://scottyfermo.com), written in Rust <br>• [rusty-aoc](https://github.com/scadoshi/rusty-aoc) - Archived Advent of Code solutions in Rust|

#### 🛠️ What am I working on?

| **Category**  | **Description**                                                                                  |
| ------------- | ------------------------------------------------------------------------------------------------ |
| **Building**  | [Zwipe](https://zwipe.net) ([source](https://github.com/scadoshi/zwipe)), under daily development and shipping weekly releases. |
| **Shipping**  | [cairn](https://github.com/scadoshi/cairn), a lifetime counter I use every day. On my own phone now, App Store review next. |
| **Iterating** | [rustmas](https://github.com/scadoshi/rustmas) and [sharpmas](https://github.com/scadoshi/sharpmas) in lockstep: the same Advent of Code tooling maintained in Rust and C#, every refactor ported both ways. |
| **Extending** | [steller](https://github.com/scadoshi/steller): pub/sub and SET options landed, MULTI/EXEC transactions next on the roadmap. |
| **Learning**  | C#, by writing all sorts of projects in it and comparing notes on Rust vs C# in online forums. |
| **Operating** | The self-hosted server Zwipe runs on: CI/CD, structured tracing, nightly backups, production metrics. |

<div align="right">

**~** [_scottyfermo.com_](https://scottyfermo.com)

</div>
