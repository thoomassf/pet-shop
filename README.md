## 💻 Sobre o projeto

Pet Shop é uma aplicação completa para gestão de um pet shop, desenvolvida com as tecnologias mais modernas do ecossistema JavaScript.

## ✨ Tecnologias

- Next.js
- Prisma
- Docker
- TypeScript

## Getting Started

Primeiramente, você precisa ter o Node.js, Docker e um gerenciador de pacotes (pnpm, npm ou yarn) instalados em sua máquina.

1. **Clone o repositório**

```bash
git clone <url-do-repositorio>
cd pet-shop
```

2. **Instale as dependências**

```bash
pnpm install
```

3. **Configure as variáveis de ambiente**

Copie o arquivo `.env.example` para um novo arquivo chamado `.env` e preencha as variáveis necessárias.

4. **Inicie o banco de dados com Docker**

```bash
docker-compose up -d
```

5. **Execute as migrations do Prisma**

```bash
pnpm prisma migrate dev
```

6. **Execute o projeto**

```bash
pnpm dev
```
