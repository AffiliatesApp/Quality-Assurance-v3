# Roteiro de Testes - Perfil Financeiro

## Informações Gerais
- **Objetivo:** Validar funcionalidades disponíveis para o perfil Financeiro
- **Pré-condição:** Usuário logado como Accountant

---

## Casos de Teste

### BRD-001 - Login
**Passos:**
1. Acessar a página de login
2. Inserir usuário e senha válidos
3. Clicar em "Entrar"

**Resultado esperado:** Acesso concedido ao painel do Financeiro  

---

### BRD-002 - Painel
**Passos:**
1. Navegar até "Painel Geral"
2. Verificar os quadros

**Pré-requisito:** Usuário logado com o perfil Accountant  
**Resultado esperado:** As estatísticas devem ser exibidas com sucesso  

---

### BRD-003 - Faturas
**Passos:**
1. Navegar até "Financeiro"
2. Verificar lista de faturas
3. Filtrar por período de datas, marca e status
4. Clicar no botão "Detalhes" de qualquer fatura

**Pré-requisito:** Usuário logado com o perfil Accountant  
**Resultado esperado:** A lista de faturas deve ser exibida corretamente, de acordo com o período de datas informado e os filtros utilizados. Os detalhes da fatura devem ser exibidos corretamente  

---

### BRD-004 - Faturas - Gerar
**Passos:**
1. Navegar até "Financeiro"
2. Clicar no botão "Gerar Fatura"
3. Selecionar uma marca
4. Selecionar um tipo de fatura
5. Selecionar uma data de vencimento
6. Clicar no botão "Gerar Fatura"

**Pré-requisito:** Usuário logado com o perfil Accountant  
**Resultado esperado:** A nova fatura deve ser gerada com sucesso  

---

### BRD-005 - Faturas - Recebimento
**Passos:**
1. Navegar até "Financeiro"
2. Clicar no botão "Confirmar" de qualquer fatura com status "Pendente"

**Pré-requisito:** Usuário logado com o perfil Accountant  
**Resultado esperado:** A fatura deve ser atualizada e os valores das comissões vinculadas à ela devem ser distribuídos corretamente  

---

### BRD-006 - Contas Digitais
**Passos:**
1. Navegar até "Contas Digitais"
2. Filtrar os status
3. Verificar documentos
4. Aprovar e/ou Recusar contas

**Pré-requisito:** Usuário logado com o perfil Accountant  
**Resultado esperado:** A lista de contas digitais deve ser exibida corretamente de acordo com os filtros utilizados. Os documentos devem ser exibidos e o registro deve ser atualizado corretamente conforma a escolha de Aprovação ou Recusa da conta  

---

### BRD-007 - Saques
**Passos:**
1. Navegar até "Solicitações de Saque"
2. Filtrar por marca
3. Aprovar e/ou Recusar uma solicitação

**Pré-requisito:** Usuário logado com o perfil Accountant  
**Resultado esperado:** A lista de solicitações de saques deve ser exibida corretamente de acordo com a marca selecionada. A solicitação deve ser aprovada ou recusada, de acordo com a ação escolhida  

