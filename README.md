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
    @Test
    Funcionalidade: Validar as funcionalidades do site https://advantageonlineshopping.com/
	Como cliente do site
	Quero acessar o menu Special Offer
	Para validar suas funcionalidades 

    Contexto:
	Dado que estou na page home

    Cenário: [Special Offer] Validar especificações do produto
    E clico no menu "Special Offer"
	Quando clico no botão "See offer"
	Então valido as especificações do produto

