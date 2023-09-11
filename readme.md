# Documentação da API

* Escolher um local do computador para criar o projeto
* Abrir o gitbash nesta pasta

Com o gitbash aberto executar o comando para criar a raiz do projeto:(mkdir: criar pasta)
```
mkdir NOME_PROJETO
```
Acessar pasta
```
cd NOME_PROJETO
```
Comando para abrir o Vscode
```
code .
```
Criar o arquivo gerenciador de pacotes node

```
npm init -y
```
Criar arquivo .gitignore na raiz do projeto, no Vscode
```
touch .gitignore
```
Criar arquivo .env: Arquivo para reservar variaveis do projeto
```
touch .env
```
# # Instalar os pacotes do projeto

Instalar pacotes para o projeto 

```
npm i express nodemon dotenv
```
* express: será o servidor da api
* nodemon: atualizar os arquivos alterados sem parar o servidor 
* detenv: gerenciador de variáveis de ambiente

Criar pasta src
```
mkdir src
```
Criar arquivo server.js dentro da pasta src
```
touch src/server.js
```
Adicionar arquivos e pastas no .gitignore
```
node_modules
.env
```
