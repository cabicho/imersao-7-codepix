# Imersão Full Stack && Full Cycle

Participe: https://imersao.fullcycle.com.br

## Microsserviço CodePix

Esse microsserviço tem o objetivo de ser um hub de transações entre os bancos que simularemos durante o projeto.

## Sobre o repositório

Esse repositório contém o código-fonte ministrado na aula Imersão: 01 Full Cycle, estudo de caso e microsserviços https://www.youtube.com/watch?v=3Zzky3X3NH4&t=186s
## Como executar

Utilizamos Docker para que todos os serviços que utilizaremos fiquem disponíveis.

- Faça o clone do projeto
- Tendo o docker instalado em sua máquina apenas execute:
`docker-compose up -d`

### Como executar a aplicação
- Acesse o container da aplicação executando: `docker exec -it codepix_app bash`
- Rode `go run cmd/codepix/main.go`

**Importante:** Esse código está sendo disponibilizado conforme o andamento das aulas, logo, o arquivo para executar o projeto talvez ainda não tenha sido criado.

### Serviços utilizados ao executar o docker-compose

- Aplicação principal
- Postgres
- PgAdmin
- Apache Kafka
- Criador dos tópicos a serem utilizados pelo Kafka
- Confluent control center
- ZooKeeper

 
