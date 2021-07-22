# simple-app-docker-nginx-node-mysql
A simple app with NodeJs, MySQL and NGINX on Docker.

### Description
> The idea is when a user access the NGINX, the same connect with app Node and this step activate the data base and put a new register (put name on people table) in MySQL database. 

__O retorno da aplicação node.js para o nginx deverá ser:__
__Return of the node.js aplication to nginx server shall be:__
```html
<h1>Full Cycle Rocks!</h1>

- Lista de nomes cadastrada no banco de dados.
```

### Requirements
1. Toda a aplicação deve estar disponível na porta 8080.
1. The entire aplication shall be available to port 8080. 
  
### to run:
```
git clone https://github.com/ErikLVicente/simple-app-nginx-node-mysql.git

cd simple-app-nginx-node-mysql

docker-compose up
```
<br/>
<br/>
