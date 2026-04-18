# 📚 Aula de Git - Guia Prático

Este repositório foi criado com o objetivo de servir como material de apoio para estudos e prática de **Git**, abordando desde conceitos básicos até fluxos mais utilizados no dia a dia de desenvolvimento.

---

## 🚀 Objetivo

Ensinar e consolidar os principais conceitos do Git, incluindo:

* Controle de versão
* Versionamento local e remoto
* Boas práticas de commit
* Resolução de conflitos
* Fluxo de trabalho profissional

---

## 🛠️ Tecnologias Utilizadas

* Git
* Git Bash / Terminal
* GitHub

---

## 📖 Conteúdos Abordados

### 🔹 Conceitos Básicos

* O que é Git
* Diferença entre Git e GitHub
* Inicialização de repositório (`git init`)
* Clonagem de repositórios (`git clone`)

### 🔹 Versionamento

* Adicionar arquivos (`git add`)
* Criar commits (`git commit`)
* Histórico (`git log`)

### 🔹 Trabalhando com Branches

* Criar branch (`git branch`)
* Trocar de branch (`git checkout`)
* Merge (`git merge`)

### 🔹 Repositório Remoto

* Conectar ao GitHub (`git remote`)
* Enviar alterações (`git push`)
* Atualizar projeto (`git pull`)

### 🔹 Correções e Boas Práticas

* Alterar último commit (`git commit --amend`)
* Resolver conflitos
* Uso de `.gitignore`
* Rebase (`git pull --rebase`)

---

## ⚠️ Problemas Comuns e Soluções

### ❌ Erro ao fazer push:

```bash
rejected - fetch first
```

### ✔️ Solução:

```bash
git pull origin main --rebase
git push origin main
```

---

## 💡 Boas Práticas

* Sempre fazer `git pull` antes de `git push`
* Escrever mensagens de commit claras
* Evitar subir arquivos desnecessários (usar `.gitignore`)
* Manter o histórico limpo e organizado

---

## 📌 Autor

Desenvolvido para fins de estudo e aprendizado de Git.

---

## 🧠 Conclusão

Dominar Git é essencial para qualquer desenvolvedor. Este repositório é um passo importante para construir uma base sólida e evoluir para fluxos mais avançados utilizados no mercado.

---
