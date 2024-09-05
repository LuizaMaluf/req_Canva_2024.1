# Inspeção do iStar

## Histórico de Versões

| Data       | Descrição                  | Autor          | Versão |
|------------|----------------------------|----------------|--------|
| 04/09/2024 | Inspeção inicial do iStar. | Caio Alexandre | 0.0    |

## Objetivo

O principal objetivo e verificar a qualidade dos artefatos produzidos pelo grupo
e priorizar quais pontos devem ser refatorados.

## Metodologia

A inspeção é um modelo eficaz que verifica os artefatos e ao final diz se estão
de acordo com a notação esperada. Foi estabelicido um checklist com os critérios
necessários para definir a qualidade do modelo iStar. Com base nos resultados, a
priorização foi dividida em qualidade alta, média e baixa, onde a de baixa
qualidade precisa ser refatorada primeiro.

## Artefatos

### Strategic Dependency Model

- [x] Todas as dependências estão direcionadas corretamente?
- [x] Os *softgoals* representam requisitos não-funcionais?	
- [ ] Os atores estão representados com a abstração correta?
  > Obs.: O ator "Canva" poderia ter sido registrado como um agente.
- [x] Os atores descritos são realmente os necessários e suficientes para o
      modelo proposto?
- [x] As metas são objetivos que se deseja alcançar?
- [x] As metas estão descritas em voz passiva?
- [x] Todos os recursos são substantivos?

### Strategic Rationale Model

#### SR Usuário

- [x] A boundary representa a fronteira de um ator, limitando o escopo de sua
      atuação?
- [x] Todos os elementos presentes dentro da fronteira são elementos
      relacionados ao ator que ela pertence?
- [x] As ligações com elementos de fora da fronteira são feitas através de
      dependências?
- [x] As ligações `and` e `or` estão corretas?
- [x] Os impactos estão representados com sentido e intensidade corretas?
- [x] Existe propagação de impacto entre diferentes ramos? (não apenas entre
      pais e filhos)
- [x] Todos os recursos são substantivos?
- [x] Todas as tarefas são ações e estão representadas com verbos?
- [x] Os *softgoals* representam requisitos não-funcionais?
- [x] As metas são objetivos que se deseja alcançar?
- [x] As metas estão descritas em voz passiva?

#### SR Canva

- [x] A boundary representa a fronteira de um ator, limitando o escopo de sua
      atuação?
- [x] Todos os elementos presentes dentro da fronteira são elementos
      relacionados ao ator que ela pertence?
- [x] As ligações com elementos de fora da fronteira são feitas através de
      dependências?
- [x] As ligações `and` e `or` estão corretas?
- [x] Os impactos estão representados com sentido e intensidade corretas?
- [x] Existe propagação de impacto entre diferentes ramos? (não apenas entre
      pais e filhos)
- [x] Todos os recursos são substantivos?
- [x] Todas as tarefas são ações e estão representadas com verbos?
- [x] Os *softgoals* representam requisitos não-funcionais?
- [x] As metas são objetivos que se deseja alcançar?
- [x] As metas estão descritas em voz passiva?


#### SR Pro

- [x] A boundary representa a fronteira de um ator, limitando o escopo de sua
      atuação?
- [x] Todos os elementos presentes dentro da fronteira são elementos
      relacionados ao ator que ela pertence?
- [x] As ligações com elementos de fora da fronteira são feitas através de
      dependências?
- [x] As ligações `and` e `or` estão corretas?
- [x] Os impactos estão representados com sentido e intensidade corretas?
- [x] Existe propagação de impacto entre diferentes ramos? (não apenas entre
      pais e filhos)
- [x] Todos os recursos são substantivos?
- [x] Todas as tarefas são ações e estão representadas com verbos?
- [x] Os *softgoals* representam requisitos não-funcionais?
- [x] As metas são objetivos que se deseja alcançar?
- [x] As metas estão descritas em voz passiva?

## Resultado

Qualidade alta.
