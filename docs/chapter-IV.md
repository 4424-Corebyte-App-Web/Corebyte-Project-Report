# Capítulo IV: Product Design

## 4.1. Style Guidelines.

### 4.1.1. General Style Guidelines.
1. Branding:
- Logo y Marca: El logo se mostrará en la parte superior izquierda de la pantalla de manera clara y visualmente agradable, tal como se ve en las pantallas del login.
- Paleta de colores:
  - Colores Primarios:
    - Burdeos profundo (#7B1E3D): Dominante en el diseño, utilizado en los encabezados, bordes principales y títulos principales.
    - Verde Oliva (#556B2F): Utilizado para botones de acción (Principal, secundaria y de navegación), tales como "Agregar cliente", "Guardar", "Ver pedidos", etc.
    - Carbón profundo (#1A1A1A): Color principal de fondo, brindando una apariencia clara y minimalista.
  - Colores Secundarios:
    - Carbón Oscuro (#242424): Color utilizado en el pie de página o footer, también en bordes de botones.
    - Dorado Metálico (#DAA520): Se utiliza para destacar elementos importantes o de acento, como botones de acción.
    - Gris Pizarra (#708090): Se utiliza para áreas de fondo secundarias o inactivas.
    - Gris Medio (#333333): Para detalles elegantes y áreas de énfasis.
  - Colores Neutrales:
    - Blanco (#FFFFFF): Sera escencial para el fondo, debido que asegura que el contenido sea legible y que la interfaz luzca amplia y despejada.
    - Gris Claro (#CCCCCC): Es lo mas recomendable para textos y elementos gráficos.

![paleta de colores](/assets/img/chapter-IV/paleta_colores.png)

2. Typography:
- Fuente Principal:
  - Nombre: Winky Rough, se utilizará para encabezados y textos de cuerpo. Da la sensación de elegancia y tradición, adecuada para el tema del viñedo.
  - Tamaños:
    - H1: 80px
    - H2: 50px
    - H3: 35px
    - Texto de cuerpo: 25px
    - Subtítulos y textos menores: 16px
- Fuente Secundaria:
  - Nombre: Roboto, se utilizará para textos secundarios, botones, y etiquetas
3. Colors:
- Backgrounds:
  - Principal: Blanco (#FFFFFF) para la mayoría de las páginas.
  - Secundario: Beige Suave (#F5F5DC) para secciones diferenciadas.
- Textos:
  - Primario: Vino Tinto (#8B0000) para el contenido principal.
  - Secundario: Negro (#000000) para subtítulos y textos complementarios.
- Elementos Interactivos:
  - Botones: Oro Antiguo (#CFAE75) con texto en Marrón Bodega (#5D4037).
  - Hover: Burdeos (#800020) para resaltar interacciones.
4. Spacing:
- Margenes y Padding:
  - Margen general de 16px alrededor del contenido.
  - Espaciado de 8px entre elementos relacionados.
  - Uso de espacio en blanco para asegurar una lectura cómoda y evitar la saturación visual.
5. Tono de Comunicación y Lenguaje:
- Tono: Formal y Respetuoso, reflejando la seriedad y profesionalismo en la gestión del viñedo.
- Lenguaje: Claro y Preciso, evitando tecnicismos innecesarios pero manteniendo la profesionalidad.

### 4.1.2. Web Style Guidelines.
1. Layout:
- Sistema de Grid: Basado en un layout de columnas para garantizar flexibilidad y adaptabilidad en diferentes tamaños de pantalla.
- Headers y Footers: Fijos en la parte superior e inferior de la pantalla con espacio para navegación principal, búsqueda, y acceso rápido a secciones clave.
- Cards: Usados para mostrar módulos individuales como con sombras y bordes redondeados para un aspecto moderno.
2. Responsive Design:
- Desktop: Columnas de contenido principal, con menús laterales y una barra de búsqueda.
- Tablet: Columnas de contenido, con navegación accesible desde un menú desplegable y expandido para adaptarse a la pantalla extendida.
- Mobile: Columnas de contenido, navegación a través de un menú desplegable.
3. Interaction Design:
- Botones: Grandes y fáciles de interactuar, con animaciones para indicar interactividad.
- Formularios: Campos claros y espaciados, con validación en tiempo real y mensajes de error amigables.
4. Images and Icons:
- Imágenes: De alta calidad y representativas del viñedo y sus operaciones, optimizadas para web.
- Íconos: Set de íconos de estilo lineal y minimalista.
5. Repositorio Central:
- Organización:
  - Carpeta de Estilos: Se creará una carpeta donde se almacenen todos los archivos CSS y SASS.
  - Repositorio de Assets: Todos los activos visuales como imágenes, iconos y logos estarán centralizados en una carpeta con subcarpetas organizadas por tipo.
  - Versionado: Se usará Git para rastrear cambios en los archivos de estilos y para asegurarse de que todos los miembros del equipo trabajen con la versión más reciente.
## 4.2. Information Architecture.

### 4.2.1. Organization Systems.
1. Jerarquía de Contenidos:

- La información se organiza en niveles jerárquicos que van de lo general a lo específico, facilitando la navegación progresiva.
- Secciones Principales: Incluyen áreas clave, como por ejemplo "Servicios", "Proveedor & Cliente", "Mi perfil", "Nosotros", etc.
- Subsecciones: Cada sección principal se divide en subsecciones más específicas, por ejemplo dentro de "Mi perfil" se pueden encontrar "Historial", "Descargars de reportes", "Configuracion de cuenta".
2. En la siguiente imagen podemos ver la organización visual de la página web la cualestá destinada para que la usen consumidores, proveedores y distribuidores:
- Consumidor:

El flujo inicia en la Landing Page, en donde el consumidor podrá ver nuestra información de la página web. Seguido el consumidor elegira la opcion de usuario consumidor, lo cual lo llevara a iniciar sesion o registro de cuenta en donde llenara sus datos. Luego podra iniciar sesion y lo llevara al apartando en el cual 
se mostrará todas las opciones que tiene para elegir. La opcion <strong>*Servicios*</strong> lo redireccionara a un apartado donde podra ver las opciones "modulos de trazabilidad" y "generacion de qr de reportes", tambien la opcion <strong>*Proveedor & Cliente*</strong> que contra con las opciones "gestion de distribuidores" y "panel de consumidores", a si mismo la opcion <strong>*Perfil*</strong> contara con las opciones "historial" que mostrara las fechas de las generaciones de reportes anteriores, "descarga de reportes" y "configuracion de cuenta", por otro lado estara la opcion de <strong>*Nosotros*</strong> que tendra informacion sobre todo el equipo, finalmente vera la opcion de <strong>*Contacto*</strong> en donde podrá mandarnos mensajes por correo electrónico o por via WhatsApp.

![organizacion_visual_consumidor](/assets/img/chapter-IV/organizacion_visual_consumidor.png)
- Productor:

El flujo inicia en la Landing Page, en donde el producto podrá la información de los productos la página web. Seguido el productor elegira la opcion de usuario productor, lo cual lo llevara a iniciar sesion o registro de cuenta en donde llenara sus datos. Luego podra iniciar sesion y lo llevara al apartando en el cual se mostrará todas las opciones que tiene para elegir. La opcion <strong>*Mi viñedo*</strong> lo redireccionara a un apartado donde podra ver las opciones "gestion de lotes", tambien la opcion <strong>*Registro de produccion*</strong> que contra con las opciones "cnonograma de fermentacion", a si mismo la opcion <strong>*Generacion de reporte*</strong> contara con las opciones "historial" que mostrara las fechas de las generaciones de reportes anteriores y "descarga de reportes", finalmente vera la opcion de <strong>*Configuracion de cuenta*</strong> en donde podrá configurar la notificaciones y seguridad de la cuenta.

![organizacion_visual_consumidor](/assets/img/chapter-IV/organizacion_visual_productor.png)

- Distribuidor:

El flujo inicia en la Landing Page, en donde el distribuidor podrá la información de los productos la página web. Seguido el distribuidor elegira la opcion usuario distribuidor, lo cual lo llevara a iniciar sesion o registro de cuenta en donde llenara sus datos. Luego podra iniciar sesion y lo llevara al apartando en el cual se mostrará todas las opciones que tiene para elegir. La opcion <strong>*Gestion de pedidos*</strong> lo redireccionara a un apartado donde podra ver las opciones "ver ordenes de pedidos" y "procesar ordenes de pedido", tambien la opcion <strong>*Seguimiento*</strong> que contra con las opciones "estado", a si mismo la opcion <strong>*Acceso*</strong> contara con las opciones "historial" que mostrara las fechas de las generaciones de reportes anteriores, ademas se podra ver <strong>*Reportes de venta*</strong> la cual mostrara la opcion "analisis de venta" y "analisis de periodo",tambien mostrara la opcion <strong>*Productores*</strong> la cual mostrara la opcion "solicitud de stock" que sera enviado por parte del productor,finalmente vera la opcion de <strong>*Configuracion de cuenta*</strong> en donde podrá configurar la notificaciones.

![organizacion_visual_consumidor](/assets/img/chapter-IV/organizacion_visual_distribuidor.png)
### 4.2.2. Labeling Systems.
- Nomenclatura:

Se utiliza un lenguaje claro y directo, evitando tecnicismos y jergas que puedan confundir al usuario.
Los nombres de secciones, botones y enlaces son descriptivos, reflejando exactamente lo que el usuario encontrará al hacer clic.
- Consistencia:

Se mantiene una nomenclatura uniforme en toda la aplicación, evitando la confusión que podría generar el uso de términos diferentes para referirse al mismo concepto.
- Lenguaje Adaptativo:

El lenguaje utilizado se adapta al contexto del usuario, asegurando que sea fácil de entender tanto para usuarios nuevos como experimentados.
### 4.2.3. SEO Tags and Meta Tags
- Title Tags:

  - Landing Page: "Trazabilidad Vitivinícola – Plataforma Integral para Productores, Distribuidores y Consumidores"
  - Web Application: "Corebyte Panel – Gestión y Trazabilidad del Viñedo en Tiempo Real"
- Meta Description:

  - Landing Page: "Corebyte conecta a productores, distribuidores, certificadoras y consumidores de vino en una sola plataforma. Asegura trazabilidad y calidad desde la cosecha hasta la copa"
  - Web Application: "Gestiona lotes, monitorea cada etapa del proceso y descarga reportes avanzados en tiempo real. Control integral de tu viñedo con Corebyte"
- Keywords:

  - Landing Page: "trazabilidad del vino, plataforma vitivinícola, gestión de viñedo, conexión productor-consumidor, calidad certificada"
  - Web Application: "panel de trazabilidad, software de viñedo, gestión de lotes, monitorización vitivinícola, reportes de producción"
- Author:
  - Corebyte
### 4.2.4. Searching Systems.
En esta sección nosotros algunos metodos para facilitar la expericiencia de busqueda para el usuario cosumidor, productor y distribuidor
- Barra de Búsqueda:

  - La barra de búsqueda estará ubicada de manera prominente en el header, accesible desde cualquier página.
  - Se implementará un sistema de búsqueda predictiva que sugiere resultados mientras el usuario escribe, mejorando la velocidad y precisión de las búsquedas.

- Filtros y Facetas:

  - Consumidor: En los filtros contara con distintos apartados para facilitar la busqueda como variedad de vinos, precio, región y puntuación de calidad
  - Productor: En los filtros contara con distintos apartados para facilitar la busqueda entre ellos Fecha de cosecha, etapa de producción y estado de lote
  - Distribuidor:  En los filtros contara con distintos apartados para facilitar la busqueda los cuales cuenta con región de destino, estado de envío y peso de pedido
  - Las facetas se presentan en panel lateral o desplegable

- Historial de Búsqueda:

  - Consumidor: Lista alfabética de últimas búsquedas y productos vistos
  - Productor: Consultas sobre lotes y reportes, los cuales seran ordenados por fechas
  - Distribuidor: Historial de búsquedas de pedidos y productores

- Resultados Relevantes:

  - Los resultados de búsqueda se ordenarán por relevancia, basados en la frecuencia de uso y la importancia del contenido.

### 4.2.5. Navigation Systems.

1. Navegación Global:

  - Un menú principal ubicado en el header proporcionará acceso a las secciones clave de la aplicación.
  - El menú estará siempre visible en dispositivos de escritorio.
    
2. Navegación Contextual:

  - Menús y enlaces contextuales dentro de cada sección permitirán al usuario profundizar en tareas específicas sin perder la orientación dentro de la aplicación.

3. Navegación Secundaria:

  - En la barra lateral se presentarán opciones de navegación adicionales, como accesos directos a herramientas y recursos utilizados frecuentemente.

## 4.3. Landing Page UI Design.

### 4.3.1. Landing Page Wireframe.
El wireframe de la página de aterrizaje es una representación visual básica que muestra la estructura y el diseño fundamental de la página. Actúa como un esquema inicial para guiar el desarrollo del diseño final, asegurando una disposición clara de los elementos principales.

Este wireframe incluirá las siguientes secciones:

1. **Nav y Hero:**

![](/assets/img/chapter-IV/inicio.png)

2. **Nosotros:**

![](/assets/img/chapter-IV/nosotros.png)

3. **Servicios:**

![](/assets/img/chapter-IV/servicios.png)

4. **Precios:**

![](/assets/img/chapter-IV/precios.png)

5. **Acerca:**

![](/assets/img/chapter-IV/acerca.png)

6. **Contacto:**

![](/assets/img/chapter-IV/contacto.png)

7. **Footer:**

![](/assets/img/chapter-IV/footer.png)

Este wireframe será el punto de partida para la creación del diseño visual y facilitará una experiencia de usuario cohesiva y efectiva.

### 4.3.2. Landing Page Mock-up.

Hero de la aplicación El hero de nuestra plataforma de vinos presenta una imagen de fondo que resalta una botella de vino cuidadosamente seleccionada, junto a un botón de llamado a la acción <strong>"Empiezza ahora"</strong> que invita a los usuarios a explorar. Con un título atractivo y una breve descripción, el hero captura la esencia de nuestra propuesta, mientras que una barra de navegación permite acceder fácilmente a las diferentes secciones de la app, ofreciendo una experiencia inmersiva y fluida.

![](/assets/img/chapter-IV/inicio-color.png)

1. **Nosotros-Corebyte:**

![](/assets/img/chapter-IV/nosotros-color.png)

2. **Servicios-Corebyte:**

![](/assets/img/chapter-IV/servicios-color.png)

3. **Precios-Corebyte:**

![](/assets/img/chapter-IV/corebyte-color.png)

4. **Acerca-Corebyte:**

![](/assets/img/chapter-IV/acerca-color.png)

5. **Contacto-Corebyte:**

![](/assets/img/chapter-IV/contacto-color.png)

6. **Footer-Corebyte:**

![](/assets/img/chapter-IV/footer-color.png)

## 4.4. Web Applications UX/UI Design.

El objetivo de esta sección Web Applications UX/UI Design es detallar el enfoque y las estrategias utilizadas en el diseño de la experiencia y la interfaz de usuario para la aplicación web. Se busca explicar cómo las decisiones tomadas en términos de diseño visual y funcionalidad contribuyen a mejorar la usabilidad, accesibilidad y satisfacción del usuario final. Además, se pretende mostrar cómo estos elementos de diseño ayudan a cumplir los objetivos comerciales del proyecto, asegurando una interacción fluida y eficiente para los usuarios en diferentes dispositivos.

### 4.4.1. Web Applications Wireframes.

En esta sección se muestran los wireframes realizados para nuestro Web Application.

1. Inicio-Corebyte:

![text](/assets/img/chapter-IV/inicio-4.png) 

2. Inicio sesión-Corebyte:

![text](/assets/img/chapter-IV/inicio-sesion-productor.png) 

3. Registrarse-Corebyte:

![text](/assets/img/chapter-IV/registro-productor.png) 


4. Historial-Corebyte:

![text](/assets/img/chapter-IV/historial-productor.png) 

5. Fermentacion-Corebyte:

![text](/assets/img/chapter-IV/fermentacion-productor.png) 

6. Inicio sesión distribuidor-Corebyte:

![text](/assets/img/chapter-IV/inicio-sesion-distribuidor.png) 

7. Regsitrarse distribuidor-Corebyte:

![text](/assets/img/chapter-IV/registro-distribuidor.png) 

8. Gestion-Corebyte:

![text](/assets/img/chapter-IV/gestion-pedidos-distribuidor.png) 

9. Seguimiento-Corebyte:

![text](/assets/img/chapter-IV/seguimiento-distribuidor.png) 

10. Acceso-Corebyte:

![text](/assets/img/chapter-IV/acceso-distribuidor.png) 

11. Reporte de venta-Corebyte:

![text](/assets/img/chapter-IV/reporte-venta-distribuidor.png) 

12. Productores-Corebyte:

![text](/assets/img/chapter-IV/prductores-distribuidor.png) 

### 4.4.2. Web Applications Wireflow Diagrams.

Los Wireflows se emplean principalmente en el diseño de la experiencia de usuario (UX) y son especialmente útiles para aplicaciones que incluyen flujos de trabajo e interacciones complejas.

![text](/assets/img/chapter-IV/prototipo.png) 

### 4.4.3. Web Applications Mock-ups.
En esta sección se muestran los mock-ups realizados para nuestro Web Application.

1. Inicio-Corebyte:

![text](/assets/img/chapter-IV/inicio-color-4.png) 

2. Inicio sesión-Corebyte:

![text](/assets/img/chapter-IV/inicio-sesion-color.png) 

3. Registrarse-Corebyte:

![text](/assets/img/chapter-IV/registrarse-color.png) 


4. Historial-Corebyte:

![text](/assets/img/chapter-IV/historial-color.png) 

5. Fermentacion-Corebyte:

![text](/assets/img/chapter-IV/fermentacion-color.png) 

6. Inicio sesión distribuidor-Corebyte:

![text](/assets/img/chapter-IV/inicio-sesion-distribuidor-color.png) 

7. Regsitrarse distribuidor-Corebyte:

![text](/assets/img/chapter-IV/registrarse-distribuidor-color.png) 

8. Gestion-Corebyte:

![text](/assets/img/chapter-IV/gestion-pedidos-color.png) 

9. Seguimiento-Corebyte:

![text](/assets/img/chapter-IV/seguimiento-color.png) 

10. Acceso-Corebyte:

![text](/assets/img/chapter-IV/acceso-color.png) 

11. Reporte de venta-Corebyte:

![text](/assets/img/chapter-IV/reporte-venta-color.png) 

12. Productores-Corebyte:

![text](/assets/img/chapter-IV/productores-color.png) 
### 4.4.4. Web Applications User Flow Diagrams.
En esta seccion presentamos los principales recorridos que nuestro segmento objetivo realizara dentro de la página web.

- User goal:Como usuario, quiero tener una experiencia de usuario fluida e intuitiva dentro de la plataforma, para que todas las funcionalidades sean fáciles de encontrar y usar.

![text](/assets/img/chapter-IV/user-goal-1.png) 


- User goal: **Como** vinicultor, **quiero** gestionar mi cartera de clientes distribuidores **para** organizar las relaciones comerciales y asegurar un seguimiento adecuado de las órdenes y preferencias de cada cliente.

![text](/assets/img/chapter-IV/user-goal-2.png) 

## 4.5. Web Applications Prototyping.

## 4.6. Domain-Driven Software Architecture.

### 4.6.1. Software Architecture Context Diagram.

### 4.6.2. Software Architecture Container Diagrams.

### 4.6.3. Software Architecture Components Diagrams.

## 4.7. Software Object-Oriented Design.

### 4.7.1. Class Diagrams.

### 4.7.2. Class Dictionary.

## 4.8. Database Design.

### 4.8.1. Database Diagram
