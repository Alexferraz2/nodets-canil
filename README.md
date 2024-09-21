# nodets-canil

# Comandos utilizados no inicio do projeto

- clonar o github: https://github.com/Alexferraz2/nodets-canil
- iniciar o projeto criando a pasta package.json: npm init
- Instalar de forma global o nodemom, typescript e ts-node com o seguinte comando: npm install -g nodemom typescript ts-node

- criar o arquivo de configuração do typescript: tsc --init
- Configurar o tsconfig.json com as seguintes linhas:
 - "target": "es2016", 
 - "outDir": "./dist",
 - "rootDir": "./src",                                  
 - "moduleResolution": "node10",

# instalando as dependêcias
- instalar o express: npm install express mustache-express dotenv

# instalando as dependências de desenvolvimento
- instalar os types: npm install --save-dev @types/express @types/mustache-express @types/node
