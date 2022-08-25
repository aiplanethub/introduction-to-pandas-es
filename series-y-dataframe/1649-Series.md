# Objetivos de aprendizaje
* ¿Qué es una serie?
* Crear una serie
# Objetos de Pandas
Antes de profundizar en las series, vamos a hacer una rápida recapitulación de los 'objetos' de pandas. En la biblioteca de pandas, hay dos estructuras fundamentales de datos/objetos :
* Series
* DataFrame

# ¿Qué es una serie?
* Es un arreglo unidimensional etiquetado 
* Puede contener datos de cualquier tipo
* Es como una columna en una tabla

# ¿Qué puede tener una serie?
* Una serie puede tener solo números:
![image_d0cedac8c4d14c8c9655af50c4da5baa-2.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_d0cedac8c4d14c8c9655af50c4da5baa-2_a0072d7870bc490dafc65f70438e1b48.png)
---
#### Series de números: Tipo de datos es *integer*
---

* Una serie puede tener solo cadenas de caracteres:
![image_fdc09c325d12430db04f51d5184055eb-2.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_fdc09c325d12430db04f51d5184055eb-2_f7bdd616c4f248f49c9dd48e8e8dc684.png)
---
#### Series de cadena de caracteres: Tipo de datos es *object*
---

* Una serie puede tener tanto números como cadenas.
* Pero el tipo de datos de la serie es siempre 'objeto' en este caso:
![image_c009b262e19442bcba27b0443b9df483.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_c009b262e19442bcba27b0443b9df483_f94eb32b05d146b9bd6e1be6e1615299.png)
---
#### Series con números y cadenas de caracteres: Tipo de datos es *object*
---

* Las series son como una lista en Python que puede tomar cualquier tipo de valor como enteros, cadenas de caracteres, números flotantes (o valores decimales), etc.
* Todos los elementos de la serie están etiquetados con índices:
![image_93dd761ed388443fbf91ccb17b94fecb.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_93dd761ed388443fbf91ccb17b94fecb_df795cf1666e4c08bf9aeda560e4c2ba.png)
**Por defecto, la indexación comienza en 0 en las series.**
---
#### Series e índices
---


# Indices humanos vs. Indices en Python
* Indices que nosotros (humanos) entendemos:
![image_7f29921bb6fe4d89805e73bde9c929ba.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_7f29921bb6fe4d89805e73bde9c929ba_c90aa3b8e3b7433faab91db5a23a3175.png)
---
#### Indices de columnas y filas para nosotros
---
* Indices que Python entiende:
![image_1e0299f3ee16440597df44913e70aba8.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_1e0299f3ee16440597df44913e70aba8_7f22742e0ee64f86879aa52c9830efeb.png)
---
#### Indices de columnas y filas para Python
---

**La única diferencia es que para Python los índices de columnas y filas comienzan en 0**

# Crear una serie
* ¡Recuerde importar la librería antes de usarla!

```
import pandas as pd
```

* Puede crear su propia serie usando una lista en Python:
![image_b065378a1c3b4c20990cb7a4fc825d2b.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_b065378a1c3b4c20990cb7a4fc825d2b_6c2ad3bb843a4da4bc69f09b4b2fad28.png)
---
#### La indexación por defecto parte en 0
---

* También puede crear su propia serie usando un diccionario: 
![image_937099e6513a4788ae90cbaf8c6bb80d.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_937099e6513a4788ae90cbaf8c6bb80d_cc3f49ca79fa4a68b6a0b9d1bb1d65da.png)