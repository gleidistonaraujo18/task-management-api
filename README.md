# Task Manager API

API RESTful para gerenciamento de tarefas, desenvolvida com Node.js, TypeScript, Express, Sequelize e MySQL.

## Funcionalidades

- **Criar Tarefa:** Adicionar novas tarefas com título, descrição e status.
- **Listar Todas as Tarefas:** Visualizar todas as tarefas cadastradas.
- **Buscar Tarefa por ID:** Obter detalhes de uma tarefa específica pelo seu ID.
- **Atualizar Tarefa:** Modificar título, descrição e status de uma tarefa existente.
- **Excluir Tarefa:** Remover uma tarefa pelo seu ID.

## Tecnologias Utilizadas

- Node.js
- TypeScript
- Express
- Sequelize
- MySQL

## Como Executar

1. **Clone o repositório:**
   ```
   git clone https://github.com/gleidistonaraujo18/task-management-api.git
   cd task-manager-api
   ```

2. **Instale as dependências:**
   ```
   npm install
   ```

3. **Configuração do Banco de Dados:**
   - Configure suas credenciais de banco de dados no arquivo `config/database.ts`.

4. **Compilação do Código TypeScript:**
   ```
   tsc
   ```

5. **Execução da Aplicação:**
   ```
   node dist/app.js
   ```

6. **Acesso à API:**
   - Acesse a API em `http://localhost:3000`.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias ou correções.

## Licença

Este projeto é licenciado sob a Licença MIT.
