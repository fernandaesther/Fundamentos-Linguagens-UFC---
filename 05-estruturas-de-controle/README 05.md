# 05 — Estruturas de Controle
**Objetivo.** Programa simples com seleção, repetição e controle de fluxo.
**Exemplo (Python).**
```python
import random
segredo = random.randint(1, 10)
for tentativa in range(1, 6):
    palpite = int(input(f"Tentativa {tentativa}: "))
    if palpite == segredo:
        print("Acertou!"); break
    elif palpite < segredo:
        print("Maior!")
    else:
        print("Menor!")
else:
    print("Acabou! O número era", segredo)
```
**Tarefa.** Adapte para outro contexto (menu, calculadora, etc.).
**Referência.** Aula 5.
