# ⚡ CMZN Consulting

Organization profile for [CMZN-Consulting](https://github.com/CMZN-Consulting).

The public org splash is [`profile/README.md`](profile/README.md). That is what
GitHub renders on the organization home page.

## 📁 What's in here

|     | Kind       | Extensions                    | Prettier |
| --- | ---------- | ----------------------------- | -------- |
| 📝  | Markdown   | `.md`                         | yes      |
| 🐚  | Shell      | `.sh`                         | yes      |
| 📦  | JSON       | `.json`                       | yes      |
| 📐  | YAML       | `.yaml`, `.yml`               | yes      |
| 🌐  | HTML       | `.html`                       | yes      |
| 🟨  | JavaScript | `.js`, `.jsx`, `.mjs`, `.cjs` | yes      |
| 🔷  | TypeScript | `.ts`, `.tsx`, `.mts`, `.cts` | yes      |
| 📄  | PDF        | `.pdf`                        | stored   |
| 📊  | Excel      | `.xlsx`, `.xls`, `.xlsm`      | stored   |

The root `.gitignore` is an allow-list. Nothing else is committed.

## ✨ Format

```bash
bun install
bun run format       # write
bun run format:check # CI / pre-push
```

Same Prettier options as `endurance` (`printWidth` 100, double quotes, trailing
commas). `prettier-plugin-sh` covers `.sh`.
