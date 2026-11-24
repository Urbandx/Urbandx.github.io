# Portafolio de Evidencias

Portafolio personal publicado con GitHub Pages.

**Contenido:** fotografía, datos personales, estudios, lenguajes, bases de datos, tecnologías y 3 proyectos con enlace.

## Cómo publicarlo en GitHub

1. Revisa que `index.html` tenga tus datos y que tu foto esté en `assets/foto.jpg`.
2. En GitHub crea un repositorio **público** llamado `Urbandx.github.io`
   (o cualquier nombre, por ejemplo `portafolio`).
3. Sube los archivos:

```powershell
git init
git add .
git commit -m "Portafolio de evidencias"
git branch -M main
git remote add origin https://github.com/Urbandx/portafolio.git
git push -u origin main
```

4. En GitHub: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
5. Tu portafolio quedará en `https://Urbandx.github.io/portafolio/`
   (o `https://Urbandx.github.io/` si usaste el nombre `Urbandx.github.io`).

Entrega el enlace de tu página y el del repositorio.
