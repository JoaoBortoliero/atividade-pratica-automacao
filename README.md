# 🧪 Testes Automatizados — Java, Selenium e Rest-Assured

Este repositório contém atividades práticas de **automação de testes** em **Front-end** e **APIs**, desenvolvidas com **Java**.  
O objetivo é aplicar conceitos de automação em um ambiente controlado e realista, utilizando ferramentas amplamente adotadas no mercado.

---

## 🎯 Objetivo

Proporcionar uma experiência prática com **testes automatizados**, explorando:
- Automação de **interfaces web** com **Selenium WebDriver**.
- Automação de **serviços REST** com **Rest-Assured**.
- Boas práticas de estruturação de código, validações e manutenção de testes.

A automação é uma competência essencial no desenvolvimento de software moderno, e a prática contínua é o melhor caminho para o desenvolvimento técnico e a excelência profissional.

---

## ⚙️ Tecnologias Utilizadas

- **Maven**  (gerenciador de dependências)
- **Selenium WebDriver** (automação de interface web)
- **Rest-Assured** (automação de APIs REST)
- **IntelliJ IDEA** (IDE recomendada)

---

## 🧭 Estrutura das Atividades

### **1. Front-end (Java + Selenium)**

Automação do fluxo de compra na aplicação **[SauceDemo](https://www.saucedemo.com/)**, cobrindo:

#### 🔹 Fluxo proposto:
1. **Login**
    - Autenticação com credenciais válidas.
    - Cenário negativo: tentativa de login com dados incorretos e validação das mensagens de erro.
2. **Listagem e Validação de Produtos**
    - Verificação da exibição correta dos produtos após o login.
3. **Carrinho de Compras**
    - Adicionar itens ao carrinho.
    - Verificar se os produtos foram adicionados corretamente.
    - Remover um item e validar a atualização.
4. **Checkout e Finalização da Compra**
    - Preencher os dados do comprador (nome, sobrenome, CEP).
    - Concluir o pedido e validar a mensagem de sucesso.

#### 🔸 Resultado esperado:
Um fluxo **end-to-end** funcional, simulando o comportamento de um usuário real no sistema.

---

### **2. APIs (Java + Rest-Assured)**

Automação de testes de APIs RESTful, com operações de **CRUD (Create, Read, Update, Delete)**.  
Você pode escolher **uma das APIs públicas** abaixo para praticar:

#### 🅰️ Opção A — Swagger Petstore
- **API:** [Swagger Petstore](https://petstore.swagger.io/)
- **Fluxo sugerido:**
    - **POST:** Criar um novo pet.
    - **GET:** Buscar o pet criado.
    - **PUT:** Atualizar o status ou nome do pet.
    - **DELETE:** Remover o pet do sistema.

#### 🅱️ Opção B — ReqRes
- **API:** [ReqRes](https://reqres.in/)
- **Fluxo sugerido:**
    - **POST:** Criar um novo usuário.
    - **GET:** Listar usuários e validar inclusão.
    - **PUT:** Atualizar dados de um usuário.
    - **DELETE:** Excluir o usuário criado.

#### 🅾️ Opção C — JSONPlaceholder
- **API:** [JSONPlaceholder](https://jsonplaceholder.typicode.com/)
- **Fluxo sugerido:**
    - **POST:** Criar um novo post.
    - **GET:** Buscar o post criado.
    - **PUT:** Editar o post.
    - **DELETE:** Remover o post.

---
