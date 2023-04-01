## 🌱 Projeto

- Criar uma API CRUD Rest em GO
- Criar 5 endpoints para operações CRUD básicas:
    - Create
    - Read all
    - Read one
    - Update
    - Delete

## ✨ Tecnologias

- Mux (Framework para construir servidores web em Go)
- Postgres (banco de dados relacional)
- Docker (para conteinerização)
- Composição do Docker

## 🚀 Etapas

- [ ] Criar um aplicativo Go usando Mux como uma estrutura
- [ ] Dockerizar o aplicativo Go escrevendo um Dockerfile e um arquivo docker-compose.yml para executar o aplicativo e o banco de dados.
- [ ] Execute o banco de dados Postgres em um contêiner usando o Docker Compose e teste-o com o TablePlus.
- [ ] Crie a imagem do Go App e execute-a em um contêiner usando o Docker Compose e, em seguida, teste-a com o Insomnia.

## 🗒 Requisitos

## Criando o Projeto

- Inicializando um novo módulo Go usando este comando

```bash
go mod init api
```

- Instalando dependências

```bash
go get github.com/gorilla/mux github.com/lib/pq
```

- Criando `Dockerfile`, `docker-compose.yml` e `main.go`

```bash
touch main.go Dockerfile docker-compose.yml
```


## 🚀 Execução

```bash
docker compose up --build
```

## 📝 Testando o aplicativo

## 📄 Licença

## 🙇 Referências