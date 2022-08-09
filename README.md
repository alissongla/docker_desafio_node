# Desafio Docker
 - Nesse desafio você colocará em prática o que aprendemos em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

---
### Critério de aceite
 - O retorno da aplicação node.js para o nginx deverá ser:
```<h1>Full Cycle Rocks!</h1>```
- Lista de nomes cadastrada no banco de dados.
---

### Para rodar a aplicação utilize o docker-compose.

```
docker-compose up -d 
```

Dentro de alguns instantes a aplicação estará no ar.

---

### Para acessar, digite o seguinte endereço no navegador:

[http://localhost:8080/](http://localhost:8080/)

---
OBS: caso apresente erro 502, aguarde mais alguns segundos e atualize a página.