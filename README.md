
# Demoblaze: Cart feature test 🛒

Processo de Teste E2E com a aplicação (https://www.demoblaze.com), onde testei e documentei a feature de carrinho do site.

## Sumário
  
- 📝 [Plano de Testes](#plano-de-testes) 
- 🖥️ [Cenários de Testes](#cenários-de-testes) 


## 📝 Plano de Testes
 
 
Documento no Google Docs: https://bit.ly/438Gf0x

**Introdução:** Os seguintes testes foram realizados no site demoblaze.com com finalidade de estudos sobre o planejamento e execução de testes manuais e automatizado, validando a feature de carrinho de compras do site Demoblaze, garantindo sua usabilidade com qualidade.

**Informações Gerais:**

**Nome do sistema:** Demoblaze (https://www.demoblaze.com) 

**Nome da funcionalidade:** Carrinho


**Versão:** 1.0 


**Responsável:** Rafael Bizarria

**Data de Criação:** 24/02/2025

**Última Atualização:** 25/02/2025



### Escopo dos testes

Teste da feature de login e carrinho de compras no site Demoblaze, serão realizados os seguintes testes de ui, funcionais, exploratórios e de compatibilidade. Os testes avaliarão a adição de produtos, edição do carrinho e remoção de itens.

Após os testes serem devidamente concluídos e documentados, os mesmos serão automatizados utilizando o Cypress.

### Regras de negócio

- O usuário pode adicionar produtos ao carrinho a partir da página do produto ou da listagem de produtos.

- O sistema deve permitir adicionar apenas produtos disponíveis em estoque.

- Se um produto estiver fora de estoque, o botão "Adicionar ao Carrinho" deve estar desativado ou oculto.

- O usuário pode adicionar múltiplas unidades do mesmo produto.

- O sistema deve atualizar automaticamente a quantidade total e o valor do carrinho.

- O usuário pode aumentar ou diminuir a quantidade de um produto diretamente no carrinho.

- Se a quantidade ultrapassar o estoque disponível, o sistema deve exibir um aviso e limitar a quantidade.

- O usuário pode remover um item do carrinho.

- O carrinho deve ser atualizado dinamicamente sem necessidade de recarregar a página.

### Pré-Condições


O usuário deve estar em um computador com conexão web na página inicial da demoblaze.com

O carrinho deve estar vazio antes de iniciar cada teste.

## 🖥️ Cenários de Testes

## Informações Gerais

|  Título             |    Adicionando produto ao carrinho                                             |
| ----------------- | ---------------------------------------------------------------- |
| ID       | CT-001 |
| Autor       | Rafael Bizarria
| Data       | 24/02/2025
| Versão       | 1.0
| Ambiente      | Produção
| Descrição      | Teste para verificar se a adição de produtos no carrinho está funcionando corretamente
| Prioridade      | Alta
| Tipo      | Funcional


|  Pré-requisitos| | 
| ----------------- | ---------------------------------------------------------------- |
| 1. | O usuário deve estar na página inicial do site da Demoblaze
| 2. | O usuário não precisa estar logado
| 3. | O carrinho deve estar vazio

|  Passo a passo | | 
| ----------------- | ---------------------------------------------------------------- |
| 1. | Acessar o site: demoblaze.com
| 2. | Clicar no nome ou foto de um produto
| 3. | Clicar no botão “Add to cart”
| 4. | Verificar se foi exibido a mensagem na tela “Product added”
| 5. | Clicar na aba “Cart” localizado no meio do menu superior
| 6. | Verificar se o produto foi adicionado corretamente

|  Resultado esperado | | 
| ----------------- | ---------------------------------------------------------------- |
| 1. | O produto se encontrará no carrinho

|  Ambiente de Testes | | 
| ----------------- | ---------------------------------------------------------------- |
| 1. | SO: macOS Sonoma 14.2.1
| 2. | Browser: Google Chrome 133.0.6943.127
| 3. | Plataforma: Web

|  Status | | 
| ----------------- | ---------------------------------------------------------------- |
| 1. | A fazer

**Você pode conferir todos os cenários de testes no Google Sheets: https://bit.ly/3XoEdpk** 

