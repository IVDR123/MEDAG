# CTX_SESION - MEDAG

## Proyecto
Página web romántica **"Ivan Valentin ❤ Maria Ester - 1 Mes"**
Aniversario de 1 mes desde el 26 de Abril de 2026.
Publicada en: `https://ivdr123.github.io/MEDAG/`

## Estructura
```
D:\PROYECTOS\MEDAG\
├── index.html
├── fotos/
│   ├── .gitkeep
│   ├── foto1.jpg
│   ├── foto2.jpg
│   ├── foto3.jpg
│   ├── foto4.jpg
│   ├── foto5.jpg
│   └── foto6.jpg
└── CTX_SESION.md
```

## Repositorio GitHub
- URL: `https://github.com/IVDR123/MEDAG.git`
- Branch: `main`
- Hosteado en GitHub Pages (repo público)

## Historial de cambios (git log)

| Commit | Descripción |
|--------|-------------|
| c02b616 | feat: primera version - pagina 1 mes de amor |
| 2f04d49 | chore: add fotos placeholder directory |
| 15926b9 | feat: add fotos to galeria |
| 7028293 | style: change background to purple theme |
| 9851972 | style: lighter purple background (#4a2a7a) |
| 7aa39bf | style: footer text white (#fff) |
| 3e2cc2b | feat: replace arrow with button, improve responsive |
| 593d2cc | feat: block scroll until button click |

## TODO Pendiente
- ~~Subir a GitHub Pages~~ (ok, en `ivdr123.github.io/MEDAG/`)
- ~~Cambiar fondo a morado~~ (ok, `#4a2a7a`)
- ~~Footer blanco~~ (ok)
- ~~Reemplazar flecha por botón "Comenzar"~~ (ok)
- ~~Responsive para smartphones~~ (ok, 2 breakpoints: 600px y 400px)
- ~~Bloquear scroll hasta click en "Comenzar"~~ (ok)
- ~~[PENDIENTE] Publicar en Netlify~~ (usar https://app.netlify.com, conectar repo GitHub)

## CSS - Paleta de colores
- Fondo: `#4a2a7a` (morado medio)
- Degradado Hero: `radial-gradient(#6a3a9a → #4a2a7a)`
- Degradado Contador: `radial-gradient(#3a2060 → #4a2a7a)`
- Degradado Carta: `radial-gradient(#6a3060 → #4a2a7a)`
- Degradado Galería: `radial-gradient(#3a2060 → #4a2a7a)`
- Texto general: `#fff`
- Detalles dorados: `#ffb347`
- Detalles rojo amor: `#ff6b6b`
- Gradiente botón: `linear-gradient(135deg, #ff6b6b, #ffb347)`

## Funcionalidades
1. **Corazones flotantes** - 30 partículas con emojis (❤💕✨💖🌸) animadas en bucle
2. **Contador de tiempo** - desde 26/04/2026, actualiza cada segundo
3. **Carta de amor** - texto personalizado
4. **Galería** - 6 fotos (grid responsive)
5. **Bloqueo de scroll** - Scroll deshabilitado hasta click en "Comenzar"
6. **Responsive** - 2 breakpoints: 600px (tablet) y 400px (smartphone)

## Próximos pasos posibles
- Publicar en Netlify (dominio personalizado tipo `ivan-y-maria.netlify.app`)
- Agregar más fotos
- Cambiar textos (fechas, carta, nombres)
- Agregar música de fondo
- Agregar más secciones (ej. timeline, playlist)
