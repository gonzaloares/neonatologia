# Protocolos de Neonatología

Manual de Neonatología basado en la estructura tecnológica de [Urgencias Pediátricas](https://github.com/gonzaloares/urgencias-pediatricas).

**Estado actual:** infraestructura preparada; todavía no se han incorporado protocolos clínicos validados. La web y el PDF inicial contienen criterios editoriales, no pautas asistenciales.

## Acceso (cuando GitHub Pages esté habilitado)
- Web: https://gonzaloares.github.io/neonatologia/
- PDF: https://gonzaloares.github.io/neonatologia/manual-neonatologia.pdf

## Funciones
- MkDocs Material con navegación por áreas y buscador compatible con términos acentuados y sin tilde.
- Web instalable como aplicación (PWA), con almacenamiento offline y estado de actualizaciones.
- PDF A4 automático: portada, índice navegable, paginación, miniíndices y marcadores de especialidad/protocolo/apartado; las tablas no parten palabras por la mitad.
- PDF descargable también desde la ejecución de GitHub Actions como artefacto `manual-neonatologia`.

## Añadir un protocolo
1. Copiar `plantillas/protocolo.md` a la sección correspondiente en `docs/` (sin espacios ni tildes en el nombre del archivo).
2. Completar los apartados y verificar indicaciones, pruebas, dosis, diluciones, vías, intervalos, controles y criterios de ingreso/traslado.
3. Obtener validación asistencial local; actualizar versión, responsables y bibliografía.
4. Añadirlo a `nav:` en `mkdocs.yml`. El orden del PDF coincidirá con la navegación.
5. Publicar en `main`; se compilan web y PDF automáticamente. Ejecución manual: **Actions → Construir y publicar Neonatología → Run workflow**.

## Configuración GitHub Pages
Este repositorio es **privado**. Para publicar, en **Settings → Pages**, seleccionar **GitHub Actions**, siempre que esté permitido en el plan GitHub. No es necesario hacer público el código. Comprueba las normas del centro: la web publicada puede ser pública aunque el repositorio sea privado. No incorporar datos identificativos de pacientes.

## Fuentes de referencia
- https://seneo.es/publicaciones
- https://www.sciencedirect.com/science/article/pii/S1695403326000123 (GRN-SENeo, 2026)

**Advertencia:** ningún borrador es un protocolo clínico vigente sin validación local.
