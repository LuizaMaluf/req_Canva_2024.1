# MoSCoW

## Histórico de Versões

| Data       | Descrição                  | Autor         | Versão |
|------------|----------------------------|---------------|--------|
| 29/07/2024 | Primeira versão da análise | Gabriel Moura | [1.0](../../elicitacao/moscow.md) |
| 03/09/2024 | Correção do MoSCoW após a inspeção | Luiza Maluf | [2.0](moscow_corrigido.md) |

## Origem

O desenvolvimento deste MoSCoW foi dado a partir da
[Reunião 3](../../atas/reuniao03.md).

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

### Justificativa e impacto de cada priorização

1. **Diversidade de formatos de design (posts, banners, apresentações, etc.):** Essencial para atender às diversas necessidades dos usuários, garantindo flexibilidade na criação de diferentes tipos de conteúdo. Sem isso, o valor central da plataforma é comprometido.

    - **Impacto:** Permite criar uma ampla gama de conteúdos para diferentes finalidades, oferecendo flexibilidade e atendendo a diversas necessidades.

2. **Templates personalizáveis para cada formato:** Facilita a criação e aumenta a acessibilidade, especialmente para usuários menos experientes. Essencial para usabilidade básica.

    - **Impacto:** Facilita a criação de designs ao fornecer estruturas pré-feitas que podem ser adaptadas, tornando o processo mais rápido e acessível.

3. **Criação de designs a partir do zero:** Oferece liberdade criativa, permitindo que os usuários expressem suas ideias sem limitações, fundamental para um editor de design.

    - **Impacto:** Oferece total liberdade criativa, permitindo que os usuários criem designs únicos e personalizados de acordo com suas visões.

4. **Importação de imagens e fotos:** Necessário para personalização e criação de designs únicos, permitindo a inclusão de elementos visuais próprios dos usuários.

    - **Impacto:** Permite adicionar elementos visuais pessoais aos designs, tornando-os mais relevantes e personalizados.

5. **Salvar e exportar designs (PDF, JPG, PNG):** Essencial para uso e compartilhamento dos designs criados em formatos amplamente suportados, garantindo aplicabilidade prática.

    - **Impacto:** Facilita o uso e compartilhamento dos designs em formatos amplamente aceitos, aumentando a praticidade.

6. **Importação de vídeos e outros arquivos:** Importante para suportar multimídia, enriquecendo os designs, mas não essencial para o lançamento inicial.

    - **Impacto:** Adiciona a capacidade de trabalhar com multimídia, enriquecendo os designs com diferentes tipos de mídia.

7. **Exportar designs em formatos adicionais (SVG, MP4, GIF):** Fornece flexibilidade e opções adicionais de uso, atendendo a necessidades específicas de alguns projetos.

    - **Impacto:** Oferece mais opções para uso e compartilhamento dos designs, atendendo a necessidades específicas de alguns projetos.

8. **Integrar com redes sociais (agendamento de posts):** Agrega conveniência ao permitir a publicação direta, mas não é essencial para o funcionamento básico.

    - **Impacto:** Permite a publicação direta dos designs nas redes sociais, economizando tempo e simplificando o processo de marketing.

9. **Ferramentas básicas de edição de imagem (cortar, redimensionar, girar):** Oferece controle básico sobre elementos visuais, essencial em qualquer editor de design.

    - **Impacto:** Dá controle básico sobre a modificação de imagens, permitindo ajustes simples e rápidos.

10. **Ajustar brilho, contraste e saturação de imagens:** Necessário para ajustes básicos de qualidade visual, facilitando melhorias intuitivas nos designs.

    - **Impacto:** Melhora a qualidade visual dos designs com ajustes simples e intuitivos.

11. **Ferramentas de edição de texto (formatação básica, escolha de fontes, cores):** Essenciais para a criação de textos personalizados e visuais atrativos nos designs.

    - **Impacto:** Permite personalizar textos de forma eficaz, criando designs visualmente atraentes e com conteúdo bem formatado.

12. **Adicionar ícones, ilustrações e formas geométricas aos designs:** Enriquecem os designs e oferecem uma ampla gama de opções criativas.

    - **Impacto:** Enriquecem os designs com elementos visuais variados, proporcionando mais opções criativas.

13. **Ferramentas avançadas de edição de imagem (filtros, efeitos, remover fundo):** Adicionam valor e aprimoram os designs, mas podem ser implementadas após o lançamento inicial.

    - **Impacto:** Permite melhorias e personalizações mais sofisticadas nas imagens, aprimorando a qualidade dos designs.

14. **Criar efeitos de texto (sombra, contorno):** Melhora a aparência dos textos com opções de estilização avançadas, importantes para designs sofisticados.

    - **Impacto:** Melhora a estética dos textos com opções de estilização adicionais, tornando-os mais impactantes.

15. **Camadas (organização básica, ordem e visibilidade):** Facilita a manipulação e organização de elementos em projetos complexos.

    - **Impacto:** Facilita a organização de elementos em projetos complexos, permitindo uma manipulação mais precisa.

16. **Camadas (opacidade, bloqueio):** Recursos adicionais para controle avançado de camadas, úteis para designs precisos, mas não essenciais inicialmente.

    - **Impacto:** Oferece controle avançado sobre a visibilidade e edição de camadas, útil para designs mais detalhados.

17. **Máscaras (linear, radial):** Oferece controle criativo para efeitos visuais complexos, mas não é crítico para a funcionalidade básica.

    - **Impacto:** Proporciona controle criativo para aplicar efeitos visuais avançados, aumentando as possibilidades de design.

18. **Compartilhamento de designs para visualização:** Fundamental para colaboração e revisão, permitindo fácil compartilhamento de projetos.

    - **Impacto:** Facilita a revisão e o feedback dos designs, permitindo que outras pessoas vejam e comentem os projetos.

19. **Compartilhamento de designs para edição com permissões básicas:** Suporta a colaboração com controles de permissão, essencial para trabalhos em equipe.

    - **Impacto:** Permite a colaboração com outros usuários, ajustando permissões para editar ou visualizar, essencial para o trabalho em equipe.

20. **Edição colaborativa em tempo real:** Melhora a eficiência de equipes, sendo implementável após a funcionalidade básica de colaboração.

    - **Impacto:** Melhora a eficiência de equipes ao permitir edição simultânea, promovendo uma colaboração mais fluida.

21. **Sistema de chat na edição colaborativa:** Facilita comunicação durante a edição, mas não é crítico para o funcionamento colaborativo inicial.

    - **Impacto:** Facilita a comunicação durante o processo de edição colaborativa, embora não seja essencial inicialmente.

22. **Comentários em elementos específicos:** Adiciona valor à revisão colaborativa, permitindo feedback direto em elementos.

    - **Impacto:** Permite fornecer feedback direto e específico sobre partes dos designs, melhorando a revisão colaborativa.

23. **Grades e guias:** Essenciais para organização precisa dos designs, ajudando no alinhamento de elementos.

    - **Impacto:** Auxilia na organização e alinhamento preciso dos elementos, garantindo uma estrutura mais limpa e profissional.

24. **Pré-visualização em tempo real:** Permite visualização imediata das mudanças feitas, melhorando a precisão e experiência de edição.

    - **Impacto:** Oferece uma visualização imediata das alterações feitas, ajudando a ajustar e refinar os designs com mais precisão.

25. **Paleta de cores:** Ajuda a manter consistência visual e personalização, importante, mas não essencial para a funcionalidade básica.

    - **Impacto:** Ajuda a manter a consistência visual e personalização dos designs, melhorando a coesão estética.

26. **Guia de estilo:** Útil para consistência, especialmente em equipes, mas pode ser implementado depois.

    - **Impacto:** Auxilia na manutenção da consistência em projetos, especialmente em equipes, garantindo uma identidade visual uniforme.

27. **Histórico de versões:** Permite reverter mudanças e acompanhar o progresso, útil para projetos complexos, mas não essencial para lançamento inicial.

    - **Impacto:** Permite reverter alterações e acompanhar o progresso, útil para gerenciar mudanças e manter o controle dos projetos.

28. **Atalhos de teclado:** Melhora a eficiência para usuários avançados, mas não é crítico para uso básico.

    - **Impacto:** Melhora a eficiência para usuários avançados, tornando o processo de edição mais rápido e ágil.

29. **Interface intuitiva e fácil de usar:** Essencial para acessibilidade e satisfação, aumentando adesão e uso da plataforma.

    - **Impacto:** Facilita o uso da plataforma, tornando-a mais acessível e agradável, especialmente para novos usuários.

30. **Arrastar e soltar:** Torna a manipulação de elementos mais intuitiva, essencial para boa experiência do usuário.

    - **Impacto:** Torna a manipulação de elementos mais intuitiva, simplificando a edição e a organização dos designs.

31. **Design responsivo:** Garante bom funcionamento em diferentes dispositivos, importante para acessibilidade, mas pode ser melhorado gradualmente.

    - **Impacto:** Garante que os designs funcionem bem em diferentes dispositivos, melhorando a acessibilidade e a experiência do usuário.

32. **Integração com outras ferramentas (redes sociais, armazenamento em nuvem):** Facilita fluxo de trabalho, mas é um recurso adicional para versões futuras.

    - **Impacto:** Facilita o fluxo de trabalho e o gerenciamento de arquivos, embora seja um recurso adicional para versões futuras.

33. **Performance rápida e eficiente:** Essencial para manter a usabilidade e satisfação do usuário, evitando frustrações.

    - **Impacto:** Assegura uma experiência de uso fluida e sem frustrações, mantendo a satisfação com a plataforma.

34. **Confiabilidade:** Necessária para a confiança dos usuários na plataforma, essencial para a credibilidade.

    - **Impacto:** Garante que a plataforma funcione de forma consistente, fortalecendo a confiança e a credibilidade entre os usuários.

35. **Segurança dos dados do usuário:** Crítica para proteção de informações pessoais, essencial para conformidade e confiança.

    - **Impacto:** Protege informações pessoais e dados sensíveis, essencial para a confiança e conformidade com regulamentações.

36. **Acessibilidade:** Importante para inclusão, melhorando o uso para pessoas com necessidades especiais, mas pode ser ajustada com o tempo.

    - **Impacto:** Melhora a inclusão de pessoas com necessidades especiais, tornando a plataforma mais acessível a um público mais amplo.

37. **Escalabilidade:** Permite crescimento sem perda de performance, importante para o futuro, mas não crítico inicialmente.

    - **Impacto:** Permite que a plataforma cresça e se adapte à medida que mais usuários e recursos são adicionados, garantindo uma boa experiência a longo prazo.

38. **Internacionalização:** Facilita o uso global da plataforma, útil para expansão, mas não é necessário para o lançamento inicial.

    - **Impacto:** Facilita o uso da plataforma em diferentes regiões e idiomas, permitindo a expansão global e melhor atendimento a um público diversificado.
