# 06 — Subprogramas
**Objetivo.** Mostrar passagem por valor e por referência.
**Python (por valor para imutáveis).**
```python
def inc(x): x += 1; return x
a = 10; print(a, inc(a), a)  # 10 11 10
```
**C (por referência via ponteiro).**
```c
void inc(int *x){ (*x)++; }
int a=10; inc(&a); // a = 11
``>
**Tarefa.** Inclua um exemplo com objeto mutável em Python (lista/dict).
**Referência.** Aula 6.
