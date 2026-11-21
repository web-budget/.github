## webBudget: controle financeiro simples, livre e de código aberto

O webBudget é um sistema livre e de código aberto para você organizar as suas finanças pessoais ou as de um pequeno negócio. Ele reúne as ferramentas essenciais do controle financeiro numa interface simples e direta, que dá a maior visibilidade possível sobre o seu dinheiro.

### Sobre o projeto

O projeto nasceu em 2008 como uma aplicação desktop em Java Swing. Depois evoluiu para uma aplicação web em JSF, e a versão 3 é a última versão estável, que continua disponível [aqui](https://github.com/arthurgregorio/web-budget).

A versão 4 é uma reconstrução completa, que atualiza a arquitetura e abre espaço para recursos novos. Na primeira fase, ela foi desenvolvida em dois repositórios, `back-end` e `front-end`, que hoje estão arquivados. O desenvolvimento agora acontece num único **monorepo**, o [web-budget/monorepo](https://github.com/web-budget/monorepo), com o server e o client lado a lado.

### Tecnologias

Das versões anteriores, que usavam JSF e PrimeFaces e nos serviram bem por muitos anos, ficou a simplicidade. A versão 4 está sendo reconstruída com uma pilha mais moderna:

- Kotlin e Spring Boot 4
- jOOQ e Liquibase
- Vue 3 e TypeScript
- PostgreSQL 18

### Versões e pré-lançamentos

A versão 4 está em fase `alpha`. As versões `alpha` **não geram release nem imagem Docker**: quem quiser experimentá-las compila o código, seguindo o guia [Compilar a partir do código-fonte](https://github.com/web-budget/monorepo/wiki/Compilar-do-codigo-fonte). Para um uso estável, a versão 3 continua sendo a indicada.

### Links

- [Site](https://webbudget.com.br/)
- [Código da versão 4 (monorepo)](https://github.com/web-budget/monorepo)
- [Documentação (wiki)](https://github.com/web-budget/monorepo/wiki)
- [Como compilar a partir do código-fonte](https://github.com/web-budget/monorepo/wiki/Compilar-do-codigo-fonte)
- [Quadro de planejamento da versão 4](https://github.com/orgs/web-budget/projects/7)
- [Versão 3, antiga e estável](https://github.com/arthurgregorio/web-budget)

### Quer contribuir?

Adoraríamos ouvir você! Se tem interesse em contribuir com o projeto, escreva para contato@consusoft.com.br e vamos conversar.

### Agradecimento especial

Um grande obrigado à JetBrains por apoiar este projeto com uma licença gratuita do IntelliJ IDEA Ultimate. As ferramentas de vocês tornam o nosso desenvolvimento mais rápido e mais agradável!
