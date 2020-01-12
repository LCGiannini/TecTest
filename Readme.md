# Evaluación QA
## Instrucciones para correr los test es Newman

Para correr el **ambiente de QA:**
```
newman run Garbarino.postman_collection.json -e QA.postman_environment.json
```

Para correr el **ambiente de QA:**
```
newman run Garbarino.postman_collection.json -e Production.postman_environment.json
```

### Variables en los enviorment:
- **host:** Que contiene el valor del host de prod/qa
- **api_key:** Que contiene el valor de las API de prod/qa