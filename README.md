Integração do Frontend AngularJS com o Middleware ExpressJS,
exemplo simples da API RESTful integrada com banco de dados mySQL

<img src="exemplo-01.png" alt="Exemplo 01" />
<img src="exemplo-02.png" alt="Exemplo 02" />

1 - Inicia a aplicação Angular
```
cd todo-app
npm install
ng serve
```

2 - Inicia o servidor
```
cd todo-server
npm install
node index.js
```

3 - Criação da tabela com SQL

```sql
CREATE DATABASE TODO_DB;

CREATE TABLE TAREFAS_TB (
    id int primary key auto_increment not null,
    nome varchar(90)
);
```

Instalação dos módulos usados no lado servidor

```
npm install express
npm install mysql
npm install body-parser
npm install cors
```