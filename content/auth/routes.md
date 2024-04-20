---
title: "Assinatura de Rotas"
type: 'blank'
date: 2021-02-06
---

## Login Auth
#### `/auth/email`, método `POST`
Login do Usuário por Email e Senha

Corpo da Requisição:
```json
{
    "email": "email@email.com.br",
    "password": "password1"
}
```

Retorno esperado:
```json
{
    "access_token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXCA9...",
    "success": true
}
```


