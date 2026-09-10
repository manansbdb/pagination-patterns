<p align="center">
  <img src="docs/banner.svg" alt="Pagination Patterns banner" width="100%" />
</p>

<h1 align="center">pagination-patterns</h1>

<p align="center">
  <strong>EN</strong> Offset & cursor pagination JSON examples<br/>
  <strong>PT</strong> Exemplos JSON de paginação offset e cursor
</p>

<p align="center">
  <a href="https://github.com/manansbdb/pagination-patterns/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/topic-pagination-3b82f6?style=for-the-badge" alt="pagination" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Concrete **offset** and **cursor** pagination response examples plus design notes. | Exemplos concretos de paginação **offset** e **cursor** plus notas de design. |
| Pick a style, copy the JSON shape into your API docs. | Escolhe um estilo e copia o JSON para a documentação da API. |

```mermaid
flowchart LR
  A["📥 Request page"] --> B{"⚙️ Style"}
  B -->|offset| C["📄 offset-example.json"]
  B -->|cursor| D["📄 cursor-example.json"]
  C --> E["📤 Items + meta"]
  D --> E
  style A fill:#2563eb,stroke:#1d4ed8,color:#fff
  style B fill:#7c3aed,stroke:#5b21b6,color:#fff
  style C fill:#f59e0b,stroke:#b45309,color:#fff
  style D fill:#14b8a6,stroke:#0f766e,color:#fff
  style E fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/pagination-patterns.git
cd pagination-patterns
```

### 2) Copy examples / Copia exemplos

```bash
mkdir -p docs/api
cp offset-example.json docs/api/
cp cursor-example.json docs/api/
cp notes.md docs/api/pagination-notes.md
```

### Requirements / Requisitos

- `git`
- No runtime dependencies

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/pagination-patterns.git
# compare offset-example.json vs cursor-example.json → adopt one
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `offset-example.json` | Offset/limit response |
| `cursor-example.json` | Cursor-based response |
| `notes.md` | Trade-offs |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
pagination-patterns/
├── docs/banner.svg
├── offset-example.json
├── cursor-example.json
├── notes.md
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
