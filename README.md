# BURGER HOUSE — Sistema Integral de Gestión de Restaurante (SIGR)

## Descripción
Prototipo académico de interfaz web para representar los componentes principales de un sistema de gestión de restaurante. Se desarrolla con HTML5 y CSS3, conservando la identidad visual BURGER HOUSE.

## Objetivo del taller
Establecer una línea base del código fuente y demostrar la gestión de configuración mediante Git y GitHub, registrando cambios incrementales, commits y versiones.

## Módulos contemplados
1. Autenticación de usuarios: perfiles de clientes, meseros y administrador.
2. Menú digital: platos, categorías, precios y disponibilidad.
3. Pedidos: registro y seguimiento de órdenes.
4. Reservas: programación por fecha, hora y cantidad de personas.
5. Caja y reportes: resumen de ventas y cierre diario.

## Alcance de la versión 1.0.0
Esta versión contiene la estructura visual inicial y las pantallas de referencia de los cinco módulos. Los formularios y datos son ilustrativos; no hay autenticación real, base de datos ni operaciones CRUD conectadas. Las funcionalidades se pueden incorporar progresivamente en las siguientes versiones, documentando cada cambio en GitHub.

## Tecnologías
- HTML5
- CSS3
- Git y GitHub para control de versiones.

## Estructura del proyecto
```text
BURGER_HOUSE_SIGR/
├── index.html
├── css/
│   └── styles.css
├── pages/
│   ├── usuarios.html
│   ├── menu.html
│   ├── pedidos.html
│   ├── reservas.html
│   └── caja.html
├── docs/
│   ├── linea-base.md
│   └── plan-versiones.md
├── README.md
├── CHANGELOG.md
└── LICENSE.txt
```

## Ejecución
No requiere instalación. Abrir `index.html` en un navegador web. Para visualizarlo publicado, se puede configurar GitHub Pages desde la rama `main`.

## Línea base
La versión `v1.0.0` establece la línea base inicial de la interfaz y de la estructura del prototipo. Los cambios posteriores deben registrarse en commits independientes, con mensajes claros y trazables. La etiqueta `v1.0.0` se creará en GitHub después de subir y validar esta versión.

## Limitaciones
Los datos mostrados son demostrativos. Los formularios están deshabilitados o son representaciones visuales; no guardan información ni procesan transacciones. No se debe presentar esta versión como un sistema operativo de restaurante.
