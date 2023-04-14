Projeto para desafio técnico da empresa VIVO

###### Pré requisitos:
- Java
- Maven
- Driver (chrome) configurado na pasta do Windows (system32 ou outras globais)

###### Frameworks/Linguagem:
- Selenium
- Junit
- Maven
- Java

###### Desgin Pattern:
- Page Objects

###### BDD:
- Cucumber

###### Example:
    @SpecialOffer
    Funcionalidade: Validar as funcionalidades do menu special offer
	Como cliente do site https://advantageonlineshopping.com/
	Quero acessar o menu Special Offer
	Para validar suas funcionalidades 

    Contexto:
	Dado que estou na page home
	E clico no menu "Special Offer"

    Cenário: [Special Offer] Validar especificações do produto
	Quando clico no botão "See offer"
	Então valido as especificações do produto

###### Como rodar:
- através do terminal: mvn test
- através da IDE:
  tests > clicar com botão direito > run 'Feature: cadastro'