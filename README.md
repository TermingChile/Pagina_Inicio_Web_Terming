# TermIng — Galería de Proyectos

Este repositorio contiene la galería de imágenes de proyectos y faenas de **TermIng Chile SPA**. La página web carga dinámicamente las imágenes desde un archivo JSON, lo que permite actualizar el contenido sin modificar el código HTML.

## 🌐 Sitio en vivo

🔗 **https://documentacionterming.netlify.app/** (cuando esté desplegado, puedes tener una subcarpeta o un sitio separado)

## 📂 Estructura del repositorio

| Archivo | Función |
|---------|---------|
| `index.html` | Página web que muestra los carruseles. |
| `galeria.json` | **Base de datos** de imágenes (categorías y URLs). |
| `README.md` | Este archivo. |

## 🚀 Cómo actualizar la galería

1. **Sube las fotos** a Google Drive (o a cualquier servicio con enlaces públicos).
2. **Obtén el enlace público** de cada imagen:
   - Haz clic derecho → "Compartir" → "Cualquier persona con el enlace" → Copiar URL.
3. **Edita el archivo `galeria.json`** en este repositorio (desde la web de GitHub o localmente).
4. **Añade o modifica las URLs** en las categorías correspondientes.
5. **Guarda los cambios** (Commit) con un mensaje claro.
6. **Espera ~30 segundos** y recarga la página. Netlify actualizará automáticamente.

## 📋 Estructura del JSON

```json
{
  "categorias": [
    {
      "nombre": "Piping Industrial",
      "imagenes": [
        {
          "titulo": "Instalación de tuberías en faena minera",
          "descripcion": "Sistema de piping ASME B31.3",
          "url": "https://drive.google.com/file/d/XXXX/view"
        }
      ]
    }
  ]
}