# Meu servidor de phpMyAdmin + MySQL

Para rodar os container de PHPMyAdmin e MySQL você precisa:

- Conexão com internet para baixar as imagens.
- Ter o Docker e Docker Compose instalado.
- Crie o arquivo `.env` usando de base o arquivo `.env.example` e preencha os dados.

Depois, vá na pasta principal do projeto e rode o comando

```bash
docker compose up -d
```

> OBS: A tag `-d` é para rodar em deamon, sem aparecer os logs no terminal.

Agora para acessar o PHPMyAdmin acesse: [localhost:8081](). Para o primeiro acesso, use o root e altere as permissões do seu usuário.

Para o mysql, as credenciais dele são:

```
host: localhost ou 127.0.0.1
port: 3306
drive: mysql
user: # defina no arquivo .env
pass: # defina no arquivo .env
```
