# 🚀 Testes em API GeoGraphQL
Teste de API Graphql do manual a CI/CD

## 🌱 O que é
Este repositório foi criado para demonstrar o processo de automação de testes numa API Graphql utilizando Postman e Newman.
                                                                                                      
## 🌍 Sobre a API Geographql   
A API Geographql oferece acesso a dados geográficos, permitindo consultas e manipulações de informações sobre países, estados e cidades.                                                    
- 🌐 Site da API: [Geographql](https://geographql.netlify.app/docs/intro/)             

## 🛠 Tecnologias Utilizadas
- Node.js: v22.14.0 ([Download](https://nodejs.org/en/download))
- Postman: 11.33.4 ([Download](https://www.postman.com/downloads/))
- Newman: v6.2.1 ([Documentação](https://www.npmjs.com/package/newman))
- Newman-reporter-html: v1.0.5 ([Documentação](https://www.npmjs.com/package/newman-reporter-html))

## 📂 Documentações
- 🔗 Documentação oficial: [Geographql API Docs](https://geographql.netlify.app/)

                                          
## 📌 Como instalar o ambiente
1️⃣ Instalação do Node.js: Certifique-se de ter o Node.js instalado em sua máquina. A versão recomendada é a v22.14.0 ou superior.

2️⃣ Instalação do Postman: O Postman pode ser utilizado tanto na versão web quanto na versão desktop.

3️⃣ Instalação do Newman: O Newman é utilizado para executar os testes via linha de comando. Para instalá-lo, execute o seguinte comando no terminal:
```
npm install -g newman
```

4️⃣ Instalação do Newman-reporter-html: Para gerar relatórios HTML dos testes, instale o Newman-reporter-html:
```
npm install -g newman-reporter-html
```

## 🤖 Como Executar os Testes
### 📫 Postman
- Importe os arquivos Geographql.postman_collection e geographql_test.postman_environment para o Postman.
- Execute os testes manualmente ou configure-os para execução automatizada.

### ☎️ Newman
- Abra o terminal na pasta onde estão os arquivos da coleção e do ambiente.
- Execute o seguinte comando para rodar os testes:                                                          
```                     
newman run Geographql.postman_collection.json -e geographql_test.postman_environment.json -r cli
```
- Para gerar um relatório HTML, execute o seguinte comando:
```
newman run Geographql.postman_collection.json -e geographql_test.postman_environment.json -r cli,htmlextra
```

## 📊 Report
Caso tenha rodado os testes com o report htmlextra, um arquivo HTML foi gerado com o resultado dos testes. Para visualizar, basta abrir a pasta newman que foi criada no diretório onde os arquivos de collection e environment se encontram.

## 🔥 Contribuição
Sinta-se à vontade para contribuir com sugestões e recomendações de aprimoramentos para os testes da API.                                                

## 👥 Integrantes do Projeto

| Nome             | LinkedIn                         | Função         |
|-----------------|--------------------------------|---------------|
| 🚀 Brayan | [LinkedIn](https://www.linkedin.com/in/brayanmoncks/) | QA/Testes     |
| 🛠 Patricia | [LinkedIn](https://www.linkedin.com/in/patricia-rosa-silva/) | QA/Testes   |
| ⏰ Tatiana | [LinkedIn](https://www.linkedin.com/in/tatiana-honda/) | QA/Testes  |
| 🔍 Willams | [LinkedIn](https://www.linkedin.com/in/willamsbarbosa/) | QA/Testes  |

## 🎯 Informações adicionais
- 🦋 Autor: Tatiana Mitiko Honda
- 📅 Última atualização: 20-02-2025
- 👩‍💻 Tech Lead: Priscila Caimi

