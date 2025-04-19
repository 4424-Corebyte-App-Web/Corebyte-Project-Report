# Capítulo IV: Product Design

## 4.1. Style Guidelines.

### 4.1.1. General Style Guidelines.

### 4.1.2. Web Style Guidelines.

## 4.2. Information Architecture.

### 4.2.1. Organization Systems.

### 4.2.2. Labeling Systems.

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems.

### 4.2.5. Navigation Systems.

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
En esta seccion se demostrará el diagrama de clases junto con la aplicación de varios patrones de diseño para mejorar tanto la estructura como la eficiencia del sistema.
### 4.7.1. Class Diagrams.
**Despliegue del diagrama de clase de Corebyte**
![diagram](/assets/img/chapter-IV/class-diagram.png)
### 4.7.2. Class Dictionary.
A continuación se presenta el código en formato markdown con las clases, atributos y métodos correspondientes:

### User

| Atributos           | Tipos    |
|---------------------|----------|
| id                  | Integer  |
| name                | String   |
| lastName            | String   |
| password            | String   |
| status              | Char     |

| Métodos                              | Descripción                                                                   |
|--------------------------------------|-------------------------------------------------------------------------------|
| login(username, password)            | Verifica las credenciales. Devuelve true si la autenticación es exitosa.       |
| register(name, lastName, password)   | Registra un nuevo usuario con la información proporcionada.                   |
| updateProfile()                      | Actualiza la información del perfil del usuario.                              |
| changePassword(oldPassword, newPassword) | Cambia la contraseña si la contraseña antigua es correcta.                |


### Consumer  
| Atributos           | Tipos    |
|---------------------|----------|
| id                  | Integer  |
| name                | String   |
| lastName            | String   |
| password            | String   |

| Métodos                              | Descripción                                                                   |
|--------------------------------------|-------------------------------------------------------------------------------|
| login(username, password)            | Verifica las credenciales. Devuelve true si la autenticación es exitosa.       |
| register(name, lastName, password)   | Registra un nuevo usuario con la información proporcionada.                   |

### Distributor

| Métodos              | Descripción                                               |
|----------------------|-----------------------------------------------------------|
| manageDistributor()  | Administra la información del distribuidor.               |
| checkOrders()        | Devuelve la lista o estado de pedidos asignados.          |
| updateOrderStatus()  | Actualiza el estado de un pedido.                         |
| requestSupport()     | Envía solicitud de soporte o asistencia.                  |


### Producer

| Métodos                        | Descripción                                                       |
|--------------------------------|-------------------------------------------------------------------|
| manageWinemaking()             | Gestiona procesos de elaboración de producto.                     |
| checkInventory()               | Devuelve el inventario disponible.                                |
| registerProduct(name, price, type) | Registra un nuevo producto con nombre, precio y tipo.         |
| manageOrder()                  | Administra pedidos recibidos.                                     |
| requestSupport()               | Envía solicitud de soporte o asistencia.                          |


### Subscription

| Atributos   | Tipos   |
|-------------|---------|
| id          | Integer |
| userID      | Integer |
| planType    | String  |
| startDate   | Date    |
| endDate     | Date    |
| cost        | Decimal |

| Métodos                  | Descripción                                               |
|--------------------------|-----------------------------------------------------------|
| selectPlan()             | Selecciona y aplica el plan de suscripción.               |
| updateSubscription()     | Actualiza los datos de la suscripción.                    |
| cancelSubscription()     | Cancela la suscripción activa.                            |


### StartFeature

| Métodos       | Descripción                                      |
|---------------|--------------------------------------------------|
| access()      | Permite el acceso a las funcionalidades básicas. |
| viewReports() | Muestra los reportes limitados del plan Start.   |


### ProFeature

| Métodos              | Descripción                                            |
|----------------------|--------------------------------------------------------|
| access()             | Permite el acceso a las funcionalidades Pro.           |
| viewReports()        | Muestra reportes ampliados del plan Pro.               |
| inventoryManagement()| Gestiona el inventario asociado al plan Pro.           |


### PremiumFeature

| Métodos              | Descripción                                                    |
|----------------------|----------------------------------------------------------------|
| access()             | Permite el acceso a todas las funcionalidades Premium.         |
| viewReports()        | Muestra reportes completos y detallados.                       |
| inventoryManagement()| Gestión avanzada del inventario.                               |
| advancedAnalysis()   | Ofrece análisis avanzados y métricas exclusivas del plan Premium.|


### Order

| Atributos   | Tipos     |
|-------------|-----------|
| id          | Integer   |
| customer    | String    |
| date        | Date      |
| product     | String    |
| total       | Decimal   |
| amount      | Integer   |

| Métodos                                     | Descripción                                             |
|---------------------------------------------|---------------------------------------------------------|
| createOrder(customerID, productID, date, total) | Crea un nuevo pedido para el cliente con los datos dados.|


### OrderHistory

| Atributos         | Tipos   |
|-------------------|---------|
| id                | Integer |
| orderID           | Integer |
| registrationDate  | Date    |
| status            | Char    |

| Métodos    | Descripción                                 |
|------------|---------------------------------------------|
| download() | Descarga el historial o reporte del pedido. |


### ClientList

| Atributos   | Tipos    |
|-------------|----------|
| id          | Integer  |
| productID   | Integer  |
| clientID    | Integer  |
| address     | String   |
| phone       | String   |
| product     | String   |
| RUC         | String   |

| Métodos                                | Descripción                                          |
|----------------------------------------|------------------------------------------------------|
| createClient(clientID)                 | Agrega un cliente a la lista de distribución.        |
| updateClient(id, address, RUC, phone)  | Actualiza datos de contacto y RUC de un cliente.     |
| deleteClient(id)                       | Elimina un cliente de la lista.                      |


### Client

| Atributos   | Tipos    |
|-------------|----------|
| id          | Integer  |
| firstName   | String   |
| lastName    | String   |
| dni         | String   |
| email       | String   |

| Métodos                                           | Descripción                                                    |
|---------------------------------------------------|----------------------------------------------------------------|
| createClient(id, firstName, lastName, dni, email) | Crea un nuevo cliente con todos sus datos.                     |
| updateClient(id, firstName, lastName, dni, email) | Actualiza la información de un cliente existente.              |
| deleteClient(id)                                  | Elimina el cliente indicado por su ID.                         |
| validateDNI(dni)                                  | Verifica que el DNI tenga un formato válido. Devuelve true/false.|


### Product

| Atributos    | Tipos    |
|--------------|----------|
| id           | Integer  |
| name         | String   |
| description  | String   |
| price        | Decimal  |
| type         | String   |

| Métodos                                   | Descripción                                  |
|-------------------------------------------|----------------------------------------------|
| addProduct(name, description, price, type)| Agrega un nuevo producto al catálogo.        |
| updateProduct(id, name, description, price)| Modifica los datos de un producto existente. |
| deleteProduct(id)                         | Elimina el producto identificado por su ID.  |


### TypeProduct

| Atributos   | Tipos    |
|-------------|----------|
| id          | Integer  |
| name        | String   |
| description | String   |

| Métodos                                | Descripción                                                     |
|----------------------------------------|-----------------------------------------------------------------|
| createProductType(name, description)   | Crea un nuevo tipo de producto.                                 |
| updateProductType(id, name, description)| Actualiza nombre o descripción de un tipo existente.           |
| deleteProductType(id)                  | Elimina el tipo de producto indicado por su ID.                 |

## 4.8. Database Design.

### 4.8.1. Database Diagram
