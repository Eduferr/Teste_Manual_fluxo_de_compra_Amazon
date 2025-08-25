<h1 align="center"> Plano de Teste – Compra na EBAC-SHOP </h1>

### Objetivo:
- Validar o fluxo de compra de um produto na lojinha EBAC - SHOP, incluindo busca, seleção, carrinho, checkout confirmação do pedido.

### Escopo:
- Busca por produto e aplicação de filtros.
- Seleção de variações (cor/tamanho).
- Adição ao carrinho.
- Checkout: endereço, pagamento, cupom.
- Confirmação do pedido.

### Ambiente:
- http://lojaebac.ebaconline.art.br/ no navegador Google Chrome atualizado
- Conta de teste com endereço e pagamento configurados.

### Dados de teste:
 - Nome do produto: Hollister Backyard Sweatshirt
 - SKU: MH05
 - Preço esperado: R$52,00
 - Cupom: ebac10 - 10% de desconto

### Riscos & Mitigações:
- Produto ficar indisponível
- Variação esgotada → Trocar cor/tamanho.
- Cupom de desconto não estiver ativo

### Critérios de aceitação:
- Preço correto em todas as etapas.
- Produto correto, quantidade correta, endereço e pagamento aplicados sem erro.
- Confirmações e mensagens exibidas corretamente.

### Entregáveis:
- Checklist preenchida, capturas de tela, relatório de execução com status (Aprovado/Reprovado) e observações.