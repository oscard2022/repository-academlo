## ✍🏻 Práctica en equipo: Mejorando la estructura de HTML y Control de Versiones

En esta práctica en equipo, ampliaremos la práctica anterior para incluir el uso de etiquetas adicionales en HTML, como imágenes, listas y estilos de texto. Además, aprenderemos a utilizar Git y GitHub para establecer un control de versiones y subir nuestro proyecto a un repositorio remoto.

### 📌 Instrucciones:
Sigue los pasos a continuación para completar la práctica:

1. Abre el archivo `index.html` que creaste en la práctica anterior en tu editor de código.
2. Dentro de cada sección de integrante, agrega una etiqueta `<img>` para incluir una imagen relacionada con cada integrante. Asegúrate de proporcionar el atributo src con la URL o ruta de la imagen.
3. Añade una lista desordenada `<ul>` dentro de cada sección para resaltar los logros o habilidades de cada integrante. Añade al menos 3 elementos de lista `<li>` dentro de cada lista.
4. Utiliza las etiquetas `<strong>` y `<em>` para resaltar texto en negrita y cursiva, respectivamente.

```html
...
<section id="integrante1">
    <h2>Integrante 1</h2>
    <p>Descripción del integrante 1.</p>
    <img src="ruta/a/la/imagen1.jpg" alt="Imagen del integrante 1">
    <ul>
        <li><strong>Logro 1:</strong> Descripción del logro 1.</li>
        <li><strong>Logro 2:</strong> Descripción del logro 2.</li>
        <li><strong>Logro 3:</strong> Descripción del logro 3.</li>
    </ul>
</section>
...
```

---

### 📌 Parte 2: Trabajando con un sistema de control de versiones (Git)

1. Abre una terminal o línea de comandos en la carpeta de tu proyecto.
2. Inicializa un repositorio de Git en tu proyecto con el comando `git init`.
3. Agrega todos los archivos de tu proyecto al área de preparación con el comando `git add .`.
4. Crea un commit con los cambios realizados con el comando `git commit -m "Agregando imágenes, listas y estilos de texto"`.

---

### 📌 Parte 3: Creación de repositorio remoto en GitHub y subida del proyecto

1. Crea un repositorio remoto en GitHub con el nombre "practica-html-semantica".
2. Sigue las instrucciones proporcionadas por GitHub para agregar un repositorio remoto. El comando será similar a: `git remote add origin https://github.com/tu-usuario/practica-html-semantica.git`.
3. Sube los cambios y el proyecto completo a GitHub ejecutando el siguiente comando: `git push -u origin main`.
4. Ingresa tus credenciales de GitHub cuando se te solicite.

¡Felicidades! Has mejorado la estructura de tu documento HTML agregando etiquetas adicionales y has aprendido a utilizar Git y GitHub para controlar y subir tu proyecto a un repositorio remoto. Trabajar con un sistema de control de versiones como Git es importante para mantener un historial de cambios, colaborar en equipo y facilitar la gestión del proyecto a lo largo del tiempo.