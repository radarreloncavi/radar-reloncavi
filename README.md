# Radar Reloncaví V3 — Web administrable

Esta versión permite editar la portada desde `/admin/` usando Decap CMS + Netlify Git Gateway.

## Estructura

```text
radar-reloncavi-v3/
├── index.html
├── admin/
│   ├── index.html
│   └── config.yml
├── data/
│   └── noticias.json
└── assets/
    └── uploads/
```

## Qué puedes editar desde /admin

- Nombre y bajada del sitio.
- Franja superior de aviso.
- Noticia principal.
- Noticias secundarias.
- Tendencias locales.
- Imágenes de noticias.
- Fuente, comuna, relevancia, texto Facebook, hashtags y plantilla visual recomendada.

## Importante

Para que el panel `/admin/` pueda guardar cambios, el sitio debe estar conectado a un repositorio GitHub y publicado en Netlify desde GitHub. Si lo subes por arrastrar y soltar, la web se verá, pero el administrador no podrá guardar cambios.

## Flujo recomendado

1. Crear repositorio en GitHub llamado `radar-reloncavi`.
2. Subir todos los archivos de esta carpeta.
3. En Netlify, crear nuevo sitio importando desde GitHub.
4. Activar Identity y Git Gateway en Netlify.
5. Invitar tu correo como usuario editor.
6. Entrar a `https://tu-sitio.netlify.app/admin/`.
7. Editar la portada.
8. Guardar/publicar.

