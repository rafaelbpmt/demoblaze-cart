
# Demoblaze - Cart Feature

Processo de Teste E2E com a aplicação (https://www.demoblaze.com), onde testei e documentei a feature de carrinho do site.

## Sumário
  
- 📝 [Plano de Testes](#plano-de-testes) 
- 🖥️ [Cenários de Testes](#cenários-de-testes) 


## Plano de Testes
 
 
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

## Cenários de Testes
