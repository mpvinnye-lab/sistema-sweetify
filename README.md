# Doce Caixa PWA — v7

Versão revisada do sistema Sweetify.

## Lógica financeira da v7
- O **custo unitário** continua existindo para analisar margem e rentabilidade de produtos e feiras.
- O custo unitário **não é descontado novamente** na divisão dos sócios.
- O valor real usado para a divisão é: **vendas registradas − compras para produção − despesas reais − despesas específicas das feiras**.
- Esse saldo real acumulado é dividido nas porcentagens configuradas (35% / 15% / 50% por padrão).
- O **Caixa Sweetify** é somente a parte da empresa, menos usos diretos e pagamentos de dívida.
- O app bloqueia retiradas, pagamentos de dívida e usos do Caixa Sweetify acima do disponível.
- Compras de estoque de um mês continuam sendo recuperadas pelas vendas futuras antes de criar novo dinheiro para divisão.

## Compatibilidade
Backups das versões anteriores são normalizados para a v7; as compras já registradas passam a entrar na nova lógica de saldo real.