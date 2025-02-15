# Utilização de Server-Sent Events (SSE)

- Projeto desenvolvido para demonstrar a utilização de Server-Sent Events (SSE) com NestJS para construção de aplicações em tempo real.
- Este exemplo utiliza o NestJS para subir a aplicação e gerenciar os módulos, que por sua vez preparam os eventos SSE para atualização contínua dos dados.

## Tecnologias
- NestJS
- TypeScript
- Express
- Prisma ORM
- MySQL
- Redis
- Docker
- Bull


## Comandos
```bash
# Instalar dependências
$ yarn install

# Criar as tabelas no banco de dados
$ npx prisma migrate dev

# Iniciar a aplicação
$ yarn dev
