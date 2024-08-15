## Especificação de Casos de Uso do Aplicativo Canva

**1. Casos de Uso**

A seção de Casos de Uso do aplicativo Canva descreve as principais funcionalidades do sistema. Esses casos de uso incluem a criação de um novo design, a edição de um design existente, o compartilhamento e o download de um design, o acesso a templates prontos, a exploração de recursos premium, a adaptação do design para diferentes formatos, bem como o login e logout da plataforma Canva.

**1.1. UC-01: Criar um Novo Design**

* **Descrição:** Este caso de uso descreve o processo de criação de um novo design no aplicativo Canva, incluindo a seleção de um formato ou modelo, a adição de elementos visuais, texto e outros recursos, bem como a customização do design de acordo com as preferências do usuário.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário seleciona a opção "Criar um Design" na tela inicial.
    2. O sistema apresenta opções de formatos e modelos pré-definidos.
    3. O usuário escolhe um formato ou modelo.
    4. O sistema cria um novo design com o formato/modelo selecionado.
    5. O usuário é direcionado para a interface de edição do novo design.
* **Fluxos Alternativos:**
    * 3a. O usuário pode optar por criar um design com dimensões personalizadas.
    * 3b. O usuário pode iniciar um design a partir de um template vazio.
* **Exceções:**
    * Falha na conexão com a internet durante o processo.

**1.2. UC-02: Editar um Design Existente**

* **Descrição:** Este caso de uso descreve a ação de editar um design existente no Canva, permitindo ao usuário modificar elementos visuais, texto, cores, fontes e outros aspectos do design de forma intuitiva e prática.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção "Seus Designs".
    2. O usuário seleciona o design que deseja editar.
    3. O sistema abre o design na interface de edição.
* **Exceções:**
    * Design inexistente ou sem permissão de edição.
    * Falha na conexão com a internet durante o processo.

**1.3. UC-03: Compartilhar um Design**

* **Descrição:** Este caso de uso descreve a funcionalidade de compartilhamento de design no Canva, permitindo que os usuários compartilhem seus projetos com outras pessoas através de diferentes métodos, como links, redes sociais ou download direto.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário abre o design que deseja compartilhar.
    2. O usuário clica no botão "Compartilhar".
    3. O sistema apresenta opções de compartilhamento (link, email, redes sociais).
    4. O usuário escolhe o método de compartilhamento.
    5. O sistema gera o link/mensagem de compartilhamento.
    6. O usuário compartilha o link/mensagem.
* **Fluxos Alternativos:**
    * 5a.  O usuário pode definir permissões de acesso ao compartilhar (visualizar, editar, comentar).
* **Exceções:**
    * Falha na conexão com a internet durante o processo.

**1.4. UC-04: Baixar um Design**

* **Descrição:** Este caso de uso descreve o processo de download de um design criado no Canva, possibilitando que os usuários salvem seus trabalhos em diferentes formatos, como imagem ou PDF, para uso posterior.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário abre o design que deseja baixar.
    2. O usuário clica no botão "Baixar".
    3. O sistema apresenta opções de formato de arquivo (PNG, JPG, PDF, etc.).
    4. O usuário escolhe o formato desejado.
    5. O sistema gera o arquivo e inicia o download.
* **Fluxos Alternativos:**
    * 4a. Opções de download adicionais (resolução, qualidade) podem ser apresentadas dependendo do tipo de arquivo.
    * 4b.  Alguns formatos ou opções de download podem ser exclusivos para Usuários Pro.
* **Exceções:**
    * Falha na conexão com a internet durante o processo.
    * Limite de downloads atingido para Usuários Gratuitos.

**1.5. UC-05: Acessar Templates Prontos**

* **Descrição:** Este caso de uso descreve a funcionalidade de acesso a templates prontos no Canva, permitindo que os usuários escolham modelos pré-definidos para criar designs de forma rápida e eficiente.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário navega pela página inicial ou utiliza a barra de pesquisa.
    2. O sistema apresenta opções de templates por categoria, formato ou palavra-chave.
    3. O usuário seleciona um template.
    4. O sistema abre o template na interface de edição. 
* **Exceções:**
    *  Falha na conexão com a internet durante o processo.

**1.6. UC-06: Exploração de Recursos Premium**

* **Descrição:** Este caso de uso descreve a exploração dos recursos premium oferecidos pelo Canva, incluindo imagens, elementos gráficos, templates exclusivos e outras funcionalidades avançadas disponíveis para assinantes pagos.
* **Ator:** Usuário Canva (Gratuito e Pro)
* **Fluxo Básico de Eventos:**
    1. O usuário navega pelas funcionalidades da plataforma.
    2. O sistema identifica e sinaliza os recursos exclusivos para usuários Premium. 
    3. O usuário visualiza a descrição e benefícios do recurso Premium. 
* **Fluxos Alternativos:**
    * 3a. Usuário Gratuito pode optar por assinar o plano Premium.
    * 3b. Usuário Pro utiliza o recurso Premium.
* **Exceções:**
    * Falha na conexão com a internet durante o processo.
