# 🚀 Laravel 13 + AI Lab

Projeto experimental criado para explorar as novidades do Laravel 13, com foco em integração com AI (OpenAI/GPT) e arquitetura moderna baseada em Docker.

---

## 🎯 Objetivo

Este projeto tem como finalidade:

- testar recursos do Laravel 13
- validar integração com OpenAI/GPT
- experimentar filas com Redis
- estruturar um ambiente moderno com Docker
- servir como laboratório prático e vitrine técnica

---

## 🧱 Stack

- Laravel 13
- PHP (FPM)
- Nginx
- MySQL
- Redis
- Docker / Docker Compose

---

## 📦 Estrutura do ambiente

Serviços disponíveis:

- `app` → PHP (Laravel)
- `nginx` → servidor web
- `mysql` → banco de dados
- `redis` → cache / filas

---

## ⚙️ Setup do projeto

### 1. Clonar o repositório

```bash
git clone <seu-repo>
cd <seu-repo>
```

---

### 2. Copiar variáveis de ambiente

```bash
cp .env.example .env
```

---

### 3. Subir os containers

```bash
docker compose up -d --build
```

---

### 4. Instalar Laravel (se ainda não estiver criado)

```bash
docker exec -it app bash

composer create-project laravel/laravel .
```

---

### 5. Gerar APP_KEY

```bash
php artisan key:generate
```

---

### 6. Rodar migrations

```bash
php artisan migrate
```

---

## 🌐 Acesso

Aplicação disponível em:

http://localhost:8080

---

## 🧪 Próximos passos

- [ ] Integração com OpenAI
- [ ] Criação de endpoints para AI
- [ ] Uso de filas com Redis
- [ ] Testes de features do Laravel 13
- [ ] Estrutura de services para AI

---

## 📌 Observações

Este projeto é experimental e focado em aprendizado prático, arquitetura e boas práticas modernas de desenvolvimento.

---

## 👨‍💻 Autor

Desenvolvido por Fábio Anunciação de Brito
