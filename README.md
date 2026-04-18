# week_6
# Paw Server | Infraestrutura Back-end para PetShop

O Paw Server é a API responsável por sustentar a lógica de negócio e a gestão de dados da plataforma PetShop. Este projeto foca-se na criação de endpoints seguros, processamento de pedidos e gestão de autenticação, servindo como o núcleo inteligente que alimenta a interface do utilizador.

---

## Resumo do Projeto

Desenvolvido para garantir alta performance e escalabilidade, o servidor gere as interações entre a base de dados e o frontend. Ele lida com processos críticos como o registo de utilizadores, gestão de inventário de produtos e o processamento de fluxos de compra, garantindo que as regras de negócio sejam aplicadas de forma consistente.

### Tecnologias e Ferramentas

| Categoria | Tecnologias Utilizadas |
| :--- | :--- |
| **Ambiente** | Node.js |
| **Framework** | Express.js |
| **Base de Dados** | PostgreSQL / MySQL (via Knex.js) |
| **Autenticação** | JWT (JSON Web Tokens) |

---

## Estrutura de Diretórios

A arquitetura do servidor foi desenhada para facilitar a manutenção e a separação de responsabilidades:

* **src/controllers/**: Lógica de resposta às requisições e regras de negócio.
* **src/routes/**: Definição dos endpoints da API (Auth, Products, Orders).
* **src/models/**: Estrutura de dados e interações com a base de dados.
* **src/database/**: Configurações de conexão e ficheiros de migração.

---

## Funcionalidades Principais

O servidor demonstra competência em arquitetura de sistemas distribuídos:

> **API RESTful de Alta Disponibilidade**
> Implementação de uma arquitetura modular que permite a expansão rápida de novas funcionalidades, com um sistema de autenticação robusto que protege os dados sensíveis dos utilizadores e clientes da loja.

---

## Instalação e Execução Local

Para colocar o servidor em funcionamento no seu ambiente:

1. Efetue o clone do repositório:
   ```bash
   git clone [https://github.com/samuel123d/Paw-sever2.git](https://github.com/samuel123d/Paw-sever2.git)
