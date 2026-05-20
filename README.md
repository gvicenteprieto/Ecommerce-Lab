# Proyecto Web: E-commerce (Laboratorio de Aplicaciones Web Cliente)

##  Descripción
Aplicación web de ejemplo desarrollada en **HTML5, CSS3 y JavaScript Vanilla** para el laboratorio de aplicaciones web cliente en ISTEA.  
El proyecto implementa un e-commerce con funcionalidades de carrito de compras, consumo de API y soporte PWA.

---

##  Objetivos del proyecto
- Diseño **responsive** adaptable a distintos dispositivos.
- Experiencia de usuario consistente (paleta de colores, tipografía, botones).
- Cumplimiento de **políticas de accesibilidad** con etiquetas semánticas.
- Consumo de productos desde API pública (`https://fakestoreapi.com/`).
- Implementación de carrito con almacenamiento en **LocalStorage**.
- Integración de **manifest.json** e íconos para soporte PWA.
- Navegación por categorías y buscador de productos.
- Uso de **sidebar** para gestionar el carrito (reemplazo de checkout.html).

---

##  Tecnologías utilizadas
- **HTML5** (estructura semántica)
- **CSS3 / Bootstrap 5** (estilos y responsive)
- **JavaScript Vanilla** (DOM, Fetch API, LocalStorage)
- **SweetAlert2** (alertas y modales)
- **SwiperJS** (sliders y carruseles)
- **Manifest.json** (configuración PWA)
- **Service Worker** (cache offline, instalación como app)

---

##  Estructura del proyecto
/
├── index.html
├── manifest.json
├── sw.js
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── images/
│   ├── shopping-cart-32.png
│   ├── iconLogo-144.png
│   ├── iconLogo-192.png
│   ├── iconLogo-512.png
│   └── otros íconos y recursos
└── README.md


---

## Funcionalidades principales
- Listado de productos en cards.
- Modal con detalles de cada producto.
- Carrito de compras en **sidebar** con badge de cantidad.
- Sidebar con listado de productos, botones (+/-), eliminar y precio dinámico.
- Persistencia de datos en LocalStorage.
- Finalizar compra y limpiar carrito.
- Buscador de productos.
- Navegación por categorías.
- Soporte **offline** y **PWA** mediante Service Worker.

---

## Integrantes
- Aixa Jezabel Sosa – [GitHub: Aixa Sosa](https://github.com/aixa-arg)
- Noelia Sanabria – [GitHub: Noelia Sanabria](https://github.com/noelia-sanabria)
- Rafael Cortez - [GitHub: Rafael Cortez](https://github.com/RafaelECortez)
- Guillermo Eduardo Vicente – [GitHub: Guillermo Vicente](https://github.com/gvicenteprieto)

---

##  Evaluación
Cada commit refleja la participación individual de los integrantes.  
El repositorio es público y cumple con los requisitos solicitados en la consigna.

---

##  Recursos de apoyo
- [Bootstrap 5](https://getbootstrap.com/)
- [SweetAlert2](https://sweetalert2.github.io/)
- [SwiperJS](https://swiperjs.com/demos)
- [Google Fonts](https://fonts.google.com/)
- [FakeStore API](https://fakestoreapi.com/)

---

## Cómo probar la PWA

1. Abrir el proyecto en un servidor local (ej. Live Server en VSCode).
2. Verificar en DevTools → Application → Service Workers que `sw.js` esté activo.
3. Desconectar Internet y refrescar: la app carga offline con los archivos cacheados.
4. En Chrome/Edge: menú de tres puntos → "Instalar aplicación".
5. La app se abre en ventana independiente con el ícono configurado en `manifest.json`.

---

## Requisitos cumplidos
- [x] Diseño responsive
- [x] Carrito en sidebar
- [x] Consumo de API pública
- [x] Persistencia con LocalStorage
- [x] Buscador y categorías dinámicas
- [x] Modales con SweetAlert2
- [x] PWA con manifest.json y Service Worker
- [x] Instalación como aplicación
- [x] Soporte offline
