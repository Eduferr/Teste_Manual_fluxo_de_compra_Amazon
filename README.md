<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/40fe69a7-d3c6-4b44-9d8b-4e0334fef827" /><img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/6980e4bf-1438-44a9-834e-c6eee91d1c1c" /><h1 align="center"> Plano de Teste – Compra na EBAC - SHOP </h1>

## Objetivo:
Validar o fluxo de compra de um produto na lojinha EBAC - SHOP, incluindo busca, seleção, carrinho, checkout confirmação do pedido.

## Escopo:

- Busca por produto e aplicação de filtros.
- Seleção de variações (cor/tamanho).
- Adição ao carrinho.
- Checkout: endereço, pagamento, cupom.
- Confirmação do pedido.

Ambiente:

http://lojaebac.ebaconline.art.br em navegador atualizado (Chrome/Edge/Firefox).

Conta de teste com endereço e pagamento configurados.

Dados de teste:

Produto-alvo (nome/ASIN/URL), CEP de teste, cupom (se existir), preço esperado.

Riscos & Mitigações:

Produto ficar indisponível → Definir 2 alternativas.

Variação esgotada → Trocar cor/tamanho.

Cobrança indevida em teste real → Encerrar antes do clique “Fazer pedido” ou cancelar logo após.

Critérios de aceitação:

Preço, frete e total corretos em todas as etapas.

Produto correto, quantidade correta, endereço e pagamento aplicados sem erro.

Confirmações e mensagens exibidas corretamente.

(Se compra real) Pedido criado e visível em “Seus pedidos”.

Entregáveis:

Checklist preenchida, capturas de tela, relatório de execução com status (Aprovado/Reprovado) e observações.
