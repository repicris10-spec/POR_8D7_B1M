# Para mi cielo, Angie ⚓

Una página web hecha con amor para Angie Téllez.

---

## Cómo subirla a GitHub Pages (paso a paso)

### Opción 1 — Desde el navegador (la más fácil, sin instalar nada)

1. Ve a [github.com](https://github.com) y haz login (o crea una cuenta gratis).
2. Arriba a la derecha, click en el **+** y luego **"New repository"**.
3. Ponle un nombre al repositorio. Por ejemplo: `para-angie` o `mi-cielo`.
   - **Importante:** déjalo como **Public** (público) — es necesario para que GitHub Pages lo muestre gratis.
4. Marca la casilla **"Add a README file"** y dale click en **"Create repository"**.
5. Ya en el repositorio, click en **"Add file"** → **"Upload files"**.
6. Arrastra ahí TODOS los archivos y la carpeta `images` que están dentro de `para-angie/`. Es decir:
   - `index.html`
   - la carpeta entera `images/` (con sus 8 fotos adentro)
7. Abajo click en **"Commit changes"**.
8. Ve a la pestaña **"Settings"** del repositorio.
9. En el menú izquierdo, click en **"Pages"**.
10. En la sección **"Build and deployment"**:
    - **Source**: selecciona **"Deploy from a branch"**
    - **Branch**: selecciona **`main`** y carpeta **`/ (root)`**, luego click en **"Save"**.
11. Espera 1–2 minutos. Refresca la página.
12. Arriba aparecerá: **"Your site is live at https://TU-USUARIO.github.io/para-angie/"**

¡Listo! Esa es la URL que le envías a Angie. 💜

---

### Opción 2 — Si ya manejas Git en consola

```bash
cd para-angie
git init
git add .
git commit -m "Para mi cielo"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/para-angie.git
git push -u origin main
```

Luego activa GitHub Pages como en los pasos 8–11 de arriba.

---

## ¿Cómo se la envío a ella?

Una vez que tengas la URL del estilo `https://tu-usuario.github.io/para-angie/`:

- Cópiala y pégasela por WhatsApp con un mensaje cortito.
- Idea: *"Cielo, hice algo para ti. No tienes que responder nada. Solo léelo cuando puedas. ⚓"*

La página se ve hermosa en celular y en computador. La música no arranca sola — hay un botón redondo arriba a la derecha para que ella elija si quiere ponerla.

---

## ¿Quieres editar algo después?

Todo el contenido está en `index.html`. Si quieres cambiar:
- **El mensaje final**: busca la sección `<!-- ===== FINAL LETTER ===== -->`
- **Las cartas de ella**: busca `<!-- ===== HER WORDS ===== -->`
- **Las cartas tuyas**: busca `<!-- ===== HIS WORDS ===== -->`
- **La canción de fondo**: busca `videoId: 'I6xI72waMvc'` y cámbialo por el ID de YouTube que quieras

Después de editar el archivo, súbelo de nuevo al repo (en GitHub, click en `index.html` → ícono del lápiz → editas → "Commit changes"). Los cambios se reflejan en 1–2 minutos.

---

Hecho con amor desde Neiva. ⚓
