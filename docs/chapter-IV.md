# Capítulo IV: Product Design

## 4.1. Style Guidelines.

### 4.1.1. General Style Guidelines.

### 4.1.2. Web Style Guidelines.

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

### 4.3.2. Landing Page Mock-up.

## 4.4. Web Applications UX/UI Design.

### 4.4.1. Web Applications Wireframes.

### 4.4.2. Web Applications Wireflow Diagrams.

### 4.4.3. Web Applications Mock-ups.

### 4.4.4. Web Applications User Flow Diagrams.

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
