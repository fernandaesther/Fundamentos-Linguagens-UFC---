# 09 — Concorrência
**Objetivo.** Explicar threads x processos + exemplo.
**Threads** compartilham memória do processo; **processos** são isolados.
**Exemplo (Python/threading).**
```python
import threading, time
def tarefa(nome):
    for i in range(3):
        print(nome, i); time.sleep(0.2)
t1 = threading.Thread(target=tarefa, args=("A",))
t2 = threading.Thread(target=tarefa, args=("B",))
t1.start(); t2.start(); t1.join(); t2.join()
```
**Referência.** Aula 11.
