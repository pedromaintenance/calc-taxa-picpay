# Calculadora de Taxa Pix

Calculadora simples, responsiva e **offline** para estimar quanto enviar em um Pix por cartão sem ultrapassar o saldo disponível.

## Como usar

Abra o `index.html` no navegador ou publique o repositório pelo GitHub Pages. Digite o saldo disponível e veja somente os dois resultados principais:

- **Valor a enviar:** maior valor possível, em centavos, sem que o total estimado ultrapasse o saldo.
- **Taxa estimada:** cobrança calculada sobre o valor a enviar.

## Taxa de referência

O cálculo usa a referência observada de **R$ 1.000,00 enviados → R$ 1.054,92 cobrados**, equivalente a **5,492%** sobre o valor enviado.

**Exemplo:** saldo de **R$ 1.620,55** → enviar **R$ 1.536,18**, com taxa de **R$ 84,37**.

O app usa busca binária e arredondamento de centavos para encontrar o maior valor possível dentro do saldo. **Não acessa contas, não faz Pix e não coleta dados.**

> **Importante:** a taxa efetiva do PicPay pode variar por usuário, cartão, valor, promoção ou data. A calculadora é uma aproximação baseada na referência acima. Confirme o total mostrado pelo PicPay antes de efetivar a operação.

## Tecnologia

HTML, CSS e JavaScript puros, sem bibliotecas externas e sem instalação.
