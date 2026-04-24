# Triple Espresso

Sitio web estático para la cafetería Triple Espresso, desarrollado como parte del programa de Desarrollo Web en TripleTen.

## Descripción

Landing page para una cafetería que permite a los visitantes conocer el establecimiento, explorar recetas de café destacadas y realizar reservaciones de mesa. El diseño aplica la metodología BEM con una estructura CSS organizada por bloques funcionales.

## Tecnologías utilizadas

- HTML5 semántico
- CSS3 — Flexbox para layouts y alineación
- Metodología BEM para nomenclatura y organización de estilos
- Normalize.css para consistencia entre navegadores

## Características

- Header con imagen de fondo y navegación principal
- Sección de recetas de café con tarjetas visuales
- Formulario de reservación de mesa
- Footer con redes sociales (Facebook, Instagram) y logo
- Múltiples fondos SVG decorativos por sección
- Dos variantes de favicon (círculos y grano de café)

## Estructura del proyecto

```
web_project_coffeeshop/
├── index.html
├── blocks/              # Estilos BEM por bloque
│   ├── header.css
│   ├── nav.css
│   ├── recipes.css
│   ├── reservation.css
│   ├── footer.css
│   ├── form.css
│   ├── span.css
│   └── page.css
├── pages/
│   └── index.css        # Importa todos los bloques
├── images/              # Recursos gráficos y fondos SVG
└── vendor/
    └── normalize.css
```

## Instalación y uso

```bash
git clone git@github.com:JManzanilla/web_project_coffeeshop.git
cd web_project_coffeeshop
```

Abre `index.html` directamente en el navegador. No requiere instalación de dependencias ni servidor.

## Autor

Jesus Manzanilla — [GitHub](https://github.com/JManzanilla)
