# Royal-Flush: Classification Models For A Poker Hands Dataset

![Image text](https://github.com/IC-03/Royal-Flush/blob/main/Imagenes/Banner-GitHub-low_res.jpg)


Proyecto para Inteligencia Artificial I - 2023-2. 

**Autores:** Isabella Callejas Mandon, Geiner Duvan Guevara Vargas

## ♦ Objetivo:

Clasificar manos de póquer según la combinación que presenten las cartas.

**Disclaimer**: Este proyecto no buscar incentivar a los juegos de azar, es con fines experimentales.

## ♦ Resumen:

### ♣ Contexto
En una baraja estándar de póquer tiene cada carta tiene dos atributos:

- Un palo o suit (S): Corazón, Trebol, Diamante, Picas. Representación respectiva [ 1-4 ]

- Un rango (C): Ace (A), 2-10, Jack o Joker (J), Queen (Q), King (K). Representación respectiva [ 1-13 ].

Por lo qué, tenemos 13 cartas por cada palo, es decir, 52 cartas en total.

Para este proyecto tampoco se tiene en cuenta si las cartas tienen un valor, nos interesa que combinación presentan en una **mano**.

Una **mano de poquer** consiste en 5 cartas, existen combinaciones muy específicas que se pueden **clasificar**, en el dataset tenemos las siguientes clases:

[ 0 ] **Nada en mano**: No entra en las otras clasificaciones

[ 1 ] **Un par**: Dos cartas con el misma rango, diferente palo

[ 2 ] **Dos pares**: Dos pares de cartas, los pares son diferentes entre sí

[ 3 ] **Trio**: 3 cartas con el mismo rango, diferente palo

[ 4 ] **Escalera**: Las 5 cartas secuenciales sin importar el palo

[ 5 ] **Flush/ Color/ Flor**: 5 cartas del mismo palo

[ 6 ] **Full House**: Trio + Par

[ 7 ] **Cuarto de un tipo** : 4 cartas de un mismo rango pero diferentes palos.

[ 9 ] **Flor Imperial / Royal Flush**: conformado por las cartas: As, K, Q, J, 10 y son del mismo palo

Nuestro reto es que con los datos que poseemos podamos hacer que la máquina pueda reconocer y clasificar estas combinaciones en cualquier orden.

### ♣ Modelos: 

Métodos usados para su desarrollo. Escribir solo palabras claves.

### ♣ Multimedia:
- Video: [Royal Flush](https://drive.google.com/file/d/1vWnw-nIVrzGQKXAuXR8vOpO1OIiLStyF/view?usp=sharing)
- Diapositivas: [Presentación Royal Flush](https://github.com/IC-03/InTime-UIS/blob/main/InTimeUIS-Presentaci%C3%B3n.pdf)
- Dataset:  [Keel Datasets](https://sci2s.ugr.es/keel/dataset.php?cod=194)

## ♦ Referencias:
