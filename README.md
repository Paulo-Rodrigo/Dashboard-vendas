# Projeto: Dashboard-vendas :chart:

![Tecnologias](https://uploaddeimagens.com.br/images/002/847/499/original/tecnologias.png?1598366640)

### Objetivos :white_check_mark:

Este projeto tem como objetivo colocar em prática meus conhecimentos de desenvolvimento back-end e Node.js 
na criação de um dashboard em tempo real baseado em operações de CRUD relacionadas a lançamento de vendas.

O usuário terá a possibilidade de registra seus produtos, quais são suas categorias e fornecedores, e em seguida
registrar quais foram as vendas destes produtos, e a cada venda lançada, o dashboard principal será atualizado 
em tempo real conforme cada venda é lançada.

### Tecnologias :computer:

* Javascript ES6
* Node.js
* Express.js
* Socket.io
* MongoDB
* Handlebars
* Arquitetura de API REST e MVC
* HTML
* Materialize CSS
* Chart.js
* Docker
* Docker-compose
* Heroku (Deployment)

### Instalação :floppy_disk:

##### Instalação local

Para instalar o projeto, execute o comando:

`yarn`

**Para rodar localmente, será necessário ter uma instância do MongoDB rodando em seu ambiente na porta 27017.**

### Execução :dvd:

##### Executando local

Para executar o projeto, rode o comando:

`yarn start`

##### Instalação e execução via docker-compose

Para instalar via docker-compose, basta apenas executar o comando:

`docker-compose up -d`

Para parar os containers, apenas execute o comando:

`docker-compose stop`

O projeto estará disponível no endereço: `http://localhost:8080`.

### Demonstração :desktop_computer:

No GIF abaixo, podemos ver a dashboard atualizando conforme são feitas
as vendas. É possível também reiniciar os dados da aplicação clicando no botão `Reiniciar dados`, logo no menu.

As funcionalidades são de visualizar o dashboard, lançar vendas, cadastrar e listar produtos, fornecedores e categorias.

### Imagens do dashboard feito com Materialize CSS e Chart.js :chart:

#### Cards (KPIs) de totais vendas finalizadas, abertas, aprovadas e rejeitadas, e gráfico com análise de vendas mensais

![Dash 1](https://uploaddeimagens.com.br/images/002/847/585/full/dashboard_01.png?1598368140)

#### Análise de vendas mensais por valor total de venda, total de vendas por produtos e fornecedores

![Dash 2](https://uploaddeimagens.com.br/images/002/847/586/original/dashboard_02.png?1598368143)

#### Análise de vendas por aprovações (ABERTA, FECHADA), por situações (APROVADA, REJEITADA e AGUARDANDO_APROVACAO) e vendas por produtos

![Dash 3](https://uploaddeimagens.com.br/images/002/847/587/original/dashboard_03.png?1598368146)

### Autor :nerd_face:

### Paulo Rodrigo
#### Desenvolvedor Full-Stack & Analista de Testes
