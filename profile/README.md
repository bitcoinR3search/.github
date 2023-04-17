# ¡BIENVENIDO a Bitcoin Research!

Este es el repositorio oficial del proyecto (bajo licencia MIT) "Bitcoin Research".

## Contenido

El proyecto tiene distintos repositorios donde se encuentran las herramietnas que se desarrollan usando #Python en el proyecto. Los principales:

---

📂 Blockchain Py/ -

Es un ejercicio en Python para montar una propia red Bitcoin que tiene: Envío de transacciones, Minería y la prueba de trabajo POW, sincronización y validación de la cadena más larga (compentencia de varios nodos y mineros).

📂 Bibliografía/ -

Libros y papers que usamos como bibliografía para profundizar conceptos.

📂 twitterbot/ -

La cuenta oficial del proyecto es [@bitcoinr3](https://twitter.com/nodobtcbot)  𓅪. Este bot esta hecho en Python y tiene las siguientes capacidades:

- Auto generador de Banner con los últimos seguidores.
- Despliega información si es invocado con algunos comandos (fee, hashrate, emisión, blockclock).
- Tuitea estadísticas diariamente.

📂 telegrambot/ -

El nodo tiene una cuenta Bot 🤖 de Telegram: [@onepi_bot](https://t.me/onepi_bot) , tiene las siguientes capacidades:

- Facilita la gestión del operador del nodo.
- Herramienta para verificar archivos `.ots`
- Herramienta para solicitar información de algun bloque o transacción para verificar las confirmaciones sin dar datos personales.

  ⚠️ Telegram no almacena el IP y con la configuración de privacidad adecuada no deja rastros de otros datos como nombres. El proyecto no almacena ni recopila datos (más que estadisticas de uso).

📂 BitcoinResearch/ -
Al disponer de un nodo sincronizado y actualizado en cada bloque se proponen realizar análisis de datos y obtener métricas. Para obtener la data habilitamos un API en el nodo accesible mediante comandos RPC (Remote Procedure Call) para bitcoin-cli y usando Python realizar análisis de cadena como:

- Análisis de transacciones: estudio de las transacciones realizadas en la red Bitcoin, como el volumen de transacciones, el valor transferido, los principales participantes, etc.
- Análisis de minería: estudio de la actividad minera en la red Bitcoin, como la distribución de potencia de hash, la competencia entre mineros, etc.
- Análisis de direcciones: estudio de las direcciones Bitcoin, como el número de direcciones activas, el saldo total, el número de transacciones, etc.
- Análisis de patrones de uso: estudio de la utilización de Bitcoin, como el tipo de transacciones que se realizan, el uso de las direcciones, etc.
