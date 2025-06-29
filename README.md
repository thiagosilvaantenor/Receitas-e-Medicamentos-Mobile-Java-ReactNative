# CRUD Mobile Receitas e Medicamentos
`CRUD em React Native, que consome uma API REST em Java Spring com MySQL, proposta de exercício da disciplina de laboratório de banco de dados`

# Tecnologias
frontend
- React Native
- Expo
- TypeScript
- Node (para gerenciar dependências)
Backend
- Maven
- Java
- Spring
- Flyway

Banco de dados
- MySQL

# Configurações
- Necessario ter instalado o Node Js e o Maven
- em \backend\src\main\resources\application.properties alterar os valores informados no arquivo
- em \frontend\src\service, nos dois arquivos, alterar o valor de API_BASE_URL para o ipv4 da maquina rodando a API (Caso esteja usando um dispositivo real com o Expo Go instalado), caso esteja usando emulador android, descomente a linha `const API_BASE_URL = 'http://10.0.2.2:8080'`, lembrando de trocar o 8080 pelo valor da porta que esta rodando a API  

# Como rodar
- App (frontend)
	- Acesse o diretório frontend
	- Use o comando do nodeJS `npm install` para instalar as dependências
	- usar o comando `npx expo start` para rodar o expo, vai ser gerado um QR Code, você deve instalar em seu celular o aplicativo "Expo Go" e ao entrar nele, apontar a camera para o QR CODE
	- Caso esteja usando emulador, com o emulador aberto, após usar o mesmo comando acima, use a tecla 'A', ele vai instalar o Expo Go e o projeto no emulador

- API (Backend)
   - Acesse o diretório backend\src\main\java\com\hospital\receitas
   - usar o comando do maven "maven install" para instalar dependências
   - usar o comando "manven Spring start" para iniciar o projeto
