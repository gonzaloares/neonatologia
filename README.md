# Protocolos de Neonatología

Colección de protocolos clínicos prácticos, desarrollados con el formato de [Urgencias Pediátricas](https://github.com/gonzaloares/urgencias-pediatricas).

- Web: https://gonzaloares.github.io/neonatologia/
- PDF: https://gonzaloares.github.io/neonatologia/manual-neonatologia.pdf

## Estructura de los capítulos

1. Título clínico breve.
2. Índice de accesos rápidos con botones que enlazan a los apartados.
3. Recuadro introductorio corto.
4. Apartados numerados: valoración, diagnóstico, tratamiento, controles, destino y algoritmo.
5. Bibliografía al final, con fuentes enlazadas.

La navegación, tablas y presentación se inspiran en Urgencias Pediátricas, con una identidad azul para Neonatología.

## Publicación y mantenimiento

La web utiliza MkDocs Material, buscador, PWA/offline y PDF automático con índice, miniíndice por capítulo, marcadores y paginación.

Para añadir un capítulo, partir de `plantillas/protocolo.md`, contrastar las recomendaciones con bibliografía vigente, verificar cifras y dosis y añadirlo al `nav` de `mkdocs.yml`. GitHub Actions publica los cambios al actualizar `main`.

No incluir información que identifique a pacientes. La adopción de cualquier protocolo como norma institucional requiere las aprobaciones internas pertinentes.
