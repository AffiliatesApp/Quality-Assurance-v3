# Roteiro de Testes - Perfil Afiliados

## Informações Gerais
- **Objetivo:** Validar funcionalidades disponíveis para o perfil Afiliados
- **Pré-condição:** Usuário logado como Afiliado

---

## Casos de Teste

### BRD-001 - Login
**Passos:**
1. Acessar a página de login
2. Inserir usuário e senha válidos
3. Clicar em "Entrar"

**Resultado esperado:** Acesso concedido ao painel de Afiliado  

---

### BRD-002 - Painel
**Passos:**
1. Navegar até "Meu Painel"
2. Verificar os quadros "Métricas" e "Meus Pedidos"
3. Comparar valores

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** Métricas e estatísticas de pedidos exibidos com sucesso  

---

### BRD-003 - Painel - Filtros
**Passos:**
1. Navegar até "Meu Painel"
2. Verificar o quadro "Métricas" e "Meus Pedidos"
3. Filtrar por qualquer período
4. Comparar valores

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** Métricas e estatísticas de pedidos exibidas com sucesso de acordo com o período selecionado  

---

### BRD-004 - Links
**Passos:**
1. Navegar até "Meus Links"
2. Verificar a lista de Links ativos
3. Fazer uma busca pelo nome do produto

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** A lista de links do afiliado deve ser exibida com informações do produto, valores e métricas  

---

### BRD-005 - Links - Gerenciamento
**Passos:**
1. Navegar até "Meus Links"
2. Verificar a lista de Links ativos
3. Clicar no botão "Copiar" de qualquer um dos links e colar na barra de endereços de outra aba do navegador
4. Clicar no botão "Compartilhar" de qualquer um dos links
5. Clicar no botão "Deletar" de qualquer um dos links

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** O link copiado deve abrir corretamente em nova aba. O link excluído deve desaparecer da lista  

---

### BRD-006 - Produtos
**Passos:**
1. Navegar até "Produtos"
2. Verificar a lista de itens na aba "Em destaque" e na aba "Todos"
3. Fazer busca por nome de produto
4. Clicar no botão "Criar Link" em qualquer um dos produtos

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** A lista de produtos deve responder de acordo com os filtros e a busca. Um novo link deve ser criado com sucesso no passo 4  

---

### BRD-007 - Campanhas
**Passos:**
1. Navegar até "Campanhas"
2. Verificar a lista de Campanhas
3. Fazer uma busca

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** A lista de campanhas deve ser exibida corretamente  

---

### BRD-008 - Binível
**Passos:**
1. Navegar até "Minha Rede"
2. Verificar a lista de subafiliados
3. Fazer busca por nome
4. Utilizar os filtros de status

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** A lista de subafiliados deve responder corretamente aos termos de busca digitados e aos filtros selecionados  

---

### BRD-009 - Treinamento
**Passos:**
1. Navegar até "Affiliates Academy"
2. Verificar a lista de treinamentos disponíveis
3. Clicar em qualquer um dos treinamentos disponíveis
4. Clicar em qualquer uma das abas de categorias disponíveis
5. Clicar no botão "Acessar Criativos"

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** A lista de treinamentos deve ser apresentada corretamente de acordo com a categoria selecionada. Um modal deve ser exibido com o treinamento selecionado. Uma nova aba com os criativos disponíveis deve ser aberta  

---

### BRD-010 - Finanças - Carteira
**Passos:**
1. Navegar até "Meus Pagamentos"
2. Verificar informações da aba "Carteira"

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** A tela deve exibir o saldo em carteira do afiliado, informações sobre pagamentos, saldo em processamento, etc.  

---

### BRD-011 - Finanças - Vendas
**Passos:**
1. Navegar até "Meus Pagamentos"
2. Clicar na aba "Vendas"
3. Selecionar os filtros de status
4. Fazer busca por produto ou SKU

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** A lista de vendas do afiliado deve ser exibida corretamente, de acordo com os filtros de status selecionados e os termos de busca digitados  

---

### BRD-012 - Finanças - Extrato
**Passos:**
1. Navegar até "Meus Pagamentos"
2. Clicar na aba "Extrato"
3. Utilizar os filtros de período e tipo

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** O extrato de movimentações do afiliado deve ser exibido corretamente, de acordo com o período de datas selecionado e o tipo.  

---

### BRD-013 - Saque
**Passos:**
1. Navegar até "Meus Pagamentos"
2. Clicar na aba "Carteira"
3. Clicar no botão "Solicitar Saque"
4. Seguir instruções

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** O afiliado deve ser capaz de realizar uma solicitação de saque  

---

### BRD-014 - Suporte - FAQ
**Passos:**
1. Navegar até "Suporte"
2. Verificar lista de Perguntas Frequentes
3. Clicar no botão "Fale conosco"
4. Enviar uma mensagem

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** A página deve exibir as perguntas frequentes e o formulário de contado corretamente  

---

### BRD-015 - Cadastro
**Passos:**
1. Navegar até a Landing Page da marca
2. Fazer o cadastro utilizando um email válido

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** A plataforma deve enviar um email com instruções para ativação do cadastro  

---

### BRD-016 - Perfil
**Passos:**
1. No canto superior direito, clicar na imagem de perfil
2. Clicar em "Meu Perfil"
3. Verificar e alterar informações do perfil
4. Clicar no botão "Salvar"

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** Os dados do perfil do usuário devem ser alterados de acordo com as informações preenchidas  

---

### BRD-017 - Perfil - Código
**Passos:**
1. No canto superior direito, clicar na imagem de perfil
2. Clicar em "Código de afiliado"

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** A plataforma deve exibir uma janela com o código do afiliado e instruções de uso  

---

### BRD-018 - Perfil - Convite
**Passos:**
1. No canto superior direito, clicar na imagem de perfil
2. Clicar em "Convide um Novo afiliado"
3. Selecionar a opção "Por e-mail"
4. Digitar um endereço de e-mail válido

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Pré-requisito:** Usuário autorizado à ter subafiliados  
**Resultado esperado:** Uma mensagem deve chegar no e-mail com o link para cadastro do convidado.  

---

### BRD-019 - Perfil - Convite
**Passos:**
1. No canto superior direito, clicar na imagem de perfil
2. Clicar em "Convide um Novo afiliado"
3. Selecionar a opção "Por link"
4. Copiar e colar o link em uma nova aba do navegador
5. Preencher o formulário como se fosse um convidado

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Pré-requisito:** Usuário autorizado à ter subafiliados  
**Resultado esperado:** O cadastro deve ser realizado com sucesso  

---

### BRD-020 - Recuperação de senha
**Passos:**
1. Na tela de login, clicar em "Esqueceu a senha"
2. Digitar um email de afiliado
3. Clicar no botão "Enviar link de recuperação"
4. Seguir instruções recebidas por email

**Pré-requisito:** Usuário logado com o perfil Afiliado  
**Resultado esperado:** O afiliado deve ser capaz de redefinir sua senha de acesso

