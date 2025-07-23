# Basket Service 🛒

Este projeto é um microserviço desenvolvido em Java com Spring Boot, responsável pela gestão de carrinhos de compras em uma aplicação de e-commerce. Ele permite adicionar produtos, atualizar quantidades, simular pagamentos e gerenciar o status dos pedidos. Os dados são persistidos com MongoDB e o cache é otimizado com Redis. Além disso, o serviço consome dados de produtos de uma API externa via OpenFeign.

## 🛠 Tecnologias utilizadas
- Java 21
- Spring Boot
- Spring Data MongoDB
- Spring Web
- OpenFeign (integração com API externa de produtos)
- Redis (cache)
- Maven

## 🔧 Funcionalidades
- CRUD de carrinhos de compras
- Integração com API de catálogo de produtos
- Suporte a múltiplos métodos de pagamento
- Cache de produtos com Redis
- Validações e tratamento de exceções com ControllerAdvice

## 🚀 Como executar
Projeto padrão Spring Boot. Basta rodar `BasketserviceApplication.java` com um MongoDB e Redis ativos.

## 📂 Estrutura
- `controller`: endpoints REST
- `service`: regras de negócio
- `repository`: integração com MongoDB
- `exceptions`: tratamento centralizado de erros
- `client`: integração com APIs externas

---

Projeto criado para fins de estudo de arquitetura de microserviços e boas práticas com Spring.
