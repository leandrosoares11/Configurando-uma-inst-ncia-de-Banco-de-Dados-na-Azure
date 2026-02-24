# Projeto DIO: Configurando uma Instância de Banco de Dados na Azure

Este projeto tem como objetivo demonstrar, passo a passo, como configurar uma instância de banco de dados SQL no Microsoft Azure, utilizando o portal web. Abaixo estão as instruções detalhadas e imagens ilustrativas para facilitar o entendimento.

---

# Pré-requisitos

- Conta ativa no [Microsoft Azure](https://portal.azure.com)
- Permissão para criar recursos
- Navegador web atualizado

---

# Passo a Passo

# 1. Acessar o Portal do Azure

- Entre no [portal do Azure](https://portal.azure.com)
- No campo de pesquisa, digite "Banco de Dados SQL"
- Clique em Banco de Dados SQL na seção de serviços

![Passo 1](https://copilot.microsoft.com/th/id/BCO.5e2365a3-a0c8-4172-a7a7-8b949c8de1c8.png)

---

# 2. Criar uma Nova Instância

- Clique em "+ Criar" para iniciar o assistente de configuração

---

# 3. Configurações Básicas

- Assinatura: selecione sua assinatura ativa
- Grupo de Recursos: crie um novo ou selecione um existente
- Nome do Banco de Dados: defina um nome único
- Servidor: crie um novo servidor ou selecione um existente
  - Defina nome, região e credenciais de administrador

---

# 4. Configurações de Segurança

- Escolha o método de autenticação:
  - SQL Authentication (usuário e senha)
  - Azure AD Authentication (mais seguro e recomendado)
- Configure regras de firewall para permitir acesso ao banco

---

# 5. Configurações de Rede

- Em Conectividade, selecione:
  - Entrada pública (para acesso externo)
  - Adicione regra de firewall para permitir acesso do seu IP

---

# 6. Configurações Avançadas

- Defina opções de desempenho (DTUs ou vCores)
- Configure backup e redundância geográfica
- Ajuste escalabilidade conforme necessidade

---

# 7. Revisão e Criação

- Revise todas as configurações
- Clique em Criar
- Aguarde a implantação da instância

---

# 8. Conectar ao Banco

- Após criado, vá até o recurso
- Copie a string de conexão
- Use ferramentas como Azure Data Studio ou SQL Server Management Studio (SSMS) para se conectar

---

# Ferramentas Utilizadas

- Microsoft Azure Portal
- Azure SQL Database
- Azure Data Studio / SSMS

---

# Referências

- [Documentação oficial Microsoft Learn](https://learn.microsoft.com/pt-br/azure/azure-sql/database/single-database-overview)
- [Portal Azure](https://portal.azure.com)
