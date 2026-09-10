# Notes / Notas

## English
- Cap `limit` (e.g. max 100).
- For cursors, encode a stable sort key (often `id` or `(created_at, id)`).
- Offset pages can skip/duplicate rows under concurrent inserts.

## Português
- Limite o `limit` (ex.: máx. 100).
- Em cursores, encode uma chave de ordenação estável (muitas vezes `id` ou `(created_at, id)`).
- Páginas offset podem saltar/duplicar linhas com inserts concorrentes.
