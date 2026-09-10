# Cristina & Víctor · Luxemburgo

Página de cuenta atrás para el viaje a Luxemburgo, del 16 al 20 de septiembre de 2026.

## Contenido

```
index.html
assets/
  fondo-luxemburgo.jpg    imagen de portada (el Grund)
  beso-luxemburgo.jpg     foto del puente Adolphe
```

## Publicarla en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html` y la carpeta `assets/` completa, manteniendo esa estructura.
3. En el repositorio, entra en **Settings → Pages**.
4. En *Source* elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. En un par de minutos la web estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Cambiar cosas

- **La fecha de la cuenta atrás**: en `index.html`, la línea `const target = new Date("2026-09-16T22:45:00+02:00")`. El `+02:00` es la hora de Luxemburgo en septiembre.
- **Las fotos**: sustituye los archivos de `assets/` conservando los mismos nombres.
- **Los colores**: están agrupados arriba del CSS, en el bloque `:root`.
