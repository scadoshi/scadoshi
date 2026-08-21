### Hey!

🦀 I'm **Scotty**. A Rust engineer in Washington state.

📱 I built [**Zwipe**](https://zwipe.net) ([source](https://github.com/scadoshi/zwipe)), a swipe-first MTG deck builder, live on the App Store with ~1,000 users. Roughly 100,000 lines of Rust across 5 crates, 600+ tests, self-hosted, built and operated by me.

🔨 I went from near-zero programming to production Rust in about a year, and I build things from scratch to understand how they actually work.

[**scottyfermo.com**](https://scottyfermo.com) · [LinkedIn](https://www.linkedin.com/in/scotty-fermo-41a35b141)

#### 🌀 Projects

| **Databases & Systems**                                                                                                                                                                                                                                                                                                                                     | **Apps & Tools**                                                                                                                                                                                                                                                                                                                                                                     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| • [nighthawk](https://github.com/scadoshi/nighthawk) - A key-value storage engine, evolved from Bitcask to an LSM-tree: WAL, memtables, SSTable compaction, bloom filters, CRC32 corruption recovery<br>• [diprotodon](https://github.com/scadoshi/diprotodon) - A Redis-compatible server in std-only Rust: hand-written RESP parser, snapshot + append-only durability, works with real `redis-cli`<br>• [gotcha](https://github.com/scadoshi/gotcha) - Cross-platform security camera: raw evdev with nix::poll on Linux, Accessibility API callbacks on macOS, releases photos only with a secret key | • [Zwipe](https://zwipe.net) - Full-stack MTG deck builder (Axum + Dioxus + PostgreSQL), live on the App Store ([source](https://github.com/scadoshi/zwipe))<br>• [marvin](https://github.com/scadoshi/marvin) - Interactive CLI chatbot built on Rig with Claude: streaming responses, web + math tools, chat persistence, dynamic model discovery. Found and fixed deprecated model constants in Rig via a PR across 17 files<br>• [upsee](https://github.com/scadoshi/upsee) - ONNX inference in Rust<br>• [halo_action_importer](https://github.com/scadoshi/halo_action_importer) - Production CLI that bulk-imports actions into Halo from CSV/Excel: runs unattended for hours against unreliable APIs, per-failure retry logic. Weeks of manual work, automated<br>• [halo_custom_field_builder](https://github.com/scadoshi/halo_custom_field_builder) - Production CLI that bulk-creates custom fields across Halo products: OAuth2 with cached tokens, type-safe domain modeling. Hours to minutes, used across Fortune 500 client implementations<br>• [rustmas](https://github.com/scadoshi/rustmas) - Advent of Code client: input fetcher and solutions<br>• [sharpmas](https://github.com/scadoshi/sharpmas) - rustmas ported to C#, same tooling rebuilt on .NET<br>• [rusty-aoc](https://github.com/scadoshi/rusty-aoc) - Archived Advent of Code solutions in Rust<br>• [portfolio](https://github.com/scadoshi/portfolio) - [scottyfermo.com](https://scottyfermo.com), written in Rust |

#### 🛠️ What am I working on?

| **Category**  | **Description**                                                                                  |
| ------------- | ------------------------------------------------------------------------------------------------ |
| **Building**  | [Zwipe](https://zwipe.net) ([source](https://github.com/scadoshi/zwipe)), under daily development and shipping weekly releases. |
| **Iterating** | [rustmas](https://github.com/scadoshi/rustmas) and [sharpmas](https://github.com/scadoshi/sharpmas) in lockstep: the same Advent of Code tooling maintained in Rust and C#, every refactor ported both ways. |
| **Extending** | [diprotodon](https://github.com/scadoshi/diprotodon): pub/sub landed, MULTI/EXEC transactions next on the roadmap. |
| **Learning**  | C#, by writing all sorts of projects in it and comparing notes on Rust vs C# in online forums. |
| **Operating** | The self-hosted server Zwipe runs on: CI/CD, structured tracing, nightly backups, production metrics. |

<div align="right">

**~** [_scottyfermo.com_](https://scottyfermo.com)

</div>
