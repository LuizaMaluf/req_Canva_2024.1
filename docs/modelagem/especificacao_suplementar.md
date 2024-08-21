# __Especificação Suplementar__

| Data       | Descrição | Autor | Versão |
| ---------- | ------ | --------- | ----- |
| 16/09/2021 | Criação do documento e definição dos requisitos não funcionais após análise de casos de uso | Henrique Quenino | 0.1 |
| 17/09/2021 | Revisão e ajustes dos requisitos não funcionais | Henrique Quenino | 1.0 |


## __1. Introdução__

Este documento descreve a Especificação Suplementar do site Canva, complementando a Especificação de Casos de Uso. Ele detalha os requisitos não funcionais, incluindo requisitos de desempenho, segurança, usabilidade e outros, essenciais para o sucesso da plataforma.

## **2. Requisitos Não Funcionais**

### __2.1. Desempenho__

* __Tempo de Carregamento:__ O site deve carregar em menos de 3 segundos em uma conexão de banda larga (5 Mbps) para 80% das requisições.
* __Tempo de Resposta:__ As interações do usuário, como arrastar e soltar elementos, aplicar filtros e salvar designs, devem ocorrer em tempo real, com um tempo de resposta máximo de 0,5 segundos.
* __Escalabilidade:__ A plataforma deve suportar um número crescente de usuários simultâneos e projetos sem degradação significativa no desempenho.
* __Disponibilidade:__ O site deve estar disponível 99,9% do tempo, com um tempo de inatividade máximo programado de 4 horas por mês para manutenção.

### __2.2. Segurança__

* __Autenticação:__ A plataforma deve oferecer autenticação segura por meio de senha, autenticação de dois fatores e login social (Google, Facebook).
* __Autorização:__ O acesso aos designs e recursos deve ser controlado por um sistema de permissões granular, permitindo o compartilhamento e a colaboração com diferentes níveis de acesso.
* __Proteção de Dados:__ As informações do usuário, incluindo dados pessoais e designs, devem ser criptografadas em repouso e em trânsito usando protocolos de segurança padrão da indústria (SSL/TLS).
* __Conformidade:__ A plataforma deve cumprir as leis e regulamentações de proteção de dados relevantes, como LGPD e GDPR.

### __2.3. Usabilidade__

* __Interface do Usuário:__ A interface deve ser intuitiva, fácil de usar e esteticamente agradável, utilizando princípios de design centrados no usuário.
* __Navegação:__ Os usuários devem ser capazes de navegar facilmente pelo site, encontrar as ferramentas e recursos necessários e acessar seus projetos rapidamente.
* __Acessibilidade:__ A plataforma deve ser acessível a usuários com deficiência, seguindo as diretrizes de acessibilidade WCAG 2.1.
* __Documentação e Suporte:__ O Canva deve fornecer documentação abrangente, tutoriais e suporte ao cliente responsivo para ajudar os usuários a utilizar todas as funcionalidades da plataforma.

### __2.4. Confiabilidade__

* __Recuperação de Falhas:__ A plataforma deve ser projetada para lidar com falhas de hardware e software, garantindo a mínima perda de dados e rápida recuperação.
* __Backup e Restauração:__ Backups regulares do site e dos dados do usuário devem ser realizados, com a capacidade de restaurar dados em caso de perda ou corrupção.
* __Monitoramento:__ O sistema deve ser monitorado continuamente para detectar e solucionar problemas de desempenho, segurança e disponibilidade.

### __2.5. Manutenibilidade__

* __Modularidade:__ A arquitetura do site deve ser modular, permitindo a atualização e manutenção de componentes individuais sem afetar outras partes do sistema.
* __Documentação Técnica:__ A documentação técnica completa, incluindo diagramas de arquitetura, código-fonte documentado e casos de teste, deve ser mantida para facilitar a manutenção e o desenvolvimento futuro.
* __Ferramentas de Desenvolvimento:__ O Canva deve utilizar ferramentas e tecnologias de desenvolvimento padrão da indústria para garantir a manutenibilidade e a escalabilidade do código.


## __3. Restrições__

* __Navegadores Suportados:__ O site deve ser compatível com as versões mais recentes dos principais navegadores da web, incluindo Chrome, Firefox, Safari e Edge.
* __Dispositivos Suportados:__ A plataforma deve funcionar corretamente em desktops, laptops, tablets e smartphones.
* __Idiomas Suportados:__ O Canva deve estar disponível em vários idiomas, incluindo português, inglês, espanhol e outros idiomas relevantes para o público-alvo.

## __4. Conclusão__

A Especificação Suplementar define os requisitos não funcionais essenciais para o desenvolvimento e operação bem-sucedidos do site Canva. Ao atender a esses requisitos, a plataforma poderá oferecer uma experiência de usuário de alta qualidade, segura, confiável e escalável para seus usuários.