# sitio estatico newlibram

Sitio estatico preparado para vista previa local y GitHub Pages.

URL publica despues de activar GitHub Pages:

`https://valera007700.github.io/site/`

## estructura

- `index.html` es el punto de entrada desplegable para GitHub Pages.
- `assets/logos/` contiene los logotipos SVG locales usados por la pagina.

## ejecucion local

La pagina es estatica, pero depende de recursos externos de Tilda CDN, por lo que la vista previa local requiere acceso a internet.

Ejecuta desde la raiz del proyecto:

```bash
python3 -m http.server 8000
```

Despues abre `http://127.0.0.1:8000/`.

## github pages

1. Sube el repositorio a GitHub.
2. En la configuracion del repositorio, abre `Pages`.
3. Configura `Build and deployment` como `Deploy from a branch`.
4. Selecciona la rama `main` y la carpeta `/ (root)`.
5. Guarda los cambios.

## dominio personalizado opcional

Si quieres publicar el sitio en un dominio personalizado como `newlibram.com`, agrega despues un archivo `CNAME` con ese dominio y configura el DNS en tu registrador.
