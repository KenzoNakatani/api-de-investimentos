# API de Investimentos

API REST desenvolvida em Java com Spring Boot para gerenciamento de investimentos, permitindo o controle de ativos, carteiras e transações financeiras.

## 📋 Sobre o projeto

Este projeto foi criado como parte do meu aprendizado em desenvolvimento de APIs com Spring Boot. A ideia é simular um sistema de controle de investimentos, onde é possível gerenciar diferentes tipos de ativos financeiros, organizá-los em carteiras e registrar as transações de compra e venda.

## 🚀 Tecnologias utilizadas

- **Java**
- **Spring Boot**
- **Maven**

## 📁 Estrutura do projeto

O projeto está organizado nos seguintes modelos principais:

- **Usuario** — representa o usuário do sistema
- **Carteira** — agrupa os ativos de um usuário
- **Ativo** — representa um ativo financeiro (ação, fundo, etc.)
- **TipoAtivo** — categoriza os tipos de ativos disponíveis
- **Transação** — registra operações de compra e venda
- **TipoTransação** — categoriza os tipos de transação (compra, venda, etc.)

## ⚙️ Como rodar o projeto

### Pré-requisitos
- Java JDK instalado
- Maven (ou usar o `mvnw` incluso no projeto)

### Passos

1. Clone o repositório:
```bash
git clone https://github.com/hyro-cyber/api-de-investimentos.git
```

2. Entre na pasta do projeto:
```bash
cd api-de-investimentos
```

3. Rode a aplicação:
```bash
./mvnw spring-boot:run
```

A aplicação vai subir por padrão em http://localhost:8080

## 📌 Status do projeto

🚧 Em desenvolvimento — projeto de aprendizado, novas funcionalidades sendo adicionadas continuamentes.

## 👤 Autor

Desenvolvido por hyro-cyber como parte do aprendizado em Java e Spring Boot.
