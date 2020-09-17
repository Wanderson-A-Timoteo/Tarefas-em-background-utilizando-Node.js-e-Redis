# Tarefas em background utilizando Node.js e Redis

Projeto de “Cadastro de usuário e envio de e-mail de confirmação de cadastro como tarefa em background utilizando Node.js”.
Nesse projeto foi aplicado os conceitos de processamento assíncrono de tarefas utilizando Node.js e Redis.


## 🚀 Recursos Utilizados

* **[Visual Studio Code](https://code.visualstudio.com/?WT.mc_id=vuechatapp_swa-github-gllemos)**
* **[Node.Js](https://nodejs.org/en/)**
* **[Express](http://expressjs.com/pt-br/
)**
* **[Redis](https://redis.io/
)**
* **[BULL](https://github.com/OptimalBits/bull
)**
* **[Mailtrap.io](https://mailtrap.io/)**




## 🔥 Executando Localmente a Aplicação 

Caso você deseja executar o projeto na sua máquina local, basta seguir os passos abaixo:

### 🌀 Começando... 

Para começar, você deve simplesmente clonar o repositório do projeto na sua máquina e instalar as dependências.

#### ❗️ Instalando as Dependências (via Windows): 

Abre o cmd (caso esteja utilizando o Windows) navegue até o local onde você clonou o projeto

```
cd "C:\Users\NomeDoComputador\Documents\cloneprojeto"
```

Depois, quando estiver na pasta do projeto, basta digitar no cmd a seguinte instrução: **(dentro da pasta do projeto clonado)**

```
npm install
```

Ao digitar a instrução acima, automaticamente ele irá baixar todas as dependências listadas e definidas no arquivo package.json:

* `node_modules` - que contêm os packages do npm que precisará para o projeto.

#### 💨 Executando a Aplicação 

Bom, agora na mesma tela do cmd, basta iniciar o server para o projeto ser executado localmente.

```
> npm start
```
Abre um segundo terminal e execute:

```
> npm queue
```


### Dependencias
Não será necessário instalar essas dependências caso você tenha efetuado o clone e as etapas descrito acima. 
```
yarn init -y
yarn add express nodemailer dotenv
yarn add nodemon sucrase -D
yarn add password-generator
yarn add bull
yarn add bull-board
docker run --name redis -p 6379:6379 -d -t redis:alpine

```


## 🚩 Tenho Dúvidas... O que fazer? 

Caso tenham dúvidas sobre o código do projeto, sintam-se a vontade em abrir uma **[ISSUE AQUI](https://github.com/Wanderson-A-Timoteo/Tarefas-em-background-utilizando-Node.js-e-Redis/issues)**. Assim que possível, estarei respondendo as todas as dúvidas que tiverem!

## Autor:

* **Wanderson A. Timóteo** - [wanderson.ga](https://wanderson.ga)


## Licença

* Licenciado sob a licença MIT - veja [LICENSE](LICENSE) para mais informações.

## Agradecimentos

![Preview](https://github.com/Wanderson-A-Timoteo/Tarefas-em-background-utilizando-Node.js-e-Redis/blob/master/cover_dio.jpg?raw=true)

* Projeto construído durante as aulas do BootCamp Node.js Web Developer da [Digital Innovation One](https://web.digitalinnovation.one/), em Setembro de 2020. 

* Agradecimento ao instrutor [Roberto Alves](https://github.com/robertosousa1) por compartilhar seu conhecimento e nos ensinar.