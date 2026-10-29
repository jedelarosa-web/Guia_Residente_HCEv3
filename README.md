# Guía Académica del Médico Residente — Hospital Central del Estado de Chihuahua

Guía de inducción para el médico residente de nuevo ingreso al **Hospital Central del Estado de Chihuahua** (sede clínica de la Facultad de Medicina y Ciencias Biomédicas de la **UACH**). Reúne el marco normativo, el modelo educativo, el reglamento y la estructura curricular de las **11 especialidades** médicas que oferta la sede.

Sitio de una sola página (HTML autocontenible, sin dependencias externas): navegación lateral, buscador, fichas por especialidad, mapas curriculares y referencias.

## 🌐 Publicar en GitHub Pages

1. Crea un repositorio en GitHub (p. ej. `guia-residente-hce`) y sube el contenido de esta carpeta.
2. En el repositorio: **Settings → Pages**.
3. En **Build and deployment → Source**, elige **Deploy from a branch**.
4. Branch: **main** · carpeta: **/ (root)** → **Save**.
5. En unos minutos el sitio quedará disponible en `https://<usuario>.github.io/<repositorio>/`.

> El archivo `index.html` es la página que se publica. El archivo vacío `.nojekyll` evita que GitHub Pages procese el sitio con Jekyll.

## 📂 Estructura

```
.
├── index.html     # Aplicación web (versión 3) — es lo que se publica
├── README.md
├── LICENSE
├── .gitignore
├── .nojekyll
└── docs/          # Documentos equivalentes para distribución/archivo
    ├── Guía del Médico Residente - HCE.docx   # Documento maestro (Word)
    ├── Guía del Médico Residente - HCE.pdf    # Versión PDF
    ├── Guia Academica del Medico Residente HCE v2.html    # HTML de distribución (archivo único)
    └── Guia Academica del Medico Residente HCE - Web.html # HTML web alterno (barra lateral)
```

## 💻 Ver en local

Abre `index.html` con doble clic en cualquier navegador moderno. No requiere servidor ni conexión a internet.

## 🔄 Actualización

El contenido se mantiene en el documento maestro de Word (`docs/`). Al actualizarlo, se regenera el HTML para conservar la equivalencia entre versiones.

## ⚠️ Nota

Documento de carácter orientativo. Para efectos formales o disciplinarios, consúltese el texto íntegro de la **NOM-001-SSA3-2023**, los **Lineamientos para las Residencias Médicas del Sistema Estatal de Salud de Chihuahua** (CIFRHS) y el **Reglamento** del Hospital Central del Estado. Verifíquese la vigencia de la normativa citada antes de su uso formal.

---

Hospital Central del Estado de Chihuahua · Jefatura de Enseñanza · 2026
