# 💎 Emerald Industries

**Pragmatic tools, frameworks, and experiments.**

We ship **small pieces, loosely joined**—composable tools that punch above their weight. Use what helps; fork the rest.

> 🛠️ **Migration in progress.** We’re moving projects into this org. Expect fresh commits and new repos as we settle in.

---

## 🌠 Highlights

- **[Dorothy](https://github.com/emeraldindustries/dorothy)** — Modular **PHP** framework for maintainable apps.
- **[Foundry](https://github.com/emeraldindustries/foundry)** — The **lighthouse & compiler** of the stack: emits repeatable artifacts, tags, and tooling. **Go** at the core.
- **[Glyf](https://github.com/emeraldindustries/glyf)** — Design system + UI primitives (**TypeScript/CSS**).
- **[Attic](https://github.com/emeraldindustries/attic)** — One‑off utilities, published **as‑is** for the community.

> Tip: Browse the **Repositories** tab for everything; we pin the most active work.

---

## 🚀 Start here

- **Grab a utility:** → **[Attic](https://github.com/emeraldindustries/attic)** (shell tools you can copy‑paste and run).
- **Curious about the build system?** → **[Foundry](https://github.com/emeraldindustries/foundry)** (release/stack tooling; deterministic by design).
- **PHP app development?** → **[Dorothy](https://github.com/emeraldindustries/dorothy)** (modular framework; drop‑in module autoload).
- **Front‑end pieces?** → **[Glyf](https://github.com/emeraldindustries/glyf)** (tokens, components, theming helpers).

---

## 🧭 Our POV

- **Boringly reliable** foundations, **delightfully generative** tooling.
- **Deterministic, idempotent outputs** (dry‑run everywhere; write‑if‑changed).
- **Polyglot on purpose:** Go for compilers/CLIs; PHP for runtime; TypeScript for UI; Shell for tiny ops.
- **Public by default:** docs, specs, and contracts live with the code.

---

## 🗺️ The ecosystem (at a glance)

**Foundry** is the **lighthouse**: it reads the stack truth and **emits artifacts** (indexes, locks, autoload bridges, tags).

**Dorothy** and apps **consume** those emissions. **Glyf** provides the UI layer. **Attic** hosts small, pragmatic helpers.

```
[Attic tools]  →  used anywhere
     │
     ├──▶  Foundry (emit truth → artifacts) ──▶ Dorothy / Apps / CI / Editors
     │
     └──▶  Glyf (design system) ──▶ Front‑end apps & docs
```

---

## 🤝 Contributing

We love **small, focused PRs**. Each repo documents its own guardrails:

- Attic’s stance & guidance: **[SUPPORT](https://github.com/emeraldindustries/attic/blob/main/docs/SUPPORT.md)** · **[CONTRIBUTING](https://github.com/emeraldindustries/attic/blob/main/docs/CONTRIBUTING.md)**
- Foundry’s vision & CLI overview: **[README](https://github.com/emeraldindustries/foundry/blob/main/README.md)**

> Prefer to start a thread? Use **Attic Discussions** → <https://github.com/emeraldindustries/attic/discussions>

---

## 🔐 Support & Security

Support expectations are documented per‑repo. **Attic** is explicitly **no‑maintenance OSS**. Security processes (when applicable) are tracked in individual repositories.

---

## 📜 License

Most projects are **MIT** unless noted otherwise. See each repository’s `LICENSE`.

---

## ⭐ Stay in the loop

- Star repos you use
- Watch releases on projects you care about
- Open a small, clear PR when you spot an improvement

> Building in public, iterating constantly. Thanks for stopping by! ✨

