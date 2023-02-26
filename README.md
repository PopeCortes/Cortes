
# Investigar acerca del modelo en MVC

El Modelo-Vista-Controlador (MVC) es un patrón de arquitectura de software que se utiliza comúnmente en el desarrollo de aplicaciones web y de escritorio. Este patrón de diseño separa la lógica de la aplicación en tres componentes principales: el modelo, la vista y el controlador. Cada uno de estos componentes tiene una función específica y está diseñado para trabajar en conjunto para proporcionar una experiencia de usuario eficiente y escalable.

## Vista

La vista es el componente de la aplicación que se encarga de la presentación de los datos al usuario. Esto incluye la generación de páginas web, la creación de formularios, la visualización de gráficos y otros elementos visuales.


![App Screenshot](https://static.wixstatic.com/media/af8b51_8f89c429555a4fc8a98a940095f7f30d~mv2.jpg/v1/fill/w_396,h_465,al_c,q_80,enc_auto/img6.jpg)


## funcionalidades de la aplicación


~Registro de usuarios,

~Inicio de sesión de usuarios

~Visualización de información de la cuenta del usuario

~Actualización de la información de la cuenta del usuario

~Visualización de una lista de productos
Búsqueda de productos

~Visualización de detalles de un producto

~Agregar productos al carrito de compras

~Actualización de la cantidad de productos en el carrito de compras

~Eliminación de productos del carrito de compras

~Procesamiento de pagos

~Envío de confirmación de compra al usuario

## Definir la infraestructura para el almacenamiento y recuperación de datos del modelo vista controlador

~ Se utilizará una base de datos relacional para almacenar la información del usuario, la información del producto y los detalles de la compra.

~ El modelo utilizará un ORM (Object-Relational Mapping) para interactuar con la base de datos y manejar las operaciones de lectura y escritura de datos.

~ Para la recuperación de datos, el modelo utilizará consultas SQL para obtener los datos de la base de datos y devolverlos al controlador.

~ El controlador utilizará los datos obtenidos del modelo para seleccionar la vista adecuada y presentar la información al usuario.

~ La vista utilizará plantillas HTML y CSS para generar la interfaz de usuario y presentar los datos de manera clara y organizada.
