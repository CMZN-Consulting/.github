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

|     | What                                                                                                                                            |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| 📚  | One options inventory. Automation does not trade options; it harvests the book.                                                                 |
| ⚡  | Hedge the residual delta. Quote a synthetic market around the same underlyings.                                                                 |
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
so the claimed expertise is inspectable.

- **[typify](https://github.com/CMZN-Consulting/typify)**: A small self-declaring type system.
- **[black76-zig](https://github.com/CMZN-Consulting/black76-zig)**: Black-76 option pricer in Zig.

## 🌱 Raising

A second line of work, funded by the desk: raising a language model without
changing its weights. The position paper is public. The formal work is not
done yet.

- **[raising](https://github.com/CMZN-Consulting/raising)**: the white paper, _Intelligence and Its Existence_.
- **[manifesto](https://github.com/CMZN-Consulting/manifesto)**: five lines for people and AI models.
- **[Discussions](https://github.com/orgs/CMZN-Consulting/discussions)**: the forum. Say what you think.

## 🧰 Stack

|     | Layer       | Languages               | Runtimes      |
| --- | ----------- | ----------------------- | ------------- |
| ⚙️  | Execution   | TypeScript, Zig         | Bun           |
| 🗄️  | State       | Erlang                  | BEAM          |
| 🧮  | Kernels     | Haskell                 | n/a           |
| 🔬  | Research    | Python, Erlang, Haskell | CPython, BEAM |
| 🖥️  | Operator UI | TypeScript, Svelte      | Bun, Browser  |

## ⚖️ License

Proprietary. © CMZN Consulting LTD. All rights reserved.
