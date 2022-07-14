# Git Flow Pede Pronto
![Image title](assets/img/git-flow.png)

[Documentação git Flow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)

## Fluxo Pede Pronto 

Uma boa gestão de versionamento nos ajuda ter uma fluidez entre as tribos, e melhora o processo de 
deploy e testes das aplicações. 

### Branchs  
Iremos adotar como nomenclatura para a master de main.

A develop e a main, como no git flow são as principais. Sendo a
develop filha da main.

Toda feature é filha da develop, e temo como padrão de nomencalatura:
- feature/{Identicado do Jira da estória}
 Ex.: featire/SER-43
    SER: squad Serviços Core
    43: numero da estória