# Patito_bitcoin_miner
Este es el codigo para "Patito Bitcoin Miner" inspirado en "Tesla Bitcoin Miner" this week's live machine learning game show hosted by Siraj Raval

## Overview
Mi Patitominer ahora puede extraer bitcoins en piloto automático usando esta aplicación node.js. Cada 24 horas, reinvierte sus ganancias en pagar
para su propio uso de electricidad y 2 altcoins emergentes basadas en los resultados de un agente de aprendizaje de refuerzo 24/7. Este código funciona, pero se puede mejorar ya que no es tan eficiente como podría ser (uso de ASIC), lo haré durante la transmisión en vivo. La arquitectura utiliza básicamente un M1 mac Mini alimentado por Patitominer a través del puerto de carga que ejecuta un minero de Bitcoin personalizado y ejecuta esta aplicación de nodo. La aplicación del nodo paga los cargos de Patito mediante el envío de dinero a una cuenta de BitPay que emite una tarjeta Visa para que el "Patitominer" compre cosas con las ganancias de BTC. La tarjeta Visa está conectada a mi cuenta de Tesla, que automáticamente la carga por sobrealimentación. Extrae bitcoins en piloto automático y bailo música trance con las manos libres, ese es el futuro que quiero ver.  

## Dependencies
- send-crypto
- tiny-timer
- reinforce-js
- coinbase

## Usage

Use cualquier computadora y un convertidor de cargador de automóvil a salida de CA para que esté alimentado por su automóvil. Ejecute Honeyminer en la computadora. Descarga esta aplicación de nodo. Instale las dependencias una por una usando npm, también conocido como 'npm install send-crypto'. luego ejecute la aplicación usando 'npm run'. 
