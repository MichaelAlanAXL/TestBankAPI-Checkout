# TestBankAPI/Checkout

Este repositório fornece uma API simulada para testes de ckeckout de pagamentos.

## Como usar

1. **Obtenha um token**:
   - Faça uma requisição GET para `/generate-token` para obter um token de teste.

2. **Faça um pagamento de teste**:
   - Use o token obtido para fazer uma requisição POST para `/checkout`.
   - Envie um corpo JSON com o número do cartão e o valor.


## Endpoints

- **GET /generate-token**: Gera um token JWT.
- **POST /checkout**: Realiza uma transação de pagamento de teste.

## Licença

Distribuído sob a licença [MIT License](LICENSE).