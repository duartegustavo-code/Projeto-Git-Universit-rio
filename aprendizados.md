# Meus Aprendizados no Projeto

Este documento reúne uma síntese de todo o conhecimento adquirido durante a construção desta documentação e a realização dos exercícios práticos. Serve como um guia de referência rápida e registro de evolução no desenvolvimento web e controle de versão.

---

## 1. Estruturação e Estilização Web

### HTML5 (A Estrutura)
* **Semântica:** O uso de tags adequadas (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`) melhora a acessibilidade e o SEO da página.
* **Organização de Informações:**
  * Listas não ordenadas (`<ul>`) são ideais para itens sem hierarquia (ex: ingredientes, tecnologias).
  * Listas ordenadas (`<ol>`) funcionam melhor para sequências e passos a passo (ex: modo de preparo, tutoriais).
* **Vínculos:** A tag `<link>` no `<head>` é fundamental para conectar o arquivo `.html` ao arquivo `.css` externo.

### CSS3 (O Estilo)
* **Centralização de Conteúdo:** O uso de `margin: 0 auto;` combinado com `max-width` no container principal ajuda a manter o layout legível em telas maiores.
* **Separacao de Responsabilidades:** Manter as regras visuais no arquivo `style.css` deixa o HTML limpo e focado apenas no significado do conteúdo.

---

## 2. Git & GitHub (Fluxo de Trabalho)

### Comandos Essenciais

| Comando | Para que serve |
| :--- | :--- |
| `git switch -c <nome-da-branch>` | Cria e muda imediatamente para a nova branch. |
| `git status` | Verifica o estado atual dos arquivos (modificados, em staging ou novos). |
| `git add .` | Prepara todas as alterações para o commit. |
| `git commit -m "mensagem"` | Registra o histórico de alterações com uma descrição do que foi feito. |
| `git push origin <branch>` | Envia as alterações da branch local para o repositório no GitHub. |

### Destaque: Resolução de Conflitos
* Conflitos acontecem quando a **mesma linha** do mesmo arquivo é alterada de formas diferentes em *branches* distintas.
* O Git marca a região do conflito usando os sinalizadores:
  * `<<<<<<< HEAD` (código da sua branch atual)
  * `=======` (divisor)
  * `>>>>>>> <nome-da-branch>` (código que você está tentando mesclar)
* **Como resolver:** A edição deve ser feita manualmente, removendo as marcações do Git e definindo qual versão do código prevalece (ou combinando ambas), seguido de um novo `git add` e `git commit`.

## 3. Documentação em Markdown

* A utilização de tabelas, blocos de código formatados com sintaxe destacada e a tag `<details>` torna a documentação técnica visualmente limpa e interativa.
* Manter um histórico de aprendizados no próprio repositório reforça o processo de estudos e facilita a consulta futura.