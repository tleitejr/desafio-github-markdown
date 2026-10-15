# 🚀 Desafio Git & GitHub - Explorando Colaboração e Markdown

<div align="center">

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

**Repositório criado para praticar Git, GitHub, colaboração e Markdown.**

[![Fork](https://img.shields.io/badge/fork%20de-alinealien-6f42c1?style=for-the-badge&logo=github)](https://github.com/alinealien)

</div>

---

## 🍴 Origem do Projeto

Este repositório é um **fork** do projeto original de **[Aline Aline (@alinealien)](https://github.com/alinealien)**, criado como parte do **Desafio de Projeto** da trilha de Git & GitHub.

> 🔗 **Repositório original:** [alinealien/desafio-github-markdown](https://github.com/alinealien/desafio-github-markdown)

A partir do fork, realizei minhas próprias alterações, documentação e experimentos para praticar o fluxo de colaboração do GitHub.

---

## 📖 Sobre o Projeto

Este repositório faz parte do **Desafio de Projeto** da trilha de Git & GitHub. O objetivo é aplicar na prática os conhecimentos sobre:

- Versionamento com **Git**
- Colaboração com **GitHub**
- Formatação com **Markdown**
- Fluxo de trabalho com **branches**, **issues** e **pull requests**
- Fluxo de **fork** e contribuição em projetos de terceiros

> 💡 **Objetivo principal:** simular um fluxo real de desenvolvimento colaborativo, partindo de um fork de um projeto existente.

---

## 🎯 Objetivos do Desafio

- [x] Criar conta no GitHub
- [x] Fazer fork do repositório original da [@alinealien](https://github.com/alinealien)
- [x] Criar repositório público `desafio-github-markdown`
- [x] Adicionar `README.md` ao repositório
- [x] Editar o projeto pelo **GitHub.dev**
- [x] Clonar o repositório localmente
- [x] Realizar alterações, commits, issues e pull requests
- [x] Formatar o `README.md` com Markdown
- [x] Criar branches e realizar merge

---

## 🗂️ Estrutura do Repositório

```text
desafio-github-markdown/
└── README.md
```

---

## 🛠️ Tecnologias e Ferramentas

| Ferramenta   | Descrição                            |
|--------------|--------------------------------------|
| Git          | Sistema de controle de versão        |
| GitHub       | Plataforma de hospedagem de código   |
| Markdown     | Linguagem de formatação de texto     |
| GitHub.dev   | Editor web integrado ao GitHub       |

---

## 🚦 Como Executar o Projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/tleitejr/desafio-github-markdown.git
cd desafio-github-markdown
```

### 2. Criar uma branch para suas alterações

```bash
git checkout -b minha-feature
```

### 3. Fazer alterações e commitar

```bash
git add .
git commit -m "feat: adiciona nova funcionalidade"
```

### 4. Enviar para o GitHub

```bash
git push origin minha-feature
```

### 5. Abrir um Pull Request

Acesse o repositório no GitHub e clique em **Compare & pull request**.

---

## 🍴 Fluxo de Fork

```text
alinealien/desafio-github-markdown  (repositório original)
        │
        │  fork
        ▼
tleitejr/desafio-github-markdown  (seu fork)
        │
        │  clone
        ▼
   máquina local
        │
        │  commit + push
        ▼
tleitejr/desafio-github-markdown  (branch nova)
        │
        │  pull request (opcional)
        ▼
alinealien/desafio-github-markdown  (upstream)
```

### Manter o fork atualizado

```bash
# Adicionar o repositório original como upstream
git remote add upstream https://github.com/alinealien/desafio-github-markdown.git

# Buscar atualizações
git fetch upstream

# Fazer merge na sua main
git checkout main
git merge upstream/main

# Enviar para o seu fork
git push origin main
```

---

## 🌿 Fluxo de Trabalho com Git

```text
main
 │
 ├── desafio/github-markdown  → edição do README
 │
 ├── feature/nova-secao       → nova seção
 │
 └── fix/correcao-typo        → correções
```

### Comandos essenciais

```bash
git status              # Verifica o estado do repositório
git log --oneline       # Histórico resumido de commits
git branch              # Lista branches locais
git checkout -b nome    # Cria e troca para nova branch
git merge nome          # Faz merge de uma branch
git pull origin main    # Atualiza a branch local
git remote -v           # Lista os remotes (origin, upstream)
```

---

## 🤝 Colaboração

Este projeto foi desenvolvido em colaboração com:

| Colaborador       | Função                     |
|-------------------|----------------------------|
| [@tleitejr](https://github.com/tleitejr) | Autor do fork / Mantenedor |
| [@alinealien](https://github.com/alinealien)   | Autora do projeto original |

### Como contribuir

1. Faça um **fork** do projeto
2. Crie uma branch: `git checkout -b feature/minha-contribuicao`
3. Commit suas mudanças: `git commit -m "feat: minha contribuição"`
4. Push para a branch: `git push origin feature/minha-contribuicao`
5. Abra um **Pull Request**

---

## 📝 Issues e Pull Requests

- 🐛 **Issues:** utilizadas para reportar bugs, sugerir melhorias ou discutir tarefas.
- 🔀 **Pull Requests:** utilizados para propor alterações no código.

### Exemplo de vinculação

```markdown
Closes #1
```

Ao fazer merge, a issue referenciada é fechada automaticamente.

---

## 📚 Guia Rápido de Markdown

| Elemento        | Sintaxe                          |
|-----------------|----------------------------------|
| Título          | `# H1`, `## H2`, `### H3`        |
| Negrito         | `**texto**`                      |
| Itálico         | `*texto*`                        |
| Link            | `[texto](url)`                   |
| Imagem          | `![alt](url)`                    |
| Código inline   | `` `código` ``                   |
| Bloco de código | ` ```linguagem ... ``` `         |
| Lista           | `- item` ou `1. item`            |
| Checklist       | `- [x] feito` / `- [ ] pendente` |
| Citação         | `> texto`                        |
| Tabela          | `\| col1 \| col2 \|`             |

---

## 🔒 Segurança

- Autenticação em dois fatores (2FA) habilitada
- Uso de chave SSH para conexão segura
- Personal Access Token em vez de senha

---

## 🏆 Conquistas

- [x] Primeiro fork realizado
- [x] Primeiro repositório público criado
- [x] README formatado com Markdown
- [x] Primeiro Pull Request aberto
- [x] Primeiro merge realizado
- [x] Primeira issue fechada

---

## 🔗 Links Úteis

- [Repositório original da @alinealien](https://github.com/alinealien/desafio-github-markdown)
- [Documentação do Git](https://git-scm.com/doc)
- [Documentação do GitHub](https://docs.github.com/)
- [Guia de Markdown](https://www.markdownguide.org/)
- [GitHub.dev](https://github.dev)

---

<div align="center">

### Ao Infinito e Além 🚀

![GIF](https://i.pinimg.com/originals/6b/7e/d3/6b7ed39c3751c92df2d3ece16a329925.gif)

**Feito com 💜 a partir de um fork de [@alinealien](https://github.com/alinealien)**

</div>