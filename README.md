# 🚀API test

# user

## create user

/api/auth/local/register

```json
{
  "email": "",
  "username": "",
  "password": ""
}
```

## login

/api/auth/local

```json
{
  "identifier": "",
  "password": ""
}
```

## Update

---

# Vaga

## List all

/api/sinergy-vagas

## detail

/api/sinergy-vagas/1

## Create

/api/sinergy-vagas

```json
{
  "data": {
    "title": "programado22",
    "local": "sp",
    "client": "confidencial",
    "salary": 3000,
    "imgString": "https://www.portalsinergyrh.com.br/Files/Config/LogoClientes/Logo-Portal-Vaga-Confidencial.png",
    "description": "What is Lorem Ipsum?\nLorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.",
    "tipo": "CLT",
    "LikeString": "TRUE",
    "like": true
  }
}
```

# Graphql

```Graphql

query allVagas{
  sinergyVagas{
    data{
      attributes{
        title
      }
    }
  }
}
```
