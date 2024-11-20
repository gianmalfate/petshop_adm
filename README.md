# Petshop Admin

Este projeto é um CRUD web para gerenciamento de clientes em um petshop, desenvolvido durante um curso **JS na Web**. Ele implementa as operações básicas de criação, leitura, atualização e remoção (CRUD) com uma API simulada e interface dinâmica.

---

## 🛠️ Funcionalidades

- **Cadastro de clientes**:
  - Nome e email com validação.
  - Redirecionamento para uma página de sucesso após o cadastro.
- **Listagem de clientes**:
  - Exibição em uma tabela dinâmica.
  - Botões de edição e exclusão para cada cliente.
- **Edição de clientes**:
  - Atualização de nome e email.
  - Feedback visual para sucesso ou erro.
- **Exclusão de clientes**:
  - Exclusão com atualização em tempo real da tabela.
- **API simulada**:
  - Utilização de `JSON Server` para armazenamento local.

---

## 🚀 Tecnologias Utilizadas

- **HTML5**, **CSS3** e **JavaScript ES6+**.
- **Módulos JavaScript** para organização do código.
- **JSON Server** para simular uma API REST.
- **Browser Sync** para um ambiente de desenvolvimento rápido.

---

## ⚙️ Como Configurar e Executar o Projeto

### Pré-requisitos

- **Node.js** instalado em sua máquina.

### Passos

1. Clone este repositório:
   ```bash
   git clone <https://github.com/gianmalfate/petshop_adm>
   cd petshop_admin
2. Instale as dependências:
    ```bash
    npm install
3. Inicie o servidor JSON:
	```bash
    npx json-server --watch db.json 
4. Inicie o servidor local para desenvolvimento:
    ```bash
    npx browser-sync start --server --file . --host --port 5000 --startPath telas/lista_cliente.html
5. Acesse o projeto no navegador em `http://localhost:5000`.

## 📂 Arquivos Importantes

-   **`cliente-service.js`**: Gerencia as chamadas à API (listar, criar, editar, excluir clientes).
-   **`cadastraClientes-controller.js`**: Controla o formulário de cadastro.
-   **`listaClientes-controller.js`**: Renderiza a tabela de clientes e gerencia exclusões.
-   **`atualizaCliente-controller.js`**: Controla o formulário de edição de clientes.

## ✨ Demonstração

1.  **Página de Listagem de Clientes**:
    -   Lista todos os clientes cadastrados.
    -   Botões para editar e excluir.
      
2.  **Cadastro de Clientes**:
    -   Formulário para adicionar novos clientes.
    -   Validações básicas no front-end.
      
3.  **Edição de Clientes**:
    -   Formulário para alterar os dados de clientes existentes.
      
4.  **Exclusão de Clientes**:
    -   Remove clientes diretamente da tabela com feedback visual.

🧑‍💻 Contato
Dúvidas ou sugestões? Entre em contato pelo email: gianmalfate@gmail.com.
