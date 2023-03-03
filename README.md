# Test-CreditCard-XML
Estructura de XML para el intercambio de información de tarjetas de crédito

# Lógica
Existen 2 archivos :
- creditCardRequest.xml
- creditCardResponse.xml

El archivo creditCardRequest.xml permite realizar una solicitud para obtener información de tarjeta de crédito y el 
archivo creditCardResponse.xml trae la respuesta de la solicitud al sistema.

Los valores reales de los campos se reemplazarían en tiempo de ejecución con los valores que se encuentren en la tabla de la base de datos. 
Por ejemplo, si el valor de systemName en la tabla es "customer", 
se reemplazaría el comodín {systemName} con "customer" al recuperar la trama XML de la base de datos y asi con los demas tags.
