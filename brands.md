# Roteiro de Testes - Perfil Marca

## Informações Gerais
- **Objetivo:** Validar funcionalidades disponíveis para o perfil Marca
- **Pré-condição:** Usuário logado como _Owner_ da Marca

---

## Casos de Teste

### BRD-001 - Login
**Passos:**
1. Acessar a página de login
2. Inserir usuário e senha válidos
3. Clicar em "Entrar"

**Resultado esperado:** Acesso concedido ao painel da Marca  

---

### BRD-002 - Painel
**Passos:**
1. Navegar até "Meu Painel"
2. Verificar o quadro "Métricas" e "Estatísticas"
3. Comparar valores

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** Métricas e Estatísticas exibidas com sucesso  

---

### BRD-003 - Painel - Filtros
**Passos:**
1. Navegar até "Meu Painel"
2. Verificar o quadro "Métricas" e "Estatísticas"
3. Filtrar por qualquer período
4. Comparar valores

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** Métricas e Estatísticas exibidas com sucesso de acordo com o período selecionado  

---

### BRD-004 - Produtos
**Passos:**
1. Navegar até "Meus Produtos"
2. Verificar a lista de itens na aba "Produtos"
3. Verificar busca e filtros

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** A lista de produtos deve responder de acordo com as ações  

---

### BRD-005 - Produtos - Comissões
**Passos:**
1. Navegar até "Meus Produtos"
2. Selecionar um item da lista na aba "Produtos"
3. Definir ou alterar o valor de comissão do item selecionado

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** O produto deve ter sua comissão definida ou alterada conforme o valor informado  

---

### BRD-006 - Categorias
**Passos:**
1. Navegar até "Meus Produtos"
2. Verificar a lista de itens na aba "Categorias"
3. Verificar busca e filtros

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** A lista de categorias deve responder de acordo com as ações  

---

### BRD-007 - Categorias - Comissões
**Passos:**
1. Navegar até "Meus Produtos"
2. Verificar a lista de itens na aba "Categorias"
3. Definir ou alterar o valor de comissão do item selecionado

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** A categoria deve ter sua comissão definida ou alterada conforme o valor informado  

---

### BRD-008 - Campanhas
**Passos:**
1. Navegar até "Minhas Campanhas"
2. Verificar a lista de cards de campanhas
3. Clicar em "Ver Campanha" em qualquer uma das campanhas
4. Verificar a lista de produtos da campanha

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** Os cards de campanhas e de produtos devem ser exibidos corretamente, com imagens, nomes, datas, valores de comissões, etc.  

---

### BRD-009 - Campanhas - Edição
**Passos:**
1. Navegar até "Minhas Campanhas"
2. Verificar a lista de cards de campanhas
3. Clicar em "Ver Campanha" em qualquer uma das campanhas
4. Clicar no botão "Editar"
5. Alterar qualquer informação da campanha
6. Clicar em "Salvar Alterações"

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** A campanha deve ser atualizada com as novas informações  

---

### BRD-010 - Campanhas - Filtros
**Passos:**
1. Navegar até "Minhas Campanhas"
2. Verificar a lista de cards de campanhas
3. Usar o campo de busca

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** Os cards de campanhas devem ser filtrados de acordo com o termo de busca digitado  

---

### BRD-011 - Campanhas - Produtos - Filtros
**Passos:**
1. Navegar até "Minhas Campanhas"
2. Verificar a lista de cards de campanhas
3. Clicar em "Ver Campanha" em qualquer uma das campanhas
4. Na lista de produtos, usar o campo de busca

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** Os cards de produtos devem ser filtrados de acordo com o termo de busca digitado  

---

### BRD-012 - Campanhas - Adicionar
**Passos:**
1. Navegar até "Minhas Campanhas"
2. Clicar no botão "Nova Campanha"
3. Preencher todas as informações
4. Clicar no botão "Criar Campanha"
5. Verificar campanha criada

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** A nova campanha deverá aparecer nos cards. Os detalhes devem apresentar corretamente os dados informados  

---

### BRD-013 - Campanhas - Excluir
**Passos:**
1. Navegar até "Minhas Campanhas"
2. Clicar em "Ver Campanha" na campanha adicionada no passo anterior
3. Clicar no botão "Deletar Campanha"

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** A campanha deve ser excluída e não aparecer mais nos cards de campanha  

---

### BRD-014 - Afiliados - Filtros
**Passos:**
1. Navegar até "Meus Afiliados"
2. Verificar lista de afiliados
3. Usar filtros de status
4. Fazer busca por nome, e-mail e indicado

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** A lista de afiliados deve responder de acordo com os filtros selecionados e as buscas  

---

### BRD-015 - Afiliados - Links
**Passos:**
1. Navegar até "Meus Afiliados"
2. Clicar no botão "Ver Links" de qualquer um dos afiliados da lista

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** A lista de links do afiliado deve ser exibida  

---

### BRD-016 - Afiliados - Novos - Busca
**Passos:**
1. Navegar até "Meus Afiliados"
2. Clicar no botão "Novos"
3. Fazer busca por nome, e-mail e indicado

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** A lista de novos afiliados deve responder de acordo com as buscas  

---

### BRD-017 - Afiliados - Novos - Aprovação
**Passos:**
1. Navegar até "Meus Afiliados"
2. Clicar no botão "Novos"
3. Clicar no botão "Aprovar" em um dos afiliados listados

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** O afiliado deve sair dessa lista e ter seu status alterado para "Ativo"  

---

### BRD-018 - Afiliados - Novos - Reprovação
**Passos:**
1. Navegar até "Meus Afiliados"
2. Clicar no botão "Novos"
3. Clicar no botão "Rejeitar" em um dos afiliados listados

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** O afiliado deve sair dessa lista e ter seu status alterado para "Desativado"  

---

### BRD-019 - Afiliados - Criar
**Passos:**
1. Navegar até "Meus Afiliados"
2. Clicar no botão "Novos"
3. Preencher todas as informações de cadastro
4. Clicar no botão "Criar Novo Afiliado"

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** O afiliado deve ser criado com sucesso  

---

### BRD-020 - Afiliados - Gerenciamento
**Passos:**
1. Navegar até "Meus Afiliados"
2. Clicar no botão "Gerenciar" em um dos afiliados listados
3. Escolher uma das opções de gerenciamento disponíveis
4. Repetir os passos 2 e 3 para todas as opções disponíveis

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** O status e informações do afiliado devem ser alterados de acordo com as opções selecionadas  

---

### BRD-021 - Ranking - Busca e Filtros
**Passos:**
1. Navegar até "Ranking de Afiliados"
2. Fazer busca por nome e cidade
3. Escolher um período de datas

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** A lista deve responder de acordo com os termos de busca utilizados e os filtros de período de datas aplicado  

---

### BRD-022 - Ranking - Links e Edição
**Passos:**
1. Navegar até "Ranking de Afiliados"
2. Clicar no botão "Ver links"
3. Clicar no botão "Editar perfil"
4. Alterar alguma informação do afiliado
5. Clicar no botão "Salvar Alterações"

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** Uma lista com os links do afiliado deve ser exibida e as informações devem ser atualizadas conforme alterações feitas em seu perfil  

---

### BRD-023 - Cupons - Busca
**Passos:**
1. Navegar até "Cupons"
2. Verificar lista de cupons
3. Fazer uma busca

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** Uma lista com os cupons cadastrados deve ser exibida e deve responder de acordo com os termos de busca digitados  

---

### BRD-024 - Cupons - Edição
**Passos:**
1. Navegar até "Cupons"
2. Clicar no botão "Editar"
3. Fazer alterações
4. Clicar no botão "Salvar Alterações"

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** O cupom deve ser alterado conforme as informações inseridas  

---

### BRD-025 - Cupons - Adição
**Passos:**
1. Navegar até "Cupons"
2. Clicar no botão "Adicionar"
3. Inserir as informações solicitadas
4. Clicar no botão "Criar Cupom"

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** O cupom deve ser criado com sucesso  

---

### BRD-026 - Cupons - Exclusão
**Passos:**
1. Navegar até "Cupons"
2. Clicar no botão "Excluir" no cupom criado no teste anterior

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** O cupom deve ser excluído com sucesso  

---

### BRD-027 - Financeiro - Lista e Filtros
**Passos:**
1. Navegar até "Financeiro"
2. Fazer busca por nome
3. Selecionar um período de datas

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** As métricas e a lista de Comissões devem responder conforme termos de busca digitos e período de datas selecionados  

---

### BRD-028 - Financeiro - Perfil
**Passos:**
1. Navegar até "Financeiro"
2. Clicar em "Ver Perfil" em qualquer um dos afiliados da lista
3. (Opcional) Fazer alterações e clicar no botão "Salvar Alterações"

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** O perfil do afiliado deve ser exibido corretamente. Caso sejam feitas alterações, elas devem refletir corretamente, de acordo com as informações alteradas  

---

### BRD-029 - Financeiro - Relatório
**Passos:**
1. Navegar até "Financeiro"
2. Clicar em "Ver Relatório" em qualquer um dos afiliados da lista
3. Selecionar um período de datas
4. Filtrar status de comissões

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** O relatório de comissões do afiliado deve ser apresentado corretamente, de acordo com o período de datas selecionado e os filtros aplicados  

---

### BRD-030 - Financeiro - Exportação
**Passos:**
1. Navegar até "Financeiro"
2. Clicar em "Exportar"
3. Selecionar um período de datas e os campos
4. Clicar no botão "Exportar"

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** O relatório detalhado de comissões deve ser exportado com sucesso no formato CSV  

---

### BRD-031 - Perfil
**Passos:**
1. No canto superior direito, clicar na imagem de perfil
2. Clicar em "Meu Perfil"
3. Verificar e alterar informações do perfil
4. Clicar no botão "Salvar"

**Pré-requisito:** Usuário logado com o perfil Marca  
**Resultado esperado:** Os dados do perfil do usuário devem ser alterados de acordo com as informações preenchidas  

---
