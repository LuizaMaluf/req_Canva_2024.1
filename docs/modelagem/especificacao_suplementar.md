# **Especificação Suplementar**

**1. Introdução**

Este documento descreve a Especificação Suplementar do site Canva, complementando a Especificação de Casos de Uso. Ele detalha os requisitos não funcionais, incluindo requisitos de desempenho, segurança, usabilidade e outros, essenciais para o sucesso da plataforma.

**2. Requisitos Não Funcionais**

**2.1. Desempenho**

* **Tempo de Carregamento:** O site deve carregar em menos de 3 segundos em uma conexão de banda larga (5 Mbps) para 80% das requisições.
* **Tempo de Resposta:** As interações do usuário, como arrastar e soltar elementos, aplicar filtros e salvar designs, devem ocorrer em tempo real, com um tempo de resposta máximo de 0,5 segundos.
* **Escalabilidade:** A plataforma deve suportar um número crescente de usuários simultâneos e projetos sem degradação significativa no desempenho.
* **Disponibilidade:** O site deve estar disponível 99,9% do tempo, com um tempo de inatividade máximo programado de 4 horas por mês para manutenção.

**2.2. Segurança**

* **Autenticação:** A plataforma deve oferecer autenticação segura por meio de senha, autenticação de dois fatores e login social (Google, Facebook).
* **Autorização:** O acesso aos designs e recursos deve ser controlado por um sistema de permissões granular, permitindo o compartilhamento e a colaboração com diferentes níveis de acesso.
* **Proteção de Dados:** As informações do usuário, incluindo dados pessoais e designs, devem ser criptografadas em repouso e em trânsito usando protocolos de segurança padrão da indústria (SSL/TLS).
* **Conformidade:** A plataforma deve cumprir as leis e regulamentações de proteção de dados relevantes, como LGPD e GDPR.

**2.3. Usabilidade**

* **Interface do Usuário:** A interface deve ser intuitiva, fácil de usar e esteticamente agradável, utilizando princípios de design centrados no usuário.
* **Navegação:** Os usuários devem ser capazes de navegar facilmente pelo site, encontrar as ferramentas e recursos necessários e acessar seus projetos rapidamente.
* **Acessibilidade:** A plataforma deve ser acessível a usuários com deficiência, seguindo as diretrizes de acessibilidade WCAG 2.1.
* **Documentação e Suporte:** O Canva deve fornecer documentação abrangente, tutoriais e suporte ao cliente responsivo para ajudar os usuários a utilizar todas as funcionalidades da plataforma.

**2.4. Confiabilidade**

* **Recuperação de Falhas:** A plataforma deve ser projetada para lidar com falhas de hardware e software, garantindo a mínima perda de dados e rápida recuperação.
* **Backup e Restauração:** Backups regulares do site e dos dados do usuário devem ser realizados, com a capacidade de restaurar dados em caso de perda ou corrupção.
* **Monitoramento:** O sistema deve ser monitorado continuamente para detectar e solucionar problemas de desempenho, segurança e disponibilidade.

**2.5. Manutenibilidade**

* **Modularidade:** A arquitetura do site deve ser modular, permitindo a atualização e manutenção de componentes individuais sem afetar outras partes do sistema.
* **Documentação Técnica:** A documentação técnica completa, incluindo diagramas de arquitetura, código-fonte documentado e casos de teste, deve ser mantida para facilitar a manutenção e o desenvolvimento futuro.
* **Ferramentas de Desenvolvimento:** O Canva deve utilizar ferramentas e tecnologias de desenvolvimento padrão da indústria para garantir a manutenibilidade e a escalabilidade do código.


**3. Restrições**

* **Navegadores Suportados:** O site deve ser compatível com as versões mais recentes dos principais navegadores da web, incluindo Chrome, Firefox, Safari e Edge.
* **Dispositivos Suportados:** A plataforma deve funcionar corretamente em desktops, laptops, tablets e smartphones.
* **Idiomas Suportados:** O Canva deve estar disponível em vários idiomas, incluindo português, inglês, espanhol e outros idiomas relevantes para o público-alvo.

**4. Conclusão**

A Especificação Suplementar define os requisitos não funcionais essenciais para o desenvolvimento e operação bem-sucedidos do site Canva. Ao atender a esses requisitos, a plataforma poderá oferecer uma experiência de usuário de alta qualidade, segura, confiável e escalável para seus usuários.