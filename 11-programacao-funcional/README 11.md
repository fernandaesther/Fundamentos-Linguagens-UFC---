# 11 — Programação Funcional
**Objetivo.** Recursão + alta ordem.
**Exemplo (map/filter/reduce).**
```python
from functools import reduce
nums = [1,2,3,4,5]
dobrados_pares = list(filter(lambda x: x%2==0, map(lambda x: x*2, nums)))
soma = reduce(lambda a,b: a+b, nums, 0)
```
**Tarefa.** Resolver um problema real (ex.: limpeza de dados) usando composição de funções.
**Referência.** Aula 10.
