#__Cenários__

| Data       | Descrição                | Autor         | Versão   |
|------------|--------------------------------------|---------------|----------|
| 12/08/2024 | Adição dos primeiros cenários encontrados durante a análise de protocolo| Luiza Maluf   | 0.0      |
| 16/07/2024 | Adição de mais cenários após avaliar os casos de uso. | Luiza Maluf   | [1.0](../../modelagem/cenarios.md)      |
| 05/09/2024 | Correção dos cenários após [verificação](../verf_cenario.md) | Henrique Quenino | 2.0      |

## Origem

O desenvolvimento destes cenários foi dado a partir da [análise de protocolo](../../elicitacao/analise_protocolo.md), feita na parte de elicitação.

Não satisfeitos com a quantidade de cenários e com uma visão diferente vinda da [Especificação de Casos de Uso](../../modelagem/casos_de_uso.md), foi possível identificar novos cenários.

## Metodologia

Foi feita a navegação dentro da plataforma anotando os principais processos que o usuáro poderia efetuar.

### __1. Criação de um Design Simples__

#### __OBJETIVO__

Um [usuário](../../modelagem/lexico.md#Usuário) novato acessa o Canva e deseja criar um [design](../../modelagem/lexico.md#Design) de cartão de visita.

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) está acessando o Canva pela primeira vez e tem pouca experiência em [design](../../modelagem/lexico.md#Design) gráfico.

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve estar logado na plataforma Canva.

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) faz login na plataforma Canva.
2. Navega pelos [templates](../../modelagem/lexico.md#Templates) disponíveis e escolhe um para cartão de visita.
3. [Personaliza](../../modelagem/lexico.md#Personalizar) o [template](../../modelagem/lexico.md#Templates), [inserindo](../../modelagem/lexico.md#Adicionar) seu nome, cargo e informações de contato.
4. [Altera](../../modelagem/lexico.md#Altera) as cores e [fontes](#Fonte) de acordo com sua preferência.
5. Visualiza o [design](../../modelagem/lexico.md#Design) final e decide [salvá-lo](../../modelagem/lexico.md#Salvar).
6. O [usuário](../../modelagem/lexico.md#Usuário) [baixa](../../modelagem/lexico.md#Baixar) o [design](../../modelagem/lexico.md#Design) para seu [Computador](../../modelagem/lexico.md#Computador).

#### __RESTRIÇÕES__

[Usuário](../../modelagem/lexico.md#Usuário) deve ter uma [conta](../../modelagem/lexico.md#Conta) ativa na plataforma Canva.

#### __PÓS-CONDIÇÃO__

[Usuário](../../modelagem/lexico.md#Usuário) [criou](../../modelagem/lexico.md#Criar) e [salvou](../../modelagem/lexico.md#Salvar) um cartão de visita simples, pronto para uso.

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) consegue [criar](../../modelagem/lexico.md#Criar) e [salvar](../../modelagem/lexico.md#Salvar) um cartão de visita simples, ficando satisfeito com a facilidade de uso da [ferramenta](../../modelagem/lexico.md#Ferramenta).

---

### __2. Colaboração em Tempo Real__

#### __OBJETIVO__

Dois [usuários](../../modelagem/lexico.md#Usuário) [colaboram](../../modelagem/lexico.md#Colaboraçãi) simultaneamente em um [design](../../modelagem/lexico.md#Design) de [apresentação](../../modelagem/lexico.md#Apresentação) para uma reunião de negócios.

#### __CONTEXTO__

Os [usuários](../../modelagem/lexico.md#Usuário) estão em locais diferentes, mas precisam trabalhar juntos no mesmo [projeto](../../modelagem/lexico.md#Projeto) em tempo real na plataforma Canva.

#### __ATORES__

- [Usuários](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva, [chat](../../modelagem/lexico.md#Chat) [integrado](../../modelagem/lexico.md#Integração).

#### __PRÉ-CONDIÇÃO__

Ambos os [usuários](../../modelagem/lexico.md#Usuário) devem estar [logados](../../modelagem/lexico.md#Login) na plataforma Canva e ter uma [conexão](../../modelagem/lexico.md#Conexão) de internet estável.

#### __EPISÓDIOS__

1. [Usuário](../../modelagem/lexico.md#Usuário) 1 [cria](../../modelagem/lexico.md#Criar) uma [apresentação](../../modelagem/lexico.md#Apresentação) no Canva.
2. [Usuário](../../modelagem/lexico.md#Usuário) 1 [compartilha](../../modelagem/lexico.md#Compartilhar) o link de [edição](../../modelagem/lexico.md#Edição) do [design](../../modelagem/lexico.md#Design) com o [Usuário](../../modelagem/lexico.md#Usuário).
3. Ambos os [usuários](../../modelagem/lexico.md#Usuário) abrem o [design](../../modelagem/lexico.md#Design) [simultaneamente](../../modelagem/lexico.md#Simultâneo) e começam a [editá-lo](../../modelagem/lexico.md#Edição).
4. [Usuário](../../modelagem/lexico.md#Usuário) 1 trabalha nos primeiros [slides](../../modelagem/lexico.md#Slide), enquanto [Usuário](../../modelagem/lexico.md#Usuário) [edita](../../modelagem/lexico.md#Edição) os últimos slides.
5. Os [usuários](../../modelagem/lexico.md#Usuário) discutem as [alterações](../../modelagem/lexico.md#Alteração) e ajustes necessários usando o [chat](../../modelagem/lexico.md#Chat) [integrado](../../modelagem/lexico.md#Integração) da [plataforma](../../modelagem/lexico.md#Plataforma).
6. Ambos revisam o [design](../../modelagem/lexico.md#Design) final juntos, fazem os ajustes necessários e [salvam](../../modelagem/lexico.md#Salvar) o [projeto](../../modelagem/lexico.md#Projeto).

#### __RESTRIÇÕES__

Ambos os [usuários](../../modelagem/lexico.md#Usuário) precisam ter [permissão](../../modelagem/lexico.md#Permissão) de [edição](../../modelagem/lexico.md#Edição) para colaborar no [design](../../modelagem/lexico.md#Design).

#### __PÓS-CONDIÇÃO__

O [design](../../modelagem/lexico.md#Design) da [apresentação](../../modelagem/lexico.md#Apresentação) foi concluído e [salvo](../../modelagem/lexico.md#Salvar), estando pronto para a reunião.

#### __RESULTADO ESPERADO__

Os dois [usuários](../../modelagem/lexico.md#Usuário) conseguem [colaborar](../../modelagem/lexico.md#Colaboração) em tempo real, completando o [design](../../modelagem/lexico.md#Design) de forma eficiente e satisfatória.

---
### __3. Exploração de Recursos Premium__
#### __OBJETIVO__ 

Um [usuário](../../modelagem/lexico.md#Usuário) [gratuito](../../modelagem/lexico.md#Gratuito) explora os benefícios de um [plano de assinatura](../../modelagem/lexico.md#Assinatura) para decidir se vale a pena [assiná-lo](../../modelagem/lexico.md#Assinar).

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) sente que as opções [gratuitas](../../modelagem/lexico.md#Gratuito) são limitadas e deseja saber se vale a pena [assinar](../../modelagem/lexico.md#Assinar) um [plano](../../modelagem/lexico.md#Assinatura).

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve estar logado na plataforma Canva.

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) navega pelos [templates](../../modelagem/lexico.md#Templates) gratuitos, mas não encontra algo que atenda às suas necessidades.
2. Ele vê a indicação de [templates](../../modelagem/lexico.md#Templates) Premium e resolve clicar para ver as opções.
3. Um pop-up aparece explicando os benefícios do [plano de assinatura](../../modelagem/lexico.md#Assinatura), como acesso a [templates](../../modelagem/lexico.md#Templates) exclusivos e recursos adicionais.
4. O [usuário](../../modelagem/lexico.md#Usuário) decide experimentar o [plano](../../modelagem/lexico.md#Assinatura) por 30 dias [gratuitamente](../../modelagem/lexico.md#Gratuito).
5. Após a ativação, ele começa a usar os [templates](../../modelagem/lexico.md#Templates) Premium e nota a diferença na qualidade e variedade.

#### __RESTRIÇÕES__

O [usuário](../../modelagem/lexico.md#Usuário) deve ter uma [conta](../../modelagem/lexico.md#Conta) ativa na plataforma Canva.

#### __PÓS-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) explora os recursos Premium e decide se continuará com a [assinatura](../../modelagem/lexico.md#Assinatura) após o período de [teste](../../modelagem/lexico.md#Teste).

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) percebe o valor dos [recursos](../../modelagem/lexico.md#Recuros) [Premium](../../modelagem/lexico.md#Assinatura) e decide continuar com a [assinatura](../../modelagem/lexico.md#Assinatura) após o período de [teste](../../modelagem/lexico.md#Teste).

---
### __4. Criação de Materiais para uma Campanha Publicitária__

#### __OBJETIVO__

Uma [equipe](../../modelagem/lexico.md#Equipe) de marketing utiliza o Canva para criar [materiais gráficos](../../modelagem/lexico.md#Elementos-Gráficos) para uma campanha publicitária.

#### __CONTEXTO__

A [equipe](../../modelagem/lexico.md#Equipe) precisa garantir que todos os materiais tenham uma [identidade visual](../../modelagem/lexico.md#Identidade-Visual) consistente e atraente.

#### __ATORES__

- [Designer](../../modelagem/lexico.md#Designer)
- Gerente de Marketing

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva.

#### __PRÉ-CONDIÇÃO__

A [equipe](../../modelagem/lexico.md#Equipe) de marketing deve estar [alinhada](../../modelagem/lexico.md#Alinhamento) quanto à [identidade visual](../../modelagem/lexico.md#Identidade-Visual) da campanha.

#### __EPISÓDIOS__

1. O [Designer](../../modelagem/lexico.md#Designer) seleciona um conjunto de [templates](../../modelagem/lexico.md#Template) que combinam entre si para garantir consistência visual.
2. Adapta cada [Templates](../../modelagem/lexico.md#Template) para diferentes formatos ([postagem](../../modelagem/lexico.md#Publicação) em redes sociais, banners para site, e-mail marketing).
3. Utiliza [elementos gráficos](../../modelagem/lexico.md#Elementos-Gráficos) e o [Banco de Imagens](../../modelagem/lexico.md#Banco-de-Imagens) para enriquecer os materiais.
4. O [gerente de marketing](../../modelagem/lexico.md#Gerente-de-Marketing) revisa e sugere pequenas [alterações](../../modelagem/lexico.md#Alterar).
5. Após aprovação, o [[Designer](../../modelagem/lexico.md#Designer)](../../modelagem/lexico.md#[Designer](../../modelagem/lexico.md#Designer)) [exporta](../../modelagem/lexico.md#Exportação) os materiais nos formatos necessários.
6. Os materiais são [compartilhados](../../modelagem/lexico.md#Compartilhamento) com a [equipe](../../modelagem/lexico.md#Equipe) e publicados conforme o cronograma da campanha.

#### __RESTRIÇÕES__

A [equipe](../../modelagem/lexico.md#Equipe) deve respeitar o prazo da campanha e as diretrizes de [identidade visual](../../modelagem/lexico.md#Identidade-Visual) estabelecidas.

#### __PÓS-CONDIÇÃO__

Os [materiais gráficos](../../modelagem/lexico.md#elementos-gráficos-elementos-gráficos) estão prontos e [alinhados](../../modelagem/lexico.md#Alinhamento) com a [identidade visual](../../modelagem/lexico.md#Identidade-Visual) da campanha.

#### __RESULTADO ESPERADO__

A [equipe](../../modelagem/lexico.md#Equipe) de marketing consegue [criar](../../modelagem/lexico.md#Criar) uma campanha coesa e visualmente atraente, melhorando a identidade da marca.

---
### __5. Adaptação de um Design para Diferentes Mídias__

#### __OBJETIVO__

Um [Designer](../../modelagem/lexico.md#Designer) adapta um único [design](../../modelagem/lexico.md#Design) para diferentes mídias, como cartazes impressos, posts em redes sociais e banners para sites.

#### __CONTEXTO__

O [Designer](../../modelagem/lexico.md#Designer) precisa garantir que a mensagem e a [identidade visual](../../modelagem/lexico.md#Identidade-Visual) sejam mantidas em todos os formatos.

#### __ATORES__

- [Designer](../../modelagem/lexico.md#Designer)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva.

#### __PRÉ-CONDIÇÃO__

O [Designer](../../modelagem/lexico.md#Designer) deve ter acesso aos [templates](../../modelagem/lexico.md#Templates) originais e aos requisitos específicos de cada mídia.

#### __EPISÓDIOS__

1. O [Designer](../../modelagem/lexico.md#Designer) seleciona o [design](../../modelagem/lexico.md#Design) original no Canva.
2. Duplica o [design](../../modelagem/lexico.md#Design) e ajusta as dimensões para cada mídia (A4 para cartazes, 1080x1080 para posts, etc.).
3. Reposiciona os [elementos gráficos](../../modelagem/lexico.md#Elementos-Gráficos) conforme necessário para manter o equilíbrio visual.
4. Ajusta o tamanho das fontes e o espaçamento para garantir legibilidade em cada formato.
5. Revisa cada adaptação e [exporta](../../modelagem/lexico.md#Exportação) os [arquivos](../../modelagem/lexico.md#Arquivo) nos formatos apropriados.

#### __RESTRIÇÕES__

O [Designer](../../modelagem/lexico.md#Designer) deve garantir que a mensagem principal permaneça clara em todas as adaptações.

#### __PÓS-CONDIÇÃO__

Os [designs](../../modelagem/lexico.md#Design) estão prontos para uso em diferentes mídias.

#### __RESULTADO ESPERADO__

O [Designer](../../modelagem/lexico.md#Designer) adapta com sucesso o [design](../../modelagem/lexico.md#Design) original para diferentes mídias, mantendo a consistência da mensagem e da [identidade visual](../../modelagem/lexico.md#Identidade-Visual).

---
### __6. Exportação de um Projeto em Alta Resolução__

#### __OBJETIVO__

Um [Designer](../../modelagem/lexico.md#Designer) exporta um [projeto](../../modelagem/lexico.md#Projeto) gráfico em alta resolução para impressão profissional.

#### __CONTEXTO__

O [Designer](../../modelagem/lexico.md#Designer) precisa garantir que o [arquivo](../../modelagem/lexico.md#Arquivo) final tenha qualidade suficiente para impressão em grande escala.

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva.

#### __PRÉ-CONDIÇÃO__

O [projeto](../../modelagem/lexico.md#Projeto) deve estar finalizado e revisado.

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) abre o [projeto](../../modelagem/lexico.md#Projeto) no Canva.
2. Seleciona a opção de [exportação](../../modelagem/lexico.md#Exportação) e escolhe o formato adequado (por exemplo, PDF para impressão).
3. Ajusta as configurações de resolução para a máxima qualidade disponível.
4. Revisa as opções de margens, caso necessário.
5. [Exporta](../../modelagem/lexico.md#Exportação) o [arquivo](../../modelagem/lexico.md#Arquivo) e faz o download.

#### __RESTRIÇÕES__

O [usuário](../../modelagem/lexico.md#Usuário) deve garantir que as configurações de [exportação](../../modelagem/lexico.md#Exportação) atendam aos requisitos da impressão.

#### __PÓS-CONDIÇÃO__

O [projeto](../../modelagem/lexico.md#Projeto) está pronto para ser enviado para a gráfica.

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) consegue [exportar](../../modelagem/lexico.md#Exportação) o [projeto](../../modelagem/lexico.md#Projeto) em alta resolução, garantindo uma impressão de alta qualidade.

---
### __7. Compartilhamento de Post para Redes Sociais__

#### __OBJETIVO__

Um [usuário](../../modelagem/lexico.md#Usuário) [cria](../../modelagem/lexico.md#Criar) e [compartilha](../../modelagem/lexico.md#Compartilhamento) um post visual para promover um novo produto em diversas redes sociais.

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) deseja utilizar o Canva para [criar](../../modelagem/lexico.md#Criar) um post atraente que será [compartilhado](../../modelagem/lexico.md#Compartilhamento) em múltiplas plataformas sociais para maximizar o alcance do novo produto.

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva, [contas](../../modelagem/lexico.md#Conta) nas redes sociais (Instagram, Facebook, Twitter, LinkedIn).

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve ter as imagens do produto, textos promocionais e informações sobre as redes sociais onde o post será [compartilhado](../../modelagem/lexico.md#Compartilhamento).

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) acessa o Canva e escolhe um [template](../../modelagem/lexico.md#Templates) de post adequado para redes sociais.
2. Personaliza o [design](../../modelagem/lexico.md#Design) com imagens do produto, texto promocional e hashtags relevantes.
3. Ajusta o [layout](../../modelagem/lexico.md#Tamplate) e o [design](../../modelagem/lexico.md#Design) para atender às diretrizes específicas de cada plataforma social.
4. Revê o post para garantir que todos os detalhes estejam corretos e que o [design](../../modelagem/lexico.md#Design) esteja otimizado para cada rede social.
5. [Exporta](../../modelagem/lexico.md#Exportação) o post no formato adequado para cada [plataforma](../../modelagem/lexico.md#Plataforma) (Instagram, Facebook, Twitter, LinkedIn).
6. [Compartilha](../../modelagem/lexico.md#Compartilhamento) o post diretamente nas [contas](../../modelagem/lexico.md#Contass) de redes sociais usando as [ferramentas](../../modelagem/lexico.md#Ferramenta) de [integração](../../modelagem/lexico.md#Itegração) do Canva ou faz o upload manualmente em cada plataforma.

#### __RESTRIÇÕES__

Os posts devem seguir as diretrizes de tamanho e formato recomendadas por cada rede social para garantir uma boa visualização e desempenho.

#### __PÓS-CONDIÇÃO__

Os posts estão [publicados](../../modelagem/lexico.md#Publicação) e visíveis nas redes sociais selecionadas.

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) cria e [compartilha](../../modelagem/lexico.md#Compartilhamento) posts atraentes que promovem eficazmente o novo produto, engajando os seguidores em diversas redes sociais.

---
### __8. Login e Logout na Plataforma Canva__

#### __OBJETIVO__

Um [usuário](../../modelagem/lexico.md#Usuário) acessa sua conta na plataforma Canva para [criar](../../modelagem/lexico.md#Criar) e gerenciar [design](../../modelagem/lexico.md#Design), e depois realiza o [logout](../../modelagem/lexico.md#Logout) para garantir a segurança da conta.

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) precisa acessar sua [conta](../../modelagem/lexico.md#Conta) na plataforma Canva para trabalhar em [projetos](../../modelagem/lexico.md#Projetos) e, após concluir seu trabalho, deseja fazer [logout](../../modelagem/lexico.md#Logout) para proteger suas informações.

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve ter uma [conta](../../modelagem/lexico.md#Conta) ativa na plataforma Canva e conhecer suas credenciais de [login](../../modelagem/lexico.md#Login).

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) [acessa](../../modelagem/lexico.md#Acesso) a página de [login](../../modelagem/lexico.md#Login) do Canva.
2. Insere seu nome de [usuário](../../modelagem/lexico.md#Usuário) e senha.
3. Clica no botão de login para [acessar](../../modelagem/lexico.md#Acesso) sua [conta](../../modelagem/lexico.md#Conta).
4. O [usuário](../../modelagem/lexico.md#Usuário) usa a plataforma Canva para [criar](../../modelagem/lexico.md#Criar) ou gerenciar [design](../../modelagem/lexico.md#Design).
5. Após concluir suas atividades, o [usuário](../../modelagem/lexico.md#Usuário) localiza a opção de [logout](../../modelagem/lexico.md#Logout) no menu de perfil.
6. Clica na opção de [logout](../../modelagem/lexico.md#Logout) para sair da conta.
7. O [usuário](../../modelagem/lexico.md#Usuário) é redirecionado para a página de [login](../../modelagem/lexico.md#Login) ou para a página inicial do Canva.

#### __RESTRIÇÕES__

O [usuário](../../modelagem/lexico.md#Usuário) deve lembrar suas credenciais para realizar o [login](../../modelagem/lexico.md#Login). Após o [logout](../../modelagem/lexico.md#Logout), é necessário fazer [login](../../modelagem/lexico.md#Login) novamente para [acessar](../../modelagem/lexico.md#Acesso) a [conta](../../modelagem/lexico.md#Conta).

#### __PÓS-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) foi desconectado da sua [conta](../../modelagem/lexico.md#Conta) na [plataforma](../../modelagem/lexico.md#Plataforma) Canva, garantindo que suas informações estejam seguras.

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) consegue fazer [login](../../modelagem/lexico.md#Login) e [logout](../../modelagem/lexico.md#Logout) com sucesso, garantindo o [acesso](../../modelagem/lexico.md#Acesso) e a segurança de sua [conta](../../modelagem/lexico.md#Conta) na [plataforma](../../modelagem/lexico.md#Plataforma) Canva.

---
### __9. Cenário: Edição de um Design Existente__

#### __OBJETIVO__

Um [usuário](../../modelagem/lexico.md#Usuário) deseja [editar](../../modelagem/lexico.md#Edição) um [design](../../modelagem/lexico.md#Design) já existente na [plataforma](../../modelagem/lexico.md#Plataforma) Canva para ajusta-lo às suas novas necessidades.

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) já criou ou tem acesso a um design na plataforma Canva e agora precisa modificá-lo para atualizá-lo ou adaptá-lo a um novo propósito.

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve estar [logado](../../modelagem/lexico.md#Login) na [plataforma](../../modelagem/lexico.md#Plataforma) Canva e ter [acesso](../../modelagem/lexico.md#Acesso) ao [design](../../modelagem/lexico.md#Design) que deseja [editar](../../modelagem/lexico.md#Edição).

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) faz [login](../../modelagem/lexico.md#Login) no Canva.
2. Navega até a seção "Meus Designs" ou utiliza a barra de pesquisa para localizar o [design](../../modelagem/lexico.md#Design) existente.
3. Clica no [design](../../modelagem/lexico.md#Design) desejado para abri-lo na interface de [edição](../../modelagem/lexico.md#Edição).
4. Realiza as modificações necessárias, como alteração de texto, imagens, cores e layout.
5. Visualiza as mudanças em tempo real para garantir que o [design](../../modelagem/lexico.md#Design) atende às novas necessidades.
6. Salva as alterações e, se necessário, exporta o [design](../../modelagem/lexico.md#Design) modificado nos formatos desejados.

#### __RESTRIÇÕES__

O [usuário](../../modelagem/lexico.md#Usuário) deve garantir que todas as [alterações](../../modelagem/lexico.md#Alterações) estejam de acordo com os requisitos do projeto ou com a nova finalidade do design.

#### __PÓS-CONDIÇÃO__

O design foi [editado](../../modelagem/lexico.md#Edição) com sucesso e está pronto para ser usado conforme o novo propósito.

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) consegue [editar](../../modelagem/lexico.md#Edição) o [design](../../modelagem/lexico.md#Design) existente de maneira eficaz, adaptando-o às suas novas necessidades e garantindo que o resultado final esteja de acordo com as expectativas.

---
### __10. Cenário: Download de um Design__

#### __OBJETIVO__

Um [usuário](../../modelagem/lexico.md#Usuário) deseja [baixar](../../modelagem/lexico.md#Baixar) um [design](../../modelagem/lexico.md#Design) da [plataforma](../../modelagem/lexico.md#Plataforma) Canva para utilizá-lo fora da plataforma, como para impressão ou [compartilhamento](../../modelagem/lexico.md#Compartilhamento).

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) terminou de [criar](../../modelagem/lexico.md#Criar) ou [editar](../../modelagem/lexico.md#Edição) um [design](../../modelagem/lexico.md#Design) na plataforma Canva e agora precisa [baixá-lo](../../modelagem/lexico.md#Baixar) para uso offline ou compartilhamento em outras plataformas.

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve estar [logado](../../modelagem/lexico.md#Login) na [plataforma](../../modelagem/lexico.md#Plataforma) Canva e ter um [design](../../modelagem/lexico.md#Design) finalizado e pronto para o download.

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) faz [login](../../modelagem/lexico.md#Login) no Canva.
2. Navega até o [design](../../modelagem/lexico.md#Design) finalizado que deseja baixar, acessando-o através da seção "Meus Designs" ou utilizando a barra de pesquisa.
3. Clica no [design](../../modelagem/lexico.md#Design) desejado e clica no botão de "Download" no canto superior direito da interface.
4. Escolhe o formato de arquivo desejado (por exemplo, PNG, JPEG, PDF) e ajusta as configurações de qualidade, resolução ou margens, se necessário.
5. Confirma as opções e inicia o download do arquivo.
6. O design é baixado para o dispositivo do usuário, ficando disponível para uso offline.

#### __RESTRIÇÕES__

O [usuário](../../modelagem/lexico.md#Usuário) deve garantir que escolheu o formato de [arquivo](../../modelagem/lexico.md#Arquivo) correto e configurou as opções de download conforme a finalidade do design.

#### __PÓS-CONDIÇÃO__

O design foi [baixado](../../modelagem/lexico.md#Baixar) com sucesso e está pronto para ser usado conforme o necessário.

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) consegue [baixar](../../modelagem/lexico.md#Baixar) o [design](../../modelagem/lexico.md#Design) no formato desejado, com a qualidade adequada, pronto para o uso offline ou compartilhado.

---
### __11. Acesso a um [Template](../../modelagem/lexico.md#Templates) Pronto__

#### __OBJETIVO__

O [usuário](../../modelagem/lexico.md#Usuário) deseja acessar um [template](../../modelagem/lexico.md#Templates) pronto na plataforma Canva para iniciar a criação de um [design](../../modelagem/lexico.md#Design) personalizado.

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) está na plataforma Canva e deseja utilizar um [template](../../modelagem/lexico.md#Templates) pré-definido como base para criar um novo [design](../../modelagem/lexico.md#Design).
__ATORES__#### 

- [Usuário](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve estar [logado](../../modelagem/lexico.md#Login) na [plataforma](../../modelagem/lexico.md#Plataforma) Canva.

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) faz [login](../../modelagem/lexico.md#Login) no Canva.
2. Na página inicial, o usuário navega até a seção de "Templates" ou utiliza a barra de pesquisa para buscar um [template](../../modelagem/lexico.md#Templates) específico.
3. O [usuário](../../modelagem/lexico.md#Usuário) explora as categorias disponíveis, como "Cartões de Visita," "Apresentações," "Postagens para Redes Sociais," entre outras.
4. Seleciona o [template](../../modelagem/lexico.md#Templates) que melhor atende às suas necessidades.
5. Abre o [template](../../modelagem/lexico.md#Templates) escolhido, visualizando uma prévia do [design](../../modelagem/lexico.md#Design).
6. Clica no botão "Usar este template" para iniciar a personalização do [design](../../modelagem/lexico.md#Design).

#### __RESTRIÇÕES__

O [usuário](../../modelagem/lexico.md#Usuário) deve garantir que escolheu um [template](../../modelagem/lexico.md#Templates) adequado ao seu propósito antes de iniciar a personalização.

#### __PÓS-CONDIÇÃO__

O usuário tem o [template](../../modelagem/lexico.md#Templates) pronto aberto na interface de edição do Canva, pronto para ser personalizado conforme desejado.

#### __RESULTADO ESPERADO__

O usuário consegue acessar e abrir um [template](../../modelagem/lexico.md#Templates) pronto na plataforma Canva, facilitando o início da criação de um [design](../../modelagem/lexico.md#Design) personalizado.

---
### __12. Gerenciamento de Pastas e Projetos no Canva__

#### __OBJETIVO__

O usuário deseja organizar seus projetos de [design](../../modelagem/lexico.md#Design) criando e gerenciando pastas na plataforma Canva.

#### __CONTEXTO__

O usuário possui vários projetos na plataforma Canva e deseja organizá-los de forma eficiente para facilitar o acesso e a gestão.

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve estar [logado](../../modelagem/lexico.md#Login) na [plataforma](../../modelagem/lexico.md#Plataforma) Canva e ter [projetos](../../modelagem/lexico.md#Projetos) criados.

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) faz [login](../../modelagem/lexico.md#Login) no Canva.
2. [Acessa](../../modelagem/lexico.md#Acesso) a seção "Meus Designs" ou utiliza a barra de pesquisa para localizar os projetos que deseja organizar.
3. Identifica a necessidade de organizar os projetos em pastas.
4. Clica na opção "Criar nova pasta" e dá um nome à nova pasta, como "Projetos de Marketing" ou "Apresentações 2024".
5. Após criar a pasta, o usuário arrasta e solta os projetos desejados dentro da pasta ou seleciona os projetos e usa a opção "Mover para a pasta" no menu de contexto.
6. O usuário também pode criar subpastas dentro das pastas principais para uma organização mais detalhada.
7. Se necessário, o usuário renomeia, exclui ou move as pastas conforme as necessidades de organização.
8. Para localizar rapidamente um projeto específico, o usuário utiliza a barra de pesquisa ou navega pelas pastas organizadas.

#### __RESTRIÇÕES__

O [usuário](../../modelagem/lexico.md#Usuário) deve organizar os projetos de maneira lógica para facilitar o acesso futuro. O Canva pode ter limitações no número de subpastas ou no número de projetos por pasta, dependendo do plano de assinatura.

#### __PÓS-CONDIÇÃO__

Os projetos estão organizados em pastas, permitindo que o [usuário](../../modelagem/lexico.md#Usuário) acesse e gerencie seus [designs](../../modelagem/lexico.md#Design) de forma mais eficiente.

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) consegue criar, organizar e gerenciar pastas para seus projetos na plataforma Canva, melhorando a eficiência na navegação e no gerenciamento dos [designs](../../modelagem/lexico.md#Design).

---
### __13. Utilização de Recursos de Inteligência Artificial no Canva__

#### __OBJETIVO__

O [usuário](../../modelagem/lexico.md#Usuário) deseja utilizar os recursos de inteligência artificial (IA) do Canva para aprimorar seus [designs](../../modelagem/lexico.md#Design), como a geração de textos automáticos ou a criação de elementos gráficos personalizados.

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) está trabalhando em um projeto de [design](../../modelagem/lexico.md#Design) no Canva e deseja explorar as ferramentas de IA disponíveis para acelerar o processo criativo e melhorar a qualidade do [design](../../modelagem/lexico.md#Design).

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web, plataforma Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve estar [logado](../../modelagem/lexico.md#Login) na [plataforma](../../modelagem/lexico.md#Plataforma) Canva e ter um [projeto](../../modelagem/lexico.md#Projetos) aberto.

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) faz [login](../../modelagem/lexico.md#Login) no Canva e abre um projeto.
2. No painel de ferramentas, o [usuário](../../modelagem/lexico.md#Usuário) identifica a seção de "Recursos de IA" ou uma ferramenta específica de IA, como "Gerador de Texto" ou "Criação Automática de Elementos Gráficos".
3. O [usuário](../../modelagem/lexico.md#Usuário) seleciona o recurso de IA que deseja utilizar, como a geração de texto automático para uma manchete ou a sugestão de paletas de cores personalizadas.
4. Se utilizando da IA, o [usuário](../../modelagem/lexico.md#Usuário) insere palavras-chave ou instruções sobre o que deseja gerar (por exemplo, "slogan para campanha de verão" ou "ilustração abstrata para fundo").
5. A IA processa as informações e apresenta sugestões ou gera os elementos solicitados.
6. O [usuário](../../modelagem/lexico.md#Usuário) revisa as sugestões e, se necessário, faz ajustes manuais para alinhar o resultado com o objetivo do projeto.
7. O [usuário](../../modelagem/lexico.md#Usuário) integra os elementos gerados pela IA ao [design](../../modelagem/lexico.md#Design) e continua a personalização conforme necessário.
8. Se satisfeito com o resultado, o [usuário](../../modelagem/lexico.md#Usuário) salva o projeto final ou faz uma exportação.

#### __RESTRIÇÕES__

Os recursos de IA podem ter limitações em termos de complexidade de geração ou em quantidade de opções oferecidas, dependendo do plano de assinatura do Canva.

#### __PÓS-CONDIÇÃO__

O [design](../../modelagem/lexico.md#Design) do projeto foi aprimorado com a ajuda dos recursos de IA, economizando tempo e aumentando a qualidade do resultado.

#### __RESULTADO ESPERADO__

O u[usuário](../../modelagem/lexico.md#Usuário)suário consegue utilizar eficazmente os recursos de inteligência artificial do Canva, como a geração automática de texto ou a criação de elementos gráficos, melhorando a eficiência do processo de [design](../../modelagem/lexico.md#Design) e o resultado final.


---
### __14. Personalizar Configurações de Conta no Canva__

#### __OBJETIVO__

O [usuário](../../modelagem/lexico.md#Usuário) deseja personalizar as configurações de sua conta no Canva para adaptar a plataforma às suas preferências e necessidades específicas.

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) está logado em sua conta no Canva e quer ajustar configurações como idioma, notificações, métodos de pagamento, ou privacidade para otimizar sua experiência na plataforma.

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web ou aplicativo móvel, conta ativa no Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve estar [logado](../../modelagem/lexico.md#Login) na [plataforma](../../modelagem/lexico.md#Plataforma) Canva.

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) faz login na plataforma Canva e acessa a página inicial.
2. O [usuário](../../modelagem/lexico.md#Usuário) localiza o menu de configurações de conta, geralmente acessível através do ícone de perfil ou das opções de menu.
3. O [usuário](../../modelagem/lexico.md#Usuário) clica na opção "Configurações de Conta" para abrir a página de configurações.
4. Na página de configurações, o [usuário](../../modelagem/lexico.md#Usuário) navega entre as diferentes categorias, como "Informações Pessoais", "Notificações", "Segurança", "Preferências de Idioma", ou "Faturamento e Pagamentos".
5. O [usuário](../../modelagem/lexico.md#Usuário) seleciona a categoria que deseja personalizar. Por exemplo:

    - Para alterar o idioma da plataforma, o [usuário](../../modelagem/lexico.md#Usuário) acessa "Preferências de Idioma" e escolhe o idioma desejado.

    - Para ajustar as notificações, o [usuário](../../modelagem/lexico.md#Usuário) acessa "Notificações" e escolhe quais tipos de alertas deseja receber por email ou no aplicativo.

    - Para atualizar métodos de pagamento, o [usuário](../../modelagem/lexico.md#Usuário) acessa "Faturamento e Pagamentos" e adiciona ou modifica as opções de pagamento.

6. Após fazer as alterações desejadas, o [usuário](../../modelagem/lexico.md#Usuário) salva as configurações.
7. O [usuário](../../modelagem/lexico.md#Usuário) revisa as mudanças feitas para garantir que as configurações estão corretas e de acordo com suas preferências.
8. Caso necessário, o [usuário](../../modelagem/lexico.md#Usuário) faz novos ajustes ou retorna à página inicial do Canva.

#### __RESTRIÇÕES__

Algumas opções de personalização podem estar disponíveis apenas para [usuários](../../modelagem/lexico.md#Usuário) com planos de assinatura específicos, como o Canva Pro.

#### __PÓS-CONDIÇÃO__

As configurações da conta do [usuário](../../modelagem/lexico.md#Usuário) no Canva são atualizadas conforme as preferências definidas.

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) consegue personalizar as configurações de sua conta no Canva, adaptando a plataforma às suas preferências e melhorando sua experiência de uso.


---
### __15. Acessar Suporte e Atendimento ao Cliente no Canva__

#### __OBJETIVO__

O [usuário](../../modelagem/lexico.md#Usuário) deseja acessar o suporte e atendimento ao cliente do Canva para resolver dúvidas, problemas técnicos, ou obter informações sobre a plataforma. 

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) está utilizando a plataforma Canva e encontra dificuldades ou questões que não consegue resolver sozinho. Ele decide buscar ajuda através dos canais de suporte disponíveis.

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)
- Representante de Suporte do Canva

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web ou aplicativo móvel, conta ativa no Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve estar [logado](../../modelagem/lexico.md#Login) na [plataforma](../../modelagem/lexico.md#Plataforma) Canva.

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) faz login na plataforma Canva e acessa a página inicial.
2. O [usuário](../../modelagem/lexico.md#Usuário) localiza a seção de "Ajuda" ou "Suporte", geralmente disponível no rodapé da página ou no menu de perfil.
3. O [usuário](../../modelagem/lexico.md#Usuário) clica na opção "Ajuda" para acessar a central de suporte do Canva.
4. Na central de suporte, o [usuário](../../modelagem/lexico.md#Usuário) pode:

    - Explorar artigos e tutoriais disponíveis na base de conhecimento do Canva para encontrar uma solução para sua dúvida.
    
    - Utilizar a barra de pesquisa para digitar palavras-chave relacionadas ao problema ou questão.
    
    -Acessar as perguntas frequentes (FAQ) para verificar se a dúvida já foi respondida.

5. Se o [usuário](../../modelagem/lexico.md#Usuário) não encontrar a solução nas opções anteriores, ele pode optar por:

    - Entrar em contato com o suporte ao cliente via [chat](../../modelagem/lexico.md#Chat) ao vivo, se disponível.

    - Enviar uma solicitação de suporte por email, detalhando o problema e aguardando a resposta da [equipe](../../modelagem/lexico.md#Equipe).

    - Acessar a comunidade do Canva para interagir com outros [usuários](../../modelagem/lexico.md#Usuário) e buscar soluções colaborativas.

6. O [usuário](../../modelagem/lexico.md#Usuário) escolhe o canal de atendimento mais adequado para sua necessidade e segue as instruções fornecidas para entrar em contato com o suporte.
7. O [usuário](../../modelagem/lexico.md#Usuário) aguarda a resposta do suporte e, caso solicitado, segue as orientações fornecidas para resolver o problema.
8. Caso necessário, o [usuário](../../modelagem/lexico.md#Usuário) faz novos ajustes ou retorna à página inicial do Canva.
9. O [usuário](../../modelagem/lexico.md#Usuário) confirma que o problema foi resolvido ou, se necessário, continua o diálogo com o suporte até a conclusão.

#### __RESTRIÇÕES__

O tempo de resposta do suporte pode variar dependendo do canal escolhido e do plano de assinatura do [usuário](../../modelagem/lexico.md#Usuário).

#### __PÓS-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) recebe o suporte necessário para resolver seu problema ou esclarecer suas dúvidas.

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) consegue acessar o suporte e atendimento ao cliente do Canva, resolve seu problema ou obtém a informação necessária, e retoma suas atividades na plataforma com sucesso.

### __16. Criação de um Design do Zero__

#### __OBJETIVO__

O [usuário](../../modelagem/lexico.md#Usuário) deseja criar um [design](../../modelagem/lexico.md#Design) do zero na plataforma Canva, sem utilizar [templates](../../modelagem/lexico.md#Templates) pré-definidos, para desenvolver um projeto personalizado.

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) tem uma ideia clara do [design](../../modelagem/lexico.md#Design) que deseja criar e prefere começar do zero, sem utilizar [templates](../../modelagem/lexico.md#Templates) existentes, para ter total liberdade criativa e personalização.

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web ou aplicativo móvel, conta ativa no Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve estar [logado](../../modelagem/lexico.md#Login) na [plataforma](../../modelagem/lexico.md#Plataforma) Canva.

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) faz [login](../../modelagem/lexico.md#Login) na plataforma Canva.
2. O [usuário](../../modelagem/lexico.md#Usuário) clica no botão "Criar um design" ou "Design em branco" para iniciar um novo projeto do zero.
3. O [usuário](../../modelagem/lexico.md#Usuário) seleciona o tipo de [design](../../modelagem/lexico.md#Design) que deseja criar, como "Cartão de Visita", "Banner", "Apresentação", ou "Postagem para Redes Sociais".
4. O [usuário](../../modelagem/lexico.md#Usuário) define as dimensões, orientação, e outras configurações iniciais do [design](../../modelagem/lexico.md#Design).
5. O [usuário](../../modelagem/lexico.md#Usuário) acessa as ferramentas de edição, como textos, formas, imagens, e ícones, para começar a construir o [design](../../modelagem/lexico.md#Design).
6. O [usuário](../../modelagem/lexico.md#Usuário) adiciona elementos ao [design](../../modelagem/lexico.md#Design), como textos, imagens, gráficos, e outros elementos visuais, de acordo com sua visão criativa.
7. O [usuário](../../modelagem/lexico.md#Usuário) personaliza as cores, fontes, tamanhos, e outros detalhes do [design](../../modelagem/lexico.md#Design) para refletir sua [identidade visual](../../modelagem/lexico.md#Identidade-Visual) ou estilo desejado.
8. O [usuário](../../modelagem/lexico.md#Usuário) revisa o [design](../../modelagem/lexico.md#Design) em tempo real, fazendo ajustes conforme necessário para alcançar o resultado desejado.
9. Após finalizar o [design](../../modelagem/lexico.md#Design), o [usuário](../../modelagem/lexico.md#Usuário) salva o projeto e, se necessário, faz uma exportação nos formatos desejados.

#### __RESTRIÇÕES__

O [usuário](../../modelagem/lexico.md#Usuário) deve ter conhecimento básico das ferramentas de edição do Canva para criar um [design](../../modelagem/lexico.md#Design) do zero com eficácia.

#### __PÓS-CONDIÇÃO__

O [design](../../modelagem/lexico.md#Design) foi criado do zero com sucesso, refletindo a visão criativa e personalizada do [usuário](../../modelagem/lexico.md#Usuário).

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) consegue criar um [design](../../modelagem/lexico.md#Design) do zero na plataforma Canva, sem utilizar [templates](../../modelagem/lexico.md#Templates) pré-definidos, desenvolvendo um projeto personalizado e único.

### __17. [Feedback](../../modelagem/lexico.md#Feedback) de um Design__

#### __OBJETIVO__

O [usuário](../../modelagem/lexico.md#Usuário) deseja obter [feedback](../../modelagem/lexico.md#Feedback) sobre um [design](../../modelagem/lexico.md#Design) criado na plataforma Canva para avaliar a qualidade, eficácia, e impacto do projeto.

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) finalizou um [design](../../modelagem/lexico.md#Design) na plataforma Canva e deseja compartilhá-lo com colegas, clientes, ou amigos para receber opiniões, sugestões, e críticas construtivas.

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)
- Revisores, colegas, clientes, amigos

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web ou aplicativo móvel, conta ativa no Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve ter finalizado um [design](../../modelagem/lexico.md#Design) na plataforma Canva e estar pronto para compartilhá-lo com outras pessoas.

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) faz login na plataforma Canva e acessa o [design](../../modelagem/lexico.md#Design) que deseja compartilhar.
2. O [usuário](../../modelagem/lexico.md#Usuário) clica no botão "Compartilhar" ou "Convidar para Editar" para gerar um link de compartilhamento ou convidar revisores para colaborar no [design](../../modelagem/lexico.md#Design).
3. O [usuário](../../modelagem/lexico.md#Usuário) copia o link de compartilhamento ou insere os emails dos revisores para enviar o convite.
4. Os revisores recebem o link ou convite e acessam o [design](../../modelagem/lexico.md#Design) para visualizá-lo e fornecer [feedback](../../modelagem/lexico.md#Feedback).
5. Os revisores analisam o [design](../../modelagem/lexico.md#Design), avaliam a qualidade, eficácia, e impacto do projeto, e compartilham suas opiniões, sugestões, e críticas construtivas.
6. O [usuário](../../modelagem/lexico.md#Usuário) revisa os [feedback](../../modelagem/lexico.md#Feedback)s recebidos, considera as sugestões e críticas, e decide se deseja fazer ajustes no [design](../../modelagem/lexico.md#Design) com base nas recomendações.
7. O [usuário](../../modelagem/lexico.md#Usuário) agradece aos revisores pelo [feedback](../../modelagem/lexico.md#Feedback) e finaliza o [design](../../modelagem/lexico.md#Design) conforme necessário.

#### __RESTRIÇÕES__

O [usuário](../../modelagem/lexico.md#Usuário) deve estar aberto a receber [feedback](../../modelagem/lexico.md#Feedback) construtivo e críticas sobre o [design](../../modelagem/lexico.md#Design), mesmo que nem todas as opiniões sejam positivas.

#### __PÓS-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) recebeu [feedback](../../modelagem/lexico.md#Feedback) sobre o [design](../../modelagem/lexico.md#Design), avaliou as sugestões e críticas, e decidiu se fará ajustes no projeto.

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) obteve [feedback](../../modelagem/lexico.md#Feedback) sobre o [design](../../modelagem/lexico.md#Design) criado na plataforma Canva, avaliou as opiniões recebidas, e decidiu se fará alterações no projeto com base nas recomendações.

### __18. Criação de Materiais Educacionais Interativos__

#### __OBJETIVO__

O [usuário](../../modelagem/lexico.md#Usuário) é um professor o aluno e deseja utilizar as ferramentas de Ensino do Canva para criar materiais educacionais interativos e envolventes.

#### __CONTEXTO__

O [usuário](../../modelagem/lexico.md#Usuário) está envolvido no ensino e deseja criar materiais educacionais interativos, como apresentações, infográficos, cartazes, ou atividades, para engajar os alunos e facilitar o aprendizado.

#### __ATORES__

- [Usuário](../../modelagem/lexico.md#Usuário)
- Alunos
- Professores

#### __RECURSOS__

[Computador](../../modelagem/lexico.md#Computador) ou [smartphone](../../modelagem/lexico.md#Smartphone), acesso à internet, navegador web ou aplicativo móvel, conta ativa no Canva.

#### __PRÉ-CONDIÇÃO__

O [usuário](../../modelagem/lexico.md#Usuário) deve estar [logado](../../modelagem/lexico.md#Login) na [plataforma](../../modelagem/lexico.md#Plataforma) Canva e ter conhecimento sobre os recursos de Ensino disponíveis.

#### __EPISÓDIOS__

1. O [usuário](../../modelagem/lexico.md#Usuário) faz [login](../../modelagem/lexico.md#Login) na plataforma Canva e acessa a seção de Ensino.
2. O [usuário](../../modelagem/lexico.md#Usuário) explora as ferramentas disponíveis para criar materiais educacionais interativos, como apresentações, infográficos, cartazes, ou atividades.
3. O [usuário](../../modelagem/lexico.md#Usuário) seleciona o tipo de material educacional que deseja criar e começa a adicionar [conteúdo](../../modelagem/lexico.md#Conteúdo) relevante, como textos, imagens, gráficos, ou vídeos.
4. O [usuário](../../modelagem/lexico.md#Usuário) personaliza o [design](../../modelagem/lexico.md#Design), ajustando cores, fontes, layouts, e outros detalhes para tornar o material mais envolvente e atraente.
5. O [usuário](../../modelagem/lexico.md#Usuário) utiliza recursos interativos, como links, botões, vídeos, ou quizzes, para tornar o material educacional mais dinâmico e interativo.
6. O [usuário](../../modelagem/lexico.md#Usuário) revisa o material educacional em tempo real, fazendo ajustes conforme necessário para melhorar a qualidade e eficácia do [conteúdo](../../modelagem/lexico.md#Conteúdo).
7. Após finalizar o material educacional, o [usuário](../../modelagem/lexico.md#Usuário) salva o projeto e, se necessário, faz uma exportação nos formatos desejados.

#### __RESTRIÇÕES__

O [usuário](../../modelagem/lexico.md#Usuário) deve ter conhecimento sobre os princípios de [design](../../modelagem/lexico.md#Design) educacional e as melhores práticas para criar materiais educacionais interativos.

#### __PÓS-CONDIÇÃO__

O material educacional interativo foi criado com sucesso, pronto para ser utilizado no ensino e aprendizado.

#### __RESULTADO ESPERADO__

O [usuário](../../modelagem/lexico.md#Usuário) consegue criar materiais educacionais interativos e envolventes na plataforma Canva, utilizando as ferramentas disponíveis para facilitar o ensino e o aprendizado.


