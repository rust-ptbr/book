<div align="center">

# 📖 The Book — A Linguagem de Programação Rust

**Tradução colaborativa do livro oficial do Rust para o português brasileiro.**

[![Status](https://img.shields.io/badge/status-em%20andamento-yellow?style=flat-square)](https://github.com/rust-ptbr/book/issues)
[![Licença](https://img.shields.io/badge/licença-MIT%20%2F%20Apache--2.0-blue?style=flat-square)](./LICENSE)
[![Contribuições abertas](https://img.shields.io/badge/contribuições-abertas-brightgreen?style=flat-square)](./CONTRIBUTING.md)

Parte da iniciativa [**rust-ptbr**](https://github.com/rust-ptbr) — traduções da documentação oficial do Rust com compromisso de longo prazo.

</div>

---

## Sobre este repositório

Este repositório contém a tradução para o português brasileiro do livro [*The Rust Programming Language*](https://github.com/rust-lang/book), a referência oficial da linguagem, mantida pela `rust-lang`.

A tradução vive em `src-ptbr/` e segue a estrutura do original. O objetivo é que qualquer pessoa que leia em português tenha a mesma experiência de qualidade de quem lê em inglês — sem atraso, sem inconsistência de termos, e sem depender de uma única pessoa para continuar existindo.

> **Este projeto está nos estágios iniciais.** A tradução ainda não começou e estamos construindo a infraestrutura e as convenções antes de abrir para contribuições em larga escala. Acompanhe as [issues abertas](https://github.com/rust-ptbr/book/issues) para ver como entrar.

---

## Como funciona este projeto

### Rastreamento automático de desatualização

Um CI roda diariamente comparando os arquivos de `src-ptbr/` com o repositório original da `rust-lang`. Se um capítulo for modificado no inglês, **uma issue é aberta automaticamente** com o diff detalhado e marcada como `desatualizado`. Nenhuma mudança no upstream passa despercebida.

### Governança com rotação de mantenedores

| Papel | Responsabilidade |
|---|---|
| **Mantenedor** | Revisa PRs, mantém o glossário, garante qualidade e consistência |
| **Revisor** | Revisa PRs de tradução sem acesso de escrita |
| **Contribuidor** | Qualquer pessoa com um PR aceito |

Mantenedores que ficarem **mais de 3 meses sem atividade** são movidos para Alumni e o papel é aberto para novos voluntários. Isso garante que o projeto não dependa de uma única pessoa.

> O documento de governança completo (`GOVERNANCE.md`) está sendo redigido e será publicado em breve.

### Glossário unificado e obrigatório

*Ownership* não pode virar "propriedade" em um capítulo e "posse" em outro. Aqui existe um **glossário oficial** que todos os PRs devem seguir. Divergências são discutidas em issues abertas e decididas coletivamente antes de virarem norma.

> O glossário (`GLOSSARY.md`) ainda está sendo construído. Quer ajudar a defini-lo? [Abra uma issue](https://github.com/rust-ptbr/book/issues/new).

---

## Como contribuir

Você não precisa ser expert em Rust para ajudar. Este é o melhor momento para entrar — as bases do projeto ainda estão sendo construídas.

**O que precisa ser feito agora:**

- Definir e revisar o glossário de termos técnicos
- Redigir o `GOVERNANCE.md` com as regras do projeto
- Redigir o `CONTRIBUTING.md` com o guia para novos contribuidores
- Começar a tradução dos primeiros capítulos em `src-ptbr/`

Acompanhe as [issues abertas](https://github.com/rust-ptbr/book/issues) para ver o que está pendente ou abra uma nova com sua sugestão.

---

## Construindo o livro localmente

O livro usa [mdBook](https://github.com/rust-lang/mdBook). Para instalar:

```bash
cargo install mdbook --locked
```

Para gerar e visualizar:

```bash
mdbook build
mdbook serve --open
```

O resultado estará disponível em `http://localhost:3000`.

---

## Estrutura do repositório

```
.
├── src/           # Fonte original em inglês (referência, não edite)
├── src-ptbr/      # Tradução em português brasileiro (em construção)
├── GLOSSARY.md    # Glossário oficial de termos técnicos (em breve)
├── GOVERNANCE.md  # Regras de governança e papéis (em breve)
└── CONTRIBUTING.md
```

---

## Licença

O código-fonte dos exemplos é distribuído sob as licenças [MIT](./LICENSE-MIT) e [Apache 2.0](./LICENSE-APACHE), seguindo a mesma política do [rust-lang.org](https://rust-lang.org/).

O texto do livro segue a licença [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

---

<p align="center">
  Feito com 🦀 pela comunidade brasileira de Rust
  <br>
  <a href="https://github.com/rust-ptbr">rust-ptbr</a> ·
  <a href="./GOVERNANCE.md">Governança</a> ·
  <a href="./GLOSSARY.md">Glossário</a> ·
  <a href="./CONTRIBUTING.md">Como contribuir</a>
</p>
