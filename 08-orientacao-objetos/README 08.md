# 08 — Programação Orientada a Objetos
**Objetivo.** Modelar uma hierarquia.
**Exemplo (Python).**
```python
class Veiculo:
    def __init__(self, cor): self.cor = cor
    def descricao(self): return f"Veículo {self.cor}"
class Carro(Veiculo):
    def descricao(self): return f"Carro {self.cor}"
```
**Tarefa.** Demonstrar encapsulamento (propriedades), herança e polimorfismo com 2 subclasses e 1 método sobrescrito.
**Referência.** Aulas 7–8.
