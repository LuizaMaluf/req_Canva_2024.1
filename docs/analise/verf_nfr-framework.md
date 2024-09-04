## Verificação - Inspeção do NFR

|    Data    | Versão |      Descrição      |        Autor     |
|------------|--------|---------------------|------------------|
| 04/09/2024 |  0.0   | Criando a documentação de Inspeção do NFR | Gabriel Moura |

## Introdução

O objetivo dessa documentação é fazer a verificação do diagrama NFR utilizando a técnica de inspeção.

## Objetivo

O principal objetivo é verificar a qualidade do artefato produzido pelo grupo e identificar se há necessidade de refatoração.

## Metodologia

A inspeção é um método de verificação que analisa os artefatos para determinar se estão em conformidade com os padrões e expectativas.

Foi elaborado um checklist com base nos princípios de modelagem NFR, com perguntas a serem respondidas com "[X]" para "Sim" (impacto positivo) ou "[]" para "Não" (impacto negativo).

A qualidade do NFR será classificada como:

* **Alta:**  Se todas as perguntas do checklist forem respondidas com "[X]".
* **Média:** Se a maioria das perguntas forem respondidas com "[X]", mas houver alguns <br> "[ ]".
* **Baixa:** Se houver um número significativo de "[ ]" no checklist, indicando a necessidade de refatoração.

## Checklist

### Primeira análise do [NFR - Geral (versão 0.0)](../modelagem/nfr-framework.md#geral-nfrf1)

- [x] O diagrama possui um objetivo claro e definido?
- [x] Os softgoals são representados por nuvens?
- [x] Os softgoals representam requisitos de qualidade?
- [x] As operacionalizações são representadas por nuvens com bordas grossas?
- [x] As operacionalizações descrevem como atingir os softgoals?
- [x] As dependências entre softgoals e operacionalizações são representadas por setas?
- [x] As setas indicam o tipo de contribuição (positiva ou negativa)?
- [ ] O diagrama utiliza uma legenda para explicar os símbolos e tipos de contribuição?
- [x] O diagrama está organizado e fácil de entender?
- [ ] As relações de decomposição e dependência entre os softgoals estão claras e completas?
- [ ] As operacionalizações propostas são viáveis e adequadas para o contexto do Canva?

### Resultado

Qualidade: **Média**
