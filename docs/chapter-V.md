# Capítulo V: Product Implementation, Validation & Deployment.

## 5.1. Software Configuration Management.
En este punto del informe se describe las decisiones y los principios que ayudarán al 
equipo a garantizar la coherencia durante el desarrollo de la solución.

### 5.1.1. Software Development Environment Configuration.
En este apartado se proporcionan los enlaces a las aplicaciones y productos de 
software creados durante el ciclo del proyecto utilizando los programas correspondientes.

Con ese fin, se organizará en las siguientes secciones:
1. [ ] Project Management
2. [ ] Requirements Management
3. [ ] Product UX/UI Design
4. [ ] Software Development
5. [ ] Software Testing
6. [ ] Software Documentation

Asimismo, se clasificarán los elementos de estas secciones como rutas de referencia 
(para software basado en modelos Saas) o rutas de descarga (para productos que se 
ejecuten en las computadoras de los miembros del equipo) para cada uno de los productos 
de software.

**Project Management**

Esta disciplina se fundamenta en la administración de proyectos y busca principalmente la 
mejora de procesos y su entorno con el propósito de lograr los resultados esperados.

* Durante el ciclo digital del proyecto, se llevará a cabo la implementación de un producto 
de software basado en el modelo SaaS, el cual funcionará a través de un navegador web; no 
obstante, no se desarrollará una versión de la aplicación móvil correspondiente.

**Requirements Management:**

Este proceso se enfoca en asegurar que una organización documente, verifique y satisfaga las 
necesidades y expectativas de sus clientes, así como las de las partes interesadas internas 
o externas.


* **Jira Software:** Esta es una plataforma que facilita la gestión de historias de usuario, 
organizándolas en epopeyas y evaluando su importancia en el programa según su prioridad y puntos 
de historia. Se utiliza debido a su capacidad para permitir que cada miembro del equipo tenga una 
vista en tiempo real de los avances en cada proyecto, contribuyendo con diferentes secciones o 
ajustando el flujo del proyecto según sea necesario.

**Product UX/UI Design**

Esta herramienta facilita la creación digital de modelos que se integran en la vida del consumidor. 
En este caso, estamos desarrollando un modelo de sitio web compatible tanto con computadoras como 
con dispositivos móviles.

Para lograrlo, utilizamos varias herramientas de diseño y colaboración, que incluyen:

1. **Uxpressia:** Uxpressia es una plataforma en línea especializada en el mapeo de la trayectoria del
cliente. Nos ayuda a crear mapas de impacto y perfiles de usuario, como User Personas, Empathy Maps 
y Journey Maps. Puedes encontrar más información sobre Uxpressia en este [enlace](https://uxpressia.com/).

2. **MIRO:** MIRO es una pizarra digital colaborativa en línea que se adapta a diversas actividades 
colaborativas, como investigación, ideación, creación de lluvias de ideas y mapas mentales. Es una 
herramienta versátil que facilita el trabajo en equipo. Descubre más sobre MIRO en su 
[sitio web](https://miro.com/es/).

3. **Figma:** Figma es una herramienta de prototipado web y un editor de gráficos vectoriales. A 
diferencia de otras herramientas, Figma se ejecuta en línea, lo que permite crear modelos que 
funcionan tanto en navegadores web como en navegadores móviles. Puedes explorar 
Figma en [este enlace](https://www.figma.com/es-es/).

4. **Lucid Chart:** Esta es una aplicación de diagramación en línea que permite a los usuarios colaborar y
trabajar juntos en tiempo real para crear una variedad de diseños, incluidos diagramas UML, mapas 
mentales, prototipos de software y otros tipos de diagramas. Puedes conocer más acerca de Lucid Chart 
en [este enlace](https://www.lucidchart.com/pages/es).

5. **Overflow:** Overflow es una herramienta de diagramación que ofrece la posibilidad de colaborar en 
tiempo real. Utilizamos esta herramienta para crear diagramas de Userflows. Si deseas obtener más 
información sobre Overflow, visita su [sitio web](https://overflow.io/).

Estas herramientas nos ayudan a dar vida a nuestros diseños digitales y a garantizar que nuestros 
productos sean accesibles y atractivos en diferentes plataformas.


**Software Development:**

El desarrollo de software es una metodología aplicada en la creación de productos de software. Esta 
metodología se utiliza para establecer un proceso que guía el desarrollo del software, y cada uno de
sus pasos describe un enfoque específico para las distintas actividades que ocurren durante el proceso.

Aquí te presentamos algunas herramientas y tecnologías clave que utilizaremos en el proyecto:

1. **GitHub:** GitHub es una plataforma de repositorio comunitario que se utiliza para almacenar y 
gestionar los avances de proyectos realizados por grupos de personas. Puedes acceder al repositorio 
del proyecto en este [enlace](https://github.com/4424-Corebyte-App-Web).

2. **Webstorm:** Webstorm es un entorno de desarrollo de JetBrains, una empresa especializada en software, 
orientado al desarrollo web en JavaScript. Esta herramienta proporciona facilidades para probar 
sitios web en navegadores como Google Chrome. En nuestro proyecto, utilizaremos webstorm para 
trabajar con lenguajes como HTML, CSS y JavaScript. Obtén más información sobre WebStorm [aquí](https://www.jetbrains.com/webstorm/).

3. **HTML:** HTML es un lenguaje de marcado que se utiliza en el desarrollo de sitios web para crear
hipertextos y enlazar a otros documentos. Este lenguaje proporciona herramientas para diseñar 
sitios web y se puede combinar eficazmente con CSS y JavaScript. En nuestro proyecto, utilizaremos 
HTML para implementar la documentación de la página web. Obtén más información sobre la edición de
archivos HTML en WebStorm [aquí](https://www.jetbrains.com/help/idea/editing-html-files.html).

4. **CSS:** CSS es un lenguaje de diseño destinado al entorno web, que posibilita la mejora de la interfaz
de usuario previamente diseñada al añadir elementos como colores y tamaños, entre otros. Además, 
es posible crear un estilo en CSS y compartirlo en el sitio web creado en HTML. Este lenguaje será 
empleado en la implementación del diseño de nuestra plataforma web. Puedes obtener más información 
sobre CSS en [enlace](https://www.jetbrains.com/help/idea/style-sheets.html).

5. **JavaScript:** Es un lenguaje de programación que es interpretado por otros programas. Funciona bajo 
el paradigma de programación orientada a objetos (POO), utilizando prototipos en lugar de clases 
para la implementación. Este lenguaje permite crear dinámicas para los usuarios a través de la 
lógica de programación y será utilizado en la creación de las interacciones dinámicas en la plataforma 
web. Puedes encontrar más detalles sobre JavaScript en [enlace](https://www.jetbrains.com/help/idea/style-sheets.html).

Estas herramientas y tecnologías desempeñarán un papel fundamental en la creación exitosa de nuestro 
producto de software.

**Software Testing:**

Se trata de la acción de evaluar los elementos y el funcionamiento del software sometido a prueba 
mediante procesos de validación y verificación.

**Lenguaje Gherkin:** Este lenguaje, conocido como DSL (Lenguaje Específico de Dominio), está diseñado 
específicamente para abordar problemas particulares. Además de poder ser interpretado en código,
permite agregar historias de usuario del programa junto con sus componentes correspondientes, como 
Característica, Escenario, Ejemplo, Esquema de Escenario, Dado, Cuando, Entonces y Y.

**Software Documentation**

Se refiere a textos escritos o ilustraciones que acompañan al software de computadora o están 
integrados en su código fuente. Esta documentación tiene como objetivo explicar cómo funciona el 
software o cómo utilizarlo.
### 5.1.2. Source Code Management.
A continuación, se describe la gestión del código fuente, también conocida por las siglas SCM (Source Code Management). Su función principal es rastrear los cambios que realizará el equipo durante el desarrollo de su proyecto en el repositorio de código fuente. Se utilizará como un sistema de control de versiones que lepermitirá realizar un seguimiento de los cambios realizados por miembros o desarrolladores individuales del proyecto. Además, es importante tener en cuenta que usaremos GitHub como nuestro sistema de control de versiones.

1. [ ] URL de la organización: 4424-Corebyte-App-Web - https://github.com/4424-Corebyte-App-Web

2. [ ] URL del repositorio de la Landing Page: Corebyte-Landing-Page - https://github.com/4424-Corebyte-App-Web/Corebyte-Landing-Page

**GitFlow**

GitFlow es un modelo alternativo para la creación de ramas en Git que se ha convertido en una herramienta esencial para muchos desarrolladores en los últimos años. Este flujo de trabajo de control de versiones, desarrollado y popularizado por Vicent Driessen, desempeña un papel crucial en la gestión de las versiones de un código, facilitando la creación ordenada de nuevas características (Features) y correcciones de problemas urgentes (Hotfixes).

![GitFlow.png](/assets/img/chapter-V/GitFlow.png)

Como se mencionó previamente, GitFlow opera con ramas o "branches". A continuación, se detallan las ramas que se utilizarán en el flujo de trabajo de nuestro proyecto.

* **Main Branches:**
    * **Main:** Esta es la rama principal desde la cual se ramifican todas las demás. Contendrá la versión más reciente junto con las versiones anteriores creadas por los desarrolladores. Aquí se mantendrá el historial oficial de las versiones publicadas.
    * **Develop:** Esta rama puede ser creada a partir de la rama principal (Main) y contendrá todas las características (Features) estables. A través de esta rama, el equipo podrá integrar las funcionalidades de manera efectiva.

* **Support Branches**
A diferencia de las ramas principales, estas ramas secundarias tienen una vida útil limitada, ya que se eliminan al fusionarse con sus ramas primarias.
    * **Feature:**
        * Se ramifica de: develop
        * Debe fusionarse de nuevo en: develop
        * Se utilizan para desarrollar las nuevas funciones que se integrarán en la próxima versión. Es importante destacar que esta rama existe únicamente mientras está en proceso de desarrollo. Sin embargo, una vez que el desarrollador haya completado esa función, se fusionará nuevamente con la rama "develop".

* **Convenciones para nombrar los Features:**
    * **Feture Branch:** feature/name
    **Example:**
        1. feature/welcome
        2. feature/about
        3. feture/myfeture
    * **Conventional Commits**
    El commit debe seguir la siguiente estructura:
    **\<type> [optional scope]: \<description>**
    **[optional body]**
    **[optional footer(s)]**
        * **Type:**
        **1\. feat:** Cuando se agrega un nuevo feature.
        **2\. fix:** cuando corriges un error.
        **3\. build:** cuando afectan los componentes de compilación como la herramienta de compilación, las dependencias o la version del proyecto.
        **4\. chore:** modificaciones privadas del código.
        **5\. docs:** commits que afectan solo a la documentación.
        **6\. refractor:** commits que reescriben o reestructura el código, pero no cambia el comportamiento.
        **7\. perf:** commits especiales que mejoran el rendimiento.
        **8\. style:** commits que no afectan el programa. (espacios en blanco, formato, puntos o comas faltantes).
        **9\. test:** commits que agregan pruebas.
        * **Scope**
        Ofrece información contextual adicional. Aunque es opcional, es beneficioso incluirlo para proporcionar a los desarrolladores una descripción más detallada del commit.
        **\<description>**
        Es una parte obligatoria del formato de los commits. Siempre debemos usar lenguaje en modo imperativo y evitar escribir en mayúsculas
        **[optional body]**
        El cuerpo es opcional y, cuando se utiliza, debe explicar la motivación detrás del cambio y contrastarlo con el comportamiento anterior. Es ideal para mencionar identificadores de problemas y sus relaciones.
        **[optional footer(s)]**
        Esta sección es opcional y puede incluir información sobre cambios significativos. Puede hacer referencia al problema por su identificación y, en esta sección, se incluyen los cambios importantes precedidos por "BREAKING CHANGES:" seguido de uno o dos saltos de línea.
        **Ejemplos:**
            1. feat(welcome): add welcome section
            2. build(release): bump version to 1.0.0
            3. style: remove empty line
            4. feat(sign up): add the button to sign up
            5. feat!: email the costumer when product is shipped
            6. feat: remove ticket list endpoint
            refers to JIRA-1337
            BREAKING CHANGES: ticket enpoints no longer supports list all entites.

Como se mencionó previamente, la gestión de nuestro código fuente se llevará a cabo mediante
GitHub. El IDE utilizado en este caso, WebStorm, debe estar vinculado directamente al 
repositorio creado por nuestra StartUp. De esta manera, cada commit realizado por 
un miembro del equipo se subirá automáticamente y se cargará en el GitHub de la organización. Las instrucciones para completar con éxito este proceso de emparejamiento se detallan a continuación:

* **Activar el controlador de versiones del IDE**
Dado que utilizaremos GitHub para gestionar nuestro código, la opción que debe estar 
habilitada o seleccionada es aquella que indique que el sistema de control se realizará
mediante Git. Para hacer esto, siga los siguientes pasos:

  1. Diríjase a la pestaña "VCS" en WebStorm.
  2. Luego, seleccione la opción "Enable Version Control Integration".

![activar-el-controlador-de-versiones-1.png](/assets/img/chapter-V/activar-el-controlador-de-versiones-1.png)

Ahora se debe seleccionar el sistema de control a través de Git y, por último aceptar los cambios.

![activar-el-controlador-de-versiones-2.png](/assets/img/chapter-V/activar-el-controlador-de-versiones-2.png)


* **Aregar una cuenta de GitHub, siga estos pasos:**
  1. Diríjase a la sección de configuración en su aplicación.
  2. Dentro de la pestaña 'File', busque y seleccione la opción 'Settings'.
  3. En la configuración, busque la sección de version control.
  4. Agregue su cuenta de GitHub para obtener acceso a los repositorios.


![aregar-una-cuenta-de-GitHub-1.png](/assets/img/chapter-V/aregar-una-cuenta-de-GitHub-1.png)

![aregar-una-cuenta-de-GitHub-2.png](/assets/img/chapter-V/aregar-una-cuenta-de-GitHub-2.png)

* **Configurar el nombre de usuario de Git:** Una vez que hayas establecido el sistema de control de versiones que se vinculará con tu IDE, deberás ingresar la cuenta que utilizarás. Para hacerlo, sigue estos pasos:
  1. Realiza un commit en tu proyecto. Durante este proceso, se te solicitará que ingreses tu nombre de usuario de Git.
  2. Después de haberlo añadido, todos los cambios se guardarán en el repositorio especificado en esa plataforma, siempre y cuando des la orden correspondiente.
  3. Para configurar tu nombre de usuario de Git, primero selecciona la opción 'commit' que se encuentra dentro de la pestaña 'Git'.


![configurar-el-nombre-de-usuario-de-Git-1.png](/assets/img/chapter-V/configurar-el-nombre-de-usuario-de-Git-1.png)


* **Guardar el progreso en GitHub:** Con todo configurado en WebStorm, ahora puedes subir tu código a GitHub sin problemas. Simplemente dirígete a la opción 'GitHub' que se encuentra en la pestaña 'Git' y comparte el proyecto.


![guardar-el-progreso-en-GitHub-1.png](/assets/img/chapter-V/guardar-el-progreso-en-GitHub-1.png)


![guardar-el-progreso-en-GitHub-2.png](/assets/img/chapter-V/guardar-el-progreso-en-GitHub-2.png)


* **Configurar la propiedad del repositorio en GitHub:** Ahora, solo necesitas configurar la ubicación del repositorio. El código ya debería estar guardado en GitHub, pero solo estará presente en tu propia cuenta. Para cambiar la propiedad y transferirla a la organización deseada, sigue estos pasos:
  1. Ingresa al repositorio creado en GitHub.
  2. Selecciona la pestaña 'settings'
  3. Dirigite al apartado de 'DangerZone'
  4. Luego da click en 'transfer'
  5. Finalmente elegimos el nuevo lugar para guardar el repositorio.


### 5.1.3. Source Code Style Guide & Conventions.


En esta sección, se presentarán las pautas, convenciones, estilos y principios que se aplicarán a cada uno de los lenguajes utilizados en la creación de nuestra aplicación. La observancia de este conjunto de directrices reviste una importancia fundamental, ya que tiene el propósito de mantener la calidad estructural del software, mejorar la legibilidad del código fuente y simplificar el mantenimiento del mismo.

Dado que en este proyecto se emplearán varios lenguajes, como HTML, CSS, JavaScript, C# y TypeScript para el desarrollo de la plataforma web, así como Gherkin para el proceso de pruebas del programa, a continuación, se detallarán y describirán las reglas y recomendaciones generales que se tendrán en cuenta al utilizarlos.


**Nomenclatura General**

Para los nombres de variables, objetos, elementos y funciones que se utilicen en el proyecto, se emplearán términos en inglés que estén relacionados con lo que representan. No se utilizarán mayúsculas en estos nombres, ya que, de acuerdo con W3Schools (sin fecha), la combinación de mayúsculas y minúsculas puede dificultar la legibilidad del código. En su lugar, se optará por utilizar exclusivamente letras minúsculas, lo que contribuirá a una mayor claridad en el código.

Ejemplos de nomenclatura estándar, siguiendo las recomendaciones de Google (s.f.):

```
.gallery {}
.video {}
.login {}
```

Estas pautas de nomenclatura ayudarán a mantener una coherencia en el código y facilitarán su comprensión.

**Sangría**

Cuando se trabaje con HTML, CSS y/o JavaScript, se aplicará un espaciado de dos espacios antes de cada línea que se encuentre dentro de un bloque. Según W3Schools (sin fecha), no se recomienda el uso de la tecla "Tabulación". A continuación, se muestra un ejemplo de la sangría estándar en HTML siguiendo las directrices de W3Schools (s.f.):

``` html
<!DOCTYPE html>
<html>
  <head>
    <title>Título del Documento</title>
  </head>
  <body>
    <h1>Encabezado Principal</h1>
    <p>Este es un párrafo dentro del cuerpo del documento.</p>
  </body>
</html>
```

Este estilo de sangría proporciona una estructura clara y organizada al código, lo que facilita su lectura y mantenimiento.

Ejemplo de formato estándar de sangría en CSS, conforme a las recomendaciones de W3Schools (s.f):

``` CSS
html {
  background: #fff; /* Fondo blanco */
  color: #404;     /* Color de texto gris */
}
```

Ejemplo de nomenclatura estándar de la sangría en JavaScript según W3School (s.f.):

``` JavaScript
function toCelsius(fahrenheit) {
  return (5 / 9) * (fahrenheit - 32);
}
```

**Especificaciones generales**

A continuación, detallaremos las reglas específicas necesarias para comprender el código de nuestra aplicación en cada lenguaje.

**HTML:**

HTML, acrónimo de HyperText Markup Language en inglés, es un lenguaje de marcado que se utiliza para definir la estructura de una página web. También incluye funcionalidades que permiten controlar el comportamiento de diferentes elementos del contenido de la página, como cambiar el tamaño del texto o aplicar formato cursiva, entre otros. En nuestro proyecto, emplearemos HTML5, y a continuación, se presentan las características y directrices que debemos seguir para utilizar este lenguaje de la siguiente manera:

* **Declare Document Type**
  La declaración del tipo de documento debe realizarse en la primera línea del código. Según las recomendaciones de Google (s.f.), se prefiere la sintaxis de HTML5 para todos los documentos HTML. Para declararla, simplemente copia lo siguiente:

``` html
<!DOCTYPE html>
```

* **Blank Lines**
  Cada vez que comiences un nuevo bloque, lista o tabla de gran longitud, es recomendable dejar una línea en blanco después del elemento anterior para mejorar la legibilidad y la presentación del código, de acuerdo con las pautas de W3Schools (s.f.):

``` html
<!DOCTYPE html>
<html>
<head>
<title>Animales Exóticos</title>
</head>
<body>
<h1>Lemur de Madagascar</h1>
<p>El lémur de Madagascar es un primate endémico de la isla de Madagascar en el Océano Índico.</p>

<h1>Pangolín</h1>
<p>El pangolín es un mamífero cubierto de escamas que se encuentra en regiones de África y Asia.</p>

<h1>Ocelote</h1>
<p>El ocelote es un felino salvaje que habita en América del Sur y Central, conocido por su pelaje moteado.</p>
</body>
</html>
```

Esta práctica de dejar una línea en blanco mejora la estructura y legibilidad del código HTML.

* **Quote attribute Values**
  Para los valores de los atributos, es común utilizar comillas dobles alrededor de ellos, aunque esta característica no sea obligatoria. Según W3Schools (sin fecha), esto mejora la legibilidad del código y es una práctica común entre los desarrolladores. Aquí tienes un ejemplo:

``` html
<table class="striped">
```

Este enfoque de usar comillas dobles alrededor de los valores de los atributos es ampliamente aceptado y recomendado en la comunidad de desarrollo web.

* **Never Skip the \<title> Element**
  El elemento `<title>` permite que las páginas aparezcan en la lista de resultados al realizar búsquedas en un navegador web. Además, este elemento es responsable de proporcionar el nombre de la página cuando se agrega a marcadores o favoritos. A continuación, se muestra un ejemplo de su uso:

``` html
<title>Guía de Estilo HTML y Convenciones de Codificación</title>
```

Este elemento es esencial para mejorar la identificación y accesibilidad de una página web.

* **HTML Line-Wrapping**
  A pesar de que en un documento HTML no exista un límite estricto en la cantidad de palabras por línea, no se recomienda generar líneas de código excesivamente largas. De hecho, hacerlo dificulta la legibilidad del código. Para continuar en la siguiente línea, se deben utilizar al menos cuatro espacios para distinguir elementos secundarios. Aquí tienes un ejemplo basado en las recomendaciones de Google (sin fecha):

``` html
<button mat-icon-button color='primary' class="menu-button"
(click)="openMenu()">
<mat-icon>menu</mat-icon>
</button>
```

Este estilo de formateo ayuda a mantener un código más legible y facilita la identificación de los elementos y su jerarquía en la estructura del documento HTML.

**CSS:**

CSS, conocido por sus siglas en inglés, Cascading Style Sheets (Hojas de Estilo en Cascada), es un lenguaje que se enfoca en definir y mejorar la presentación de un documento basado en HTML. A continuación, se presentan las directrices que debemos seguir al utilizar CSS:

* **Shorthand Properties**
  Se recomienda utilizar abreviaturas de propiedades y declarar los campos de los elementos en la menor cantidad de líneas posible, según las pautas de Google (sin fecha). Esto aumenta la eficiencia del código y lo hace más legible. Además, se debe evitar agregar unidades después del valor cero. Aquí tienes un ejemplo:

``` css
border-top: 0;
font: 100%/1.6 palatino, georgia, serif;
padding: 0 1em 0;
```

Siguiendo estas recomendaciones, se puede lograr un código CSS más conciso y fácil de entender.

* **Declaration Stops**
  Es importante incluir un punto y coma al final de cada declaración en CSS, al igual que en la mayoría de los lenguajes de programación. Siguiendo las pautas de Google (sin fecha), esta práctica contribuye a mantener la coherencia en el código. A continuación, se muestra un ejemplo:

``` css
html {
  background: #fff;
  color: #404;
}
```

El uso consistente de puntos y comas al final de las declaraciones CSS ayuda a prevenir errores y mejora la claridad del código.

* **Property Name Stops**
  Es necesario incluir un espacio entre los dos puntos que siguen al nombre de una propiedad y el valor correspondiente. Siempre se debe colocar un solo espacio después de los dos puntos, pero no antes. A continuación, se muestra un ejemplo siguiendo esta convención estándar de Google (s.f):

``` css
html {
  background: #fff;
  color: #404;
}
```

Mantener esta consistencia en la colocación de espacios ayuda a que el código CSS sea más legible y fácil de entender.

* **Declaration Block Separation**
  Es esencial utilizar un espacio separador después del nombre de un selector de elemento y antes de la llave que inicia un bloque de declaración CSS. Además, la llave de apertura del bloque debe estar en la misma línea que el selector. Aquí tienes un ejemplo siguiendo esta convención estándar de Google (sin fecha):

``` css
html {
  background: #fff;
  color: #404;
}
```

El cumplimiento de estas directrices ayuda a mantener la consistencia y la legibilidad en el código CSS.

* **CSS quotation Marks**
  No se deben utilizar comillas dobles (`"`) en el código CSS; en su lugar, se permiten y deben emplearse comillas simples (`'`) únicamente para selectores de atributos y valores de propiedades.
  Ejemplo conforme a las pautas estándar de Google (sin fecha):

``` css
html {
  font-family: 'open sans', arial, sans-serif;
}
```

Este ejemplo demuestra el uso de comillas simples para encerrar el valor del atributo `font-family` en CSS, lo cual es una práctica común y aceptada.

**JavaScript**

JavaScript es un lenguaje de programación que permite especificar de manera precisa las acciones que debe realizar el navegador web, incluyendo el orden de ejecución de tareas y la frecuencia con la que se deben llevar a cabo. A continuación, se presentan las pautas para el uso de JavaScript en nuestro proyecto:

* **Spaces around operators**
  Es importante añadir espacios alrededor de cada operador matemático y comas que se utilicen en el código JavaScript. A continuación, se muestra un ejemplo siguiendo la convención estándar de W3Schools (sin fecha):

``` javascript
let x = y + z;
const myArray = ['Volvo', 'Saab', 'Fiat'];
```

El uso consistente de espacios alrededor de operadores y comas mejora la legibilidad del código JavaScript.

* **Simple Statement's End**
  Es fundamental que una instrucción simple finalice con un punto y coma, tal como es el caso en muchos otros lenguajes de programación. A continuación, se muestra un ejemplo que cumple con la convención estándar de W3Schools (sin fecha):

``` javascript
let x = v + 7;
const myArray = ['Volvo', 'Saab', 'Fiat'];
```

El uso de punto y coma al final de cada instrucción ayuda a garantizar la estructura correcta del código JavaScript y a evitar posibles errores.

* **Beginning and End of Function**
  Un bloque de función debe incluir una llave al final de la primera línea, de modo que el cierre de la función esté en la última línea, sin necesidad de un punto y coma. Este mismo principio se aplica a las estructuras condicionales y los bucles. A continuación, se muestra un ejemplo que cumple con la convención estándar de W3Schools (sin fecha):

``` javascript
function toCelsius(fahrenheit) {
  return (5 / 9) * (fahrenheit - 32);
}
```

En este ejemplo, la función `toCelsius` está formateada de acuerdo con estas pautas, con la llave de apertura en la misma línea que la declaración de la función y la llave de cierre en la última línea. Esto ayuda a mantener la estructura y la legibilidad del código JavaScript.

* **Object Rules**
  Para la creación de un objeto, al igual que en una función, se comienza con una llave al final de la primera línea. Sin embargo, en este caso, la llave de cierre debe ir seguida de un punto y coma. Para definir las propiedades del objeto, se utilizan dos puntos y un espacio para separar el nombre de la propiedad de su valor. Si el valor es un string, se debe encerrar entre comillas dobles. A continuación, se muestra un ejemplo siguiendo la convención estándar de W3Schools (sin fecha):

``` javascript
const person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
```

En este ejemplo, el objeto `person` está formateado de acuerdo con estas pautas, lo que mejora la legibilidad y la estructura del código JavaScript.

**Gherking:**

Gherkin es un Lenguaje Específico de Dominio (DSL por sus siglas en inglés) que se utiliza para resolver problemas específicos mediante la generación de casos de prueba que validan una característica en diversos escenarios. Gherkin incluye varios elementos, entre los cuales los más conocidos y utilizados son Feature, Scenario, Example, Given, When y Then. A continuación, se presentan las pautas que debemos seguir al utilizar Gherkin en nuestro código:

* **Discernible Given-When-Then Blocks**
  Es importante aplicar sangría a los elementos que representan los pasos a seguir en un escenario. En el caso de "And", se debe aplicar una sangría adicional. Siguiendo la recomendación de Keiblinger (2021), este enfoque ayuda a identificar rápidamente las partes que componen un escenario. A continuación, se muestra un ejemplo:

``` gherkin
Scenario: Ingreso de requisitos con claridad
  Given que en el formulario de ingreso de oferta laboral
  When escribo claramente los requisitos
  Then se mostrará el mensaje
  And mi oferta solo aparecerá a quienes cumplan con estos
  And se habilita la opción
```

En este ejemplo, se ha aplicado la sangría de manera adecuada para resaltar los pasos del escenario, y se ha utilizado una sangría adicional para los pasos que comienzan con "And". Esto mejora la legibilidad y la comprensión de los escenarios escritos en Gherkin.

* **Step with Tables**
  Conforme a la recomendación de Keiblinger (2021), cuando sea necesario introducir valores en partes del escenario, se debe emplear una tabla o crear un formulario que refleje esa parte del escenario. Antes de esta representación, se deben colocar dos puntos. Aquí tienes un ejemplo:

``` gherkin
Then se mostrará el mensaje:
  | Mensaje |
  | Se completaron los requisitos adecuadamente |
```

Este enfoque permite una representación clara y estructurada de los valores relacionados con una parte específica del escenario.

* **Reducing Noise**
  Para evitar la acumulación de demasiadas líneas de código en un escenario, es recomendable incluir valores por defecto dentro de los pasos para campos que no sean muy relevantes para ese escenario en particular. Los valores "estándar" que se coloquen deben estar entre comillas simples. Siguiendo el consejo de Keiblinger (2021), esta práctica contribuye significativamente a la reducción del tamaño del código. A continuación, se muestra un ejemplo:

``` gherkin
When escribo claramente los requisitos 'dominio en C'
```

En este ejemplo, se ha incluido un valor por defecto ('dominio en C') entre comillas simples dentro del paso para representar un campo que no es esencial en ese escenario. Esto ayuda a mantener el escenario más conciso y legible.

* **Scenarios Separator**
  Para separar dos escenarios, se debe insertar un salto de línea y, según la sugerencia de Keiblinger (2021), si es posible, agregar una línea de comentario para facilitar la visualización de estos. De esta manera, se identifica rápidamente el inicio y el fin de un escenario. A continuación, se presenta un ejemplo:

``` gherkin
Scenario: Ingreso de requisitos con claridad
Given que en el formulario de ingreso de oferta laboral
When escribo claramente los requisitos
Then se mostrará el mensaje
And mi oferta solo aparecerá a quienes cumplan con estos
And se habilita la opción

# --------------------------

Scenario: Otro escenario
Given que en otro contexto
When ocurre algo diferente
Then se muestra otro resultado
```

En este ejemplo, se ha agregado un salto de línea entre los dos escenarios y se ha incluido una línea de comentario como separador para mejorar la visualización y la identificación de cada escenario.

**C#:**

C# es un lenguaje de programación desarrollado por Microsoft en el año 2000 como parte de su plataforma .NET. Desde su creación, C# ha evolucionado significativamente, convirtiéndose en una herramienta esencial para el desarrollo de una amplia gama de aplicaciones, desde software de escritorio hasta aplicaciones web y móviles, así como servicios en la nube. Su diseño moderno y su integración con el ecosistema de .NET lo han consolidado como una opción preferida para muchos desarrolladores a nivel global.

A continuación, se presentan las pautas para utilizar C# en nuestro proyecto:

* **Datos de cadena**


Use **interpolación de cadenas** para concatenar cadenas cortas, como se muestra en el código siguiente.

```C#  
  string displayName = $"{nameList[n].LastName}, {nameList[n].FirstName}";
```

Para anexar cadenas en bucles, especialmente cuando se trabaja con grandes cantidades de texto, utilice un objeto System.Text.StringBuilder.
En este ejemplo, se han seguido las pautas para nombrar clases e interfaces de manera clara y legible.


```C#  
  var phrase = "lalalalalalalalalalalalalalalalalalalalalalalalalalalalalala";
  var manyPhrases = new StringBuilder();
  for (var i = 0; i < 10000; i++)
  {
      manyPhrases.Append(phrase);
  }
  //Console.WriteLine("tra" + manyPhrases);
```

* **Delegados**

Use **Func<> y Action<>** en lugar de definir tipos de delegado. En una clase, defina el método delegado.

```C#  
  Action<string> actionExample1 = x => Console.WriteLine($"x is: {x}");
  
  Action<string, string> actionExample2 = (x, y) => Console.WriteLine($"x is: {x}, y is {y}");
  
  Func<string, int> funcExample1 = x => Convert.ToInt32(x);
  
  Func<int, int, int> funcExample2 = (x, y) => x + y;
```

Llame al método con la signatura definida por el delegado Func<> o Action<>.

```C#  
  actionExample1("string for x");
  actionExample2("string for x", "string for y");
  Console.WriteLine($"The value is {funcExample1("1")}");
  Console.WriteLine($"The sum is {funcExample2(1, 2)}");
```

* **try-catch y using en el control de excepciones**

Use **try-catch** para controlar las excepciones. Use **using** para liberar recursos no administrados.

``` C#  
  try
  {
      // Code that may throw an exception
  }
  catch (Exception ex)
  {
      // Code to handle the exception
  }
  
  using (var resource = new Resource())
  {
      // Code that uses the resource
  }
```

* **Operadores && y ||**

Use **&&** y **||** en lugar de **&** y **|** para operaciones lógicas. Los operadores **&&** y **||** realizan una evaluación de cortocircuito, lo que significa que si la primera parte de la expresión es suficiente para determinar el resultado, la segunda parte no se evalúa.

```C#  
  if (a == 10 && b == 20)
  {
      // Code to execute if both conditions are true
  }
  
  if (a == 10 || b == 20)
  {
      // Code to execute if either condition is true
  }
```

* **Comentarios**

Use comentarios para explicar el código y proporcionar información adicional. Los comentarios deben ser claros y concisos.

```C#  
  // This is a single-line comment
  
  /*
  This is a multi-line comment
  that spans multiple lines
  */
```
* **Operador new**

Use **new** para crear instancias de clases y estructuras.

```C#  
  var person = new Person();
  var point = new Point(10, 20);
```

* **Control de eventos**

Use **eventos** para notificar a los suscriptores cuando ocurre un evento.

```C#  
  public class Button
  {
      public event EventHandler Click;
  
      protected virtual void OnClick(EventArgs e)
      {
          Click?.Invoke(this, e);
      }
  }
```

* **Consultas LINQ**

Use consultas LINQ para realizar operaciones de consulta en colecciones de datos.

```C#  
  var query = from c in customers
              where c.City == "London"
              select c;
```

* **Variables locales con asignación implícita de tipos**

Use la asignación implícita de tipos para las variables locales cuando el tipo se puede inferir fácilmente.

```C#  
  var name = "John";
  var age = 30;
```

**Typescript**

JavaScript es uno de los lenguajes más populares y ha experimentado un rápido avance y mejora en los últimos años. A continuación, se presentan las pautas para utilizar JavaScript en nuestro proyecto:

En TypeScript, se recomienda que las variables se declaren en minúsculas y se especifique el tipo de dato utilizando dos puntos después del nombre de la variable. Aquí tienes ejemplos de cómo declarar y asignar valores a variables en TypeScript:

``` typescript
// Definición e inicialización separadas
let edad: number;
edad = 20;

// Definición e inicialización en la misma línea.
let edadAitor: number = 18;
```

Además, en TypeScript, se siguen las mismas convenciones que se utilizan en JavaScript.


### 5.1.4. Software Deployment Configuration.

#### Landing Page Deployment

Para desplegar la Landing Page desde GitHubPages hay que seguir los siguientes pasos:

**1. Ubicar el repositorio que tiene guardado el codigo fuente y dirigirse al apartado de configuración (settings):**

![repo-landing-page.png](/assets/img/chapter-V/repo-landing-page.png)


**1. Seleccionar la sección pages:**


![pages-landing-page.png](/assets/img/chapter-V/pages-landing-page.png)


**1. Configurar la rama que será usada para hacer deploy:**

![rama-landing-page.png](/assets/img/chapter-V/rama-landing-page.png)


## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1
En la fase inicial de nuestro proyecto, nos propusimos llevar a cabo la implementación del diseño de nuestra Landing Page utilizando WebStorm como entorno de desarrollo. Esto implica que al concluir el Sprint, todas las secciones, ya sea Home, Services, Pricing, Testimonials o About Us, deben estar completadas. A continuación, adjuntamos imágenes que ilustran cómo gestionamos las tareas en Jira Software.

Repositorio: [https://github.com/orgs/4424-Corebyte-App-Web/repositories](https://github.com/orgs/4424-Corebyte-App-Web/repositories)

Landing Page Deployed: https://4424-corebyte-app-web.github.io/Corebyte-Landing-Page/

#### 5.2.1.1. Sprint Planning 1.

<table>
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Planning Background </p1></td>
        </tr>
        <!--FILA 1-->
        <tr>
            <td>Date</td>
            <td>20-04-2025</td>
        </tr>
        <!--FILA 2-->
        <tr>
            <td>Time</td>
            <td> 10:00 p.m </td>
        </tr>
        <!--FILA 3-->
        <tr>
            <td>Location</td>
            <td>Discord</td>
        </tr>
         <!--FILA 4-->
        <tr>
            <td>Prepared By</td>
            <td>Oscar Armas</td>
        </tr>
         <!--FILA 5-->
        <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Renzo Llerena - Matías Diaz - Renzo Villafuerte - Giovany Torres </td>
        </tr>
        <!--FILA 6-->
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Goal & User Stories </p1></td>
        </tr>
        <!--FILA 7-->
        <tr>
            <td>Sprint 1 Goal</td>
            <td> 
              Nuestro enfoque está en implementar la landing page de TraceWine, incluyendo todas las 
              secciones acordadas y el requisito de cambio de idioma para la aplicación. Creemos que esto
              mejora la accesibilidad y la experiencia del usuario, permitiendo que más productores de vinos y 
              distribuidores se conecten con la plataforma. Esto se confirmará cuando la landing page 
              esté completa, funcional y los usuarios puedan navegar por las secciones en su idioma 
              preferido, reportando satisfacción con la interfaz y la usabilidad.
            </td>
        </tr>
        <!--FILA 8-->
        <tr>
            <td>Sprint 1 Velocity</td>
            <td> 23 </td>
        </tr>
        <!--FILA 9-->
        <tr>
            <td>Sum of Story Points</td>
            <td> 21 </td>
        </tr>
    </tbody>
</table>

#### 5.2.1.2. Aspect Leaders and Collaborators.
Esta sección presenta la matriz de liderazgo y colaboración elaborada para el primer sprint. Los aspectos clave considerados en esta etapa se enfocan en las distintas secciones del landing page y en los estilos que deben aplicarse en cada una:

<table border="1">
  <thead>
    <tr>
      <th>Team Member<br>(Last Name, First Name)</th>
      <th>Github Username</th>
      <th>Inicio</th>
      <th>Nosotros</th>
      <th>Servicios</th>
      <th>Precios</th>
      <th>Acerca</th>
      <th>Contacto</th>
      </tr>
  </thead>
  <tbody>
    <tr>
      <td>Llerena Delagado, Renzo Miguel</td>
      <td>Renxoll</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td>L</td>
      <td></td>
    </tr>
    <tr>
      <td>Villafuerte Tapia, Renzo Alonso </td>
      <td>RenzoVi21</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td>L</td>
    </tr>
    <tr>
      <td>Armas Sánchez, Oscar Javier</td>
      <td>Racso24k</td>
      <td></td>
      <td></td>
      <td>L</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Torres Apolinario, Giovany Smith</td>
      <td>Giovany7x</td>
      <td></td>
      <td>L</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Diaz Quispe, Matias Sebastian</td>
      <td>equinox-1092</td>
      <td>L</td>
      <td></td>
      <td></td>
      <td>L</td>
      <td></td>
      <td>L</td>
    </tr>
  </tbody>
</table>


#### 5.2.1.3. Sprint Backlog 1.
Tal como se indicó previamente en la planificación del sprint 1, su objetivo principal fue desarrollar y publicar una versión inicial del landing page del producto. Esto implicó implementar las distintas secciones que componen un landing page, con el fin de brindar a los visitantes una mejor comprensión del producto en desarrollo.

Una vez establecido el objetivo del sprint, se identificaron las historias de usuario relevantes para esta etapa. Luego, cada historia fue desglosada en tareas específicas relacionadas con su implementación y cumplimiento. Para gestionar el avance del sprint, se utilizó la herramienta Trello.



<table>
    <thead>
        <tr>
            <th colspan="7">Sprint #</th>
            <th> Sprint 1</th>
        </tr>
    </thead>
    <tbody>
        <!--FILA 1-->
        <tr>
            <td colspan="1">User Story</td>
            <td colspan="15">Work-Item / Task</td>
        </tr>
        <!--FILA 2-->
        <tr>
            <td>Id</td>
            <td>Title</td>
            <td>Id</td>
            <td>Title</td>
            <td>Description</td>
            <td>Estimation (hours)</td>
            <td>Assigned To</td>
            <td>Status</td>
        </tr>
        <!--FILA 3-->
        <tr>
            <td rowspan="4" >US-001</td>
            <td rowspan="4" >Hipervínculos en el encabezado</td>
            <td>T001</td>
            <td>Definir enlaces del encabezado</td>
            <td>Identificar y organizar los enlaces del encabezado.</td>
            <td>1</td>
            <td>Matias Diaz</td>
            <td>Done</td>
        </tr>
        <!--FILA 4-->
        <tr>
            <td>T002</td>
            <td>Implementar hipervínculos</td>
            <td>Añadir hipervínculos en HTML</td>
            <td>1</td>
            <td>Matias Diaz</td>
            <td>Done</td>
        </tr>
        <!--FILA 5-->
        <tr>
            <td>T003</td>
            <td>Estilizar con CSS</td>
            <td>Aplicar estilos básicos a los enlaces del encabezado</td>
            <td>2</td>
            <td>Matias Diaz</td>
            <td>Done</td>
        </tr>
        <!--FILA 6-->
        <tr>
            <td>T004</td>
            <td>Pruebas de funcionamiento</td>
            <td>Asegurarse de que los hipervínculos funcionen correctamente.</td>
            <td>1</td>
            <td>Matias Diaz</td>
            <td>Done</td>
        </tr>
        <!--FILA 7-->
        <tr>
            <td rowspan="4" >US-002</td>
            <td rowspan="4" >Información sobre beneficios de la aplicación</td>
            <td>T001</td>
            <td>Definir contenido de beneficios</td>
            <td>Identificar los beneficios clave de la aplicación.</td>
            <td>2</td>
            <td>Osacar Javier</td>
            <td>Done</td>
        </tr>
        <!--FILA 8-->
        <tr>
            <td>T002</td>
            <td>Redactar sección de beneficios</td>
            <td>Escribir los beneficios de la aplicación de forma clara.</td>
            <td>2</td>
            <td>Osacar Javier</td>
            <td>Done</td>
        </tr>
        <!--FILA 9-->
        <tr>
            <td>T003</td>
            <td>Estilizar la sección de beneficios</td>
            <td>Aplicar estilos visuales a la sección de beneficios</td>
            <td>2</td>
            <td>Osacar Javier</td>
            <td>Done</td>
        </tr>
        <!--FILA 10-->
        <tr>
            <td>T004</td>
            <td>Pruebas de funcionalidad de beneficios</td>
            <td>Asegurarse de que la sección de beneficios sea accesible y clara.</td>
            <td>1</td>
            <td>Osacar Javier</td>
            <td>Done</td>
        </tr>
        <!--FILA 11-->
        <tr>
            <td rowspan="4" >US-003</td>
            <td rowspan="4" >Información sobre beneficios de la aplicación para vinicultores</td>
            <td>T001</td>
            <td>Definir beneficios específicos para vinicultores</td>
            <td>Identificar beneficios clave que impactan directamente a los vinicultores.</td>
            <td>2</td>
            <td>Osacar Javier</td>
            <td>Done</td>
        </tr>
        <!--FILA 12-->
        <tr>
            <td>T002</td>
            <td>Redactar contenido para vinicultores</td>
            <td>Escribir los beneficios específicos para vinicultores de forma clara.</td>
            <td>2</td>
            <td>Osacar Javier</td>
            <td>Done</td>
        </tr>
        <!--FILA 13-->
        <tr>
            <td>T003</td>
            <td>Estilizar la sección de beneficios para vinicultores</td>
            <td>Aplicar estilos visuales a la sección específica de vinicultores.</td>
            <td>2</td>
            <td>Osacar Javier</td>
            <td>Done</td>
        </tr>
        <!--FILA 14-->
        <tr>
            <td>T004</td>
            <td>Pruebas de funcionalidad de beneficios para vinicultores</td>
            <td>Asegurarse de que la sección sea clara y útil para los vinicultores.</td>
            <td>1</td>
            <td>Osacar Javier</td>
            <td>Done</td>
        </tr>
        <!--FILA 3-->
        <tr>
            <td rowspan="4" >US-004</td>
            <td rowspan="4" >Opciones de Precios Claras para Decisiones Informadas</td>
            <td>T001</td>
            <td>Definir opciones de precios</td>
            <td>Establecer diferentes opciones de precios para los usuarios.</td>
            <td>2</td>
            <td>Matias Diaz</td>
            <td>Done</td>
        </tr>
        <!--FILA 4-->
        <tr>
            <td>T002</td>
            <td>Redactar descripción de precios</td>
            <td>Escribir descripciones claras y transparentes para cada opción de precio.</td>
            <td>2</td>
            <td>Matias Diaz</td>
            <td>Done</td>
        </tr>
        <!--FILA 5-->
        <tr>
            <td>T003</td>
            <td>Estilizar opciones de precios</td>
            <td>Aplicar diseño visual para hacer las opciones de precios fáciles de identificar.</td>
            <td>2</td>
            <td>Matias Diaz</td>
            <td>Done</td>
        </tr>
        <!--FILA 6-->
        <tr>
            <td>T004</td>
            <td>Pruebas de funcionalidad de precios</td>
            <td>Verificar que todas las opciones de precios funcionen correctamente.</td>
            <td>1</td>
            <td>Matias Diaz</td>
            <td>Done</td>
        </tr>
        <!--FILA 7-->
        <tr>
            <td rowspan="4" >US-005</td>
            <td rowspan="4" >Acceso fácil a soporte y asesoramiento</td>
            <td>T001</td>
            <td>Definir canales de soporte</td>
            <td>Establecer los diferentes canales a través de los cuales los usuarios pueden recibir soporte.</td>
            <td>2</td>
            <td>Renzo Villafuerte</td>
            <td>Done</td>
        </tr>
        <!--FILA 8-->
        <tr>
            <td>T002</td>
            <td>Redactar contenido de soporte</td>
            <td>Escribir instrucciones claras para acceder al soporte y asesoramiento.</td>
            <td>2</td>
            <td>Renzo Villafuerte</td>
            <td>Done</td>
        </tr>
        <!--FILA 9-->
        <tr>
            <td>T003</td>
            <td>Estilizar el acceso a soporte</td>
            <td>Asegurarse de que el acceso al soporte sea fácil de encontrar y utilizar.</td>
            <td>2</td>
            <td>Renzo Villafuerte</td>
            <td>Done</td>
        </tr>
        <!--FILA 10-->
        <tr>
            <td>T004</td>
            <td>Pruebas de funcionalidad de soporte</td>
            <td>Verificar que todos los canales de soporte sean funcionales.</td>
            <td>1</td>
            <td>Renzo Villafuerte</td>
            <td>Done</td>
        </tr>
        <!--FILA 11-->
        <tr>
            <td rowspan="4" >US-006</td>
            <td rowspan="4" >Opiniones de usuarios que inspiran confianza</td>
            <td>T001</td>
            <td>Recopilar opiniones de usuarios</td>
            <td>Solicitar y recopilar opiniones de usuarios sobre la aplicación.</td>
            <td>2</td>
            <td>Renzo Miguel</td>
            <td>Done</td>
        </tr>
        <!--FILA 12-->
        <tr>
            <td>T002</td>
            <td>Redactar opiniones destacadas</td>
            <td>Seleccionar y escribir las opiniones más destacadas de los usuarios.</td>
            <td>2</td>
            <td>Renzo Miguel</td>
            <td>Done</td>
        </tr>
        <!--FILA 13-->
        <tr>
            <td>T003</td>
            <td>Estilizar opiniones de usuarios</td>
            <td>Aplicar un diseño visual atractivo para mostrar las opiniones de los usuarios.</td>
            <td>2</td>
            <td>Renzo Miguel</td>
            <td>Done</td>
        </tr>
        <!--FILA 14-->
        <tr>
            <td>T004</td>
            <td>Pruebas de funcionalidad de opiniones</td>
            <td>Asegurarse de que las opiniones se muestren correctamente.</td>
            <td>1</td>
            <td>Renzo Miguel</td>
            <td>Done</td>
        </tr>
        <!--FILA 15-->
        <tr>
            <td rowspan="4" >US-007</td>
            <td rowspan="4" >Navegación fluida en dispositivos móviles</td>
            <td>T001</td>
            <td>Optimizar navegación para dispositivos móviles</td>
            <td>Asegurarse de que la navegación sea fluida en dispositivos móviles.</td>
            <td>3</td>
            <td>Renzo Miguel</td>
            <td>Done</td>
        </tr>
        <!--FILA 16-->
        <tr>
            <td>T002</td>
            <td>Rediseñar menús para móviles</td>
            <td>Ajustar los menús de navegación para mejorar la experiencia móvil.</td>
            <td>3</td>
            <td>Renzo Miguel</td>
            <td>Done</td>
        </tr>
        <!--FILA 17-->
        <tr>
            <td>T003</td>
            <td>Pruebas de funcionalidad móvil</td>
            <td>Verificar que la navegación móvil funcione correctamente.</td>
            <td>2</td>
            <td>Giovany Torres</td>
            <td>Done</td>
        </tr>
        <!--FILA 18-->
        <tr>
            <td>T004</td>
            <td>Realizar pruebas de rendimiento móvil</td>
            <td>Asegurarse de que la experiencia de navegación sea rápida en dispositivos móviles.</td>
            <td>2</td>
            <td>Giovany Torres</td>
            <td>Done</td>
        </tr>
        <!--FILA 19-->
        <tr>
            <td rowspan="4" >US-008</td>
            <td rowspan="4" >Adaptación de la landing page en tabletas</td>
            <td>T001</td>
            <td>Rediseñar layout para tabletas</td>
            <td>Adaptar la landing page para una visualización optimizada en tabletas.</td>
            <td>3</td>
            <td>Renzo Miguel</td>
            <td>Done</td>
        </tr>
        <!--FILA 20-->
        <tr>
            <td>T002</td>
            <td>Rediseñar elementos interactivos</td>
            <td>Ajustar botones y enlaces para mejorar la experiencia en tabletas.</td>
            <td>2</td>
            <td>Renzo Miguel</td>
            <td>Done</td>
        </tr>
        <!--FILA 21-->
        <tr>
            <td>T003</td>
            <td>Pruebas de funcionalidad en tabletas</td>
            <td>Verificar que la landing page funcione correctamente en tabletas.</td>
            <td>2</td>
            <td>Matias Diaz</td>
            <td>Done</td>
        </tr>
        <!--FILA 22-->
        <tr>
            <td>T004</td>
            <td>Realizar pruebas de rendimiento en tabletas</td>
            <td>Asegurarse de que la experiencia sea rápida y fluida en tabletas.</td>
            <td>2</td>
            <td>Matias Diaz</td>
            <td>Done</td>
        </tr>
        <!--FILA 23-->
        <tr>
            <td rowspan="4" >US-009</td>
            <td rowspan="4" >Compatibilidad en computadoras de escritorio</td>
            <td>T001</td>
            <td>Optimizar layout para computadoras de escritorio</td>
            <td>Asegurarse de que la landing page sea completamente funcional en escritorios.</td>
            <td>3</td>
            <td>Matias Diaz</td>
            <td>Done</td>
        </tr>
        <!--FILA 24-->
        <tr>
            <td>T002</td>
            <td>Rediseñar elementos para escritorio</td>
            <td>Ajustar el diseño de botones y menús para computadoras de escritorio.</td>
            <td>2</td>
            <td>Oscar Javier</td>
            <td>Done</td>
        </tr>
        <!--FILA 25-->
        <tr>
            <td>T003</td>
            <td>Pruebas de funcionalidad en escritorio</td>
            <td>Verificar que todos los elementos funcionen correctamente en computadoras de escritorio.</td>
            <td>2</td>
            <td>Renzo Miguel</td>
            <td>Done</td>
        </tr>
        <!--FILA 26-->
        <tr>
            <td>T004</td>
            <td>Realizar pruebas de rendimiento en escritorio</td>
            <td>Asegurarse de que la página cargue rápidamente y sin errores en computadoras de escritorio.</td>
            <td>2</td>
            <td>Renzo Villafuerte</td>
            <td>Done</td>
        </tr>
    </tbody>
</table>




#### 5.2.1.4. Development Evidence for Sprint Review.
En esta sección se detallan los principales logros alcanzados durante el primer sprint. El avance más significativo fue la creación de la versión inicial de cada sección del landing page. Cada integrante del equipo trabajó de forma progresiva en el desarrollo de dichas secciones. Posteriormente, se aplicaron estilos a través de CSS para darles formato.

A continuación, se presenta una tabla que resume los commits realizados, los cuales integran partes de las funcionalidades necesarias para completar este primer sprint.

<table>
    <thead>
        <tr>
            <th rowspan="" >Repository</th>
            <th>Branch</th>
            <th>Commit Id</th>
            <th>Commit Message</th>
            <th>Commited on (Date)</th>
        </tr>
    </thead>
    <tbody>
        <!--FILA 1 -->
        <tr>
            <td rowspan="14">https://github.com/4424-Corebyte-App-Web/Corebyte-Landing-Page</td>
            <td>master</td>
            <td>989c513aff9000ef61b828540ba489a75c4cc05d</td>
            <td>Initial commit</td>
            <td>24/24/2025</td>
        </tr>
        <!--FILA 2 -->
        <tr>
            <td>develop</td>
            <td>c77773e32554125a0c306c9fe2fd24fe79bd46c6</td>
            <td>feat(start): add start section and styles</td>
            <td>24/24/2025</td>
        </tr>
        <!--FILA 3 -->
        <tr>
            <td>feature/about</td>
            <td>989c513aff9000ef61b828540ba489a75c4cc05d</td>
            <td>Initial commit</td>
            <td>24/24/2025</td>
        </tr>
        <!--FILA 4 -->
        <tr>
            <td>feature/about-app</td>
            <td>44b743ac8c78ae066b0e07ab8b55ebec37b3956b</td>
            <td>feat(prices): add prices section and styles</td>
            <td>24/24/2025</td>
        </tr>
        <!--FILA 5 -->
        <tr>
            <td>feature/contact</td>
            <td>2e1735e81ffa8d485708e38e52caefe681a3a3ee</td>
            <td>docs:update index.html</td>
            <td>24/24/2025</td>
        </tr>
        <!--FILA 6 -->
        <tr>
            <td>feature/prices</td>
            <td>44b743ac8c78ae066b0e07ab8b55ebec37b3956b</td>
            <td>feat(prices): add prices section and styles</td>
            <td>24/24/2025</td>
        </tr>
        <!--FILA 7 -->
        <tr>
            <td>feature/services</td>
            <td>ed0ba970539a24d09c25d94c221effaf4ee77b7e</td>
            <td>commit: update services section</td>
            <td>26/24/2025</td>
        </tr>
        <!--FILA 8 -->
        <tr>
            <td>feature/start</td>
            <td>c77773e32554125a0c306c9fe2fd24fe79bd46c6</td>
            <td>feat(start): add start section and styles</td>
            <td>24/24/2025</td>
        </tr>
        <!--FILA 9 -->
        <tr>
            <td>release</td>
            <td>989c513aff9000ef61b828540ba489a75c4cc05d</td>
            <td>Initial commit</td>
            <td>24/24/2025</td>
        </tr>
    </tbody>
</table>

#### 5.2.1.5. Execution Evidence for Sprint Review.


Después de completar el Sprint 1, logramos implementar todas las secciones de nuestra Landing Page para garantizar una visualización perfecta. Además, le dimos un formato atractivo que captura la atención del usuario hacia sus diferentes componentes. También agregamos métodos de navegación en la página, como botones ubicados al principio, que te permiten moverte fácilmente de una sección a otra. A continuación, te mostraremos los avances a través de imágenes del resultado obtenido.

Es importante destacar que el objetivo principal de la Landing Page es convertir a los visitantes en futuros clientes o usuarios habituales de nuestro servicio. Para lograrlo, utilizamos llamados a la acción (Call To Action) que los guían hacia la aplicación web.

A continuación, te presentamos capturas de pantalla del desarrollo de la Landing Page:


**Encabezado y botones de desplazamiento:**

En la parte superior, se encuentra el encabezado (Header) que incluye botones de inicio (Home), beneficios (benefits), Pricing (Pricing), sobre la aplicación (about), testimonios de usuarios (testimonials), un formulario para que nos contacten (Contact), un apartado para saber sobre el equipo (About us) y un botón para cambiar el idioma entre inglés y español. Estos elementos permiten a los visitantes desplazarse fácilmente a la sección que deseen visualizar.

Imagen 01: Encabezado y botones de desplazamiento

![header-landing-page.png](../assets/img/chapter-V/header-landing-page.png)

**Sección Hero:**

Se presenta la sección "Hero", que incluye una breve descripción y una frase representativa de TraceWine. Además, permite iniciar el uso del servicio web y proporciona una imagen relacionada con el mismo.

Imagen 02: Sección Hero

![hero-landing-page.png](../assets/img/chapter-V/hero-landing-page.png)


**Sección Services:**

Se presenta la sección de servicio que ofrecemos para nuestros segmentos objetivos. En esta sección, se describen los beneficios y características de TraceWine, lo que permite a los visitantes conocer más sobre el servicio.

Imagen 03: Sección Services
![services-landing-page.png](../assets/img/chapter-V/services-landing-page.png)


**Sección Pricing:**

En la sección de precios, se detallan los planes y precios de TraceWine. Esta información es esencial para que los visitantes conozcan las opciones disponibles y puedan elegir la que mejor se adapte a sus necesidades.

Imagen 04: Sección Pricing
![plans-landing-page.png](../assets/img/chapter-V/plans-landing-page.png)


**Sección About the App:**

En esta sección, se presenta información detallada sobre la aplicación TraceWine, sus características y funcionalidades. Esto permite a los visitantes conocer más sobre la aplicación y cómo puede ayudarles en su día a día.

Imagen 05: Sección About the App

![about-the-app-landing-page.png](../assets/img/chapter-V/about-the-app-landing-page.png)


**Sección About the Team:**

En la sección "About the Team", se presenta información sobre el equipo de desarrollo de TraceWine. Esto permite a los visitantes conocer a las personas detrás del servicio y generar confianza en la calidad y profesionalismo del equipo.

![about-the-team-landing-page.png](../assets/img/chapter-V/about-the-team-landing-page.png)

**Sección Contact:**

En la sección de contacto, se presenta un formulario que permite a los visitantes enviar consultas, comentarios o solicitudes de información sobre TraceWine. Esto facilita la comunicación con los usuarios y permite responder a sus necesidades de manera eficiente.

![contact-landing-page.png](../assets/img/chapter-V/contact-landing-page.png)

**Footer:**

En el pie de página (Footer), se incluyen enlaces a las redes sociales de TraceWine, información de contacto y un botón para volver al inicio de la página. Esto permite a los visitantes acceder a más información y mantenerse conectados con el servicio.

![footer-landing-page.png](../assets/img/chapter-V/footer-landing-page.png)



#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

En el primer Sprint el equipo de desarrollo de CoreByte ha diseñado, programado y puesto en funcionamiento el sitio web (Landing Page) Para presentar la aplicación Web propuesta denominada "TraceWine". En este sitio web (Landing Page), se lográ visualizar varias secciones que ilustran en que consiste "TraceWine", cada integrante del equipo de desarrollo de CoreByte estuvo a cargo de una sección en especifico.

<table>
  <thead>
    <tr>
      <th>End Point</th>
      <th> Funciones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>https://4424-corebyte-app-web.github.io/Corebyte-Landing-Page/</td>
        <td>Mostrar la Landing Page Desplegada</td>
    </tr>
  </tbody>
</table>


#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para la implementación de nuestro sitio web, optamos por utilizar GitHub Pages. En este proceso, creamos un repositorio en GitHub donde gestionamos el control de versiones. En la sección de Configuración, publicamos el proyecto almacenado en la rama "develop" que previamente se encontrba en la rama release-1.0.

[Landing Page TraceWine](https://4424-corebyte-app-web.github.io/Corebyte-Landing-Page/) - https://4424-corebyte-app-web.github.io/Corebyte-Landing-Page/

#### 5.2.1.8. Team Collaboration Insights during Sprint.

En esta entrega, nuestra meta principal fue la implementación de la Landing Page. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, Visual Studio Code, WebStorm, HTML, CSS y JavaScript. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo CoreByte:

A continuación se muestra la cantidad de commits realizadas por cada integrante del equipo durante el desarrollo de la landing page.

![tb1-pulse.png](../assets/img/chapter-V/tb1-pulse.png)

Los siguientes gráficos ofrecen una representación visual de las clonaciones registradas en nuestro repositorio, junto con la fecha en que cada una de estas acciones se llevó a cabo. Además, se presenta información sobre la cantidad de visitantes que ha tenido el repositorio de nuestro equipo a lo largo del tiempo.

![tb1-traffic.png](../assets/img/chapter-V/tb1-traffic.png)

### 5.2.2. Sprint 2 

Repositorio: [https://github.com/orgs/4424-Corebyte-App-Web/repositories](https://github.com/orgs/4424-Corebyte-App-Web/repositories)

Landing Page Deployed: https://corebyte-landing.web.app/

Front-end application deployed: [Front-end application](https://vuetb2.web.app)

#### 5.2.2.1. Sprint Planning 2. 

| Sprint #                                     | Sprint 2                                               |
|----------------------------------------------|--------------------------------------------------------|
| <b> Sprint planning Background </b>          | --                                                     |
| Date                                         | 2025/05/08                                             |
| Time                                         | 08:00 AM                                               |
| Location                                     | Reunión virtual-Meet                                   |
| Prepared By                                  | Oscar Armas                                            |
| Attendees                                    | Renzo Miguel Llerena Delagado / Diaz Quispe Matías Sebastian / Renzo Alonso Villafuerte Tapia / Oscar Javier Armas Sánchez / Torres Apolinario Giovany Smith |
| Sprint 1 Review Summary                      | En el sprint anterior, el equipo completó una primera vista de la página de destino, implementando las secciones y estilos básicos necesarios, como Contacto, Precios y Servicios sobre la startup. |
| Sprint 1 Retrospective Summary               | El principal aspecto que el equipo debe mejorar es la comunicación entre los miembros para que se mantengan al tanto del progreso de cada uno. Ahora, el plan para el próximo sprint es trabajar de forma más organizada para que cada miembro sepa qué hacer.  |
| <b> Sprint Goal & User Stories </b>          | --                                                     |
| Sprint 2 Goals                               | Nuestro objetivo es implementar la primera version funcional de la aplicaion front-end con funciones principales como ordenes, estado, historial, solicitudes, panel de control y gestion de lotes. Como equipo pensamos ofrecer una vizualizacion amigable y detallada para una mayor adaptabilidad de la página de destino de Corebyte, ademas, creemos que ofrece una primera visión completa de las funcionalidades que la aplicación ofrece a los segmentos objetivo. Esto nos confirmará cuando nuestros segmentos objetivo se registren en la aplicación y utilicen las principales funcionalidades, como almacenes y guías de anáilisis de venta |
| Sprint 2 Velocity                            | 130                                                    |
| Sum of Story Points                          | 130                                                    |

#### 5.2.2.2. Aspect Leaders and Collaborators. 

En esta sección, se incluye la matriz de liderazgo y colaboración desarrollada para este segundo sprint. Los principales aspectos que se toman en cuenta en este sprint se centran en cada las principales secciones que presenta el Front-End Web Application. Para esto, hemos definido las siguientes secciones: Login, Ordenes, Estados, Historial, Gestion de lotes, Análisis de venta y solicitud de stock

| Team Member                        | GitHub Username | Login  | Ordenes          | Historial y Estado | Gestion de lotes | Reabastecimiento              | 
|------------------------------------|-----------------|--------|------------------|--------------------|------------------|-------------------------------|
| Renzo Miguel Llerena Delagado      | Renxoll         |        |                  |                    | L                |                               |
| Diaz Quispe Matías Sebastian       | equinox-1092    |        |                  | L                  |                  |                               |
| Renzo Alonso Villafuerte Tapia     | RenzoVi21       | L      |                  |                    |                  |                               |
| Oscar Javier Armas Sánchez         | Racso24k        |        |                  |                    |                  | L                             |
| Torres Apolinario Giovany Smith    | Giovany7x       |        | L                |                    |                  |                               |

#### 5.2.2.3. Sprint Backlog 2. 

Como se mencionó previamente en el planeamiento del sprint número 2, el objetivo del mismo es (OBJETIVO).

Luego de definir el objetivo del sprint, se identificaron las historias de usuario útiles para este sprint. A continuación, se dividió cada historia de usuario en tareas relacionadas a la implementación y cumplimiento de dicha historia. 

A continuación, se presenta la tabla con las tareas necesarias para completar satisfactoriamente este segundo sprint. Además, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.
[Link de acceso al Sprint Backlog #2 en Trello](https://trello.com/invite/b/681cc645085eedc15240526c/ATTIe5d02782fd704438be9b7f155b65d2cc3DDD1D0A/corebyte-sprint-backlog-2)

<p align="center">
  <img src="../assets/img/chapter-V/Vista1.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

  <p align="center">
 <img src="../assets/img/chapter-V/Vista2.png" 
  alt="Sprint Backlog 2 en desarrollo"/>
      
A continuación, se presenta la tabla con las tareas necesarias para completar el sprint nuemero 2, tambien, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.

| Sprint 2     | Sprint Backlog 2                                              |             |                                                                                    |                                                                                                                                                                     |                    |                 |             |
|--------------|---------------------------------------------------------------|-------------|------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|-----------------|-------------|
| User Stories |                                                               | Work Item/Task                                                                                   |                                                                                                                                                                     |                    |                 |             |
| Id           | Title                                                         | Id          | Title                                                                              | Description                                                                                                                                                         | Estimation (Hours) | Assigned to     | Status      |
| US027        | Registro de nuevos insumos en el inventario               | US027T001   | Crear una seccion para el registro de insumos en el inventario                   | Crear un componente que registre em una tabla los productos.                                                                                    | 4                  | Oscar Javier  | Done |
| US014        | Registro del estado de embotellado               | US014T001   |  Crear un boton para el registro de embotellado                  | Programar un boton dirija a al apartado de registro de embotellado.                                                                                    | 3                  | Renzo Miguel  | Done |
| US016        | Crear un cliente distribuidor               | US016T001   | Crear un cliente                   | Programar una funcion que cree un nuevo usuario dependiendo si es distribuidor o productor.                                                                                    | 6                  | Renzo Alonso  | Done |
|              |                                             | US016T002   | Crear seccion de detalle de tipo de cuenta                   | Crear un apartado para visualizar el tipo de cuenta actual.                                                                                    | 4.5                  | Renzo Alonso  | Done |
|              |                                             | US016T003   | Crear seccion de detalle de plan para actualizar                   | Crear un apartado para visualizar el tipo de desea actualizar .                                                                                    | 3                  | Renzo Alonso  | Done |
| US035        | Administrar el estado de un pedido               | US035T001   | Crear una tabla con los pedidos segun su estado                   | Crear un componente que muestre en una tabla los productos que tengan los estados de pendiente o entregado.                                                                                    | 4.5                  | Matías Diaz  | Done |
| US013        | Registro del estado de añejamiento               | US013T001   | Crear un formulario para crear un registro de añejamiento                  | crear unos cuadrados para completar la informacion correspondiente para el añejamientto.                                                                                    | 7                  | Renzo Miguel  | Done |
| US029        | Reabastecimiento de insumos directamente desde la plataforma               | US029T001   | Crear una sección para reabastecer insumos en el inventario                   | Crear un componente que permita ingresar y registrar los en el inventario directamente desde la plataforma.                                                                                    | 6                  | Oscar Javier  | Done |
| US015        | Registro de pedido               | US015T001   | Crear una sección para registrar nuevos pedidos                   | Crear un componente que permita registrar un nuevo pedido con detalles de productos, cantidades, cliente y imagen de referencia.                                                                                    | 5                  | Giovany Torres  | Done |
| US034        | Obtener detalles de un pedido               | US034T001   | Crear un boton para ver detalles de un pedido                   | Crear un boton que muestre la información detallada de un pedido.                                                                                    | 3                  | Giovany Torres  | Done |
| US012        | Registro del estado de prensado               | US012T001   | Crear una sección para registrar el estado de prensado                   | Crear un componente que permita documentar el progreso del proceso de prensado con fecha, lote y tipo.                                                                                    | 8                  | Renzo Miguel  | Done |
| US022        | Seguimiento del estado del pedido               | US022T001   | Crear una sección para seguir el estado de pedidos                   | Crear una tabla con la informacion del producto, ademas de mostrar en que estado se encuentra el producto.                                                                                    | 5                  | Matías Diaz  | Done |
| US010        | Registro del estado de fermentación               | US010T001   | Crear una sección para registrar el estado de fermentación                   | Crear un componente que permita documentar el progreso del proceso de fermentacion con tipo y descripcion de la temperatura recomendado.                                                                                    | 6                  | Renzo Miguel  | Done |
| US011        | Registro del estado de clarificación               | US011T001   | Crear una sección para registrar el estado de clarificación                   | Crear un componente que permita documentar el progreso del proceso de fermentacion con tipo y cantidad de agentes clarificantes.                                                                                    | 7                  | Renzo Miguel  | Done |
|              |                                                    | US011T002   | Crear una sección para registrar el estado de clarificación                   | Crear un componente que permita registrar y actualizar el registro del estado de clarificación.                                                                                    | 5                  | Renzo Miguel  | Done |
| US031        | Informes de inventario               | US031T001   | Crear una sección para generar informes de inventario                   | Crear un componente que genere informes de stock de insumos con la extencion pdf.                                                                                    | 4.5                  | Matías Diaz  | Done |


#### 5.2.2.4. Development Evidence for Sprint Review. 

En esta sección, se describen los principales avances de implementación realizados en este segundo sprint.

A continuación, se muestra una tabla que contiene la información sobre los _commits_ hechos que contienen partes de las funcionalidades que debemos implementar para completar el primer sprint.

| Repository                             | Branch                           | Commit Id                                         | Commit Message                                                   | Commited On |
|----------------------------------------|----------------------------------|---------------------------------------------------|------------------------------------------------------------------|-------------|
| Corebyte/Corebyte-Front-End-App        | develop                          | d6056d8fec0e259095dcba758200073f9e1d273a          |  chore: add alerts                                               | 14/05/2025  |
| Corebyte/Corebyte-Front-End-App        | develop                          | 0c2e3e17800e89b392d8f61c169c28ab012028f1          |  chore: add batch management                                     | 14/05/2025  |
| Corebyte/Corebyte-Front-End-App        | develop                          | 3f8ebbc7322dc877c0b961c2da2a7b9050cb3e88          |  chore: add profile management                                   | 14/05/2025  |
| Corebyte/Corebyte-Front-End-App        | feature/fake-api                 | 76d549816f7968a276d714ef2bd165cbc2345807          |  feat(fake-api): add fake-api support with json server.          | 16/05/2025  |
| Corebyte/Corebyte-Front-End-App        | feature/i18n                     | 441658633db5ce77469d21d44ca1ced0ae9715bc          |  feat(i18n): add language english                                | 16/05/2025  |
| Corebyte/Corebyte-Front-End-App        | feature/i18n                     | ae3db439a86e03436a2d6f9a594af00639aba4c1          |  feat(i18n): add language spanish                                | 16/05/2025  |
| Corebyte/Corebyte-Front-End-App        | feature/history-status           | ee1318494817f374e0282a569fa76982df252c09          |  feat(services): add function get and update of record           | 16/05/2025  |
| Corebyte/Corebyte-Front-End-App        | feature/history-status           | 6d4a98066fbd38ec2bf7a745c492c60f0773b5fd          |  feat(status): add component status page                         | 16/05/2025  |
| Corebyte/Corebyte-Front-End-App        | feature/history-status           | 5c24c0181d955e8c32b9ce356605500d2bc0b299          |  feat(record): add components page record                        | 16/05/2025  |
| Corebyte/Corebyte-Front-End-App        | feature/authentication           | ca649730d4ad48a080b8db48421fc1c8be0a00fd          |  docs:update feature/authentication                              | 16/05/2025  |
| Corebyte/Corebyte-Front-End-App        | feature/batch-management         | 1e8a8b4e83f5bf2226e098d34aa4ec24e3c03458          |  batch-management ui                                             | 16/05/2025  |
| Corebyte/Corebyte-Front-End-App        | feature/profile-management       | cc510edd2035838756c16fda6eb219a0eaf6023a          |  Create benefits.component.vue                                   | 16/05/2025  |

#### 5.2.2.5. Execution Evidence for Sprint Review. 

El objetivo de este sprint fue realizar, en colaboracion con todo el equipo, la creacion del front-end application.

<p align="center">
  <img src="../assets/img/chapter-V/imagen1.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

<p align="center">
  <img src="../assets/img/chapter-V/imagen2.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

<p align="center">
  <img src="../assets/img/chapter-V/imagen3.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

<p align="center">
  <img src="../assets/img/chapter-V/imagen4.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

<p align="center">
  <img src="../assets/img/chapter-V/imagen5.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

<p align="center">
  <img src="../assets/img/chapter-V/imagen6.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

<p align="center">
  <img src="../assets/img/chapter-V/imagen7.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

<p align="center">
  <img src="../assets/img/chapter-V/imagen8.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

<p align="center">
  <img src="../assets/img/chapter-V/imagen9.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

<p align="center">
  <img src="../assets/img/chapter-V/imagen10.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

<p align="center">
  <img src="../assets/img/chapter-V/imagen11.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

<p align="center">
  <img src="../assets/img/chapter-V/imagen12.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

<p align="center">
  <img src="../assets/img/chapter-V/imagen13.png" 
  alt="Sprint goal y Stories del Sprint #2"/>


#### 5.2.2.6. Services Documentation Evidence for Sprint Review. 

| Endpoint                             | Acción                           | Verbo HTTP                                         | Descripción                                                   | Ejemplo de Response |
|--------------------------------------|----------------------------------|----------------------------------------------------|---------------------------------------------------------------|---------------------|
| /products      | almacenar los productos ingresados                          | POST           |  Mostrara los proudctos almacenados                                            | {"id": "1001","customer": "Carlos Vega","date": "2025-05-14","product": "Cabernet Sauvignon","amount": 6,"total": 1200,"status": "Pendiente"} |
| /record      | almacenar los los informes de los productos                          | POST           |  Mostrara la lista de productos registrado para generar el informe                                            | {"id": "1001","customer": "Carlos Vega","type": "Cabernet Sauvignon","year": "2025","producer":"Cabernet Sauvignon","batch": 6,"stock": 1200}, |
| /orders      | almacenar los productos ingresados de las ordenes generados                          | POST           |  Mostrara los proudctos en la tabla de ordenes                                            | {"id": "1001","client": "Bodega El Sol","date": "2025-06-01","product": "Vino Tinto Reserva 2020","quantity": 10,"total": 1200,"imageUrl": "https://ferrand.com.pe/cdn/shop/files/B3DC6785-9365-4C2B-A774-E75DE90C526B.png?crop=center&height=480&v=1729894924&width=480"} |

#### 5.2.2.7. Software Deployment Evidence for Sprint Review. 
La organizacion de nuestro codigo se realizo en un repositorio en GitHub. Para el despliegue del front-end application

- Primero se creo un repositorio para alojar el codigo del front-end application
- Segundo, cada integrante del equipo creo una rama de cada funcion del front-end application

<p align="center">
  <img src="../assets/img/chapter-V/rama.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

- Tercero, se realizo el merge a develop para corregir errores

#### 5.2.2.8. Team Collaboration Insights during Sprint. 

El proyecto se realizo mediante repositorio en GitHub. Integrantes participantes:

<p align="center">
  <img src="../assets/img/chapter-V/people.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

Commits de los integrantes en el Landing Page:

<p align="center">
  <img src="../assets/img/chapter-V/advance.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

Grafico de los push y merge realizados por el equipo:

<p align="center">
  <img src="../assets/img/chapter-V/push-merge.png" 
  alt="Sprint goal y Stories del Sprint #2"/>

## 6. Conclusiones, Bibliografía y Anexos.

### Conclusiones 

El objetivo principal de este informe es proporcionar un análisis exhaustivo y detallado que describa la solución de software propuesta, conocida como ElixirControl. Para cumplir con este objetivo, es necesario ofrecer una descripción clara y concisa del proyecto, que abarque todos los aspectos relevantes, desde la concepción inicial de la idea hasta la especificación de los requisitos técnicos y las funcionalidades deseadas para el sistema. Este análisis debe ser lo suficientemente completo para proporcionar una comprensión profunda de cómo ElixirControl abordará las necesidades específicas del sector vitivinícola, ofreciendo una solución integral que optimice diversos procesos dentro de esta industria.

Dentro de este contexto, las user stories (historias de usuario) juegan un papel esencial en el proceso de desarrollo de ElixirControl. Estas historias permiten expresar los requisitos del sistema de forma simple, directa y orientada a las necesidades del usuario final. Las user stories no solo facilitan la comunicación entre los miembros del equipo de desarrollo, sino que también garantizan que las funcionalidades del software estén alineadas con las expectativas reales de los usuarios. De este modo, se asegura que el equipo de desarrollo se enfoque en crear un producto que no solo sea técnicamente sólido, sino que también cumpla con las expectativas de los clientes en términos de usabilidad, eficiencia y funcionalidad.

Además, las user stories son fundamentales en el marco de trabajo ágil, ya que permiten una evolución continua y una retroalimentación constante durante todo el ciclo de vida del desarrollo del software. Este enfoque iterativo facilita la adaptación a cambios en los requisitos y mejora la capacidad del producto para satisfacer las necesidades dinámicas del sector vitivinícola. En resumen, las user stories no solo son un componente clave para organizar y priorizar el trabajo del equipo, sino que también juegan un papel crucial en la creación de una experiencia de usuario óptima, que es uno de los objetivos centrales de ElixirControl.

En conclusión, este informe busca ofrecer una visión detallada y precisa de la solución de software ElixirControl, subrayando cómo las user stories son herramientas esenciales que permitirán al equipo de desarrollo centrarse en lo que realmente importa: crear un producto que aborde de manera efectiva las necesidades del sector vitivinícola y facilite la gestión de los procesos productivos y logísticos en esta industria.

### Bibliografía

Celis Escudero, F. R. (2001). Elaboración de vino con mosto concentrado de uva borgoña negra (Vitis labrusca) [Tesis, Universidad Nacional de San Martín]. Repositorio UNSM. https://repositorio.unsm.edu.pe/bitstream/11458/58/1/21%272%2700075.pdf

Celis Escudero, F. R. (2001). Elaboración de vino con mosto concentrado de uva borgoña negra (Vitis labrusca) [Tesis, Universidad Nacional de San Martín]. Repositorio UNSM. https://repositorio.unsm.edu.pe/bitstream/11458/58/1/21%272%2700075.pdf

Gómez Rubio, D. J. (2014). Investigación científica y tecnológica de la vinificación de la uva Red Globe (Vitis Vinífera L.) [Tesis, Universidad Católica de Santa María]. Repositorio UCSM. https://repositorio.ucsm.edu.pe/items/8d95b4ac-8c09-4354-8df7-2507eed3c70a

Husnayo Guillermo, E. G. (2012). Análisis económico de la elaboración del vino en Tacna [Tesis, Universidad Nacional Jorge Basadre Grohmann]. Repositorio UNJBG. https://repositorio.unjbg.edu.pe/server/api/core/bitstreams/668098dd-4976-4b2f-9acf-2c7bdb6cfc28/content

Wein Manager App. (n.d.). Track your wine cellar inventory with our professional Wine Cellar Manager app. Retrieved September 27, 2024, from https://winemanager.app

VinoTEC. (n.d.). Software ERP y CRM - Bodegas y cooperativas vitivinícolas. Retrieved September 27, 2024, from https://vinotec.net

Vintrace. (n.d.). Winery software | A better way to make wine. Retrieved September 27, 2024, from https://www.vintrace.com


### Anexos

| **Sección**                         | **Características del video**  | **Sobre el contenido** | **Integración y entrega**                                                                 |
|-------------------------------------|--------------------------------|------------------------|-------------------------------------------------------------------------------------------|
| **Needfinding Interviews**          | Cantidad de videos: 1         | Nomenclatura: upc-pre-202501-1ASI0730-4424-CoreByte-needfinding-sprint-1 | Formato: .mp4 <br> Consolida todas las entrevistas realizadas <br> [Link]() |
| **Exposición**                      | Cantidad de videos: 1         | Nomenclatura: upc-pre-202501-1ASI0730-4424-CoreByte-expo-tb1 | Formato: .mp4 <br> Consolida las exposiciones de la TB1 <br> [Link]() |
| **Prototypes Navigation / Product Navigation** | Cantidad de videos: 1         | Nomenclatura: upc-pre-202501-1ASI0730-4424-CoreByte-prototype-navigation-sprint-1 | Formato: .mp4 <br> Consolida demostración del flujo de navegación de las aplicaciones, priorizando los user flows relacionados con el core business. <br> [Link]() |
| **Validation Interviews**            | Contenido                     | Contenido              | Contenido                                                                                 |
| **About the Product**               | Cantidad de videos: 1         | Nomenclatura: upc-pre-202501-1ASI0730-4424-CoreByte-aboutthe-product-sprint-3 | Formato: .mp4 <br> Orientación promocional, resumiendo el modelo de negocio, las características y beneficios del producto, incluyendo algunas escenas de interacción con el producto y al menos una opinión por cada segmento objetivo. <br> [Link]() |
| **About the Team**                  | Contenido                     | Contenido              | Contenido                                                                                 |
| **Conclusiones, Bibliografía y Anexos** | Contenido                     | Contenido              | Contenido                                                                                 |

