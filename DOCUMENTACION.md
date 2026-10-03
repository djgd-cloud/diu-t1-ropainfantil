# Documentación de la interfaz — Mini Figma

## 1. Justificación del diseño
### 1.1 Importancia del diseño centrado en el usuario
    El diseño centrado en el usuario es muy importante en el comercio electrónico infantil, esto debido a que quien elige y paga el producto no es quien finalmente lo recibe.
    Diseñar partiendo de las bases del usuario permite minimizar la incertidumbre sobre tallas, agilizar la toma de decisiones y reducir la tasa de abandono asegurado en una interfaz accesible, intuitiva y perdecible.
### 1.2 Objetivos y metas del proyecto      
    - Reducción de tiempo de compra: permitir que el usuario localice el producto que sea de manera bastante intuitiva de modo que el tiempo de selección sea menos de 2 minutos.
    - Eficiencia en la consulta de tallas: que al menos el 90% de usuarios consulten la guía de tallas a los 10 segundos de estar desde la ficha de producto.
    - Mayor resolución de errores en checkout: Que el 85% de usuarios identifiquen un error del formulario en 45 segundos o menos.
### 1.3 Beneficios esperados                 
    Para el usuario: Conseguir una interfaz bastante intuitiva de modo que no tenga que perder mucho tiempo en la aplicación.
    Para el negocio: Que recibamos menos devoluciones por talla equivocada para los niños y poder retener a más clientes habituales.

## 2. Investigación y análisis de usuarios
### 2.1 Datos demográficos y segmentación
    El público ojetivo se divide en dos segmentos habituales:
    - Segmento primario: Se tratan más que nada de padres o tutores legales de entre 25 a 45. Usan de forma habitual los dispositivos móviles y que al disponer de poco tiempo le proporcionamos métodos de compra bastante rápidas.
    - Segmento secundario: Son familiares mayores, de entre unos 55 a 75 años. Ellos no cuentan con muchas habilidades tecnológicas por lo que nuestra plataforma al ser rápida e intuitiva le vendrá perfecta para ellos.

### 2.2 Personas                             
    *Persona 1: Javier Gallego - Comprador habitual
        - Edad: 30 años.
        - Contexto: Es padre de familia con dos hijos y se pasa todo el tiempo en oficina, por los que las compras de cumpleaños, navidades, fiestas, etc... las hace en sus descando del trabajo por lo que no tiene mucho tiempo que perder.
        - Objetivos: Encontrar ropa para el cumpleaños de su hijo Federico y Ramona filtrando por edades.
        - Frustraciones: Catálogos mal organizados sin separación clara por meses o años y cambios de equivalencia de talla entre las marcas.

    *Persona 2: Eloy Jímenez - Comprador de regalos
        - Edad: 67 años.
        - Contexto: es una persona jubilada que no se maneja muy bien con un dispositivo móvil. Busca algo de ropa para el cumpleaños de su nieta Manuela.
        - Objetivos: acertar las medidas exáctas sin tener que preguntarle a sus padres y completar el pedido sin confusiones visuales.
        - Frustraciones: la letra pequeña, los contrastes bajos y mensajes de error que no explican de manera clara cuál es el fallo.

### 2.3 Análisis de la competencia           
    *Zara Kids
        - Que hace bien: Fotografía detallada y navegación visual.
        - Que hacen mal: Tipografía pequeña y bajo contraste.
        - Que nos llevamos: Estructura limpia de cuadrícula cuidando el contraste y la legibilidad.
    *H&M
        - Que hace bien: Dividir bien los trampos de edad en el menú principal.
        - Que hacen mal: Proceso de checkout sobrecargado con avisos promocionales.
        - Que nos llevamos: Menú de categorias dirtectas por edad.
    *Mayoral
        - Que hace bien: Fichas de producto que comentan varias especificaciones del tejido.
        - Que hacen mal: Menús de filtros lentos y quitaron la opción de deshacer del carrito de compra.
        - Que nos llevamos: Uso de filtros en el catálogo y que es importante la opción de deshacer del carrito.

### 2.4 Insights y hallazgos clave           
    - Dudas recurrentes en el tallaje infantil: Para el crecimiento de talla del niño entre compra del producto a dentro de unos meses hemos incorporado un botón de "Guía de tallas" en el que el producto que despliega un botón interactivo con medidas equivalentes a la edad.
    - Necesidad de filtrado ágil sin salir del listado: Los compradores quieren saber las opciones según la edad y el presupuesto de manera inmediata. Para ello usamos el filter chips de Material Design 3 y selector de ordenación en la cabecera del catálogo.
    - Miedo al borrado accidental en la cesta: En pantallas táctiles es común pulsar sin querer sobre la papelera por error. Para ello usaremos un aviso emergente con snackbar con el que podamos deshacer la desición que se ha tomado.
    - Frustración ante errores en el formulario de pago: Los usuarios abandonan la compra si no encuentran el causante del fallo. Para ello hemos implementado text fields para que los errores sean visibles con iconos semánticos y textos de ayuda claros.