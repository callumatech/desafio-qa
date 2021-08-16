# Canal Dstak Desafio NodeJS (Backend)

## Instruções

Você possui *uma semana* para fazer o teste. Nesse teste todas as suas habilidades serão avaliadas, dentre elas:

- Poder de simplificação
- Autonomia e soluções criativas
- Conhecimento NodeJS e Clean Architecture
- Conhecimento técnico componentização
- Conhecimento em git
- Capacidade em explicar as decisões tomadas e como testar o projeto

### Para Submeter

Você deve:

- Fazer o fork particular e privado do projeto do desafio e compartilhar com:
  - @cloped
  - @romfmoura
- Codificar
- Commitar seu código

### Boa sorte!

No Canal Dstak acreditamos que tudo é possível e queremos contar com pessoas incríveis. Mostre o seu potencial, acreditamos em você. Boa sorte!

![Boa-Sorte](https://media.giphy.com/media/12XDYvMJNcmLgQ/giphy.gif)

## Antes de programar

Você verá que o desafio em questão é bem similar ao que o Canal Dstak se propõe a resolver, para avaliarmos também a sua capacidade de inovar conosco dê uma olhada no nosso app e anote todas as sugestões do que pode ser feito de novo ou até melhor, adicione isso no seu README.

Após você implementar o seu desafio revisite as suas sugestões e veja se há algo a mais que queira adicionar.

## Desafio

Você está em uma startup que acabou de pivotar para criar um marketplace de venda de roupas, será necessário um backoffice para suportar a operação e o atendimento aos compradores e vendedores. Você precisará fazer o mais simples com a melhor qualidade possível!

Sua tarefa é bem simples. Precisa criar um microserviço que faça a validação de um CEP, e retorne seus daddos (endereço) em uma estrutura normalizada. Para essa implementação, você poderá utilizar o express ou a plataforma serverless da AWS (Api gateway + lambda). A infra é de sua escolha, apenas justifique no README e documente os passos para execução de seu microserviço.

### Requisitos

* Básicos
  * A aplicação deverá ser em NodeJS com Typescript
  * Simplificar o que deve ser feito mantendo qualidade
  * Estruture o teste unitátio com o Jest
  * A interface do microserviço deverá ser RESTFULL. Defina a conversação como quiser e documente no README (request e response)
  * Não há necessidade de autenticação para essa rota
  * Utilize conceitos de clean architecture (entrypoint, usecase, connector, entity, etc..)
  * Para consulta do CEP, utilize o VIACEP (https://viacep.com.br/ws/01001000/json/)
  * Regra de negócio: Verifique se o input recebido está no formato correto de um CEP. Se tiver, faça a consulta dos dados no VIACEP e formate a resposta. Trate todos os erros possíveis.
  * Utilize commits atômicos
  * Documente do que você fez e das suas motivações no README. Isso servirá como guia para a entrevista técnica.

* Você se destacará ainda mais se fizer algum desses pontos:
  * Configuração/uso de lint
  * Componentização
  * Utilizar os padrões Clean Code
  * Criação de testes unitário
  * Tratativas de Erro
  * Padrões RESTFULL

### Avaliação

* **50%**: Arquitetura de desenvolvimento
* **30%**: Testes unitários e tratamento de erro
* **20%**: Documentação do README

### Entrevista técnica

Esse desafio será o assunto principal da entrevista técnica. Nessa conversa discutiremos o código, a arquitetura implementada fazendo um paralelo à nossa realidade. Faremos também um bate papo sobre suas decisões tomadas para essa implementação.

# Canal Dstak Desafio NodeJS (Backend)

## Instruções

Você possui *uma semana* para fazer o teste. Nesse teste todas as suas habilidades serão avaliadas, dentre elas:

- Poder de simplificação
- Autonomia e soluções criativas
- Conhecimento NodeJS e Clean Architecture
- Conhecimento técnico componentização
- Conhecimento em git
- Capacidade em explicar as decisões tomadas e como testar o projeto

### Para Submeter

Você deve:

- Fazer o fork particular e privado do projeto do desafio e compartilhar com:
  - @cloped
  - @romfmoura
- Codificar
- Commitar seu código

### Boa sorte!

No Canal Dstak acreditamos que tudo é possível e queremos contar com pessoas incríveis. Mostre o seu potencial, acreditamos em você. Boa sorte!

![Boa-Sorte](https://media.giphy.com/media/12XDYvMJNcmLgQ/giphy.gif)

## Antes de programar

Você verá que o desafio em questão é bem similar ao que o Canal Dstak se propõe a resolver, para avaliarmos também a sua capacidade de inovar conosco dê uma olhada no nosso app e anote todas as sugestões do que pode ser feito de novo ou até melhor, adicione isso no seu README.

Após você implementar o seu desafio revisite as suas sugestões e veja se há algo a mais que queira adicionar.

## Desafio

Você está em uma startup que acabou de pivotar para criar um marketplace de venda de roupas, será necessário um backoffice para suportar a operação e o atendimento aos compradores e vendedores. Você precisará fazer o mais simples com a melhor qualidade possível!

Sua tarefa é bem simples. Precisa criar um microserviço que faça a validação de um CEP, e retorne seus daddos (endereço) em uma estrutura normalizada. Para essa implementação, você poderá utilizar o express ou a plataforma serverless da AWS (Api gateway + lambda). A infra é de sua escolha, apenas justifique no README e documente os passos para execução de seu microserviço.

### Requisitos

* Básicos
  * A aplicação deverá ser em NodeJS com Typescript
  * Simplificar o que deve ser feito mantendo qualidade
  * Estruture o teste unitátio com o Jest
  * A interface do microserviço deverá ser RESTFULL. Defina a conversação como quiser e documente no README (request e response)
  * Não há necessidade de autenticação para essa rota
  * Utilize conceitos de clean architecture (entrypoint, usecase, connector, entity, etc..)
  * Para consulta do CEP, utilize o VIACEP (https://viacep.com.br/ws/01001000/json/)
  * Regra de negócio: Verifique se o input recebido está no formato correto de um CEP. Se tiver, faça a consulta dos dados no VIACEP e formate a resposta. Trate todos os erros possíveis.
  * Utilize commits atômicos
  * Documente do que você fez e das suas motivações no README. Isso servirá como guia para a entrevista técnica.

* Você se destacará ainda mais se fizer algum desses pontos:
  * Configuração/uso de lint
  * Componentização
  * Utilizar os padrões Clean Code
  * Criação de testes unitário
  * Tratativas de Erro
  * Padrões RESTFULL

### Avaliação

* **50%**: Arquitetura de desenvolvimento
* **30%**: Testes unitários e tratamento de erro
* **20%**: Documentação do README

### Entrevista técnica

Esse desafio será o assunto principal da entrevista técnica. Nessa conversa discutiremos o código, a arquitetura implementada fazendo um paralelo à nossa realidade. Faremos também um bate papo sobre suas decisões tomadas para essa implementação.

# Canal Dstak Desafio NodeJS (Backend)

## Instruções

Você possui *uma semana* para fazer o teste. Nesse teste todas as suas habilidades serão avaliadas, dentre elas:

- Poder de simplificação
- Autonomia e soluções criativas
- Conhecimento NodeJS e Clean Architecture
- Conhecimento técnico componentização
- Conhecimento em git
- Capacidade em explicar as decisões tomadas e como testar o projeto

### Para Submeter

Você deve:

- Fazer o fork particular e privado do projeto do desafio e compartilhar com:
  - @cloped
  - @romfmoura
- Codificar
- Commitar seu código

### Boa sorte!

No Canal Dstak acreditamos que tudo é possível e queremos contar com pessoas incríveis. Mostre o seu potencial, acreditamos em você. Boa sorte!

![Boa-Sorte](https://media.giphy.com/media/12XDYvMJNcmLgQ/giphy.gif)

## Antes de programar

Você verá que o desafio em questão é bem similar ao que o Canal Dstak se propõe a resolver, para avaliarmos também a sua capacidade de inovar conosco dê uma olhada no nosso app e anote todas as sugestões do que pode ser feito de novo ou até melhor, adicione isso no seu README.

Após você implementar o seu desafio revisite as suas sugestões e veja se há algo a mais que queira adicionar.

## Desafio

Você está em uma startup que acabou de pivotar para criar um marketplace de venda de roupas, será necessário um backoffice para suportar a operação e o atendimento aos compradores e vendedores. Você precisará fazer o mais simples com a melhor qualidade possível!

Sua tarefa é bem simples. Precisa criar um microserviço que faça a validação de um CEP, e retorne seus daddos (endereço) em uma estrutura normalizada. Para essa implementação, você poderá utilizar o express ou a plataforma serverless da AWS (Api gateway + lambda). A infra é de sua escolha, apenas justifique no README e documente os passos para execução de seu microserviço.

### Requisitos

* Básicos
  * A aplicação deverá ser em NodeJS com Typescript
  * Simplificar o que deve ser feito mantendo qualidade
  * Estruture o teste unitátio com o Jest
  * A interface do microserviço deverá ser RESTFULL. Defina a conversação como quiser e documente no README (request e response)
  * Não há necessidade de autenticação para essa rota
  * Utilize conceitos de clean architecture (entrypoint, usecase, connector, entity, etc..)
  * Para consulta do CEP, utilize o VIACEP (https://viacep.com.br/ws/01001000/json/)
  * Regra de negócio: Verifique se o input recebido está no formato correto de um CEP. Se tiver, faça a consulta dos dados no VIACEP e formate a resposta. Trate todos os erros possíveis.
  * Utilize commits atômicos
  * Documente do que você fez e das suas motivações no README. Isso servirá como guia para a entrevista técnica.

* Você se destacará ainda mais se fizer algum desses pontos:
  * Configuração/uso de lint
  * Componentização
  * Utilizar os padrões Clean Code
  * Criação de testes unitário
  * Tratativas de Erro
  * Padrões RESTFULL

### Avaliação

* **50%**: Arquitetura de desenvolvimento
* **30%**: Testes unitários e tratamento de erro
* **20%**: Documentação do README

### Entrevista técnica

Esse desafio será o assunto principal da entrevista técnica. Nessa conversa discutiremos o código, a arquitetura implementada fazendo um paralelo à nossa realidade. Faremos também um bate papo sobre suas decisões tomadas para essa implementação.

# Canal Dstak Desafio NodeJS (Backend)

## Instruções

Você possui *uma semana* para fazer o teste. Nesse teste todas as suas habilidades serão avaliadas, dentre elas:

- Poder de simplificação
- Autonomia e soluções criativas
- Conhecimento NodeJS e Clean Architecture
- Conhecimento técnico componentização
- Conhecimento em git
- Capacidade em explicar as decisões tomadas e como testar o projeto

### Para Submeter

Você deve:

- Fazer o fork particular e privado do projeto do desafio e compartilhar com:
  - @cloped
  - @romfmoura
- Codificar
- Commitar seu código

### Boa sorte!

No Canal Dstak acreditamos que tudo é possível e queremos contar com pessoas incríveis. Mostre o seu potencial, acreditamos em você. Boa sorte!

![Boa-Sorte](https://media.giphy.com/media/12XDYvMJNcmLgQ/giphy.gif)

## Antes de programar

Você verá que o desafio em questão é bem similar ao que o Canal Dstak se propõe a resolver, para avaliarmos também a sua capacidade de inovar conosco dê uma olhada no nosso app e anote todas as sugestões do que pode ser feito de novo ou até melhor, adicione isso no seu README.

Após você implementar o seu desafio revisite as suas sugestões e veja se há algo a mais que queira adicionar.

## Desafio

Você está em uma startup que acabou de pivotar para criar um marketplace de venda de roupas, será necessário um backoffice para suportar a operação e o atendimento aos compradores e vendedores. Você precisará fazer o mais simples com a melhor qualidade possível!

Sua tarefa é bem simples. Precisa criar um microserviço que faça a validação de um CEP, e retorne seus daddos (endereço) em uma estrutura normalizada. Para essa implementação, você poderá utilizar o express ou a plataforma serverless da AWS (Api gateway + lambda). A infra é de sua escolha, apenas justifique no README e documente os passos para execução de seu microserviço.

### Requisitos

* Básicos
  * A aplicação deverá ser em NodeJS com Typescript
  * Simplificar o que deve ser feito mantendo qualidade
  * Estruture o teste unitátio com o Jest
  * A interface do microserviço deverá ser RESTFULL. Defina a conversação como quiser e documente no README (request e response)
  * Não há necessidade de autenticação para essa rota
  * Utilize conceitos de clean architecture (entrypoint, usecase, connector, entity, etc..)
  * Para consulta do CEP, utilize o VIACEP (https://viacep.com.br/ws/01001000/json/)
  * Regra de negócio: Verifique se o input recebido está no formato correto de um CEP. Se tiver, faça a consulta dos dados no VIACEP e formate a resposta. Trate todos os erros possíveis.
  * Utilize commits atômicos
  * Documente do que você fez e das suas motivações no README. Isso servirá como guia para a entrevista técnica.

* Você se destacará ainda mais se fizer algum desses pontos:
  * Configuração/uso de lint
  * Componentização
  * Utilizar os padrões Clean Code
  * Criação de testes unitário
  * Tratativas de Erro
  * Padrões RESTFULL

### Avaliação

* **50%**: Arquitetura de desenvolvimento
* **30%**: Testes unitários e tratamento de erro
* **20%**: Documentação do README

### Entrevista técnica

Esse desafio será o assunto principal da entrevista técnica. Nessa conversa discutiremos o código, a arquitetura implementada fazendo um paralelo à nossa realidade. Faremos também um bate papo sobre suas decisões tomadas para essa implementação.

# Canal Dstak Desafio NodeJS (Backend)

## Instruções

Você possui *uma semana* para fazer o teste. Nesse teste todas as suas habilidades serão avaliadas, dentre elas:

- Poder de simplificação
- Autonomia e soluções criativas
- Conhecimento NodeJS e Clean Architecture
- Conhecimento técnico componentização
- Conhecimento em git
- Capacidade em explicar as decisões tomadas e como testar o projeto

### Para Submeter

Você deve:

- Fazer o fork particular e privado do projeto do desafio e compartilhar com:
  - @cloped
  - @romfmoura
- Codificar
- Commitar seu código

### Boa sorte!

No Canal Dstak acreditamos que tudo é possível e queremos contar com pessoas incríveis. Mostre o seu potencial, acreditamos em você. Boa sorte!

![Boa-Sorte](https://media.giphy.com/media/12XDYvMJNcmLgQ/giphy.gif)

## Antes de programar

Você verá que o desafio em questão é bem similar ao que o Canal Dstak se propõe a resolver, para avaliarmos também a sua capacidade de inovar conosco dê uma olhada no nosso app e anote todas as sugestões do que pode ser feito de novo ou até melhor, adicione isso no seu README.

Após você implementar o seu desafio revisite as suas sugestões e veja se há algo a mais que queira adicionar.

## Desafio

Você está em uma startup que acabou de pivotar para criar um marketplace de venda de roupas, será necessário um backoffice para suportar a operação e o atendimento aos compradores e vendedores. Você precisará fazer o mais simples com a melhor qualidade possível!

Sua tarefa é bem simples. Precisa criar um microserviço que faça a validação de um CEP, e retorne seus daddos (endereço) em uma estrutura normalizada. Para essa implementação, você poderá utilizar o express ou a plataforma serverless da AWS (Api gateway + lambda). A infra é de sua escolha, apenas justifique no README e documente os passos para execução de seu microserviço.

### Requisitos

* Básicos
  * A aplicação deverá ser em NodeJS com Typescript
  * Simplificar o que deve ser feito mantendo qualidade
  * Estruture o teste unitátio com o Jest
  * A interface do microserviço deverá ser RESTFULL. Defina a conversação como quiser e documente no README (request e response)
  * Não há necessidade de autenticação para essa rota
  * Utilize conceitos de clean architecture (entrypoint, usecase, connector, entity, etc..)
  * Para consulta do CEP, utilize o VIACEP (https://viacep.com.br/ws/01001000/json/)
  * Regra de negócio: Verifique se o input recebido está no formato correto de um CEP. Se tiver, faça a consulta dos dados no VIACEP e formate a resposta. Trate todos os erros possíveis.
  * Utilize commits atômicos
  * Documente do que você fez e das suas motivações no README. Isso servirá como guia para a entrevista técnica.

* Você se destacará ainda mais se fizer algum desses pontos:
  * Configuração/uso de lint
  * Componentização
  * Utilizar os padrões Clean Code
  * Criação de testes unitário
  * Tratativas de Erro
  * Padrões RESTFULL

### Avaliação

* **50%**: Arquitetura de desenvolvimento
* **30%**: Testes unitários e tratamento de erro
* **20%**: Documentação do README

### Entrevista técnica

Esse desafio será o assunto principal da entrevista técnica. Nessa conversa discutiremos o código, a arquitetura implementada fazendo um paralelo à nossa realidade. Faremos também um bate papo sobre suas decisões tomadas para essa implementação.

# Canal Dstak Desafio NodeJS (Backend)

## Instruções

Você possui *uma semana* para fazer o teste. Nesse teste todas as suas habilidades serão avaliadas, dentre elas:

- Poder de simplificação
- Autonomia e soluções criativas
- Conhecimento NodeJS e Clean Architecture
- Conhecimento técnico componentização
- Conhecimento em git
- Capacidade em explicar as decisões tomadas e como testar o projeto

### Para Submeter

Você deve:

- Fazer o fork particular e privado do projeto do desafio e compartilhar com:
  - @cloped
  - @romfmoura
- Codificar
- Commitar seu código

### Boa sorte!

No Canal Dstak acreditamos que tudo é possível e queremos contar com pessoas incríveis. Mostre o seu potencial, acreditamos em você. Boa sorte!

![Boa-Sorte](https://media.giphy.com/media/12XDYvMJNcmLgQ/giphy.gif)

## Antes de programar

Você verá que o desafio em questão é bem similar ao que o Canal Dstak se propõe a resolver, para avaliarmos também a sua capacidade de inovar conosco dê uma olhada no nosso app e anote todas as sugestões do que pode ser feito de novo ou até melhor, adicione isso no seu README.

Após você implementar o seu desafio revisite as suas sugestões e veja se há algo a mais que queira adicionar.

## Desafio

Você está em uma startup que acabou de pivotar para criar um marketplace de venda de roupas, será necessário um backoffice para suportar a operação e o atendimento aos compradores e vendedores. Você precisará fazer o mais simples com a melhor qualidade possível!

Sua tarefa é bem simples. Precisa criar um microserviço que faça a validação de um CEP, e retorne seus daddos (endereço) em uma estrutura normalizada. Para essa implementação, você poderá utilizar o express ou a plataforma serverless da AWS (Api gateway + lambda). A infra é de sua escolha, apenas justifique no README e documente os passos para execução de seu microserviço.

### Requisitos

* Básicos
  * A aplicação deverá ser em NodeJS com Typescript
  * Simplificar o que deve ser feito mantendo qualidade
  * Estruture o teste unitátio com o Jest
  * A interface do microserviço deverá ser RESTFULL. Defina a conversação como quiser e documente no README (request e response)
  * Não há necessidade de autenticação para essa rota
  * Utilize conceitos de clean architecture (entrypoint, usecase, connector, entity, etc..)
  * Para consulta do CEP, utilize o VIACEP (https://viacep.com.br/ws/01001000/json/)
  * Regra de negócio: Verifique se o input recebido está no formato correto de um CEP. Se tiver, faça a consulta dos dados no VIACEP e formate a resposta. Trate todos os erros possíveis.
  * Utilize commits atômicos
  * Documente do que você fez e das suas motivações no README. Isso servirá como guia para a entrevista técnica.

* Você se destacará ainda mais se fizer algum desses pontos:
  * Configuração/uso de lint
  * Componentização
  * Utilizar os padrões Clean Code
  * Criação de testes unitário
  * Tratativas de Erro
  * Padrões RESTFULL

### Avaliação

* **50%**: Arquitetura de desenvolvimento
* **30%**: Testes unitários e tratamento de erro
* **20%**: Documentação do README

### Entrevista técnica

Esse desafio será o assunto principal da entrevista técnica. Nessa conversa discutiremos o código, a arquitetura implementada fazendo um paralelo à nossa realidade. Faremos também um bate papo sobre suas decisões tomadas para essa implementação.

# Canal Dstak Desafio NodeJS (Backend)

## Instruções

Você possui *uma semana* para fazer o teste. Nesse teste todas as suas habilidades serão avaliadas, dentre elas:

- Poder de simplificação
- Autonomia e soluções criativas
- Conhecimento NodeJS e Clean Architecture
- Conhecimento técnico componentização
- Conhecimento em git
- Capacidade em explicar as decisões tomadas e como testar o projeto

### Para Submeter

Você deve:

- Fazer o fork particular e privado do projeto do desafio e compartilhar com:
  - @cloped
  - @romfmoura
- Codificar
- Commitar seu código

### Boa sorte!

No Canal Dstak acreditamos que tudo é possível e queremos contar com pessoas incríveis. Mostre o seu potencial, acreditamos em você. Boa sorte!

![Boa-Sorte](https://media.giphy.com/media/12XDYvMJNcmLgQ/giphy.gif)

## Antes de programar

Você verá que o desafio em questão é bem similar ao que o Canal Dstak se propõe a resolver, para avaliarmos também a sua capacidade de inovar conosco dê uma olhada no nosso app e anote todas as sugestões do que pode ser feito de novo ou até melhor, adicione isso no seu README.

Após você implementar o seu desafio revisite as suas sugestões e veja se há algo a mais que queira adicionar.

## Desafio

Você está em uma startup que acabou de pivotar para criar um marketplace de venda de roupas, será necessário um backoffice para suportar a operação e o atendimento aos compradores e vendedores. Você precisará fazer o mais simples com a melhor qualidade possível!

Sua tarefa é bem simples. Precisa criar um microserviço que faça a validação de um CEP, e retorne seus daddos (endereço) em uma estrutura normalizada. Para essa implementação, você poderá utilizar o express ou a plataforma serverless da AWS (Api gateway + lambda). A infra é de sua escolha, apenas justifique no README e documente os passos para execução de seu microserviço.

### Requisitos

* Básicos
  * A aplicação deverá ser em NodeJS com Typescript
  * Simplificar o que deve ser feito mantendo qualidade
  * Estruture o teste unitátio com o Jest
  * A interface do microserviço deverá ser RESTFULL. Defina a conversação como quiser e documente no README (request e response)
  * Não há necessidade de autenticação para essa rota
  * Utilize conceitos de clean architecture (entrypoint, usecase, connector, entity, etc..)
  * Para consulta do CEP, utilize o VIACEP (https://viacep.com.br/ws/01001000/json/)
  * Regra de negócio: Verifique se o input recebido está no formato correto de um CEP. Se tiver, faça a consulta dos dados no VIACEP e formate a resposta. Trate todos os erros possíveis.
  * Utilize commits atômicos
  * Documente do que você fez e das suas motivações no README. Isso servirá como guia para a entrevista técnica.

* Você se destacará ainda mais se fizer algum desses pontos:
  * Configuração/uso de lint
  * Componentização
  * Utilizar os padrões Clean Code
  * Criação de testes unitário
  * Tratativas de Erro
  * Padrões RESTFULL

### Avaliação

* **50%**: Arquitetura de desenvolvimento
* **30%**: Testes unitários e tratamento de erro
* **20%**: Documentação do README

### Entrevista técnica

Esse desafio será o assunto principal da entrevista técnica. Nessa conversa discutiremos o código, a arquitetura implementada fazendo um paralelo à nossa realidade. Faremos também um bate papo sobre suas decisões tomadas para essa implementação.

# Canal Dstak Desafio NodeJS (Backend)

## Instruções

Você possui *uma semana* para fazer o teste. Nesse teste todas as suas habilidades serão avaliadas, dentre elas:

- Poder de simplificação
- Autonomia e soluções criativas
- Conhecimento NodeJS e Clean Architecture
- Conhecimento técnico componentização
- Conhecimento em git
- Capacidade em explicar as decisões tomadas e como testar o projeto

### Para Submeter

Você deve:

- Fazer o fork particular e privado do projeto do desafio e compartilhar com:
  - @cloped
  - @romfmoura
- Codificar
- Commitar seu código

### Boa sorte!

No Canal Dstak acreditamos que tudo é possível e queremos contar com pessoas incríveis. Mostre o seu potencial, acreditamos em você. Boa sorte!

![Boa-Sorte](https://media.giphy.com/media/12XDYvMJNcmLgQ/giphy.gif)

## Antes de programar

Você verá que o desafio em questão é bem similar ao que o Canal Dstak se propõe a resolver, para avaliarmos também a sua capacidade de inovar conosco dê uma olhada no nosso app e anote todas as sugestões do que pode ser feito de novo ou até melhor, adicione isso no seu README.

Após você implementar o seu desafio revisite as suas sugestões e veja se há algo a mais que queira adicionar.

## Desafio

Você está em uma startup que acabou de pivotar para criar um marketplace de venda de roupas, será necessário um backoffice para suportar a operação e o atendimento aos compradores e vendedores. Você precisará fazer o mais simples com a melhor qualidade possível!

Sua tarefa é bem simples. Precisa criar um microserviço que faça a validação de um CEP, e retorne seus daddos (endereço) em uma estrutura normalizada. Para essa implementação, você poderá utilizar o express ou a plataforma serverless da AWS (Api gateway + lambda). A infra é de sua escolha, apenas justifique no README e documente os passos para execução de seu microserviço.

### Requisitos

* Básicos
  * A aplicação deverá ser em NodeJS com Typescript
  * Simplificar o que deve ser feito mantendo qualidade
  * Estruture o teste unitátio com o Jest
  * A interface do microserviço deverá ser RESTFULL. Defina a conversação como quiser e documente no README (request e response)
  * Não há necessidade de autenticação para essa rota
  * Utilize conceitos de clean architecture (entrypoint, usecase, connector, entity, etc..)
  * Para consulta do CEP, utilize o VIACEP (https://viacep.com.br/ws/01001000/json/)
  * Regra de negócio: Verifique se o input recebido está no formato correto de um CEP. Se tiver, faça a consulta dos dados no VIACEP e formate a resposta. Trate todos os erros possíveis.
  * Utilize commits atômicos
  * Documente do que você fez e das suas motivações no README. Isso servirá como guia para a entrevista técnica.

* Você se destacará ainda mais se fizer algum desses pontos:
  * Configuração/uso de lint
  * Componentização
  * Utilizar os padrões Clean Code
  * Criação de testes unitário
  * Tratativas de Erro
  * Padrões RESTFULL

### Avaliação

* **50%**: Arquitetura de desenvolvimento
* **30%**: Testes unitários e tratamento de erro
* **20%**: Documentação do README

### Entrevista técnica

Esse desafio será o assunto principal da entrevista técnica. Nessa conversa discutiremos o código, a arquitetura implementada fazendo um paralelo à nossa realidade. Faremos também um bate papo sobre suas decisões tomadas para essa implementação.

# Canal Dstak Desafio NodeJS (Backend)

## Instruções

Você possui *uma semana* para fazer o teste. Nesse teste todas as suas habilidades serão avaliadas, dentre elas:

- Poder de simplificação
- Autonomia e soluções criativas
- Conhecimento NodeJS e Clean Architecture
- Conhecimento técnico componentização
- Conhecimento em git
- Capacidade em explicar as decisões tomadas e como testar o projeto

### Para Submeter

Você deve:

- Fazer o fork particular e privado do projeto do desafio e compartilhar com:
  - @cloped
  - @romfmoura
- Codificar
- Commitar seu código

### Boa sorte!

No Canal Dstak acreditamos que tudo é possível e queremos contar com pessoas incríveis. Mostre o seu potencial, acreditamos em você. Boa sorte!

![Boa-Sorte](https://media.giphy.com/media/12XDYvMJNcmLgQ/giphy.gif)

## Antes de programar

Você verá que o desafio em questão é bem similar ao que o Canal Dstak se propõe a resolver, para avaliarmos também a sua capacidade de inovar conosco dê uma olhada no nosso app e anote todas as sugestões do que pode ser feito de novo ou até melhor, adicione isso no seu README.

Após você implementar o seu desafio revisite as suas sugestões e veja se há algo a mais que queira adicionar.

## Desafio

Você está em uma startup que acabou de pivotar para criar um marketplace de venda de roupas, será necessário um backoffice para suportar a operação e o atendimento aos compradores e vendedores. Você precisará fazer o mais simples com a melhor qualidade possível!

Sua tarefa é bem simples. Precisa criar um microserviço que faça a validação de um CEP, e retorne seus daddos (endereço) em uma estrutura normalizada. Para essa implementação, você poderá utilizar o express ou a plataforma serverless da AWS (Api gateway + lambda). A infra é de sua escolha, apenas justifique no README e documente os passos para execução de seu microserviço.

### Requisitos

* Básicos
  * A aplicação deverá ser em NodeJS com Typescript
  * Simplificar o que deve ser feito mantendo qualidade
  * Estruture o teste unitátio com o Jest
  * A interface do microserviço deverá ser RESTFULL. Defina a conversação como quiser e documente no README (request e response)
  * Não há necessidade de autenticação para essa rota
  * Utilize conceitos de clean architecture (entrypoint, usecase, connector, entity, etc..)
  * Para consulta do CEP, utilize o VIACEP (https://viacep.com.br/ws/01001000/json/)
  * Regra de negócio: Verifique se o input recebido está no formato correto de um CEP. Se tiver, faça a consulta dos dados no VIACEP e formate a resposta. Trate todos os erros possíveis.
  * Utilize commits atômicos
  * Documente do que você fez e das suas motivações no README. Isso servirá como guia para a entrevista técnica.

* Você se destacará ainda mais se fizer algum desses pontos:
  * Configuração/uso de lint
  * Componentização
  * Utilizar os padrões Clean Code
  * Criação de testes unitário
  * Tratativas de Erro
  * Padrões RESTFULL

### Avaliação

* **50%**: Arquitetura de desenvolvimento
* **30%**: Testes unitários e tratamento de erro
* **20%**: Documentação do README

### Entrevista técnica

Esse desafio será o assunto principal da entrevista técnica. Nessa conversa discutiremos o código, a arquitetura implementada fazendo um paralelo à nossa realidade. Faremos também um bate papo sobre suas decisões tomadas para essa implementação.


