🚗 Electric Car Store

Este proyecto es un template de frontend estático para una tienda en línea de vehículos eléctricos. Presenta una interfaz con un catálogo de productos, opciones de filtrado y una estructura de navegación básica.✨ Características Principales
Diseño: Estructura web simple basada en HTML5 y CSS (asumiendo estilos definidos en ./assets/style.css).
Navegación: Barra de navegación (<nav>) con el nombre de la tienda ("Electric Cars") y enlaces principales (Inicio, Catálogo, Ofertas, Contacto).
Filtrado de Productos: Barra lateral (<aside>) para ordenar los productos por Precio, Modelo o Marca.
Catálogo de Productos: Presentación de vehículos mediante tarjetas (<article class="card">) que incluyen:
Imagen del vehículo con link para verla en una nueva pestaña.
Nombre del modelo (ej: BYD Dolphin Mini, Chevrolet Bolt EUV).
Tipo de modelo (ej: City Car, Station, SUV).
Botón "Ver mas...".
Paginación: Componente de paginación básico para navegar por los resultados.
Pie de Página: Contiene íconos de redes sociales (Facebook, Instagram) y un aviso de derechos de autor.
🛠️ Tecnologías Utilizadas
HTML5
CSS (archivo local ./assets/style.css)
Iconografía Externa:
Material Design Icons (para el ícono del logo)
Font Awesome (para los íconos sociales)
📁 Estructura del Proyecto

La estructura del código proporcionado sugiere la siguiente organización de archivos:
.
├── assets/
│   ├── icons/
│   │   └── icons/
│   │       └── icons.css (Asumido)
│   ├── img/
│   │   ├── Auto1.jpg
│   │   ├── Auto2.jpg
│   │   ├── Auto3.jpg
│   │   ├── Auto4.jpg
│   │   └── Auto5.jpg
│   └── style.css
└── index.html  <-- Archivo principal con el código HTML
🚀 Instalación y Uso

Dado que este es un proyecto de frontend puramente estático (HTML y CSS):
Descarga o clona el código fuente.
Asegúrate de que la carpeta assets/ contenga las imágenes (Auto1.jpg a Auto5.jpg) y los archivos CSS necesarios.
Abre el archivo index.html directamente en cualquier navegador web moderno. No se requiere de un servidor web.
🛒 Modelos en Catálogo

El catálogo inicial presenta los siguientes modelos de vehículos eléctricos:
BYD Dolphin Mini (Model: City Car)
Great Wall Ora O3 (Model: City Car)
Fiat 500e (Model: City Car)
Chevrolet Bolt EUV (Model: Station)
Omoda E5 (Model: SUV)