# **Práctica 1: Web scraping**

## **Descripción**

Esta práctica se ha realizado bajo el contexto de la asignatura *Tipología y ciclo de vida de los datos*, perteneciente al Máster en Ciencia de Datos de la Universitat Oberta de Catalunya. En ella, se aplican técnicas de *web scraping* mediante el lenguaje de programación Python para extraer así datos de:

(1) amazon de UK, USA, ES, AU, NL, DE. Se hace foco en las mascarillas tipo FFP2 y N95.

[www.amazon.co.uk](http://www.amazon.co.uk)

[www.amazon.com](http://www.amazon.co.uk)

[www.amazon.fr](http://www.amazon.fr)

[www.amazon.de](http://www.amazon.de)

[www.amazon.es](http://www.amazon.es)

[www.amazon.it](http://www.amazon.it)

[www.amazon.au](http://www.amazon.au)

[www.amazon.nl](http://www.amazon.nl)

(2) www.worldometers.info/coronavirus/

## **Miembros del equipo**

La actividad ha sido realizada de manera conjunta por:

Héctor Bastidas

Fernando Cachadiña 

## **Ficheros del código fuente**

• **src/proxies.py:** Adquisición de direcciones y puertos de proxies válidos.

• **src/scraper.py:** Implementación de métodos de scrapping como Beautiful Soup y selectores CSS  para la extracción de datos desde las web de Amazon y Worldometers. Se genera un conjunto de datos en bruto para cada web.

• **src/normalization.py:** Implementación de algoritmos para la normalización de los datos extraídos y almacenamiento en una base SQL local.

 

## **Recursos**

1 Lawson, R. (2015). *Web Scraping with Python*. Packt Publishing Ltd. Chapter 2. Scraping the Data.

2 Mitchel, R. (2015). *Web Scraping with Python: Collecting Data from the Modern Web*. O'Reilly Media, Inc. Chapter 1. Your First Web Scraper.

 