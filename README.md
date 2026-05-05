# Biblioteca-estudo-de-caso-carol
# 📚 Sistema de Biblioteca em C#

Sistema simples de biblioteca desenvolvido em **C#**, com foco no aprendizado de **Programação Orientada a Objetos (POO)**.

---

## 📌 Sobre o projeto

Este projeto simula o funcionamento básico de uma biblioteca, permitindo:

* Cadastro de livros 📖
* Cadastro de alunos 👤
* Empréstimo de livros 📦
* Devolução de livros 🔄
* Visualização dos livros e seus status 📋

O sistema é executado via **console**, sendo ideal para estudos e prática.

---

## 🧠 Conceitos utilizados

* Classes e Objetos
* Construtores
* Métodos
* Listas (`List<T>`)
* Condições (`if/else`)
* Interpolação de strings

---

## 🏗️ Estrutura do projeto

```text
📁 sistema-biblioteca
 ┣ 📄 Program.cs
 ┣ 📄 Livro.cs
 ┣ 📄 Aluno.cs
 ┗ 📄 README.md
```

---

## 📘 Classe Livro

Responsável por representar os livros da biblioteca.

**Atributos:**

* Titulo
* Autor
* AnoPublicacao
* Disponivel

**Métodos:**

* ExibirDetalhes()
* Emprestar()
* Devolver()

---

## 👨‍🎓 Classe Aluno

Representa os alunos cadastrados no sistema.

**Atributos:**

* Nome
* Matricula
* Turma

**Métodos:**

* ExibirDados()

---

## ▶️ Como executar

### ✅ Pré-requisitos

* .NET SDK instalado

### 🚀 Passos

```bash
git clone https://github.com/seu-usuario/sistema-biblioteca.git
cd sistema-biblioteca
dotnet run
```

---

## 💻 Exemplo de saída

```text
O livro "Dom Casmurro" foi emprestado.
O livro "Dom Casmurro" já está emprestado.

LISTA DE LIVROS CADASTRADOS
Título: Sem título
Autor: Desconhecido
Ano de Publicação: 0
Situação: Disponível
-------------------------
Título: Dom Casmurro
Autor: Machado de Assis
Ano de Publicação: 1899
Situação: Emprestado
-------------------------
Título: O Pequeno Príncipe
Autor: Antoine de Saint-Exupéry
Ano de Publicação: 1943
Situação: Disponível
-------------------------

ALUNO RESPONSÁVEL PELO EMPRÉSTIMO
Nome: Aldete Vitoriano
Matrícula: 2026001
Turma: Informática

DEVOLUÇÃO DO LIVRO
O livro "Dom Casmurro" foi devolvido.
```

---

## 📈 Melhorias futuras

* Implementar `get` e `set`
* Relacionar alunos com livros emprestados
* Criar classe Biblioteca
* Adicionar banco de dados
* Criar interface gráfica

---

## 👨‍💻 Autor

Aldete Vitoriano

---

## 📄 Licença

Projeto para fins educacionais.
