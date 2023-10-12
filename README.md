# Configuración de los Microservicios

# Dev

Activar el servicio de vault

```vault server --dev --dev-root-token-id="00000000-0000-0000-0000-000000000000"```

Subir la configuración a vault

* ```vault kv put secret/booking-microservice @booking-microservice.json```
* ```vault kv put secret/product-microservice @product-microservice.json```
* ```vault kv put secret/stock-microservice @stock-microservice.json```