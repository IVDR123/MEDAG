# CTX_SESION - MEDAG v2

## Proyecto
Página web romántica **"Ivan Valentin ❤ Maria Ester"** — Versión dinámica multimes.
Aniversario desde el **26 de Abril de 2026**.
Publicada originalmente en: `https://ivdr123.github.io/MEDAG/`

## Novedades v2
- **Contador de meses dinámico** — Calcula automáticamente los meses transcurridos
- **Timeline de momentos** — Navegación entre meses con cartas individuales
- **Fácil de extender** — Solo hay que agregar un objeto al array `CONFIG.meses`
- **Barra de progreso** de scroll
- **Puntos de navegación** lateral entre secciones
- **CSS con variables** para tema fácil de modificar
- Diseño responsive mejorado (3 breakpoints)

## Estructura
```
D:\PROYECTOS\MEDAG-v2\
├── index.html
├── fotos/
│   ├── foto1.jpg
│   ├── foto2.jpg
│   ├── foto3.jpg
│   ├── foto4.jpg
│   ├── foto5.jpg
│   └── foto6.jpg
└── CTX_SESION.md
```

## Cómo agregar un nuevo mes
Abrir `index.html`, buscar la sección `CONFIG.meses` y agregar:

```js
{
  numero: 3,
  titulo: 'Tres Meses de...',
  rango: '26 de Junio — 26 de Julio de 2026',
  mensaje: `Escribe aquí el mensaje...`,
  firma: 'Siempre tuyo,\nIvan Valentin ❤'
},
```

## Fecha de inicio
26 de Abril de 2026 — el contador y los meses se calculan desde esta fecha.

## Paleta de colores (CSS Variables)
| Variable | Color |
|---|---|
| `--bg-primary` | `#4a2a7a` |
| `--bg-hero` | `#6a3a9a` |
| `--bg-dark` | `#3a2060` |
| `--gold` | `#ffb347` |
| `--rose` | `#ff6b6b` |

## Funcionalidades
1. Corazones flotantes (30 partículas)
2. Contador dinámico (días, horas, minutos, segundos)
3. Timeline de meses navegable con cartas de amor
4. Galería de fotos (6 fotos con fallback)
5. Bloqueo de scroll inicial con botón "Comenzar"
6. Navegación lateral por secciones
7. Barra de progreso de scroll
8. Hero con mes actual dinámico
