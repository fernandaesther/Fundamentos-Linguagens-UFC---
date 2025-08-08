# 07 — Implementação de Subprogramas
**Objetivo.** Desenhar a pilha de chamadas (recursão).
**Exemplo (fatorial).**
```python
def fat(n): return 1 if n==0 else n*fat(n-1)
print(fat(4))
```
**Pilha (conceito).**
- `fat(4)` empilha → `fat(3)` → `fat(2)` → `fat(1)` → `fat(0)`
- Desempilha multiplicando resultados.
**Entregáveis.**
- Diagrama (PNG) da pilha com campos: parâmetros, retorno.
**Referência.** Aula 6.
