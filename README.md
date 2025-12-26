# 📋 Formulário de Cadastro com Laravel

Este projeto é uma implementação simples de um **formulário de cadastro de usuários** utilizando o **Laravel**, ideal para **estudo e prática** dos principais conceitos do framework PHP.

---

## 🧪 Funcionalidades do Projeto

* 📄 Tela simples de cadastro de usuário
* ✅ Validações básicas de formulário
* 🧱 Estrutura padrão do Laravel (**MVC**)

---

## 🛠️ Tecnologias Utilizadas

* PHP 8.2+
* Laravel
* Composer
* Node.js
* MySQL (ou outro banco suportado pelo Laravel)

---

## ✅ Requisitos

Certifique-se de ter as seguintes dependências instaladas:

* **PHP 8.2 ou superior**
* **Composer** (gerenciador de dependências do PHP)
* **Node.js 22 ou superior**
* **MySQL** (ou outro banco compatível)

---

## ⚙️ Como Configurar e Executar o Projeto

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/MaduSantoss/formulario-cadastro-laravel
```

### 2️⃣ Acessar a pasta do projeto

```bash
cd formulario-cadastro-laravel
```

### 3️⃣ Copiar e configurar o arquivo `.env`

```bash
cp .env.example .env
```

Edite o arquivo `.env` e configure corretamente o acesso ao banco de dados.

---

### 4️⃣ Instalar as dependências do PHP

```bash
composer install
```

---

### 5️⃣ Gerar a chave da aplicação

```bash
php artisan key:generate
```

---

### 6️⃣ Rodar as migrações do banco de dados (se houver)

```bash
php artisan migrate
```

---

### 7️⃣ Instalar dependências do front-end

```bash
npm install
```

---

### 8️⃣ Rodar o servidor local

```bash
php artisan serve
```

Acesse o projeto no navegador:
👉 **[http://127.0.0.1:8000](http://127.0.0.1:8000)**

---

## 🚀 Criando um Projeto Laravel do Zero (Opcional)

Caso queira replicar o processo desde o início:

```bash
composer create-project laravel/laravel .
php artisan serve
```

---

## 🎯 Objetivo do Projeto

* Praticar o uso do Laravel
* Entender o fluxo MVC
* Trabalhar com formulários e validações
* Consolidar fundamentos do desenvolvimento web com PHP

---

## ⭐ Considerações Finais

Este projeto é ideal para quem está começando com **Laravel** e deseja entender, na prática, como funciona a criação de formulários, validações e estruturação de um projeto real.

---
