<p align="center">
  <a href="https://duoc.cl">
    <img src="img/intro.png" alt="Logo" width=800>
  </a>

  <!-- <h3 align="center">Logo</h3> -->

  <p align="center">
    Este repositorio contiene los archivos y herramientas para ejecutar un entorno de desarrollo para python. Los estudiantes de éste curso pueden instalar esta configuración base en su computador y trabajar con Visual Studio Code
    <br>
    <!-- <a href="https://reponame/issues/new?template=bug.md">Report bug</a>
    ·
    <a href="https://reponame/issues/new?template=feature.md&labels=feature">Request feature</a> -->
  </p>
</p>


## Tabla de contenidos

- [Tabla de contenidos](#tabla-de-contenidos)
- [Prerequisitos](#Prerequisitos)
- [Python](#python)
- [Contenido](#contenido)
- [Librerías](#librerías)
- [Creación y mantención](#creación-y-mantención)
- [Agradecimientos](#agradecimientos)
- [Instalar y ejecutar este entorno de desarrollo](#instalar-y-ejecutar-este-entorno-de-desarrollo)


## Prerequisitos

- La implementación utiliza Docker lo que permite generar un entorno de desarrollo aislado del computador anfitrión. El contenedor generado utiliza como base linux y sobre él se instalan las aplicaciones y librerías necesarias para ejecutar los ejemplos en lenguaje Python que se utilizan en el curso.
- Usted debe tener instaladas, previamente, las siguientes aplicaciones gratuitas:

| Aplicación          | Vínculo de descarga                                                        |
|---------------------|----------------------------------------------------------------------------|
| docker-desktop      | [https://www.docker.com](https://www.docker.com/products/docker-desktop/ ) |
| visual studio code  | [https://code.visualstudio.com](https://code.visualstudio.com/download)    |
| LM Studio           | [https://lmstudio.ai](https://lmstudio.ai)    |
| Git (Windows)       | [https://git-scm.com/download/win](https://git-scm.com/download/win)    |
| Git (Mac)           | [https://git-scm.com/download/mac](https://git-scm.com/download/mac)    |
| Git (Linux)         | `apt-get install git`    |

## Python

El entorno de desarrollo viene con Python 3.10 y el gestionador de paquetes PIP ya instalado.

Si se requiere instalar otras librerías de Python, se debe realizar desde la Terminal. Por ejemplo si se desea instalar la libreria seaborn:

```text
pip install seaborn
```

PIP es el gestionador de paquetes y librerías para Python, se puede acceder a su pagina [www.pypi.org](https://pypi.org/project/pip/)

## Contenido

La estructura base de este repositorio se muestra a continuación:

```text
base_ia_tools
└── .devcontainer
    ├── devcontainer.json
    ├── docker-compose.yml
    ├── Dockerfile
└── Herramientas/
    ├── 1_Ejecutar_Carpeta_en_Contenedor.ipynb
└── img 
    ├── [imagenes usadas algunos archivos .ipynb]
└── otras carpetas...
```

## Librerías

El entorno de programación viene con 162 librerías pre instaladas.

Algunas de las librerías son las siguientes:

```text
- ipykernel
- numpy
- pandas
- matplotlib
- torch 
- torchvision 
- torchaudio 
- openai
- scikit-learn
- tqdm
- nbconvert
```

Para ver el total de librerias ejecute el siguiente comando en el Terminal:

```text
pip list
```

## Instalar y ejecutar este entorno de desarrollo

1. Crear o seleccione una carpeta donde se descargara este repositorio
2. Abrir la terminal sobre la carpeta anterior (click derecho sobre la carpeta: Abrir en Terminal (Win) | Servicios-> New terminal at folder (Mac))
3. Clonar este repositorio en una carpeta local de su computador
   
```text
git clone https://github.com/rsaldias/base_ia_tools_v2
```
   
5. Ingresar a la carpeta base_ia_tools_v2

```text
cd base_ia_tools_v2
```
   
7. Para abrir VSC sobre esta carpeta, ejecutar

```text
code .
```
   
9. Si todo va bien usted debería ver

<p align="center">
    <img src="img/todo_ok.png" alt="Logo" width=400>
</p>

El archivo 1_Ejecutar_Carpeta_en_Contenedor.ipynb contiene las instrucciones iniciales para ejecutar el contenedor.



## Creación y mantención

**Ricardo Saldías F.**

email
- ri.saldias@profesor.duoc.cl
  
github
- <https://github.com/rsaldias>
- <https://github.com/ricardosaldias>

## Agradecimientos

Este curso ha sido posible gracias al apoyo de; Matias Bosshardt (director de la escuela de comunicación de DuocUC), Claudio Palacios (subdirector de la escuela de comunicación de DuocUC), Mauricio Benavente (docente DuocUC) y a los equipos del centro de formación docente y desarrollo curricular, Gracias a Tod@s!



<p align="center">
  <a href="https://duoc.cl">
    <img src="img/logo_duoc.png" alt="Logo" width=600>
  </a>

  <!-- <h3 align="center">Logo</h3> -->

  <p align="center">
    @2024
    <br>
    <!-- <a href="https://reponame/issues/new?template=bug.md">Report bug</a>
    ·
    <a href="https://reponame/issues/new?template=feature.md&labels=feature">Request feature</a> -->
  </p>
</p>


