## 💻 Sobre o # Projeto XYZ

Este é o projeto XYZ, uma aplicação Java usando o Spring Boot.

## Pré-requisitos

Antes de executar a aplicação, verifique se você tem o seguinte instalado em sua máquina:

- Java Development Kit (JDK) 11 ou superior
- Docker

## Configuração do Banco de Dados

1. Execute o seguinte comando para criar e executar um contêiner MySQL:

```bash
docker run -d \
  --name mysql-container \
  -p 3306:3306 \
  -e MYSQL_DATABASE=vollmed \
  -e MYSQL_ROOT_PASSWORD=root \
  -v mysql-data:/var/lib/mysql \
  mysql:8.0
