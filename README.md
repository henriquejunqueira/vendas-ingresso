# Repositório do evento Level Up for Juniors da Fullcycle

## Projeto Vendas Ingresso

- O sistema é uma API REST projetada para permitir a criação, gerenciamento e venda de ingressos para eventos por meio de parceiros

### Configuração do projeto

- Criação do arquivo package.json de configuração do node: `$ npm init -y`
- Instalação do typescript como dependência de desenvolvimento: `$ npm install typescript --save-dev`
- Criação do arquivo tsconfig.json de configuração do typescript: `$ npx tsc --init`
- Instalação do express: `$ npm install express`
- Instalação da dependência de tipagens do typescript para o express em modo de desenvolvimento: `$ npm install --save-dev @types/express`
- Instalação do ts-node como dependência de desenvolvimento: `$ npm install ts-node --save-dev`
- Instalação nodemon como dependência de desenvolvimento: `$ npm install nodemon --save-dev`
- Instalação do mysql2: `$ npm install mysql2`
- Instalação do bcrypt: `$ npm install bcrypt`
- Instalação das tipagens do typescript para o bcrypt como dependência de desenvolvimento: `$ npm install --save-dev @types/bcrypt`

### Rodando projeto

- Rodando projeto utilizando nodemon: `$ npx nodemon`

### Arquivo de configuração do container docker:

- Configurado arquivo docker-composer.yaml na raiz do projeto

### Levantando o container docker

- Rodando docker compose: `$ docker compose up`

### Remove o container docker

- Removendo o container: `$ docker compose down`

### Visualizando os containers docker rodando

- Listando container ativos: `$ docker ps`

### Parando o container docker

- Stopando o container pelo id: `$ $ docker stop numero_id_container`
