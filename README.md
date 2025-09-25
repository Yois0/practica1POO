# practica1POO
Este proyecto es un ejemplo de POO en Python usando herencia, encapsulamiento y polimorfismo.

Vehiculo: clase base con marca, velocidad, métodos para acelerar, frenar, mostrar datos y consumo de combustible.
Coche: hereda de Vehiculo, agrega número de puertas y límite de velocidad de 120 km/h.
Moto: hereda de Vehiculo, incluye tipo de casco recomendado, límite de 150 km/h y un método extra (caballito).
Camion: hereda de Vehiculo, añade capacidad de carga en toneladas y límite de 90 km/h.
Cada clase redefine mostrar_datos() y consumo_combustible() para comportarse distinto.
En el bloque __main__ se crean objetos de cada clase para probar su funcionamiento.
