# MoSCoW

## Histórico de Versões

| Data       | Descrição                  | Autor         | Versão |
|------------|----------------------------|---------------|--------|
| 29/07/2024 | Primeira versão da análise | Gabriel Moura | [1.0](moscow.md)    |

## Origem

O desenvolvimento deste MoSCoW foi dado a partir da
[Reunião 3](../atas/reuniao03.md).

## Metodologia

## Introdução

A análise MoSCoW é uma técnica de priorização de requisitos amplamente utilizada
em gerenciamento de projetos, especialmente em metodologias ágeis. Ela auxilia
na tomada de decisão sobre quais funcionalidades devem ser implementadas
primeiro, categorizando os requisitos em quatro níveis de prioridade: *must*,
*should*, *could* e *could*. 

Essa técnica é fundamental para garantir que os recursos sejam alocados de forma
eficiente, focando nos requisitos que trazem maior valor para o projeto, dentro
do tempo e do orçamento disponíveis.

## Objetivo

O objetivo da análise MoSCoW é, em conjunto com o que foi aprendido em sala de
aula,  definir quais funcionalidades serão priorizadas no desenvolvimento da
plataforma Canva. Priorizando as funcionalidades que são essenciais para o
funcionamento básico da ferramenta, para posteriormente categorizar as
funcionalidades que agregam valor à experiência do usuário e podem ser
implementadas em versões futuras.

A análise MoSCoW se baseia em quatro categorias:

* **Must (Essencial):** Requisitos **absolutamente essenciais** para o sistema
  funcionar. Se um requisito *must* não for atendido, o projeto é considerado um
  fracasso.
* **Should (Importante):** Requisitos importantes, mas **não essenciais** para o
  lançamento da versão inicial. Podem ser implementados posteriormente, se
  necessário.
* **Could (Desejável):** Requisitos desejáveis que agregam valor, mas **não são
  críticos**. A implementação deles depende de tempo e recursos disponíveis.
* **Would (Opcional):** Requisitos de menor prioridade que podem ser
  considerados em versões futuras.

A equipe analisa cada requisito e o classifica em uma dessas categorias, com
base em seu impacto no projeto, valor para o usuário, custo de implementação e
risco. 

## Artefatos

### Tabela de Requisitos

#### Versão 1.0

##### Tabela de Requisitos Agrupados

<!--
Se alguém for mudar essa tabela, peço que mantenha o formato dela para melhorar
a visualização e compreensão.

Caio Alexandre
-->

| ID | Descrição                                                                     | Prioridade |
|----|-------------------------------------------------------------------------------|------------|
| 1  | Diversidade de formatos de design (posts, banners, apresentações, etc.).      | Must       |
| 2  | Templates personalizáveis para cada formato.                                  | Must       |
| 3  | Criação de designs a partir do zero.                                          | Must       |
| 4  | Importação de imagens e fotos.                                                | Must       |
| 5  | Salvar e exportar designs (PDF, JPG, PNG).                                    | Must       |
| 6  | Importação de vídeos e outros arquivos.                                       | Should     |
| 7  | Exportar designs em formatos adicionais (SVG, MP4, GIF).                      | Should     |
| 8  | Integrar com redes sociais (agendamento de posts).                            | Could      |
| 9  | Ferramentas básicas de edição de imagem (cortar, redimensionar, girar).       | Must       |
| 10 | Ajustar brilho, contraste e saturação de imagens.                             | Must       |
| 11 | Ferramentas de edição de texto (formatação básica, escolha de fontes, cores). | Must       |
| 12 | Adicionar ícones, ilustrações e formas geométricas aos designs.               | Must       |
| 13 | Ferramentas avançadas de edição de imagem (filtros, efeitos, remover fundo).  | Should     |
| 14 | Criar efeitos de texto (sombra, contorno).                                    | Should     |
| 15 | Camadas (organização básica, ordem e visibilidade).                           | Should     |
| 16 | Camadas (opacidade, bloqueio).                                                | Could      |
| 17 | Máscaras (linear, radial).                                                    | Could      |
| 18 | Compartilhamento de designs para visualização.                                | Must       |
| 19 | Compartilhamento de designs para edição com permissões básicas.               | Must       |
| 20 | Edição colaborativa em tempo real.                                            | Should     |
| 21 | Sistema de chat na edição colaborativa.                                       | Could      |
| 22 | Comentários em elementos específicos.                                         | Could      |
| 23 | Grades e guias.                                                               | Must       |
| 24 | Pré-visualização em tempo real.                                               | Must       |
| 25 | Paleta de cores.                                                              | Should     |
| 26 | Guia de estilo.                                                               | Could      |
| 27 | Histórico de versões.                                                         | Could      |
| 28 | Atalhos de teclado.                                                           | Could      |
| 29 | Interface intuitiva e fácil de usar.                                          | Must       |
| 30 | Arrastar e soltar.                                                            | Must       |
| 31 | Design responsivo.                                                            | Should     |
| 32 | Integração com outras ferramentas (redes sociais, armazenamento em nuvem).    | Could      |
| 33 | Performance rápida e eficiente.                                               | Must       |
| 34 | Confiabilidade.                                                               | Must       |
| 35 | Segurança dos dados do usuário.                                               | Must       |
| 36 | Acessibilidade.                                                               | Should     |
| 37 | Escalabilidade.                                                               | Could      |
| 38 | Internacionalização.                                                          | Could      |

##### Tabelas de Requisitos Separadas por Prioridade

###### Must

<!--
Se alguém for mudar essa tabela, peço que mantenha o formato dela para melhorar
a visualização e compreensão.

Caio Alexandre
-->

| ID | Descrição                                                                     |
|----|-------------------------------------------------------------------------------|
| 1  | Diversidade de formatos de design (posts, banners, apresentações, etc.).      |
| 2  | Templates personalizáveis para cada formato.                                  |
| 3  | Criação de designs a partir do zero.                                          | 
| 4  | Importação de imagens e fotos.                                                | 
| 5  | Salvar e exportar designs (PDF, JPG, PNG).                                    | 
| 9  | Ferramentas básicas de edição de imagem (cortar, redimensionar, girar).       | 
| 10 | Ajustar brilho, contraste e saturação de imagens.                             | 
| 11 | Ferramentas de edição de texto (formatação básica, escolha de fontes, cores). | 
| 12 | Adicionar ícones, ilustrações e formas geométricas aos designs.               | 
| 18 | Compartilhamento de designs para visualização.                                |
| 19 | Compartilhamento de designs para edição com permissões básicas.               |
| 23 | Grade e guias.                                                                |
| 24 | Pré-visualização em tempo real.                                               |
| 29 | Interface intuitiva e fácil de usar.                                          |
| 30 | Arrastar e soltar.                                                            |
| 33 | Performance rápida e eficiente.                                               |
| 34 | Confiabilidade.                                                               |
| 35 | Segurança dos dados do usuário.                                               |

###### Should

<!-- TODO(Caio): Melhorar a legibilidade desta tabela. -->

|Nº|Requisito|
|--|---------|
| 6 | Importação de vídeos e outros arquivos | 
| 7 | Exportar designs em formatos adicionais (SVG, MP4, GIF) | 
| 13 | Ferramentas avançadas de edição de imagem (filtros, efeitos, remover fundo) |
| 14 | Criar efeitos de texto (sombra, contorno) | 
| 15 | Camadas (organização básica, ordem e visibilidade) |
| 20 | Edição colaborativa em tempo real  | 
| 25 | Paleta de cores | 
| 31 | Design responsivo  |
| 36 | Acessibilidade | 

###### Could

|Nº|Requisito|
|--|---------|
| 8 | Integrar com redes sociais (agendamento de posts) |
| 16 | Camadas (opacidade, bloqueio) | 
| 17 | Máscaras (linear, radial) |
| 21 | Sistema de chat na edição colaborativa |
| 22 | Comentários em elementos específicos |
| 26 | Guia de estilo |
| 27 | Histórico de versões | 
| 28 | Atalhos de teclado | 
| 32 | Integração com outras ferramentas (redes sociais, armazenamento em nuvem) | 
| 37 | Escalabilidade |
| 38 | Internacionalização | 

###### Would

<!-- TODO(Caio): Melhorar a legibilidade desta tabela. -->

|Nº|Requisito|
|--|---------|
|  |  (Nenhum requisito foi classificado como Would nesta versão) |  
