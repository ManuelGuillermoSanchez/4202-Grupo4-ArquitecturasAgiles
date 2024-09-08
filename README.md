# 4202-Grupo4-ArquitecturasAgiles
Instrucciones de Ejecucion
Para esta semana estaremos realizando el experimento nuemero 1 que aplica las tacticas que favorece la disponibilidad sobre un servicio que detectan las fallas de conexión y las enmascaran basados en tácticas de redundancia y reintento de conexión.​

## Integrantes
| Nombre | Email |
|------|----------------------------------------------|
|Juan Nicolas Malagón Navarro | jn.malagon@uniandes.edu.co |
|Manuel Sanchez Ballen| mg.sanchezb1@uniandes.edu.co |
|Sergio Arturo Perez Rincon | sa.perezr12@uniandes.edu.co |
|Oscar Ivan Manco Racines| o.manco@uniandes.edu.co |

## Pasos para la ejecución

## ApiGateway
-flask run --port=5000

## Servidor de cliente
-flask run --port=5001

-flask run --port=5002 (servicio de respaldo)

## Simular solicitudes
-node experimento1.js
