# Tu sitio nuevo — guía de despliegue

Este es tu sitio personal en **al-folio**, ya personalizado con tu contenido real:
About, News (7 entradas), Publications (5 papers), Projects (6), CV estructurado + PDFs,
y tus redes (GitHub, LinkedIn, Kaggle).

## Paso 1 — Subirlo a GitHub

Opción A (recomendada, sin línea de comandos):
1. Crea un repo nuevo en GitHub llamado **`HiramZ04.github.io`** (exactamente así).
2. En tu compu, descomprime esta carpeta.
3. En el repo nuevo → "uploading an existing file" → arrastra TODO el contenido de la carpeta.
4. Commit.

Opción B (con git):
```bash
cd site
git init && git add -A && git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/HiramZ04/HiramZ04.github.io.git
git push -u origin main
```

## Paso 2 — Activar GitHub Pages
En el repo → **Settings → Pages** → Source: **GitHub Actions**.
El sitio se construye solo en 1-2 minutos. Quedará en `https://HiramZ04.github.io`.

## Paso 3 — Conectar tu dominio hirambigdata.com
Ya incluí el archivo `CNAME` (apunta a `www.hirambigdata.com`).
En tu panel de Wix (gestión de dominio → registros DNS):
- **CNAME**: host `www` → valor `HiramZ04.github.io`
- **4 registros A** para el dominio raíz (host `@`):
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153

Luego en GitHub → Settings → Pages → Custom domain → escribe `www.hirambigdata.com`,
guarda, y marca **Enforce HTTPS** (aparece tras unos minutos).
Propagación: de minutos a ~24h.

> El plan de hosting de Wix lo puedes cancelar/dejar vencer. Solo conservas el dominio.

## Paso 4 — Lo que TÚ debes reemplazar (importante)

1. **Tu foto**: reemplaza `assets/img/prof_pic.jpg` con una foto tuya profesional
   (cuadrada, ~800x800px).
2. **Imágenes de proyectos**: los proyectos usan placeholders (`assets/img/1.jpg`, etc.).
   Reemplázalas con capturas reales de cada proyecto, o cambia la línea `img:` en cada
   archivo de `_projects/` apuntando a tus propias imágenes.
3. **Author lists en papers**: en `_bibliography/papers.bib` puse `Zuniga, Hiram and others`.
   Cambia `others` por los nombres reales de tus coautores, en el orden correcto.
4. **Links de repos en proyectos**: en `_projects/*.md` agrega el link directo a cada repo.
5. **Google Scholar**: cuando crees tu perfil, descomenta `scholar_userid:` en
   `_data/socials.yml` y ponlo. Igual con ORCID.

## Estructura rápida (qué editar dónde)
- Texto del home → `_pages/about.md`
- Noticias → `_news/` (un archivo por entrada; el nombre con fecha ordena)
- Papers → `_bibliography/papers.bib`
- Proyectos → `_projects/`
- CV (texto en la página) → `_data/cv.yml`
- CVs en PDF → `assets/pdf/` (ya están los 3: academic, industry, qualcomm)
- Config general (título, colores, links) → `_config.yml`
