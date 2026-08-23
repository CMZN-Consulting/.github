# ⚡ CMZN Consulting

**Proprietary trading.** Crypto derivatives. Volatility.

Long gamma: the world moves more than the smile prepaid. One options book.
Automation hedges the residual and quotes a synthetic market around the same
underlyings. Models, risk, and the software that carries them are built here.

```text
📚  desk options book
          │
          ├── ⚡ automated hedge
          └── 📈 synthetic quotes
                    │
                    ▼
             🎯 execution venue
```

## 📈 Desk

|     | What                                                                                                                             |
| --- | -------------------------------------------------------------------------------------------------------------------------------- |
| 📚  | One options inventory. Automation does not trade options; it harvests the book.                                                  |
| ⚡  | Hedge the residual delta. Quote a synthetic market around the same underlyings.                                                  |
| 💰  | P&L is realised volatility beating implied, spread capture, and tail capture; maker rebates when eligible — not a directional call on the coin. |

## 🛠️ In-house

Nothing in the critical path is rented. Execution is stateless; durable state
and an append-only integrity log live beside it. Research advises; it does not
place orders. The operator surface is read-only.

## 🧪 Research

Vol surfaces, native pricing kernels, evolutionary calibration, typed ledgers.
The interesting pieces stay closed. What we can strip of alpha, we publish.

## 📦 Open source

Selected internals, MIT licensed — alpha-neutralized, trade secrets redacted —
so the claimed expertise is inspectable. No links yet; they land here when they
are clean enough to show.

## 🧰 Stack

|     | Layer       | Languages               | Runtimes      |
| --- | ----------- | ----------------------- | ------------- |
| ⚙️  | Execution   | TypeScript, Rust        | Bun           |
| 🗄️  | State       | Erlang                  | BEAM          |
| 🧮  | Kernels     | Haskell                 | n/a           |
| 🔬  | Research    | Python, Erlang, Haskell | CPython, BEAM |
| 🖥️  | Operator UI | TypeScript, Svelte      | Bun, Browser  |

## ⚖️ License

Proprietary. © CMZN Consulting LTD. All rights reserved.
