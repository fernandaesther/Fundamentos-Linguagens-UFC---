# 13 — Linguagens para Scripts e Web
**Objetivo.** Automação simples.
**Exemplo (Python/requests).**
```python
import requests
r = requests.get("https://httpbin.org/json", timeout=10)
print(r.status_code, r.headers.get("Content-Type"))
```
**Tarefa.** Escolha: organizar arquivos locais **ou** consumir uma API e salvar JSON.
**Referência.** Aulas 12 (HTTP/assíncrono).
