# FAQs de Blosm

## Key 

⚠️IMPORTANTE⚠️ Guardar la KEY y no la compartáis más allá del grupo para tener controlado su uso.

## Límites de Google Maps Tile API

El servicio de Google tiene limitaciones en su versión gratuita que hay que conocer para no pasarse. Son medidas en general para desarrolladores de aplicaciones que usan muchos datos pero es mejor tenerlo controlado. Los usos y condiciones son confusos y liosos en la página de Google pero según foros informados sobre el tema los límites que nos interesan son: 

- Máximo 300 `root tileset queries` cada día. Esto cuantas veces se pide información, es decir, cada vez que se importa un mapa.
- Máximo 250.000 `renderer’s tile requests` cada día. Esto hace referencia a la cantidad de Tiles o baldosas se descargan en cada mapa. Es díficil saber cuántas son por mapa pero cuanto más detalle tenga el mapa más tiles. 

Podéis consultar el uso de datos en este link: [maps-apis/quotas](https://console.cloud.google.com/google/maps-apis/quotas)

En la página de Quotas seleccionando `Map Tiles API` puedes ver las cuotas de `3D Tiles renderer requests` y `3D Tiles root requests`

![maps](/archivos/maps.png)

En `3D Tiles renderer requests` puedes ver el uso de Tiles o baldosas por cada día.

![maps](/archivos/maps2.png)

⚠️IMPORTANTE⚠️ Podéis poner un límite a la cantidad que ahora mismo esta `unlimited`. Poner el máximo de 250.000 para que si lo alcanza se pare el servicio.

![maps](/archivos/maps4.png)

En `3D Tiles root requests` puedes ver cuántas veces has descargado cosas por cada día. En este caso el límite está ya ajustado a los 300.

![maps](/archivos/maps3.png)
