# __Especificação Suplementar__

| Data       | Descrição | Autor | Versão |
| ---------- | ------ | --------- | ----- |
| 16/08/2024 | Criação do documento e definição dos requisitos não funcionais após análise de casos de uso | Henrique Quenino | 0.1 |
| 17/08/2024 | Revisão e ajustes dos requisitos não funcionais | Henrique Quenino | [1.0](../../modelagem/especificacao_suplementar.md) |
| 03/09/2024 | Correção da especificação suplementar após a inspeção | Luiza Maluf | [2.0](esp_suplementar_corrigido.md)

## Origem

A Especificação Suplementar foi criada após a análise dos casos de uso do site Canva, com o objetivo de definir os requisitos não funcionais essenciais para o desenvolvimento e operação da plataforma.

## Metodologia

Os requisitos não funcionais foram identificados considerando as necessidades dos usuários, as restrições do sistema e as melhores práticas de desenvolvimento de software, tendo em vista os [casos de usos](../../modelagem/casos_de_uso.md) produzidos durante a modelagem dos requisitos.


## __1. Introdução__

Este documento descreve a Especificação Suplementar do site Canva, complementando a Especificação de Casos de Uso. Ele detalha os requisitos não funcionais, incluindo requisitos de desempenho, segurança, usabilidade e outros, essenciais para o sucesso da plataforma.

## **2. Requisitos Não Funcionais**

### __2.1. Desempenho__

* __Tempo de Carregamento:__ O site deve carregar em menos de 3 segundos em uma conexão de banda larga (5 Mbps) para 80% das requisições.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-08](../../modelagem/casos_de_uso.md#18-uc-08-logar-na-plataforma-canva)

* __Tempo de Resposta:__ As interações do usuário, como arrastar e soltar elementos, aplicar filtros e salvar designs, devem ocorrer em tempo real, com um tempo de resposta máximo de 0,5 segundos.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-02](../../modelagem/casos_de_uso.md#12-uc-02-editar-um-design-existente)

* __Escalabilidade:__ A plataforma deve suportar um número crescente de usuários simultâneos e projetos sem degradação significativa no desempenho.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-11](../../modelagem/casos_de_uso.md#111-uc-11-colaborar-em-tempo-real)

* __Disponibilidade:__ O site deve estar disponível 99,9% do tempo, com um tempo de inatividade máximo programado de 4 horas por mês para manutenção.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-08](../../modelagem/casos_de_uso.md#18-uc-08-logar-na-plataforma-canva)

### __2.2. Segurança__

* __Autenticação:__ A plataforma deve oferecer autenticação segura por meio de senha, autenticação de dois fatores e login social (Google, Facebook).

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-08](../../modelagem/casos_de_uso.md#18-uc-08-logar-na-plataforma-canva)

* __Autorização:__ O acesso aos designs e recursos deve ser controlado por um sistema de permissões granular, permitindo o compartilhamento e a colaboração com diferentes níveis de acesso.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-03](../../modelagem/casos_de_uso.md#13-uc-03-compartilhar-um-design)

* __Proteção de Dados:__ As informações do usuário, incluindo dados pessoais e designs, devem ser criptografadas em repouso e em trânsito usando protocolos de segurança padrão da indústria (SSL/TLS).

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-08](../../modelagem/casos_de_uso.md#18-uc-08-logar-na-plataforma-canva)

* __Conformidade:__ A plataforma deve cumprir as leis e regulamentações de proteção de dados relevantes, como LGPD e GDPR.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-08](../../modelagem/casos_de_uso.md#18-uc-08-logar-na-plataforma-canva)

### __2.3. Usabilidade__

* __Interface do Usuário:__ A interface deve ser intuitiva, fácil de usar e esteticamente agradável, utilizando princípios de design centrados no usuário.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-02](../../modelagem/casos_de_uso.md#12-uc-02-editar-um-design-existente)

* __Navegação:__ Os usuários devem ser capazes de navegar facilmente pelo site, encontrar as ferramentas e recursos necessários e acessar seus projetos rapidamente.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-10](../../modelagem/casos_de_uso.md#110-uc-010-gerenciar-pastas-e-projetos)

* __Acessibilidade:__ A plataforma deve ser acessível a usuários com deficiência, seguindo as diretrizes de acessibilidade WCAG 2.1.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-02](../../modelagem/casos_de_uso.md#12-uc-02-editar-um-design-existente)

* __Documentação e Suporte:__ O Canva deve fornecer documentação abrangente, tutoriais e suporte ao cliente responsivo para ajudar os usuários a utilizar todas as funcionalidades da plataforma.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-15](../../modelagem/casos_de_uso.md#115-uc-15-acessar-suporte-e-atendimento-ao-cliente)

### __2.4. Confiabilidade__

* __Recuperação de Falhas:__ A plataforma deve ser projetada para lidar com falhas de hardware e software, garantindo a mínima perda de dados e rápida recuperação.

    - **Rastreabilidade:** Relacionado a todos os casos de uso.

* __Backup e Restauração:__ Backups regulares do site e dos dados do usuário devem ser realizados, com a capacidade de restaurar dados em caso de perda ou corrupção.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-01](../../modelagem/casos_de_uso.md#uc-01-criar-um-novo-design)

* __Monitoramento:__ O sistema deve ser monitorado continuamente para detectar e solucionar problemas de desempenho, segurança e disponibilidade.

    - **Rastreabilidade:** Relacionado a todos os casos de uso.

### __2.5. Manutenibilidade__

* __Modularidade:__ A arquitetura do site deve ser modular, permitindo a atualização e manutenção de componentes individuais sem afetar outras partes do sistema.

    - **Rastreabilidade:** Relacionado a todos os casos de uso.

* __Documentação Técnica:__ A documentação técnica completa, incluindo diagramas de arquitetura, código-fonte documentado e casos de teste, deve ser mantida para facilitar a manutenção e o desenvolvimento futuro.

    - **Rastreabilidade:** Relacionado ao desenvolvimento e manutenção geral do sistema.

* __Ferramentas de Desenvolvimento:__ O Canva deve utilizar ferramentas e tecnologias de desenvolvimento padrão da indústria para garantir a manutenibilidade e a escalabilidade do código.

    - **Rastreabilidade:** Relacionado ao desenvolvimento e manutenção geral do sistema.


## __3. Restrições__

* __Navegadores Suportados:__ O site deve ser compatível com as versões mais recentes dos principais navegadores da web, incluindo Chrome, Firefox, Safari e Edge.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-08](../../modelagem/casos_de_uso.md#18-uc-08-logar-na-plataforma-canva)

* __Dispositivos Suportados:__ A plataforma deve funcionar corretamente em desktops, laptops, tablets e smartphones.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-08](../../modelagem/casos_de_uso.md#18-uc-08-logar-na-plataforma-canva)

* __Idiomas Suportados:__ O Canva deve estar disponível em vários idiomas, incluindo português, inglês, espanhol e outros idiomas relevantes para o público-alvo.

    - **Rastreabilidade:** Relacionado ao Caso de Uso [US-08](../../modelagem/casos_de_uso.md#18-uc-08-logar-na-plataforma-canva)

## __4. Conclusão__

A Especificação Suplementar define os requisitos não funcionais essenciais para o desenvolvimento e operação bem-sucedidos do site Canva. Ao atender a esses requisitos, a plataforma poderá oferecer uma experiência de usuário de alta qualidade, segura, confiável e escalável para seus usuários.