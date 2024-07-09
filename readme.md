# Proyecto de Mesa de Extensión para Máquina de Coser Casera

Este repositorio contiene el proyecto final del curso de Fabricación Digital. Se diseñó una mesa de extensión específicamente para la máquina de coser casera Janome Sakura 95.

Las explicaciones sobre las piezas se basan en el documento `Piezas.pdf`, que muestra el número de pieza de cada parte del diseño.

## Resultado
<img src="img/funcionamiento.jpg" alt="adaptador" width="500">

## Archivos del Proyecto

En el repositorio se encuentran las siguientes carpetas y archivos:

- **origen**
  - **ensamble**
    - `proyecto_final`: archivo del ensamble final que referencia al resto de archivos.
    - **ensamble_cajon**: carpeta que contiene imágenes que muestran cómo se acoplan las piezas del cajón.
  - **fdm**: contiene los archivos de las piezas que se fabricaron con impresión 3D
    - **adaptador pata**: carpeta que contiene los archivos de la pieza número 8
    - **tirador**: carpeta que contiene los archivos de la pieza número 9
  - **img**: carpeta con archivos de imágenes usadas en este documento.
  - **router_cnc**: contiene los archivos de las piezas fabricadas por corte en router CNC
    - **cajon bottom**: carpeta que contiene los archivos de la pieza número 2
    - **cortes**: carpeta que contiene archivos de corte de las piezas del cajón base
    - **frontal**: carpeta que contiene los archivos de la pieza número 4
    - **lado 1**: carpeta que contiene los archivos de la pieza número 1
    - **lado 2**: carpeta que contiene los archivos de la pieza número 6
    - **mesa top**: carpeta que contiene los archivos de la pieza número 7
    - **posterior**: carpeta que contiene los archivos de la pieza número 3
    - **tapa**: carpeta que contiene los archivos de la pieza número 5
- `Piezas.pdf`: archivo que muestra el número y tabla de piezas generada por el software Fusion360.

## Diseño

Se realizó el diseño del proyecto en el software Fusion 360. Los archivos se encuentran ordenados en las carpetas descritas anteriormente.

Se diseñó una mesa a medida de la maquina de coser Janome Sakura 95. El diseño contempla un cajón en la base que permite guardar accesorios de la máquina e implementos de costura.

Se numeran las piezas como sigue:
<img src="/img/piezas_numeradas.png" alt="Tabla de piezas, materiales y procesos" width="500">


## Piezas, Materiales y Procesos de Fabricación

<img src="/img/tabla_de_piezas_materiales_y_procesos.png" alt="Tabla de piezas, materiales y procesos" width="500">

## Ensamble

El ensamble general se encuentra en el archivo de `proyecto_final`.

Paso a paso:
1. Ensamblar la caja base uniendo con cola fría las piezas 1, 2, 3, 4 y 6. Deben calzar las ranuras en los bolsillos. Se adjuntan distintas vistas del proceso.
Vista superior 1.
<img src="/ensamble/ensamble_cajon/union_cajon_vista1.png" alt="Unión de piezas de cajón base. Vista superior 1." width="500">
Vista superior 2.
<img src="/ensamble/ensamble_cajon/union_cajon_vista2.png" alt="Unión de piezas de cajón base. Vista superior 2." width="500">
Vista inferior.
<img src="/ensamble/ensamble_cajon/union_cajon_vista3.png" alt="Unión de piezas de cajón base. Vista inferior." width="500">
2. Unir a la parte superior de la caja base del paso 1 la pieza 7. Se puede pegar solo con cola fría o agregar clavos (en mi caso no fue necesario).
<img src="img/top_pegado.jpg" alt="Pegado de top" width="200">

3. Unir con tornillos de 3x10mm la pieza 9 a la parte inferior de la pieza 5.
El tirador debe ir con el orificio de 2 profundidades hacia arriba, para ahí insertar el tornillo.
<img src="img/posicion_tirador.jpg" alt="Union de tirador" width="200">
Tornillo 3x10mm.
<img src="img/tornillo_usado.jpg" alt="tornillo usado" width="200">
Así queda:
<img src="img/tapa_con_tirador.jpg" alt="tapa" width="200">
4. Unir con tornillos de 3x10mm las piezas 8 a la parte inferior de la pieza 7, siguiendo la distancia del diseño del proyecto. Cortar un cilindro de madera de 30mm de diametro en 3 piezas de largo 6.3mm, para utilizar como pieza 10. Luego insertar estas piezas en cada adaptardor (pieza 8).
Adaptador atornillado:
<img src="img/adaptador_pata.jpg" alt="adaptador" width="200">
Agragar pieza 10:
<img src="img/posicion_adaptador_y_patas.jpg" alt="adaptador" width="200">
5. Deslizar la pieza 9 con la pieza 5 hacia abajo por las ranuras del cajon base armado en el paso 1.
<img src="img/tapa_corredera.jpg" alt="tapa" width="200">
<img src="img/acople_de_tapa_en_caja_base.jpg" alt="acople" width="200">

6. Lijar toda la pieza con lija de madera hasta que la superficie sea suave, para no enganchar la tela.
7. Opcional: agregar bases de goma antideslizantes.
<img src="img/antideslizante.jpg" alt="Gomas antideslizante" width="200">
Patas:
<img src="img/detalle_pata.jpg" alt="Gomas antideslizante" width="200">
Cajón vista inferior:
<img src="img/detalle_tapa_y_tirador_vista_inferior.jpg" alt="Gomas antideslizante" width="200">


## Material Extra

En la carpeta img se adjuntan imágenes del proceso incluyendo las que se encuentran en este archivo.

