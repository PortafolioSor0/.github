# Lineamientos de la organización de portafolio

## Crear la organización (lo haces tú en la web)
1. https://github.com/account/organizations/new?plan=free → plan **Free**.
2. Nombre corto y profesional, p. ej. `sofiro11-portfolio` o `sofia-rodriguez-portfolio`.
3. Correo de contacto: uno profesional (no el universitario si vas a perder acceso a él).
4. "Belongs to: My personal account".

## Configuración recomendada (Settings de la organización)
- **Profile:** nombre visible, foto, descripción de una línea, enlace a LinkedIn.
- **Member privileges → Base permissions:** Read. Solo tú como Owner.
- **Repository creation:** solo Owners.
- **Authentication security:** exigir 2FA a los miembros.
- **Code security:** activar Dependabot alerts, secret scanning y push protection por defecto en repos nuevos.
- **Pinned repositories:** fija los 4–6 mejores proyectos.
- Repo **`.github`** público con `profile/README.md` (el borrador está en esta carpeta): es la portada de la organización.

## Reglas para cada repo publicado
- Repo nuevo con **un solo commit** limpio. Nunca hacer público un repo privado que ya tiene historial.
- Commits con `Sofiro11 <133816198+Sofiro11@users.noreply.github.com>`.
- Sin secretos, datos personales, IPs, seriales ni rutas locales. Datos de ejemplo ficticios.
- `README.md` con: problema, cómo funciona (diagrama), cómo correrlo, tecnologías y autoría.
- `docs/FORMACION_PROFESIONAL.md` con competencias y evidencia.
- `.gitignore` y `.env.example` cuando aplique.
- Descripción y *topics* en GitHub (p. ej. `homelab`, `openmediavault`, `docker`, `linux`, `security`).
- Licencia: MIT para código, o "All rights reserved" si solo quieres mostrarlo.
- Proyectos académicos: verificar la política del curso. Proyectos laborales: permiso escrito de la empresa.
