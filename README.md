# ai-session-01 [Readme v0.1]
Repositorio del material utilizado en el evento AI Session 01: Machine Learning

## TODO List 

Aceptamos colaboraciones! o denme más tiempo. Cualquier comentario es bienvenido.
- [ ] Mejorar el Readme.md
- [ ] Instructivo para windows
- [ ] Explicar sobre Anaconda
- [ ] Explicar sobre environments en python
- [ ] Explicar sobre Jupyter Notebooks

## Comenzando...

Las siguientes instrucciones son para que puedan correr el proyecto en sus computadoras tanto para desarrollo, prueba y modificaciones del contenido presentado durante la charla. 

### Prerrequisitos

Antes de comenzar es necesario tener instalado Miniconda con Python 3.6. Miniconda (Anaconda) es un gestor de paquetes y environments de Python. Se puede descargar desde el siguiente link https://conda.io/miniconda.html

### Instalación

Paso a paso el proceso de instalación una vez cumplidos los prerrequisitos. Durante el siguiente instructivo vamos a suponer que nos encontramos parados en la carpeta del sistema "~/Documents"

``` sh
$ cd ~/Documents
# clonamos el repo
$ git clone https://github.com/DevC-Cordoba/ai-session-01
$ cd ai-session-01/setup
# corremos el script con el cual se descargan las dependencias necesarias 
# y crea el environment ai-session-01
# PUEDE TARDAR VARIOS MINUTOS, SEAN PACIENTES
$ sh setup.sh
```
Si todo termina con éxito ya estarán listos para trabajar con las jupyter notebooks. Para chequear la correcta instalación ejecuten el siguiente comando para activar el environment ai-session-01
```sh
$ source activate ai-session-01
```
Deberían ver en los comandos delante de todo lo siguiente -> (ai-session-01) 

## Ejecutando la presentación (Jupyter Notebook)

Para poder ejecutar la presentación en Jupyter Notebook deberan tener el environment activado, si no ven lo siguiente en su terminal (ai-session-01) entonces ejecuten 
```sh
$ source activate ai-session-01
```
Luego, teniendo en cuenta que están en la carpeta "~/Documents/ai-session-01" ejecuten el siguiente comando
```sh
$ jupyter notebook
```
Esto les abrirá un browser con la siguiente url http://localhost:8888/tree
Para desactivar el environment ejecuten
```sh
$ source deactivate ai-session-01
```

## Utilizando Jupyter Notebook

Aca hay un instructivo https://live.osgeo.org/es/quickstart/jupyter_quickstart.html
Les recomiendo ir ejecutando celda por celda, Jupyter Notebook tiene un intérprete entonces se van cargando las variables a medida que vas ejecutando el código

## Built With

* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Searborn](https://seaborn.pydata.org/)
* [Numpy](http://www.numpy.org/)
* [Scikit-learn](http://scikit-learn.org)

## Autores

* **Joaquín Barotto** - Speaker - [JoacoIB](https://github.com/JoacoIB)
* **Daniel Bridera** - Speaker - [danielstaff](https://github.com/danielstaff)
* **Emanuel Lupi** - Speaker - [WaVEV](https://github.com/WaVEV)
