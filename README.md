<p align="center">
  <img src="docs/banner.svg" alt="Makefile Templates banner" width="100%" />
</p>

<h1 align="center">makefile-templates</h1>

<p align="center">
  <strong>EN</strong> Common Makefile targets for generic, Node, and Python projects<br/>
  <strong>PT</strong> Targets Makefile comuns para projetos genéricos, Node e Python
</p>

<p align="center">
  <a href="https://github.com/manansbdb/makefile-templates/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/Make-A8B9CC?style=for-the-badge" alt="Make" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| **Makefile templates** with common targets for generic, Node, and Python repos. | **Templates Makefile** com targets comuns para repos genéricos, Node e Python. |
| Copy a template as `Makefile` and adjust commands. | Copia um template como `Makefile` e ajusta os comandos. |

```mermaid
flowchart LR
  A["📋 Pick template"] --> B["📄 Makefile.*"]
  B --> C["⚙️ make help"]
  C --> D["✅ Build / test"]
  style A fill:#f59e0b,stroke:#b45309,color:#fff
  style B fill:#1e293b,stroke:#0f172a,color:#fff
  style C fill:#0ea5e9,stroke:#0369a1,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/makefile-templates.git
cd makefile-templates
```

### 2) Apply / Aplica

```bash
cp templates/Makefile.generic /path/to/your-project/Makefile
# or Makefile.node / Makefile.python
```

### Requirements / Requisitos

- `git`
- GNU Make (or compatible)

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/makefile-templates.git
cp makefile-templates/templates/Makefile.node ./Makefile
make help
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `templates/Makefile.generic` | Generic targets |
| `templates/Makefile.node` | Node-oriented |
| `templates/Makefile.python` | Python-oriented |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
makefile-templates/
├── docs/banner.svg
├── templates/Makefile.generic
├── templates/Makefile.node
├── templates/Makefile.python
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
