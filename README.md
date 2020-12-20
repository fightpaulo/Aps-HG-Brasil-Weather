## Qual é a previsão do tempo de sua cidade nos próximos dias?
Site criado em ASP.NET MVC 5 para a disciplina APS (Atividades Práticas Supervisionadas) da faculdade. O intuito da atividade era trabalhar com webservices e apresentar os dados em um site simples.

## O que foi "exercitado" durante a criação desse projeto?
- Javascript
- CSS 3
- Bootstrap
- Generics no C#
- Newtonsoft para serialização e desserialização de objetos JSON
- Uso da classe HttpClient para realização das requisições HTTPs

## APIs usadas
- [IBGE](https://servicodados.ibge.gov.br/api/docs): utilizada para busca dos municípios de um determinado estado
- [HG Weather Brasil](https://hgbrasil.com/status/weather): utilizada para obtenção das previsões do tempo para um determinado município

## Itens que julguei importantes para a construção do site
- Uso do Razor Template Engine que permite a conversão de um arquivo.cshtml para string
- Criação de mais um arquivo de configuração para definição de chave/valor que pode ser usado em todo o projeto

## O que fazer para executar o site
Importante que você tenha o Visual Studio instalado bem como o .NET Framework 4.7.2
Ao realizar o clone ou download do projeto, faça o rebuild da Solution para garantir que as dependências sejam carregadas corretamente.
