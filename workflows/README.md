<img src="https://cdn.rawgit.com/pagarme/brand/9ec30d3d4a6dd8b799bca1c25f60fb123ad66d5b/logo-circle.svg" width="127px" height="127px" align="left"/>

# Workflows

[Voltar para a home do Handbook][back]

<br/>

Para facilitar o aprendizado e centralizar a consulta de informações
criamos materiais e reservamos links que podem ser consultados para
entender melhor como trabalhar na Pagar.me!

## Trabalhando

Usamos o Github para desenvolver e gerenciar nossos projetos. Para mais
informações sobre como funciona o fluxo de trabalho de desenvolvimento
leia sobre o [The Github Flow][about-gh-flow].

## Pesquisando no Github

Quando precisar de uma informação ou tiver algum problema, que tal começar
pela busca? Acesse [github.com/pagarme][gh-pagarme] e
digite no campo de busca `como reservar salas`, dê enter e acesse a seção
de `Issues`. No Github você encontrará wikis, reports e documentos de todos
os tipos.

Veja o vídeo abaixo para entender como você pode utilizar o Github para
buscar por informações ou problemas parecidos com o seu:

[![Buscando no Github](http://img.youtube.com/vi/Pl9J9w55ST0/0.jpg)](http://www.youtube.com/watch?v=by4qsV3p0lA "Buscando no Github")

#### Links úteis

* [Github Docs for Search][about-gh-search]
* [Using search to filter issues and pull requests][about-gh-search-issues]

## Descobrindo onde reportar problemas

Se você não encontrou nada na sua busca, sinta-se livre para criar uma nova
**Issue**. Conhecer e validar as situacões abaixo irá ajudar você a descobrir
em qual projeto reportar:

| Problema                                    | Dashboard | API |
|---------------------------------------------|-----------|-----|
| Dashboard não carrega                       | X         |     |
| Dashboard em branco                         | X         |     |
| Sessão ou parte da dashboard não aparece    | X         |     |
| Dashboard carrega mas dados nunca aparecem  |           | X   |
| Muitas notificações de erro na dashboard    |           | X   |
| Filtro de metadata não funciona             |           | X   |

Se você perceber que algum item está errado, altere!
Se você ver que algo pode ser feito melhor, faça melhor!
Vamos contribuir para isso!

| Escopo          | Onde encontrar                               |
|-----------------|----------------------------------------------|
| Dashboard       | https://github.com/pagarme/pagarme-dashboard |
| API + Gateway   | https://github.com/pagarme/pagarme-core      |


## Diagnosticando no navegador

Para diagnosticar problemas na dashboard e checkout, navegadores como
o Chrome, Safari e Firefox dispõe de ferramentas interessantes, que podem
prover maiores informações sobre o problema.

Estas informações são super importantes para que os nosssos
desenvolvedores possam atacar o problema mais eficientemente.

Veja o vídeo abaixo para entender como você pode utilizar estas ferramentas
para enriquecer seu report!

[![Diagnosticando a Dashboard](http://img.youtube.com/vi/by4qsV3p0lA/0.jpg)](http://www.youtube.com/watch?v=by4qsV3p0lA "Diagnosticando a Dashboard")

## Ferramentas

No dia-a-dia precisamos coletar evidencias de bugs, problemas e também usar
imagens para explicar de maneira mais clara nossos pensamentos. É altamente
recomendado o uso de GIFs e capturas de tela!! Abaixo você pode conferir
alguns links para ferramentas úteis no nosso dia-a-dia!!

* [Lightshot Screenshot Tool para Chrome][screenshot-chrome]
* [Lightshot Screenshot Tool para Firefox][screenshot-firefox]
* [Gerador e validador de CPF e CNPJ][gerador-cnpj]
* [Caixa de e-mail temporária][yopmail]

## Fluxos

Estes são os fluxos básicos que precisamos dominar para um trabalho fluído no
dia-a-dia. Qualquer dúvida, converse diretamente com seu gestor ou use o forum.

### Como entrar no GitHub da organização?

1. Crie uma conta no GitHub
1. Preencha as informações básicas de nome e bio
1. Adicione uma foto de perfil, ela é importante!
1. Habilite a opção de [Two Factor Auth][twofactor-gh] do Github
1. Informe seu usuário ao seu gestor, ele solicitará seu acesso

### Quando eu encontrar um problema

1. Acessar [github.com/pagarme][gh-pagarme]
1. Procurar se o problema já existe ([veja o vídeo](#pequisando-no-github))
1. Utilize as tabelas acima para localizar onde reportar seu problema
1. Entre no projeto, navegue até a seção **Issues** e clique em **New Issue**
1. Siga as instrucoes que estao no campo de texto
1. Atente-se se o repositório é público ou privado!
1. Não use dados privados (chaves, IDs) em repositórios públicos
1. Adicione tickets, prints, queries, prints do DevTools

#### Dicas:

* Evite a criacao de issues duplicadas
* Use os comentarios para adicionar detalhes
* Melhore issues já existentes

#### Links uteis

* [Mastering Issues][mastering-issues]

### Após criar uma issue

1. Evite atribuir a issue a uma pessoa, projeto ou milestone
1. Nao há necessidade de mandar a issue para varias pessoas
1. O time ira recepcionar sua issue, e fazer triagem
1. Use os comentarios para acompanhar o andamento da situacao

> Uma issue que reporta um problema contém uma carga de informação útil sobre o
> problema. Se você encontrar essa issue, melhore-a. Tente reproduzir o
> problema e compartilhe o que você descobriu!

O fluxo descrito abaixo é seguido pelos squads para tratar das issues:

![Issues workflow diagram][issues-workflow]

### Para criar milestones

1. Os owners são responsáveis pela manutenção das issues de seu escopo
1. Os owners mapeiam todas as atividades e formulam milestones
1. Os owners unificam possíveis duplicados
  1. Referenciando outras issues, tickets, etc com o link
  1. Através de uma issue duplicada com mais informações
  1. Através de uma nova issue que concentra todo conhecimento
1. Os owners alinham as milestones com o time

#### Links úteis

* [About Milestones][about-milestones]
* [Creating and editing milestones for issues and pull requests][creating-milestones]

### Durante uma milestone

1. Time pratica reunioes semanais para alinhar as entregas
1. Faz multiplos deploys em test e live se aplicável
1. Comunicam a conclusão de issues mediante seu fechamento
1. Os owners orquestram o [andamento das issues com o time][team-progress]

### Ao final da milestone

O final de uma milestone não deveria passar despercebido pelas pessoas, é um evento
que merece atenção dos times pois é quando a equipe deixa claro quais são os
próximos passos a ser tomados.

Então traga suas estratégias, suas sugestões, seus números e evidências para
discutirmos sobre o resultado do nosso trabalho.

1. Compartilha os resultados e apredizado com a empresa e a comunidade
1. Firma o compromisso com a próxima milestone
1. Reservar uma sala espaçosa para mais de 30 pessoas
1. Solicitar lanches, água e sucos
1. Enviar email da reserva com mais informações sobre o encontro

As milestones seguem o seguinte fluxo:

![Milestones workflow diagram][milestones-workflow]

---

[back]: ..

[issues-workflow]: https://rawgit.com/pagarme/handbook/workflows/workflows/issues-workflow.svg
[milestones-workflow]: https://rawgit.com/pagarme/handbook/workflows/workflows/milestones-workflow.svg

[screenshot-chrome]: https://chrome.google.com/webstore/detail/lightshot-screenshot-tool/mbniclmhobmnbdlbpiphghaielnnpgdp
[screenshot-firefox]: https://addons.mozilla.org/fr/firefox/addon/lightshot
[gerador-cnpj]: http://www.geradordecnpj.org
[yopmail]: http//www.yopmail.com

[gh-pagarme]: https://github.com/pagarme
[about-gh-flow]: https://guides.github.com/introduction/flow
[about-gh-search]: https://help.github.com/categories/search
[about-gh-search-issues]: https://help.github.com/articles/using-search-to-filter-issues-and-pull-requests/
[about-issues-and-prs]: https://guides.github.com/features/issues
[about-milestones]: https://help.github.com/articles/about-milestones
[mastering-issues]: https://guides.github.com/features/issues
[creating-milestones]: https://help.github.com/articles/creating-and-editing-milestones-for-issues-and-pull-requests/
[team-progress]: http://2.bp.blogspot.com/-5eCIBitfxb8/USlWfBPKx6I/AAAAAAAACj4/6NhFZChzrpQ/s1600/787+assembly.jpg
[twofactor-gh]: https://github.com/settings/security

