# 🏨 Hotel Manager (Python)

Sistema de linha de comando para gerenciar as reservas de um hotel de 50 quartos (101 a 150), feito como atividade de **Algoritmos / Programação** do curso de Sistemas de Informação da **UNEMAT**.

O desafio do exercício era usar **somente listas unidimensionais**: cada informação de um quarto fica numa lista separada (*arrays paralelos*) e o mesmo índice liga tudo.

## ✨ Funcionalidades

- **Check-in**: registra o hóspede e quantos dias ele vai ficar
- **Check-out**: libera o quarto e manda pra limpeza
- **Limpeza / manutenção**: volta o quarto para "Livre"
- Consulta de um quarto específico e visão geral da ocupação
- Menu interativo no terminal com **InquirerPy**

## 🧠 Conceitos praticados

- Arrays paralelos (`numeros_quartos`, `status_quartos`, `hospedes_quartos`, `dias_estadia`)
- Busca de índice e tratamento de erro (`list.index` + `try/except`)
- Funções com responsabilidade única e validação de estados

## ▶️ Como executar

```bash
pip install InquirerPy
python Hotel_manager.py
```

---
Desenvolvido por **Diego da Silva Ferreira**, estudante de Sistemas de Informação na UNEMAT (Sinop - MT).
