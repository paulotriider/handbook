<img src="https://cdn.rawgit.com/pagarme/brand/9ec30d3d4a6dd8b799bca1c25f60fb123ad66d5b/logo-circle.svg" width="127px" height="127px" align="left"/>

# Workflows

[Voltar para a home do Handbook][back]

<br/>

Para facilitar o aprendizado e centralizar a consulta de informações,
criamos materiais e selecionamos links que podem ser consultados, para que
você possa entender melhor como trabalhar no Pagar.me.

## Trabalhando

Usamos o Github para desenvolver e gerenciar nossos projetos. Para mais
informações sobre como funciona o fluxo de trabalho de desenvolvimento
leia sobre o [The Github Flow][about-gh-flow].

## Pesquisando no Github

Quando precisar de uma informação ou tiver algum problema, que tal começar
pela busca? Acesse [github.com/pagarme][gh-pagarme] e
digite no campo de busca `como reservar salas`, dê enter e acesse a seção
de `Issues`. No GitHub, você encontra wikis, reports e documentos de todos
os tipos.


Veja o vídeo abaixo e entenda como você pode utilizar o Github para buscar
por informações ou problemas parecidos com o seu:

[![Buscando no Github](http://img.youtube.com/vi/Pl9J9w55ST0/0.jpg)](http://www.youtube.com/watch?v=by4qsV3p0lA "Buscando no Github")

#### Links úteis

* [Github Docs for Search][about-gh-search]
* [Using search to filter issues and pull requests][about-gh-search-issues]

## Descobrindo onde reportar problemas

Se você não encontrou nada na sua busca, sinta-se livre para criar uma nova
**Issue**. Conhecer e validar as situações abaixo irá ajudar você a descobrir
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
Se você encontrar que algo pode ser feito melhor, faça melhor!
Vamos contribuir para isso!

| Escopo          | Onde encontrar                               |
|-----------------|----------------------------------------------|
| Dashboard       | https://github.com/pagarme/pagarme-dashboard |
| API + Gateway   | https://github.com/pagarme/pagarme-core      |


## Diagnosticando no navegador

Para diagnosticar problemas na dashboard e checkout, navegadores como
o Chrome, Safari e Firefox dispõe de ferramentas interessantes que podem
prover maiores informações sobre o problema.

Estas informações são essenciais para que os nossos desenvolvedores possam
atacar o problema mais eficientemente.

Assista o vídeo abaixo para entender como utilizar estas ferramentas, assim
você pode enriquecer seu report!

[![Diagnosticando a Dashboard](http://img.youtube.com/vi/by4qsV3p0lA/0.jpg)](http://www.youtube.com/watch?v=by4qsV3p0lA "Diagnosticando a Dashboard")

## Ferramentas

No dia-a-dia precisamos coletar evidencias de bugs, problemas e também usar
imagens para explicar de maneira mais clara nossos pensamentos. É altamente
recomendado o uso de GIFs e capturas de tela!! Confira alguns links para
ferramentas úteis no nosso dia-a-dia:


* [Lightshot Screenshot Tool para Chrome][screenshot-chrome]
* [Lightshot Screenshot Tool para Firefox][screenshot-firefox]
* [Gerador e validador de CPF e CNPJ][gerador-cnpj]
* [Caixa de e-mail temporária][yopmail]

## Fluxos

Estes são os fluxos básicos que precisamos dominar para trabalhar de maneira
fluída no dia-a-dia. Qualquer dúvida, converse diretamente com seu gestor ou
use o fórum.

### Como entrar no GitHub da organização?

1. Crie uma conta no GitHub
1. Preencha as informações básicas de nome e bio
1. Adicione uma foto de perfil, ela é importante!
1. Habilite a opção de [Two Factor Auth][twofactor-gh] do Github
1. Informe seu usuário ao seu gestor, ele solicitará seu acesso

### Se encontrar um problema

1. Acesse [github.com/pagarme][gh-pagarme]
1. [Procure](#pequisando-no-github) se o problema já foi abordado
1. Utilize as tabelas acima para localizar em qual projeto você deve reportar
   seu problema
1. Entre no projeto, navegue até a seção **Issues** e clique em **New Issue**
1. Siga as instruções que estão no campo de texto
1. **Atente-se se o repositório é público ou privado**
1. Não use dados privados (chaves, IDs) em repositórios públicos
1. Adicione links, tickets, prints, queries, prints do DevTools

#### Dicas:

* Evite a criação de issues duplicadas
* Use os comentários para adicionar detalhes
* Melhore issues já existentes

#### Links uteis

* [Mastering Issues][mastering-issues]

### Após criar uma issue

1. Evite atribuir a issue a uma pessoa, projeto ou milestone
1. Não há necessidade de mandar a issue para varias pessoas
1. O time irá recepcionar sua issue e fazer triagem
1. Use os comentários para acompanhar o andamento da situacão

> Uma issue que reporta um problema possui uma carga de informação útil
> sobre ele. Se você encontrar essa issue, melhore-a. Tente reproduzir o
> problema e compartilhe o que você descobriu!

Para tratar das issues, os squads seguem o fluxo abaixo:

![Issues workflow diagram][issues-workflow]

### Para criar milestones

1. Os owners são responsáveis pela manutenção das issues de seu escopo
1. Os owners mapeiam todas as atividades e formulam milestones
1. Os owners unificam possíveis issues duplicadas
  1. Referenciando com o link de outras issues, tickets, etc
  1. Através de uma issue duplicada com mais informações
  1. Através de uma nova issue que concentra todo conhecimento
1. Os owners alinham as milestones com o time

#### Links úteis

* [About Milestones][about-milestones]
* [Creating and editing milestones for issues and pull requests][creating-milestones]

### Durante uma milestone

1. São feitas reuniões semanais para alinhar as entregas
1. Faz múltiplos deploys em test e live, se aplicável
1. O time comunica a conclusão das issues ao fechá-las
1. Os owners orquestram o [andamento das issues com o time][team-progress]

### Ao final da milestone

1. Compartilha os resultados e apredizado com a empresa e a comunidade
1. Firma o compromisso com a próxima milestone
1. Reserva uma sala espaçosa para mais de 30 pessoas
1. Solicita lanches, água e sucos
1. Envia um e-mail com mais informações sobre o encontro

O final de uma milestone não deveria passar despercebido. E um evento que
merece atenção dos times, pois é quando a equipe deixa claro quais são os
próximos passos a ser tomados.

Traga suas estratégias, sugestões, números e evidências para discutirmos
sobre o resultado do nosso trabalho.

O fluxo de uma milestone é:

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

