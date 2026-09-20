# Conceitos Fundamentais:HTML e CSS

## Bem-vindo à seção de conceitos! Antes de colocar as mãos no código, é fundamental entender o papel de cada tecnologia na construção da web.
 
# O que é HTML?

## HTML (HyperText Markup Language / Linguagem de Marcação de Hipertexto) é a estrutura base de qualquer página web. Ela não é uma linguagem de programação, mas sim uma linguagem de marcação que utiliza tags para indicar como os elementos devem ser exibidos no navegador.

# Principais Conceitos de HTML:
- ### Tags ```(<tag>)```: Instruções usadas para delimitar o início e o fim de um elemento. Exemplo: ```<p>``` para parágrafos.
- ### Elementos: Conjunto formado pela tag de abertura, conteúdo e tag de fechamento (ex: ```<p>Olá, mundo!</p>```).
- ### Atributos: Informações adicionais passadas para uma tag que alteram seu comportamento ou estilo (ex: src, href, class, id).

# Estrutura Básica:
 
## O esqueleto essencial de um documento HTML5:

``` <!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8">
    <title>Minha Primeira Página</title>
  </head>
  <body>
    <h1>Olá, Mundo!</h1>
  </body>
</html> 
```

# O que é CSS?

## CSS (Cascading Style Sheets / Folhas de Estilo em Cascata) é a tecnologia usada para estilizar e organizar visualmente a estrutura criada pelo HTML. Com o CSS, definimos cores, fontes, espaçamentos, layouts e responsividade.

# Principais Conceitos de CSS:

## Sintaxe de Regras: Uma regra CSS é composta por um seletor e um bloco de declarações:

```
seletor {
  propriedade: valor;
}
```

* ### Seletores: Formas de indicar qual elemento HTML será estilizado.
* ### Tag: Seleciona todos os elementos do tipo (p { ... }).
* ### Classe (.): Seleciona elementos com uma classe específica (.item { ... }).
* ### ID (#): Seleciona um único elemento com ID exclusivo (#menu { ... }).
* ### Box Model (Modelo de Caixa): Todo elemento HTML é visto pelo navegador como uma caixa retangular composta por:

- ### Conteúdo (Content): O texto, imagem ou mídia.
- ### Espaçamento Interno (Padding): Espaço entre o conteúdo e a borda.
- ### Borda (Border): A linha ao redor do padding.
- ### Margem (Margin): Espaço externo que afasta o elemento de outros.

# Como HTML e CSS se Conectam?

## Existem três formas de aplicar CSS ao HTML. A maneira recomendada e mais utilizada no mercado é através do CSS Externo:

* ### CSS Externo (Recomendado): Criamos um arquivo .css separado e o vinculamos dentro da tag ```<head>``` do HTML:

```<link rel="stylesheet" href="estilo.css">```

* ### CSS Interno: Inserido diretamente dentro de uma tag ```<style> na seção <head>``` da página.

* ### CSS Inline: Aplicado diretamente na tag HTML através do atributo style="" (deve ser evitado no dia a dia).

 | Tecnologia | Papel Principal | Analogia |
| :--- | :--- | :--- |
| **HTML** | Estrutura e Conteúdo | O esqueleto e as paredes de uma casa. |
| **CSS** | Estilo e Apresentação | A pintura, móveis e decoração da casa. |

# Pull Request

## O que foi feito
- Definição dos principais conceitos do HTML e estrutura básica

## Como revisar
- Compreender se o conceito se encaixa com o que foi dito no parágrafo anterior

## Checklist
- [✅] Conteúdo revisado
- [✅] Links testados
- [✅] Sem conflito pendente
- [✅] Commits claros
