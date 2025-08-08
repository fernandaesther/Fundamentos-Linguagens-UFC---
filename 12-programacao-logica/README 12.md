# 12 — Programação Lógica
**Objetivo.** Modelar um problema com regras.
**Exemplo (Prolog).**
```prolog
pai(joao, maria).
mae(maria, ana).
avo(X,Y) :- pai(X,Z), mae(Z,Y).
```
**Tarefa.** Criar 5 fatos e 2 regras novas; demonstrar 2 consultas.
**Referência.** Aula 9.
