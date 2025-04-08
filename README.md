# 🎶 Projeto Tião Carreiro — Fullstack App

Este repositório centraliza o projeto **Tião Carreiro**, desenvolvido como parte de um teste técnico. O desafio foi criar uma aplicação fullstack moderna, com arquitetura separada entre frontend e backend, boas práticas de desenvolvimento e cobertura de testes.

A proposta foi tão interessante que decidi manter o projeto no meu portfólio pessoal!

![2025-04-08_12-40](https://github.com/user-attachments/assets/672f6f3d-be06-42a6-8bb3-8b029ef305ac)

---

## 🧠 Sobre o Projeto

Uma aplicação web desenvolvida que exibe uma lista das músicas mais tocadas da dupla **Tião Carreiro e Pardinho** e permite que usuários sugiram novas músicas através de links válidos do YouTube.

> O backend trata o link, realiza o _scraping_ das informações (título, views e thumbnail) e adiciona ao banco de dados.  
> A aplicação conta com autenticação e sistema administrativo para aprovação, edição e exclusão das sugestões.

---

## 📁 Repositórios

- 🔗 **Frontend (React + Vite)**  
  👉 [viniblack/tiao-carreiro-fe](https://github.com/viniblack/tiao-carreiro-fe)

- 🔗 **Backend (Laravel 11)**  
  👉 [viniblack/tiao-carreiro-be](https://github.com/viniblack/tiao-carreiro-be)

---

## 🚀 Funcionalidades Principais

- Autenticação com controle de acesso (usuário comum e administrador)
- Sugestão de vídeos via link do YouTube
- Scraping automático dos dados do vídeo (título, views, thumbnail)
- Listagem das músicas mais tocadas
- Paginação a partir da 6ª música
- Dashboard administrativo:
  - Aprovar/reprovar sugestões
  - Editar e excluir vídeos
- Interface moderna com Material UI
- Testes automatizados com **Vitest** (frontend) e **PHPUnit** (backend)

...

## 🛠️ Tecnologias Utilizadas

### Frontend

- React + Vite
- Tailwind CSS
- Material UI
- React Router DOM
- Axios
- Vitest

### Backend

- Laravel 11 (PHP 8.2+)
- SQLite
- PHPUnit
- Composer

---

## 🧪 Testes Automatizados

- O frontend conta com testes utilizando **Vitest**
- O backend possui cobertura com **PHPUnit**
- Testes focados em fluxos principais como autenticação, sugestão e administração

---

## 📦 Organização do Código

O projeto foi separado em dois repositórios para refletir uma arquitetura profissional baseada em serviços. Cada parte possui sua própria documentação de setup no respectivo `README.md`.

> A estrutura visa facilitar a escalabilidade, testes e futura containerização.

---

## ⏳ Prazo e Desenvolvimento

Projeto desenvolvido individualmente entre os dias **03/04** e **07/04**.  
Organizei o desenvolvimento em etapas e priorizei entregas completas com testes, do início ao fim.

...

## ⚙️ Como Executar

Cada repositório possui seu próprio guia de execução no `README.md`.  
Acesse:

- [Guia do frontend](https://github.com/viniblack/tiao-carreiro-fe)
- [Guia do backend](https://github.com/viniblack/tiao-carreiro-be)

---

## ✨ Possibilidades Futuras

- Deploy completo da aplicação (frontend e backend)
- Containerização com Docker
- Autenticação via OAuth (ex: Google)
- Histórico de sugestões e aprovações

---

## 📬 Contato

Se quiser saber mais sobre o projeto, fique à vontade para entrar em contato por [LinkedIn](https://linkedin.com/in/viniblack).

_Curtiu o projeto? Estou aberto a feedbacks, contribuições ou novas oportunidades!_

---

_Desenvolvido com 💻 e 🎧 ao som de Tião Carreiro e Pardinho._
