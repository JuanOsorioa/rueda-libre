## 1. Información de las solicitudes HTTP

| Status | Method | Domain | File |
|---|---|---|---|
| 304 | GET | 127.0.0.1 | index.html |
| 101 | GET | 127.0.0.1 | ws |
| 404 | GET | 127.0.0.1 | favicon.ico |

| Propiedad | Valor |
|---|---|
| Path | /rueda-libre/index.html |
| URL | http://127.0.0.1:5500/rueda-libre/index.html |
| Protocol | HTTP/1.1 |
| Port | 5500 |

## 2. Código de estado HTTP 404

| Código | Significado |
|---|---|
| 404 | Significa que la ruta solicitada por el cliente no fue encontrada en el servidor. |

## 3. Lenguajes de desarrollo web

| Lenguaje | Función | Ejemplo |
|---|---|---|
| HTML | Cumplirá el rol de contenido principal de la página, como su texto o imágenes. | En los párrafos, las tablas, los videos y las imágenes se colocan por medio del lenguaje HTML. |
| CSS | Cumplirá el rol de ser el lenguaje por el cual se puede agregar estilo a los contenidos agregados previamente. | Por medio de CSS agregaré color, modificaré formas y cambiaré el tipo de letra en mi página web. |
| JavaScript | Es el lenguaje de programación que permite agregar lógica y funcionalidad a la página. | Puedo crear la lógica del funcionamiento de un buscador de bicicletas. |

## 4. Estructura del repositorio

| Archivo o carpeta | Descripción |
|---|---|
| rueda-libre | Repositorio |
| index.html | Página principal |
| bitacora.texto | Archivo de bitácora |
| img | Carpeta de imágenes |
| ├── Dropped Image(2).png | Imagen |
| ├── Dropped Image(3).png | Imagen |
| └── Dropped Image.png | Imagen |
| paginas | Carpeta con las páginas del sitio |
| ├── reservas.html | Página de reservas |
| └── tarifas.txt | Archivo de tarifas |

## 5. Elecciones para los tipos de datos del formulario

| Elemento | Justificación |
|---|---|
| `<option>` | Lo seleccioné porque solo aparece una opción a la vez una vez se ha seleccionado, lo que evita posibles equivocaciones por parte del usuario al momento de llenar el formulario. |
| `type="checkbox"` | Es estándar al momento de aceptar términos y condiciones de servicios. |
| `type="email"` | Evita que el usuario envíe un texto que no contenga @ y .com. |

# Semana 2

## Día 1

### 1. Comportamiento responsive

Cuando estrecho la ventana del navegador, los elementos que están dentro del footer y del header se amontonan uno encima del otro gracias a la propiedad `flex-wrap: wrap`.

### 2. Distribución de columnas según el ancho de pantalla

| Resolución | Número de columnas |
|---|---|
| 1280px | 4 columnas |
| 900px | 3 columnas |
| 500px | 1 columna |

### 3. Implementación de Grid y Flexbox

| Sección | Tecnología utilizada | Justificación |
|---|---|---|
| Portada | Grid | Es óptimo al momento de dividir una sección en dos partes iguales. |
| Galería | Flexbox | Permite mantener el formato tipo galería y también hacer wrap. |
| Reservas | Grid y Flexbox | Grid para el contenido general del formulario y Flexbox para determinar las filas del formulario. |
| Encabezado | Flexbox | Permite asegurar el amontonamiento de los elementos en pantallas pequeñas. |
| Pie de página | Flexbox | Permite asegurar el amontonamiento de los elementos en pantallas pequeñas. |

## Día 2

### 1. Uso de Bootstrap

| Aspecto | Descripción |
|---|---|
| Tiempo invertido | 15 minutos |
| Líneas de CSS en la distribución de flota (versión actual) | 0 |
| Líneas de CSS en la distribución de flota (versión anterior) | 17 |

**Reflexión:**

Bootstrap es una herramienta que me permite desarrollar de forma responsive de manera fácil y rápida. A veces no conozco ciertas palabras clave en el framework; sin embargo, abordo esta dificultad consultando activamente la documentación.

### 2. Clases de Bootstrap descubiertas

| Clase | Función |
|---|---|
| `.mark` | Permite agregar resaltador a un texto o a una columna en concreto. |
| `.mb` | Da margen inferior a una fila. |
| `.d-none` | Oculta un elemento en un responsive determinado. |
| `.display-5` | Permite agregar tamaño e importancia a un texto sin alterar su etiqueta original en HTML. |
| `.list-inline-item` | Agrega las viñetas o puntos en una lista HTML. |

# Semana 3

## Día 1

### 1. En la semana número 2 construí un botón copiandolo y pegandolo desde los componentes predeterminados de la documentación en Boostrap, sin embargo esta semana creé mi propio botón a partir de las utilidades de Tailwind:
* rounded
* border border-solid
Un framework de componentes te entrega partes pre-diseñadas de componentes de la página web, mientras que un framework de utilidades, te da las herramientas para diseñar las partes de los componentes que el desarrollador construye por si mismo.

### 2. 
Una clase que uso:
 .font-serif {
    font-family: var(--font-serif);

Una clase que NO uso:
.text-gray-700 {
    color: var(--color-gray-700);
  }

Encontré una clase que probablemente se agregó de forma automatica al escribir algo como h1 en html