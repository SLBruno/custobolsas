# Preço das Bolsas

Calculadora de preço para bolsas costuradas à mão. Soma materiais, tempo de trabalho (valor da hora), parte dos custos fixos do mês, lucro e taxas de venda, e guarda o histórico de cada bolsa calculada.

É uma página única (`index.html`), sem build. Os dados ficam salvos no navegador do aparelho (localStorage).

## Como o preço é calculado

- custo = materiais + horas × valor da hora + horas × (custos fixos do mês ÷ horas trabalhadas no mês)
- preço = (custo + lucro) ÷ (1 − taxa de venda)
