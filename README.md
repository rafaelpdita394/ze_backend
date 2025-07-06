# Rafael PDITA394

# Zé Delivery Backend Challenge

Este é um projeto simples em PHP + MySQL para atender ao desafio técnico de backend do Zé Delivery.

## Funcionalidades

- Cadastro de parceiro com GeoJSON (área de cobertura e endereço)
- Busca por ID do parceiro
- Busca do parceiro mais próximo de um ponto

## Como rodar localmente

### Pré-requisitos:
- XAMPP ou WAMP instalado (PHP + MySQL)
- Postman ou Insomnia para testar

### Passos:

1. Clone este repositório em `htdocs` ou equivalente.
2. Crie o banco de dados executando o arquivo `sql/schema.sql` no phpMyAdmin.
3. Inicie o Apache e MySQL no XAMPP.
4. Acesse `http://localhost/ze_delivery_backend`.

## Endpoints

- `POST /partner` - Cadastrar parceiro
- `GET /partner/{id}` - Buscar parceiro por ID
- `GET /partner/search?lat={LAT}&lon={LON}` - Buscar parceiro mais próximo

## Autor
Desenvolvido como parte do desafio técnico para Zé Delivery.
