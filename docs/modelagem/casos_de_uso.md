# **Especificação de Casos de Uso**

**1. Casos de Uso**

A seção de Casos de Uso do aplicativo Canva descreve as principais funcionalidades do sistema. Esses casos incluem:

- [UC-01: Criar um Novo Design](#11-uc-01-criar-um-novo-design)
- [UC-02: Editar um Design Existente](#12-uc-02-editar-um-design-existente)
- [UC-03: Compartilhar um Design](#13-uc-03-compartilhar-um-design)
- [UC-04: Baixar um Design](#14-uc-04-baixar-um-design)
- [UC-05: Acessar Templates Prontos](#15-uc-05-acessar-templates-prontos)
- [UC-06: Exploração de Recursos Premium](#16-uc-06-exploração-de-recursos-premium)
- [UC-07: Adaptação do Design para diversos formatos](#17-uc-07-adaptação-do-design-para-diversos-formatos)
- [UC-08: Logar na plataforma Canva](#18-uc-08-logar-na-plataforma-canva)
- [UC-09: Logout da plataforma Canva](#19-uc-09-logout-da-plataforma-canva)
- [UC-010: Gerenciar Pastas e projetos](#110-uc-010-gerenciar-pastas-e-projetos)
- [UC-011: Colaborar em tempo real](#111-uc-011-colaborar-em-tempo-real)
- [UC-012: Utilizar Recursos de Inteligência Artificial](#112-uc-012-utilizar-recursos-de-inteligência-artificial)
- [UC-013: Acessar Recursos de Aprendizado](#113-uc-013-acessar-recursos-de-aprendizado)
- [UC-014: Personalizar Configurações de Conta](#114-uc-014-personalizar-configurações-de-conta)
- [UC-015: Acessar Suporte e Atendimento ao Cliente](#115-uc-015-acessar-suporte-e-atendimento-ao-cliente)
- [UC-016: Acessar Recursos de Colaboração](#116-uc-016-acessar-recursos-de-colaboração)
- [UC-017: Acessar Recursos de Marketing](#117-uc-017-acessar-recursos-de-marketing)
- [UC-018: Acessar Recursos de Design Gráfico](#118-uc-018-acessar-recursos-de-design-gráfico)
- [UC-019: Acessar Recursos de Fotografia](#119-uc-019-acessar-recursos-de-fotografia)
- [UC-020: Acessar Recursos de Vídeo](#120-uc-020-acessar-recursos-de-vídeo)
- [UC-021: Acessar Recursos de Áudio](#121-uc-021-acessar-recursos-de-áudio)



## **1.1. UC-01: Criar um Novo Design**

* **Descrição:** Este caso de uso descreve o processo de criação de um novo design no aplicativo Canva, incluindo a seleção de um formato ou modelo, a adição de elementos visuais, texto e outros recursos, bem como a customização do design de acordo com as preferências do usuário.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário seleciona a opção "Criar um Design" na tela inicial.
    2. O sistema apresenta opções de formatos e modelos pré-definidos.
    3. O usuário escolhe um formato ou modelo.
    4. O sistema cria um novo design com o formato/modelo selecionado.
    5. O usuário é direcionado para a interface de edição do novo design.
* **Fluxo Alternativo:**
    1. O usuário pode optar por criar um design com dimensões personalizadas.
    2. O usuário pode iniciar um design a partir de um template vazio.
* **Fluxo de Exceções:**
    1. Falha na conexão com a internet durante o processo.
    2. Formato ou modelo selecionado não está disponível.
    3. Limite de designs atingido para Usuários Gratuitos.

## **1.2. UC-02: Editar um Design Existente**

* **Descrição:** Este caso de uso descreve a ação de editar um design existente no Canva, permitindo ao usuário modificar elementos visuais, texto, cores, fontes e outros aspectos do design de forma intuitiva e prática.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção "Seus Designs".
    2. O usuário seleciona o design que deseja editar.
    3. O sistema abre o design na interface de edição.
* **Fluxo Alternativo:**
    1. O usuário pode duplicar o design antes de editar.
    2. O usuário pode acessar o histórico de revisões do design.
    3. O usuário pode adicionar colaboradores para edição em tempo real.
    4. O usuário pode acessar recursos de inteligência artificial para sugestões de design.
* **Fluxo de Exceções:**
    1. Design inexistente ou sem permissão de edição.
    2. Falha na conexão com a internet durante o processo.

## **1.3. UC-03: Compartilhar um Design**

* **Descrição:** Este caso de uso descreve a funcionalidade de compartilhamento de design no Canva, permitindo que os usuários compartilhem seus projetos com outras pessoas através de diferentes métodos, como links, redes sociais ou download direto.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário abre o design que deseja compartilhar.
    2. O usuário clica no botão "Compartilhar".
    3. O sistema apresenta opções de compartilhamento (link, email, redes sociais).
    4. O usuário escolhe o método de compartilhamento.
    5. O sistema gera o link/mensagem de compartilhamento.
    6. O usuário compartilha o link/mensagem.
* **Fluxo Alternativo:**
    1.  O usuário pode definir permissões de acesso ao compartilhar (visualizar, editar, comentar).
    2.  O usuário pode definir uma data de expiração para o compartilhamento.
    3.  O usuário pode adicionar uma senha de acesso ao compartilhamento.
    4.  O usuário pode compartilhar diretamente em redes sociais.
* **Fluxo de Exceções:**
    1. Falha na conexão com a internet durante o processo.
    2. Limite de compartilhamentos atingido para Usuários Gratuitos.
    3. Compartilhamento em redes sociais requer autenticação adicional.

## **1.4. UC-04: Baixar um Design**

* **Descrição:** Este caso de uso descreve o processo de download de um design criado no Canva, possibilitando que os usuários salvem seus trabalhos em diferentes formatos, como imagem ou PDF, para uso posterior.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário abre o design que deseja baixar.
    2. O usuário clica no botão "Baixar".
    3. O sistema apresenta opções de formato de arquivo (PNG, JPG, PDF, etc.).
    4. O usuário escolhe o formato desejado.
    5. O sistema gera o arquivo e inicia o download.
* **Fluxo Alternativo:**
    1. Opções de download adicionais (resolução, qualidade) podem ser apresentadas dependendo do tipo de arquivo.
    2.  Alguns formatos ou opções de download podem ser exclusivos para Usuários Pro.
* **Fluxo de Exceções:**
    1. Falha na conexão com a internet durante o processo.
    2. Limite de downloads atingido para Usuários Gratuitos.

## **1.5. UC-05: Acessar Templates Prontos**

* **Descrição:** Este caso de uso descreve a funcionalidade de acesso a templates prontos no Canva, permitindo que os usuários escolham modelos pré-definidos para criar designs de forma rápida e eficiente.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário navega pela página inicial ou utiliza a barra de pesquisa.
    2. O sistema apresenta opções de templates por categoria, formato ou palavra-chave.
    3. O usuário seleciona um template.
    4. O sistema abre o template na interface de edição. 
* **Fluxo Alternativo:**
    1. O usuário pode favoritar um template para acesso rápido.
    2. O usuário pode visualizar designs relacionados ao template selecionado.
    3. O usuário pode acessar templates exclusivos para Usuários Pro.
* **Fluxo de Exceções:**
    1.  Falha na conexão com a internet durante o processo.
    2. Template não disponível ou removido.
    3. Limite de templates acessados atingido para Usuários Gratuitos.

## **1.6. UC-06: Exploração de Recursos Premium**

* **Descrição:** Este caso de uso descreve a exploração dos recursos premium oferecidos pelo Canva, incluindo imagens, elementos gráficos, templates exclusivos e outras funcionalidades avançadas disponíveis para assinantes pagos.
* **Ator:** Usuário Canva (Gratuito e Pro)
* **Fluxo Básico de Eventos:**
    1. O usuário navega pelas funcionalidades da plataforma.
    2. O sistema identifica e sinaliza os recursos exclusivos para usuários Premium. 
    3. O usuário visualiza a descrição e benefícios do recurso Premium. 
* **Fluxo Alternativo:**
    1. Usuário Gratuito pode optar por assinar o plano Premium.
    2. Usuário Pro utiliza o recurso Premium.
    3. Usuário Pro pode acessar recursos
* **Fluxo de Exceções:**
    1. Falha na conexão com a internet durante o processo.
    2. Recurso Premium não disponível no momento.
    3. Usuário Gratuito tenta acessar recurso exclusivo para Usuários Pro.

## **1.7. UC-07: Adaptação do Design para diversos formatos**

* **Descrição:** Este caso de uso descreve a funcionalidade de redimensionamento de um design existente para diferentes formatos, como redes sociais, banners, cartões de visita, entre outros, garantindo a consistência visual e a qualidade do projeto.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário abre um design existente.
    2. O usuário utiliza a função "Redimensionar" (botão ou menu).
    3. O sistema apresenta opções de formatos pré-definidos. 
    4. O usuário seleciona o novo formato.
    5. O sistema redimensiona o design automaticamente, ajustando os elementos.
* **Fluxo Alternativo:**
    1. O usuário pode optar por redimensionar manualmente, definindo dimensões personalizadas.
    2. O usuário pode salvar o design em diferentes formatos para uso posterior.
* **Fluxo de Exceções:**
    1. Distorção de elementos visuais após o redimensionamento automático, necessitando ajustes manuais.
    2. Falha na conexão com a internet durante o processo.

## **1.8. UC-08: Logar na plataforma Canva**

* **Descrição:** Este caso de uso descreve o processo de login na plataforma Canva, permitindo que os usuários acessem suas contas de forma segura e acessem recursos exclusivos disponíveis para usuários cadastrados.
* **Ator:** Usuário Anônimo, Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a tela inicial do aplicativo.
    2. O usuário informa seus dados de login (e-mail e senha) ou utiliza credenciais de redes sociais.
    3. O sistema valida as informações.
    4. O usuário é redirecionado para a página inicial da plataforma.
* **Fluxo Alternativo:**
    1. O usuário pode optar por "Esqueci minha senha" para recuperar o acesso.
    2. O sistema pode solicitar autenticação de dois fatores.
* **Fluxo de Exceções:**
    1. Falha na conexão com a internet durante o processo.
    2. Dados de login inválidos.

## **1.9. UC-09: Logout da plataforma Canva**

* **Descrição:** Este caso de uso descreve o processo de logout da plataforma Canva, permitindo que os usuários encerrem suas sessões de forma segura e garantam a privacidade de suas informações.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário clica na foto de perfil ou ícone de usuário.
    2. O usuário seleciona a opção "Sair".
    3. O sistema encerra a sessão do usuário.
* **Fluxo Alternativo:**
    1. O usuário pode optar por "Permanecer Conectado" para manter a sessão ativa.
* **Fluxo de Exceções:**
    1. Falha na conexão com a internet durante o processo.


## **1.10. UC-010: Gerenciar Pastas e projetos**

* **Descrição:** Este caso de uso descreve a funcionalidade de gerenciamento de pastas e projetos no Canva, permitindo que os usuários organizem seus designs em pastas, criem novas pastas, movam designs entre pastas e excluam pastas e designs.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção "Pastas e Projetos".
    2. O sistema exibe a lista de pastas existentes e designs associados.
    3. O usuário cria uma nova pasta.
    4. O usuário move designs para a nova pasta.
    5. O usuário exclui uma pasta e seus designs associados.
* **Fluxo Alternativo:**
    1. O usuário pode renomear uma pasta existente.
    2. O usuário pode mover designs entre pastas existentes.
    3. O usuário pode restaurar designs excluídos da lixeira.
* **Fluxo de Exceções:**
    1. Falha na conexão com a internet durante o processo.
    2. Exclusão acidental de designs sem possibilidade de recuperação.
    3. Limite de pastas ou designs atingido.
    4. O usuário tenta criar uma pasta com um nome já existente no mesmo nível da estrutura de pastas.
    5. O usuário tenta realizar uma ação em uma pasta/projeto sem a devida permissão (ex: deletar um projeto compartilhado onde ele possui apenas permissão de visualização).

## **1.11. UC-11: Colaborar em tempo real**

* **Descrição:** Este caso de uso descreve a funcionalidade de colaboração em tempo real no Canva, permitindo que os usuários trabalhem em um design simultaneamente, visualizando as alterações em tempo real e interagindo com outros colaboradores.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário abre um design existente.
    2. O usuário clica no botão "Compartilhar para Colaboração".
    3. O sistema gera um link de colaboração.
    4. O usuário compartilha o link com outros colaboradores.
    5. Os colaboradores acessam o link e visualizam o design em tempo real.
    6. Os colaboradores podem editar, comentar ou visualizar o design.
* **Fluxo Alternativo:**
    1. O usuário pode definir permissões de colaboração (visualizar, editar, comentar).
    2. O usuário pode encerrar a colaboração a qualquer momento.
    3. O usuário pode visualizar o histórico de edições e comentários.
* **Fluxo de Exceções:**
    1. Falha na conexão com a internet durante o processo.
    2. Limite de colaboradores atingido.
    3. Conflitos de edição entre colaboradores.

## **1.12. UC-12: Utilizar Recursos de Inteligência Artificial**

* **Descrição:** Este caso de uso descreve a utilização de recursos de inteligência artificial no Canva, como sugestões de design, detecção de cores, recomendações de fontes e outros recursos automatizados que auxiliam os usuários na criação de designs visualmente atraentes.

* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção de edição de um design.
    2. O sistema identifica elementos visuais e texto no design.
    3. O sistema sugere cores, fontes, imagens ou elementos gráficos com base no conteúdo do design.
    4. O usuário aceita ou rejeita as sugestões.
* **Fluxo Alternativo:**
    1. O usuário pode solicitar sugestões específicas para um elemento visual ou texto.
    2. O usuário pode desativar os recursos de inteligência artificial.
* **Fluxo de Exceções:**
    1. Falha na conexão com o internet durante o processo.
    2. Sugestões inadequadas ou imprecisas.

## **1.13. UC-13: Acessar Recursos de Aprendizado**

* **Descrição:** Este caso de uso descreve a funcionalidade de acesso a recursos de aprendizado no Canva, como tutoriais, dicas, guias e cursos online, que auxiliam os usuários a explorar as funcionalidades da plataforma, aprimorar suas habilidades de design e obter inspiração para seus projetos.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção de "Recursos de Aprendizado".
    2. O sistema exibe uma lista de tutoriais, dicas e cursos disponíveis.
    3. O usuário seleciona um recurso de aprendizado.
    4. O sistema abre o recurso selecionado para visualização.
* **Fluxo Alternativo:**
    1. O usuário pode filtrar os recursos por categoria, nível de dificuldade ou interesse.
    2. O usuário pode marcar recursos como favoritos para acesso rápido.
* **Fluxo de Exceções:**
    1. Falha na conexão com a internet durante o processo.
    2. Recurso de aprendizado não disponível no momento.
    3. Usuário Gratuito tenta acessar recurso exclusivo para Usuários Pro.

## **1.14. UC-14: Personalizar Configurações de Conta**

* **Descrição:** Este caso de uso descreve a funcionalidade de personalização das configurações de conta no Canva, permitindo que os usuários atualizem suas informações pessoais, preferências de design, notificações, privacidade e outras configurações relacionadas à sua conta.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção de "Configurações de Conta".
    2. O sistema exibe opções de personalização disponíveis.
    3. O usuário atualiza suas informações pessoais (nome, e-mail, senha, etc.).
    4. O usuário configura suas preferências de design (cores, fontes, estilos).
    5. O usuário define suas preferências de notificações (e-mail, push).
    6. O usuário ajusta suas configurações de privacidade (compartilhamento, visibilidade).
* **Fluxo Alternativo:**
    1. O usuário pode ativar/desativar recursos de inteligência artificial.
    2. O usuário pode definir permissões de colaboração padrão.
    3. O usuário pode configurar a autenticação de dois fatores.
* **Fluxo de Exceções:**

    1. Falha na conexão com a internet durante o processo.
    2. Dados inválidos ou incompletos.
    3. Configurações não salvas corretamente.

## **1.15. UC-15: Acessar Suporte e Atendimento ao Cliente**

* **Descrição:** Este caso de uso descreve a funcionalidade de acesso ao suporte e atendimento ao cliente no Canva, permitindo que os usuários obtenham ajuda, tirem dúvidas, relatem problemas, solicitem recursos ou forneçam feedback sobre a plataforma.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção de "Suporte e Atendimento".
    2. O sistema exibe opções de contato (chat, e-mail, telefone).
    3. O usuário seleciona o método de contato preferido.
    4. O sistema inicia o atendimento ao cliente.
* **Fluxo Alternativo:**
    1. O usuário pode acessar a base de conhecimento ou FAQ.
    2. O usuário pode enviar feedback ou sugestões de melhorias.
* **Fluxo de Exceções:**
    1. Falha na conexão com o internet durante o processo.
    2. Tempo de espera prolongado para atendimento.
    3. Resolução inadequada do problema ou dúvida.

## **1.16. UC-16: Acessar Recursos de Colaboração**

* **Descrição:** Este caso de uso descreve a funcionalidade de acesso a recursos de colaboração no Canva, como comentários, revisões, aprovações, marcações, compartilhamento de projetos e outras ferramentas que facilitam a comunicação e o trabalho em equipe.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção de "Recursos de Colaboração".
    2. O sistema exibe opções de colaboração disponíveis.
    3. O usuário seleciona um recurso de colaboração.
    4. O sistema abre o recurso selecionado para utilização.
* **Fluxo Alternativo:**
    1. O usuário pode adicionar comentários em designs compartilhados.
    2. O usuário pode solicitar revisões ou aprovações de projetos.
    3. O usuário pode marcar outros colaboradores em designs.
* **Fluxo de Exceções:**
    1. Falha na conexão com o internet durante o processo.
    2. Recurso de colaboração não disponível no momento.
    3. Usuário Gratuito tenta acessar recurso exclusivo para Usuários Pro.

## **1.17. UC-17: Acessar Recursos de Marketing**

* **Descrição:** Este caso de uso descreve a funcionalidade de acesso a recursos de marketing no Canva, como modelos de cartões de visita, banners, flyers, posts para redes sociais, apresentações, entre outros, que auxiliam os usuários a criar materiais promocionais de forma rápida e profissional.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção de "Recursos de Marketing".
    2. O sistema exibe opções de templates disponíveis por categoria (negócios, eventos, vendas, etc.).
    3. O usuário seleciona um template de marketing.
    4. O sistema abre o template selecionado para edição.
* **Fluxo Alternativo:**
    1. O usuário pode personalizar o template de acordo com suas necessidades.
    2. O usuário pode salvar o design em diferentes formatos para uso posterior.
* **Fluxo de Exceções:**
    1. Falha na conexão com o internet durante o processo.
    2. Template de marketing não disponível no momento.
    3. Usuário Gratuito tenta acessar template exclusivo para Usuários Pro.

## **1.18. UC-18: Acessar Recursos de Design Gráfico**

* **Descrição:** Este caso de uso descreve a funcionalidade de acesso a recursos de design gráfico no Canva, como ícones, ilustrações, formas, texturas, fundos, paletas de cores, fontes, entre outros, que auxiliam os usuários a criar designs visualmente atraentes e profissionais.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção de "Recursos de Design Gráfico".
    2. O sistema exibe opções de recursos disponíveis por categoria (ícones, ilustrações, formas, etc.).
    3. O usuário seleciona um recurso de design gráfico.
    4. O sistema abre o recurso selecionado para utilização.
* **Fluxo Alternativo:**
    1. O usuário pode pesquisar recursos por palavra-chave ou categoria.
    2. O usuário pode favoritar recursos para acesso rápido.
* **Fluxo de Exceções:**
    1. Falha na conexão com o internet durante o processo.
    2. Recurso de design gráfico não disponível no momento.
    3. Usuário Gratuito tenta acessar recurso exclusivo para Usuários Pro.

## **1.19. UC-19: Acessar Recursos de Fotografia** 

* **Descrição:** Este caso de uso descreve a funcionalidade de acesso a recursos de fotografia no Canva, como imagens, fotos, ilustrações, fundos, texturas, filtros, efeitos, entre outros, que auxiliam os usuários a criar designs visualmente atraentes e profissionais.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção de "Recursos de Fotografia".
    2. O sistema exibe opções de recursos disponíveis por categoria (imagens, fotos, ilustrações, etc.).
    3. O usuário seleciona um recurso de fotografia.
    4. O sistema abre o recurso selecionado para utilização.
* **Fluxo Alternativo:**
    1. O usuário pode pesquisar recursos por palavra-chave ou categoria.
    2. O usuário pode favoritar recursos para acesso rápido.
* **Fluxo de Exceções:**
    1. Falha na conexão com o internet durante o processo.
    2. Recurso de fotografia não disponível no momento.
    3. Usuário Gratuito tenta acessar recurso exclusivo para Usuários Pro.

## **1.20. UC-20: Acessar Recursos de Vídeo**

* **Descrição:** Este caso de uso descreve a funcionalidade de acesso a recursos de vídeo no Canva, como vídeos, animações, transições, efeitos, trilhas sonoras, narrações, entre outros, que auxiliam os usuários a criar designs audiovisuais atraentes e profissionais.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção de "Recursos de Vídeo".
    2. O sistema exibe opções de recursos disponíveis por categoria (vídeos, animações, transições, etc.).
    3. O usuário seleciona um recurso de vídeo.
    4. O sistema abre o recurso selecionado para utilização.
* **Fluxo Alternativo:**
    1. O usuário pode pesquisar recursos por palavra-chave ou categoria.
    2. O usuário pode favoritar recursos para acesso rápido.
* **Fluxo de Exceções:**
    1. Falha na conexão com o internet durante o processo.
    2. Recurso de vídeo não disponível no momento.
    3. Usuário Gratuito tenta acessar recurso exclusivo para Usuários Pro.

## **1.21. UC-21: Acessar Recursos de Áudio**

* **Descrição:** Este caso de uso descreve a funcionalidade de acesso a recursos de áudio no Canva, como músicas, efeitos sonoros, narrações, trilhas sonoras, entre outros, que auxiliam os usuários a criar designs audiovisuais atraentes e profissionais.
* **Ator:** Usuário Canva
* **Fluxo Básico de Eventos:**
    1. O usuário acessa a seção de "Recursos de Áudio".
    2. O sistema exibe opções de recursos disponíveis por categoria (músicas, efeitos sonoros, narrações, etc.).
    3. O usuário seleciona um recurso de áudio.
    4. O sistema abre o recurso selecionado para utilização.
* **Fluxo Alternativo:**
    1. O usuário pode pesquisar recursos por palavra-chave ou categoria.
    2. O usuário pode favoritar recursos para acesso rápido.
* **Fluxo de Exceções:**
    1. Falha na conexão com o internet durante o processo.
    2. Recurso de áudio não disponível no momento.
    3. Usuário Gratuito tenta acessar recurso exclusivo para Usuários Pro.



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
