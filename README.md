# WebApplicationTP2

# Teste de Performance 2 - Páginas Razor

Este é um projeto de teste de performance (TP) para praticar os conhecimentos adquiridos sobre o framework .NET e a criação de páginas Razor.

## Sobre o projeto

O projeto é uma aplicação web básica que emprega o ASP.NET Core e as páginas Razor para apresentar dados relacionados a indivíduos.

## Perguntas e respostas

- O que são as páginas Razor do ASP.NET Core e como funciona a sua estrutura?
- Os outros questionamentos referentes so TP estão respondidos no código apresentado

### O que são as páginas Razor do ASP.NET Core e como funciona a sua estrutura?

As páginas Razor do ASP.NET Core oferecem uma abordagem para desenvolver páginas web dinâmicas que integram código C# e HTML. Identificadas pela extensão .cshtml, essas páginas podem incluir elementos como tags HTML, expressões C#, diretivas Razor e componentes, entre outros recursos. Todo o processamento das páginas Razor ocorre no servidor, resultando na geração do HTML que é então enviado para o navegador.

A estrutura de uma página Razor consiste em duas partes principais: o modelo de página e a própria página Razor. O modelo de página é uma classe C# que herda de PageModel e encapsula a lógica e os dados pertinentes à página. Por outro lado, a página Razor é um arquivo .cshtml que combina o código HTML e C# para definir a apresentação visual da página. Para conectar a página Razor ao seu modelo correspondente, utiliza-se a diretiva @model.
