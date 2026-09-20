# Registro de Resolução de Conflito no Git

Este documento registra a simulação de um conflito de *merge* gerado propositalmente durante o desenvolvimento do projeto **HTML e CSS para Iniciantes**, detalhando a causa, o estado do código conflitante e como ele foi resolvido.

---

## 1. Causa do Conflito

O conflito ocorreu porque a **mesma linha de código** no arquivo `README.md` foi alterada de maneiras diferentes em duas *branches* separadas antes de serem unificadas:

* **Branch `master`:** Alterou o título da página para dar foco em HTML.
* **Branch `feature/conflitos`:** Alterou o mesmo título da página para dar foco em CSS.

Ao tentar fazer o *merge* da branch `master` estando na branch `feature/conflitos`, o Git não soube qual das duas versões manter e interrompeu o processo.

---

## 2. O Conflito Gerado (Visão do Código)

Ao rodar o comando `git merge feature/conflitos`, o Git inseriu automaticamente as marcações de conflito no arquivo `README.md`
