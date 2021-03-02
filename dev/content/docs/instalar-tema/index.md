---
title: 'Instalar Tema'
date: 2020-06-17T19:30:08+10:00
draft: false
weight: 2
summary: Tutorial de intalación del tema utilizando el Framework Hugo.
---

<!-- Contenido del Post -->

## Crear un nuevo sitio Hugo

Comando a utilizar para la creación de un nuevo sitio, utilizando la terminal de comandos.

```
hugo new site misitio
```

Esto creará un nuevo sitio de Hugo en una carpeta con nombre `misitio`, este paso será necesario realizarlo sólo una vez, ya que este proceso automatizado genera una serie de archivos y carpetas que son la base del sitio web desarrollado con Hugo. 

## Instalar un template de Hugo

Copie o clone la carpeta del template del sitio en la carpeta `misitio/themes`.

## Ejecutar Hugo

Para el desarrollo de manera local, ejecute el servidor incorporado con Hugo utilizando la terminal de comandos.

```
hugo server
```

Ahora ingrese a [`localhost:1313`](http://localhost:1313) en la barra de URL de su navegador.

Después de editar el contenido y generar el sitio web, obtenga el compilado de archivos web a través del siguiente comando en la terminal. Este comando generará una carpeta `misitio/public` al interior de la carpeta del sitio web.

```
hugo
```

