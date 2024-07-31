## Análise First Things First dos Requisitos do Canva (Criação e Design)

|    Data    | Versão | Descrição | Responsável por documentar |
|------------|--------|-----------|-------|
| 29/07/2024 |  1.0   | Primeira versão da análise FTF | Gabriel Moura |

### Introdução

A técnica First Things First é um método de priorização que visa classificar os requisitos com base na relação entre seu valor e o custo/risco envolvido em sua implementação. Essa técnica é especialmente útil para determinar a ordem de desenvolvimento das funcionalidades, garantindo que as de maior valor e menor custo/risco sejam priorizadas.

### Objetivo

O objetivo da análise First Things First é definir a ordem ideal de implementação dos requisitos elicitados para a plataforma Canva, considerando o benefício proporcionado ao usuário em relação ao custo e risco de desenvolvimento. 

### Metodologia

A metodologia First Things First se baseia em uma tabela onde cada requisito é avaliado em quatro critérios, utilizando uma escala de 1 a 9:

1.  **Benefício Relativo:**  Representa o quão benéfico o requisito é para o usuário, caso seja implementado. 
2.  **Penalidade Relativa:**  Indica o quão prejudicial seria para o usuário caso o requisito não fosse implementado.
3.  **Custo Relativo:**  Reflete o custo estimado (em tempo, esforço e recursos) para implementar o requisito.
4.  **Risco Relativo:**  Avalia o risco potencial de encontrar problemas ou dificuldades na implementação do requisito.

Com base nessas avaliações, são calculados os seguintes valores:

* **Valor Total:** Soma do Benefício Relativo e da Penalidade Relativa.
* **Valor %:** Porcentagem que o Valor Total de um requisito representa em relação à soma de todos os Valores Totais.
* **Custo %:** Porcentagem que o Custo Relativo de um requisito representa em relação à soma de todos os Custos Relativos.
* **Risco %:** Porcentagem que o Risco Relativo de um requisito representa em relação à soma de todos os Riscos Relativos.
* **Prioridade:** Calculada pela fórmula: Valor % / (Custo % + Risco %).

Os requisitos são então ordenados de forma decrescente de acordo com o valor de Prioridade. Aqueles com maior prioridade devem ser implementados primeiro.

### Requisitos tabelados
| Nº | Requisito | Benefício Relativo | Penalidade Relativa | Valor Total | Valor % | Custo Relativo | Custo % | Risco Relativo | Risco % | Prioridade |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Diversidade de formatos de design (posts, banners, apresentações, etc.) | 9 | 9 | 18 | 8.87% | 8 | 9.09% | 2 | 2.63% | **0.70** |
| 2 | Templates personalizáveis para cada formato | 9 | 8 | 17 | 8.37% | 7 | 8.00% | 3 | 3.95% | **0.72** |
| 3 | Criação de designs a partir do zero | 8 | 7 | 15 | 7.39% | 6 | 6.82% | 4 | 5.26% | **0.69** |
| 4 | Importação de imagens e fotos | 9 | 9 | 18 | 8.87% | 5 | 5.68% | 2 | 2.63% | **1.05** |
| 5 | Salvar e exportar designs (PDF, JPG, PNG) | 9 | 9 | 18 | 8.87% | 4 | 4.55% | 1 | 1.32% | **1.45** |
| 6 | Importação de vídeos e outros arquivos | 8 | 5 | 13 | 6.41% | 6 | 7.14% | 4 | 5.26% | **0.64** |
| 7 | Exportar designs em formatos adicionais (SVG, MP4, GIF) | 7 | 4 | 11 | 5.43% | 4 | 4.76% | 3 | 3.95% | **0.76** |
| 8 | Integrar com redes sociais (agendamento de posts) | 9 | 6 | 15 | 7.41% | 7 | 8.33% | 5 | 6.41% | **0.58** |
| 9 | Ferramentas básicas de edição de imagem (cortar, redimensionar, girar) | 9 | 8 | 17 | 8.37% | 3 | 3.41% | 2 | 2.63% | **1.56** |
| 10 | Ajustar brilho, contraste e saturação de imagens | 8 | 7 | 15 | 7.39% | 2 | 2.27% | 1 | 1.32% | **2.14** |
| 11 | Ferramentas de edição de texto (formatação básica, escolha de fontes, cores) | 9 | 9 | 18 | 8.87% | 4 | 4.55% | 1 | 1.32% | **1.45** |
| 12 | Adicionar ícones, ilustrações e formas geométricas aos designs | 8 | 7 | 15 | 7.39% | 3 | 3.41% | 2 | 2.63% | **1.42** |
| 13 | Ferramentas avançadas de edição de imagem (filtros, efeitos, remover fundo) | 8 | 6 | 14 | 6.91% | 5 | 5.95% | 4 | 5.26% | **0.75** |
| 14 | Criar efeitos de texto (sombra, contorno) | 6 | 3 | 9 | 4.44% | 3 | 3.57% | 2 | 2.63% | **0.81** |
| 15 | Camadas (organização básica, ordem e visibilidade) | 9 | 7 | 16 | 7.90% | 6 | 7.14% | 3 | 3.95% | **0.73** |
| 16 | Camadas (opacidade, bloqueio) | 5 | 2 | 7 | 3.46% | 2 | 2.38% | 1 | 1.32% | **1.12** |
| 17 | Máscaras (linear, radial) | 6 | 4 | 10 | 4.93% | 4 | 4.76% | 3 | 3.95% | **0.67** |
| 18 | Compartilhamento de designs para visualização | 9 | 8 | 17 | 8.37% | 2 | 2.27% | 1 | 1.32% | **2.32** |
| 19 | Compartilhamento de designs para edição com permissões básicas | 8 | 7 | 15 | 7.39% | 3 | 3.41% | 2 | 2.63% | **1.42** |
| 20 | Edição colaborativa em tempo real  | 9 | 8 | 17 | 8.40% | 8 | 9.52% | 6 | 7.69% | **0.55** |
| 21 | Sistema de chat na edição colaborativa | 7 | 5 | 12 | 5.92% | 5 | 5.95% | 4 | 5.26% | **0.64** |
| 22 | Comentários em elementos específicos | 8 | 6 | 14 | 6.91% | 6 | 7.14% | 4 | 5.26% | **0.64** |
| 23 | Grade e guias  | 9 | 8 | 17 | 8.37% | 2 | 2.27% | 1 | 1.32% | **2.32** |
| 24 | Pré-visualização em tempo real | 9 | 9 | 18 | 8.87% | 1 | 1.14% | 1 | 1.32% | **3.92** |
| 25 | Paleta de cores | 7 | 4 | 11 | 5.43% | 3 | 3.57% | 2 | 2.63% | **0.96** |
| 26 | Guia de estilo | 5 | 3 | 8 | 3.95% | 4 | 4.76% | 3 | 3.95% | **0.48** |
| 27 | Histórico de versões | 8 | 6 | 14 | 6.91% | 7 | 8.33% | 5 | 6.41% | **0.58** |
| 28 | Atalhos de teclado | 6 | 2 | 8 | 3.95% | 2 | 2.38% | 2 | 2.63% | **0.98** |
| 29 | Interface intuitiva e fácil de usar | 9 | 9 | 18 | 8.87% | 7 | 8.00% | 1 | 1.32% | **0.86** |
| 30 | Arrastar e soltar | 9 | 9 | 18 | 8.87% | 1 | 1.14% | 1 | 1.32% | **3.92** |
| 31 | Design responsivo  | 9 | 7 | 16 | 7.90% | 5 | 5.95% | 3 | 3.95% | **0.85** |
| 32 | Integração com outras ferramentas | 7 | 5 | 12 | 5.92% | 6 | 7.14% | 4 | 5.26% | **0.59** |
| 33 | Performance rápida e eficiente | 9 | 9 | 18 | 8.87% | 9 | 10.34% | 1 | 1.32% | **0.62** |
| 34 | Confiabilidade | 9 | 9 | 18 | 8.87% | 8 | 9.09% | 1 | 1.32% | **0.74** |
| 35 | Segurança dos dados do usuário | 9 | 9 | 18 | 8.87% | 9 | 10.34% | 2 | 2.63% | **0.61** |
| 36 | Acessibilidade | 8 | 7 | 15 | 7.41% | 4 | 4.76% | 3 | 3.95% | **0.93** |
| 37 | Escalabilidade | 9 | 8 | 17 | 8.40% | 9 | 10.71% | 7 | 8.97% | **0.45** |
| 38 | Internacionalização | 7 | 6 | 13 | 6.41% | 7 | 8.33% | 6 | 7.69% | **0.51** |
| **TOTAL** | **301** | **252** | **553** | **100%** | **113** | **100%** | **89** | **100%** | **--** |
