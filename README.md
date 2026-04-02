# 💻LeiloesTDSat
Este é um projeto educacional utilizado nas aulas de versionamento.

# ✔ Tarefas(ATIVIDADE2)
- [x] **Configuração da Tela Principal:** Definida a `cadastroVIEW` como interface inicial do sistema.
- [x] **Funcionalidade de Cadastro:** Implementada a lógica para salvar produtos no banco de dados através do botão "Cadastrar".
- [x] **Feedback ao Usuário:** Inclusão de mensagens de sucesso ou erro (JOptionPane) após tentativas de cadastro.
- [x] **Listagem de Produtos:** Implementada a tela `listagemVIEW` que recupera e exibe todos os itens cadastrados no banco de dados.
- [x] **Boas Práticas de Versionamento:** Uso de mensagens de commit descritivas e gerenciamento de ramificações (branches) para novas funcionalidades.

## 🚀Tecnologias utilizadas
* **Linguagem:** Java (JDK 11 ou superior)
* **IDE:** Apache NetBeans 13
* **Banco de Dados:** MySQL 8.0
* **Driver JDBC:** MySQL Connector/J
* **Versionamento:** Git & GitHub

## 📂 Como rodar o projeto

1. **Banco de Dados:**
   - Execute o script contido em `Script.sql` no seu MySQL Workbench para criar a base de dados `leiloes_db` e a tabela `produtos`.
   
2. **Configuração na IDE:**
   - Abra o projeto no NetBeans.
   - Certifique-se de que o Driver JDBC do MySQL está adicionado à pasta `Libraries`.
   - Ajuste as credenciais de acesso ao banco (usuário e senha) no arquivo `conectaDAO.java`.

3. **Execução:**
   - Execute o projeto. A tela `cadastroVIEW` será aberta automaticamente.
