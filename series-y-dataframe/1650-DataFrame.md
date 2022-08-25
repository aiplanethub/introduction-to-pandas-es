# Learning Objectives
* ¿Qué es un DataFrame?
* Crear un DataFrame

# ¿Qué es un DataFrame?
* Es una tabla bidimensional
* Compuesta por una colección de series
* Estructurado con ejes etiquetados (filas y columnas)

Un DataFrame luce como la tabla que se muestra a continuación:
![image_ebaddd603f8d4917abf0f77bbc358eeb.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_ebaddd603f8d4917abf0f77bbc358eeb_a0748e6f993a495ea5f7efd30a7e2b3c.png)

# Crear un DataFrame
*  Puede crear un DataFrame usando una lista de Python o un arreglo de NumPy:
![image_7365e26062974270be514dc0d7a0963f.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_7365e26062974270be514dc0d7a0963f_50fe628d15b845a69be48e43365332e3.png)
---
#### Esta es una lista de Python. También puede usar un arreglo de Numpy.
#### Tiene índices de filas y columnas por defecto
---

* Ejercicio: Trate de crear un DataFrame usando un arreglo de NumPy.
* Si no le gusta que sus índices comiencen de 0, puede otorgar sus propios índices para columnas y filas:
[![image_cbcd08ba73904b2d882dea2d06283a31.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_cbcd08ba73904b2d882dea2d06283a31_6123875dd7e34f378c4251d2829c14c6.png)]()
---
#### Puede otorgar sus propios nombres/índices para columnas y filas
---
* Puede crear un DataFrame usando un diccionario :

![image_1064cc0cabc74eb985e5d95c7be8c6a0.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_1064cc0cabc74eb985e5d95c7be8c6a0_c036d61b84674611b78b908a1499f321.png)
---
#### Una llave del diccionario es una columna del DataFrame. Los valores asociados a la llave son los valores de esa columna en el DataFrame
---

# Una columna es una serie
* Un DataFrame es una colección de series
* Una serie es una columna en una tabla o un DataFrame
![image_c26c3dfa04f1419d83d73bbb22a8a446.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_c26c3dfa04f1419d83d73bbb22a8a446_d0409c17db7e4b8f8c1f13e469022295.png)
---
#### Una columna de un DataFrame es una serie
---
* Hay 3 series en el DataFrame anterior: 'Regd. No', 'Names' and 'Marks%'