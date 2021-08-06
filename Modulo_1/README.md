# Modulo 1: Introducción 

## 01.- Instalación de Visual Studio Code
Paso no realizado dado que estaba previamente en mi PC.

## 02.- Instalación de Node.JS
En mi equipo esta instalada la versión 12.18.3, suficiente para realizar este bootcamp, por lo que mantengo dicha versión.

## 03.- Instalación de lite-server

Validamos que npme esta instalado: npm --version     =>  6.14.16
Instalamo paquete:  npm i -g lite-server

Al crear el ejercicio validamos que la instalación se ha realizado correctamente.
Por un conflicto con la asignación de mi host, el servidor no funciona en localhost:3000, tal y conmo se abre la ventana, pero funciona sin problemas como 127.0.0.1:3000. Lo dejo estar.

## 04.- Interacción con el DOM / JavaScript

### 04.1.- Crear una estructura básica de HTML.

Desde dentro de VS Code creamos un nuevo fichero HTML ./index.html
Agregamos una estructura HTML básica (recordad, escribimos html:5 y presionamos intro).

./index.html

'''html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Datos de usuario</title>
  </head>

  <body></body>
</html>

'''

Agregamos los contenedores genéricos para estructurar nuestra página.
./index.html

```html 

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Datos de usuario</title>
  </head>

  <body>
    <!-- diff -->
    <div class="container">
      <div class="img"></div>
      <div class="data"></div>
    </div>
    <!-- diff -->
  </body>
</html>
```

Ahora vamos a crear dos cajas de texto con etiquetas para rellenarlas.
./index.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Datos de usuario</title>
  </head>

  <body>
    <div class="container">
      <div class="img"></div>
      <div class="data">
        <!-- diff -->
        <label for="name"><b>Name</b></label>
        <input type="text" id="name" name="name" />

        <label for="lastName"><b>Last name</b></label>
        <input type="text" id="lastName" name="lastName" />
        <!-- diff -->
      </div>
    </div>
  </body>
</html>

```



### 04.2.- 