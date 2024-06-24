##Documentação: 
### Criar um arquivo .env no diretorio do programa
* Adicionar a variável DATABASE_URL="file:./dev.db" para conexão no banco
* Adicionar a variável jwt_Token_Validation="{Nome_do_token}" para validação do token
### Comandos Para Rodar na máquina Local
* npm install
* npx prisma generate
* npx ts-node-dev ./src/server

### Comandos Para Rodar No Docker
* npm install
* npx prisma generate
* docker-compose up --build
