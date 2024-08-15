# **Especificação de Casos de Uso do Aplicativo Canva**

**1. Casos de Uso**

A seção de Casos de Uso do aplicativo Canva descreve as principais funcionalidades do sistema. Esses casos de uso incluem a criação de um novo design, a edição de um design existente, o compartilhamento e o download de um design, o acesso a templates prontos, a exploração de recursos premium, a adaptação do design para diferentes formatos, bem como o login e logout da plataforma Canva, o gerenciamento de pastas e projetos, a colaboração em tempo real e a utilização de recursos de inteligência artificial.

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
    * Formato ou modelo selecionado não está disponível.
    * Limite de designs atingido para Usuários Gratuitos.

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
    * Limite de compartilhamentos atingido para Usuários Gratuitos.
    * Compartilhamento em redes sociais requer autenticação adicional.

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
    * Template não disponível ou removido.
    * Limite de templates acessados atingido para Usuários Gratuitos.

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

**1.7. UC-07: Adaptação do Design para diversos formatos**

* **Descrição:** Este caso de uso descreve a funcionalidade de redimensionamento de um design existente para diferentes formatos, como redes sociais, banners, cartões de visita, entre outros, garantindo a consistência visual e a qualidade do projeto.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário abre um design existente.
    2. O usuário utiliza a função "Redimensionar" (botão ou menu).
    3. O sistema apresenta opções de formatos pré-definidos. 
    4. O usuário seleciona o novo formato.
    5. O sistema redimensiona o design automaticamente, ajustando os elementos.
* **Fluxos Alternativos:**
    * 4a. O usuário pode optar por redimensionar manualmente, definindo dimensões personalizadas.
* **Exceções:**
    * Distorção de elementos visuais após o redimensionamento automático, necessitando ajustes manuais.

**1.8. UC-08: Logar e Deslogar da plataforma Canva**

* **Descrição:** Este caso de uso descreve o processo de login e logout da plataforma Canva, permitindo que os usuários acessem suas contas de forma segura e realizem o logout quando necessário, garantindo a privacidade de suas informações.
* **Ator:** Usuário Anônimo, Usuário Canva
* **Fluxo Básico de Eventos (Logar):**
    1. O usuário acessa a tela inicial do aplicativo.
    2. O usuário informa seus dados de login (e-mail e senha) ou utiliza credenciais de redes sociais.
    3. O sistema valida as informações.
    4. O usuário é redirecionado para a página inicial da plataforma.
* **Fluxos Alternativos (Logar):**
    * 2a. O usuário pode optar por "Esqueci minha senha" para recuperar o acesso.
    * 4a. O sistema pode solicitar autenticação de dois fatores.
* **Fluxo Básico de Eventos (Deslogar):** 
    1.  O usuário clica na foto de perfil ou ícone de usuário.
    2. O usuário seleciona a opção "Sair".
    3. O sistema encerra a sessão do usuário.
* **Exceções:**
    * Falha na conexão com a internet durante o processo.
    * Dados de login inválidos.

**1.9. UC-09: Gerenciar Pastas e projetos**

* **Descrição:** Este caso de uso descreve a funcionalidade de gerenciamento de pastas e projetos no Canva, permitindo que os usuários organizem seus designs em pastas, criem novas pastas, movam designs entre pastas e excluam pastas e designs.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção "Pastas e Projetos".
    2. O sistema exibe a lista de pastas existentes e designs associados.
    3. O usuário cria uma nova pasta.
    4. O usuário move designs para a nova pasta.
    5. O usuário exclui uma pasta e seus designs associados.
* **Fluxos Alternativos:**
    * 3a. O usuário pode renomear uma pasta existente.
    * 4a. O usuário pode mover designs entre pastas existentes.
    * 5a. O usuário pode restaurar designs excluídos da lixeira.
* **Exceções:**
    * Falha na conexão com a internet durante o processo.
    * Exclusão acidental de designs sem possibilidade de recuperação.
    * Limite de pastas ou designs atingido.
    * O usuário tenta criar uma pasta com um nome já existente no mesmo nível da estrutura de pastas.
    * O usuário tenta realizar uma ação em uma pasta/projeto sem a devida permissão (ex: deletar um projeto compartilhado onde ele possui apenas permissão de visualização).

**1.10. UC-10: Colaborar em tempo real**

* **Descrição:** Este caso de uso descreve a funcionalidade de colaboração em tempo real no Canva, permitindo que os usuários trabalhem em um design simultaneamente, visualizando as alterações em tempo real e interagindo com outros colaboradores.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário abre um design existente.
    2. O usuário clica no botão "Compartilhar para Colaboração".
    3. O sistema gera um link de colaboração.
    4. O usuário compartilha o link com outros colaboradores.
    5. Os colaboradores acessam o link e visualizam o design em tempo real.
    6. Os colaboradores podem editar, comentar ou visualizar o design.
* **Fluxos Alternativos:**
    * 4a. O usuário pode definir permissões de colaboração (visualizar, editar, comentar).
    * 6a. O usuário pode encerrar a colaboração a qualquer momento.
* **Exceções:**
    * Falha na conexão com a internet durante o processo.
    * Limite de colaboradores atingido.
    * Conflitos de edição entre colaboradores.

**1.11. UC-11: Utilizar Recursos de Inteligência Artificial**

* **Descrição:** Este caso de uso descreve a utilização de recursos de inteligência artificial no Canva, como sugestões de design, detecção de cores, recomendações de fontes e outros recursos automatizados que auxiliam os usuários na criação de designs visualmente atraentes.

* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção de edição de um design.
    2. O sistema identifica elementos visuais e texto no design.
    3. O sistema sugere cores, fontes, imagens ou elementos gráficos com base no conteúdo do design.
    4. O usuário aceita ou rejeita as sugestões.
* **Exceções:**
    * Falha na conexão com o internet durante o processo.

**2. Modelo de Casos de Uso:**

**2.1. Atores:**

* Usuário Anônimo: Qualquer pessoa que acessa o aplicativo Canva sem estar logado.
* Usuário Canva: Pessoa cadastrada na plataforma, podendo ser um Usuário Gratuito ou Usuário Pro (assinante).

**2.2. Fluxo Básico de Eventos:**

Descrito em cada caso de uso (UC-XX).

**2.3. Fluxos Alternativos e Excepcionais:**

Descritos em cada caso de uso (UC-XX).

**3. Considerações Finais:**

**3.1. Benefícios da Especificação de Casos de Uso:**

* Define o comportamento esperado do sistema do ponto de vista do usuário.
* Facilita a comunicação entre desenvolvedores, designers e stakeholders.
* Auxilia na identificação de requisitos funcionais e não funcionais.
* Serve como base para testes e validação do sistema.
