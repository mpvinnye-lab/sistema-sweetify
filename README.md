# Doce Caixa PWA — v5

Versão com Caixa Sweetify separado por porcentagem do lucro.

- O lucro é calculado por vendas - custo vendido - despesas operacionais.
- A divisão do lucro usa os percentuais configurados (padrão 35% / 15% / 50%).
- O Caixa Sweetify acumula somente a porcentagem da empresa e diminui com pagamentos de dívida ou usos da própria loja.
- Retiradas dos sócios reduzem somente o disponível daquele sócio.
- Compras para produção não reduzem o lucro duas vezes: o custo entra pelo custo unitário dos produtos vendidos.
- Salvamento automático local + IndexedDB + backup.

Ao atualizar no GitHub Pages, substitua `index.html`, `sw.js`, `manifest.webmanifest` e mantenha a pasta `icons`.
