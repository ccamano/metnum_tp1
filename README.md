# Métodos Numéricos - Trabajo Práctico Nº1
## "Trabajamos y nos divertimos..."

Este trabajo práctico consisten en implementar un programa que calcule la isoterma solicitada de un [alto horno](https://es.wikipedia.org/wiki/Alto_horno), conociendo las dimensiones del horno y las mediciones de temperatura en la pared exterior.

Los archivos adjuntos de este TP constituyen :

- Código realizado en C++ para la resolución del problema propuesto
- Archivo Makefile para la creación de 1 ejecutable
- Notebook realizado en Python para la creación de 3 datasets distinguidos
- Notebook realizado en Python para el cómputo de 3 experimentos con distintos fines
- Notebook realizado en Python para ploteo de gráficos para cada experimento

donde la estructura de los mismos es :

```
TP
├─README.md 
├─.gitignore 
├─src 
│  ├─Makefile 
│  ├─main.cpp 
│  ├─auxiliares.h 
│  ├─auxiliares.cpp 
│  ├─algoritmos.h 
│  └─algoritmos.cpp 
| 
└─python 
   ├─generar-instancias.ipynb 
   ├─experimentos.ipynb 
   └─analisis.ipynb 
```

## Uso

Para resolver el problema es necesario compilar los archivos fuentes que se encuentran en la carpeta `src`, corriendo simplemente el siguiente comando por con sola en la misma carpeta
```
make

```

Luego de ello, ya es posible resolver una instancia (`input_file`) del problema pasandole la misma al ejecutable en formato de texto plano, indicando un archivo de salida para guardar el resultado del cómpu (`output_file`) también como texto plano, y especificando un algoritmo a utilizar, los mismo son:

- `0` : `Gauss`
- `1` : `LU`

Esto se puede realizar con el siguiente commando por consola donde se ubica el ejecutable:
```
./ejecutable input_file output_file 0

```
(en el ejemplo de arriba, se está ejecutando el algoritmo de `Gauss`)

## Experimentación

Si se desea replicar la experimentación conllevada para el informe, se recomienda tener instalado [Jupyter Lab o Jupyter Notebook](https://jupyter.org/).

Con ello, es posible abrir los notebooks de python y replicar el proceso.
















