---
layout: post
title:  "Marco teórico"
date:   2019-05-19 16:20:00 -0500
categories: jekyll update
---

Hola compañeros,

En este post realizaremos un análisis del proyecto de investigación. En este post
hablaremos de los antecedentes históricos y de las bases matemáticas en las cuales
se rige la teoría del __Perceptrón__.

## Antecedentes históricos

En un principio el *perceptron* se clasificó como un __modelo cerebral__. Este modelo
busca explicar el funcionamiento *psicológico y fisiológico* del cerebro por medio
de modelos matemáticos y el conocimiento que se tiene en neurociencias (@rosenblatt).  

El modelo del *perceptron* en la actualidad es utilizado para *clasificar* espacios
dimensionales lineale y no-lineales. Aunque el mismo autor mencionó que no solo
sirve como modelo clasificador, si no también para poder simular el funcionamiento
del cerebro humano (@rosenblatt). Esta premisa es constantemente cuestionada por
ámbito científico, ya que en la actualidad estamos muy lejos de saber como es que
funciona el ser humano.

## El modelo matemático primera parte

Un *perceptrón* está conformado por 3 capas, las cuales pueden ser aumentadas para
generar mejores resultados, las teorías modernas del aprendizaje profundo (Deep learning)
respaldan esta afirmación.

En este post nos centraremos en la estructura básica de un perceptrón.

### Capas de un percetrón

La primera capa está constituida por las *entradas*, estas son representadas por
un vector de una dimensión. En la imagen siguiente podemos observar una representación
gráfica de un perceptrón. La primera capa es la que describimos como las *entradas*.

![Perceptrón](https://raw.githubusercontent.com/CICJoshua/poperagnarok/master/Images/unidad2/perceptron.png)

En la segunda capa está la parte lógica del perceptrón en esta capa ocurre las
matemáticas. Por cada una de los nodos de entrada, pasan al segundo nodo por medio
del producto punto de los *pesos* y las *entradas*.

## Pesos y bias

Los pesos son la perillas que ajusta el algoritmo del perceptrón para ajustar la
línea que separa el espacio dimensional. Recordemos la ecuación general de la recta:

$$ax+by+c = 0$$

En esta ecuación, los coeficientes *a y b* son los pesos que el algoritmo deberá
modificar para poder clasificar __nuevas entradas__.

El bias es el coeficiente *c* en la ecuación, esta sirve para encontrar en donde
la recta corta el eje *y* en el plano cartesiano. Esto sirve siempre y cuando
los datos estén desplazados del centro del eje cartesiano.
