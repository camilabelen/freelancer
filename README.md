# Freelancer

* **Track:** _Common Core_
* **Curso:** _Creando tu primer sitio web interactivo_
* **Unidad:** _Maquetado web con HTML & CSS_

***

Para completar este reto, hemos creado este repositorio boilerplate (plantilla
inicial) con todos los recursos que necesitas. Esto incluye imágenes y
estructura de carpetas y archivos donde colocarás tu código.

## Flujo de trabajo

1. Debes realizar un [**fork**](https://gist.github.com/ivandevp/1de47ae69a5e139a6622d78c882e1f74)
   de este repositorio.

2. Luego deberás **clonar** tu fork en tu máquina. Recuerda que el comando a usar
   es `git clone` y su estructura normalmente se ve así:

   ```bash
   git clone https://github.com/<nombre-de-usuario>/freelancer.git
   ```

## Objetivo

El reto consiste en replicar el sitio de **Freelancer**, este será el resultado
a lograr:

![Freelancer Website](docs/fullpage.png)

## Consideraciones

* Encontrarás un archivo base `index.html` en el cual deberás escribir la
  estructura de tu proyecto y enlazar tus archivos de estilos (CSS).

* En la carpeta `css` tendrás un archivo base `main.css` donde agregarás los
  estilos necesarios para tu proyecto.

* Dentro de la carpeta `assets` se encuentra la carpeta `images` donde
  encontrarás todas las imágenes necesarias para completar tu proyecto.

* Deberás **actualizar el archivo `README.md`** explicando el contenido de tu
  repositorio.

* Esta web utiliza 2 tipografías: `Montserrat` y `Lato`.

* La paleta de colores puedes obtenerla inspeccionado el sitio original, pero
  para ganar tiempo, puedes usar los siguientes: `#2c3e50`, `#18bc9c`,
  `#212529`.

* Los íconos de redes sociales puedes obtenerlos de [Font Awesome](http://fontawesome.io/).

* Para este reto, encontrarás ciertas cosas que probablemente aun no has visto
  en clase (formularios). No te preocupes, estamos seguros que lo afrontarás con
  éxito, de igual forma aquí unos tips:

  - Para el formulario, revisa las etiquetas como `form`, `input`, `button`.

* El subrayado que incluye la estrella en las diversas secciones del sitio, en
  la web original se hace con un ícono y pseudoelementos (`:after`, `:before`),
  es un reto entretenido, sin embargo, no trates de enfocarte en esa parte desde
  un inicio ya que no es el objetivo principal del reto :)

* Puedes ver el [sitio original](https://blackrockdigital.github.io/startbootstrap-freelancer/)
  para que te des una idea de como debe quedar.

  > Nota: El sitio original tiene ciertos efectos y funcionalidades que
están fuera del alcance de este reto. Enfócate en obtener la maquetación
lo más parecido posible, usando lo aprendido en clase ;)

## A tener en cuenta

Este reto será evaluado sobre lo siguiente:

* Pixel perfect (replicar el diseño con exactitud)
* Nombramiento de clases, id, etc
* Indentación
* Archivo `README.md` actualizado y correctamente redactado
* Uso de comentarios para hacer tu código más legible

# Mi repositorio

El repositorio cuenta con el archivo index.html, una carpeta css con main.css, imagenes e iconos.

Para desarrollar el maquetado del tema de Bootstrap "Freelancer" usé la etiqueta _nav_ para definir el menú con posición fija y para las demás secciones de la página usé la etiqueta section y para el pie de página footer.

1. En la etiqueta _nav_ hice uso de las etiquetas _h1_ y _a_ para los botones.

2. La primera _section_ con clase _profile_ contiene una etiqueta _img_ con la imagen, _h2_ y _p_.
  * El icono de la estrella en esta sección como en todas las otras lo hice contenido en un _div_ y cada línea a los lados de la estrella también son un _div_ con un _width_, _height_ y _background-color_.


3. La segunda _section_ con clase _portfolio_ contiene un título _h1_ y seis etiquetas _img_.
  * Estos elementos, tanto como los anteriores y los siguientes fueron modificados en su posición con la propiedad _float_ y su valor _left_.

4. La siguiente _section_ con clase _about_ contiene dos _div_ que a su vez contienen el icono de la estrella y el texto en etiquetas _p_ correspondientemente.

5. La cuarta _section_ con clase _contact_ contiene una etiqueta _h1_ como título y un formulario _form_ que a su vez contiene cinco _div_ cada uno con un _input_, en el caso del área para el mensaje la etiqueta utilizada fue _textarea_.

6. La ultima sección de la página, etiqueta _footer_ contiene un _div_ por cada columna (3 div) y además el _div_ contenedor del _copyright_.