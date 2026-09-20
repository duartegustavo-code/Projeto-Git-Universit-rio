Markdown
# Exercício Prático: Seu Primeiro Cartão de Apresentação

Chegou a hora de colocar em prática o que aprendemos sobre HTML, CSS e versionamento com Git! Neste exercício, você vai criar uma página web simples que serve como o seu **Cartão de Visitas Digital**.

---

## Requisitos do Exercício

### 1. Estrutura e Estilo (HTML & CSS)
Crie um arquivo chamado `index.html` e um arquivo `style.css` que contenham:
* Um título principal (`<h1>`) com o seu nome.
* Um parágrafo (`<p>`) com uma breve descrição sobre você ou o seu objetivo na programação.
* Uma lista não ordenada (`<ul>`) contendo 3 tecnologias que você quer aprender.
* Estilização básica via CSS:
  * Altere a cor do fundo da página (`background-color`).
  * Altere a fonte e a cor dos títulos.

---

## Passo a Passo no Git (Fluxo de Trabalho)

Siga estas etapas no terminal para versionar a sua solução:

1. **Crie uma nova branch** para realizar o exercício:
   ```bash
   git switch -c feature/exercicio-cartao

2. **Adicione os arquivos à área de preparação e faça o commit**:

    ''' **git add .**
    **git commit -m "feat: cria pagina de cartao de visita"** '''

3. **Envie a branch para o GitHub** :

    **git push origin feature/exercicio-cartao**
    
    **Abra um Pull Request (PR) na interface do GitHub solicitando a inclusão da sua feature/exercicio-cartao na branch main.**

# Gabarito de Apoio

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Meu Cartão de Visitas</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Olá, eu sou [Seu Nome]</h1>
    <p>Estudante de desenvolvimento web dando os primeiros passos no front-end!</p>
    
    <h2>Tecnologias que quero aprender:</h2>
    <ul>
        <li>HTML5</li>
        <li>CSS3</li>
        <li>Git & GitHub</li>
    </ul>
</body>
</html>