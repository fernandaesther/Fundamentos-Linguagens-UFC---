# 03 — Sintaxe e Semântica
**Objetivo.** Criar uma mini‑gramática + exemplo de análise léxica.
**Minha linguagem (ex.):** *ChocoLang*
```
<prog>     ::= <stmt> { <stmt> }
<stmt>     ::= mostre <texto> ";" | var <id> "=" <num> ";"
<texto>    ::= '"' { caractere } '"'
<id>       ::= letra { letra | digito }
<num>      ::= digito { digito }
```
**Lexemas (ex.):** `var x = 42;` → `[var, x, =, 42, ;]`
**Tarefa.** Inclua mais 2 produções e 2 exemplos válidos e 1 inválido.
**Referência.** Aula 4 + material de “Conceitos” (léxico/sintático).
