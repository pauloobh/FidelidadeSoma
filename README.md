# Cartão Fidelidade SRFarma
http://fidelidade.redesoma.com.br/

## Obter Token ##
Post http://fidelidade.redesoma.com.br/v1/token

### Parametros
email: string,
password: string

### Retorno
#### Status 200
{ "api_token": "string" }
#### Status 400
{ "error": "string" }
