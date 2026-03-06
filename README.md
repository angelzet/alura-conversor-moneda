# alura-conversor-moneda
Practica de converso de moneda usando una API del curso Alura

## CONVERSOR DE MONEDA

Este es un conversor de moneda del curso Alura Latam

## USO DE LA API ExchangeRate-API

 . Esta API contiene todos los tipos de moneda actualizados
 . Su uso es mediante el tipo de moneda con tres caracteres:
    Ejemplo: USD para dolar estado unidense y MXN para peso mexicano.

## EL PROYCETO CONTIENE DOS CLASES

1.- CLASE CONVERSOR:
    - Contiene la función o metodo que servirá para solicitar los codigos del país y la cantidad dentro de sus parametros, para poder usar esta API es necesario conectar el modulo Gson para poder leer la cantidad que contiene cada codigo.
2.- CLASE MENU:
    - Básicamente es el menú principal que incluye los ejemplos vistos en la demostración del challenge así como una opción que permite ponder el codigo de tres digitos de cualquier país y la cantidad y hace la conversión usando la clase anterior.