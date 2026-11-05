# Neonatología · Consulta rápida de guardia

**Propósito:** resolver dudas asistenciales concretas en segundos, no crear un libro de texto ni un tratado de Neonatología.

El contenido está diseñado como **fichas de decisión** para médicos durante la guardia: qué comprobar, qué hacer, qué dosis o perfusión preparar, cuándo reevaluar y cuándo escalar o trasladar. Las explicaciones extensas y las referencias se sitúan después de las instrucciones operativas.

**Situación actual:** estructura técnica disponible. Las futuras fichas clínicas aún deben incorporarse y validarse. La página actual no contiene pautas asistenciales aprobadas.

## Accesos

- Web: https://gonzaloares.github.io/neonatologia/
- Versión PDF para consulta y respaldo: https://gonzaloares.github.io/neonatologia/manual-neonatologia.pdf

El archivo PDF conserva su dirección histórica para no romper enlaces; es una **recopilación de fichas**, no un manual teórico.

## Formato obligatorio de cada ficha

1. **Pregunta de guardia** en lenguaje clínico, como se formularía junto a la incubadora.
2. **Respuesta rápida:** decisiones y pasos inmediatos, visibles antes de hacer scroll.
3. **Datos necesarios para decidir:** peso, edad gestacional y posnatal, situación clínica u otros condicionantes.
4. **Tratamiento concreto:** dosis, vía, dilución, preparación y velocidad cuando corresponda; sin cifras no validadas.
5. **Controles y reevaluación:** momento, objetivo y qué cambiar si no evoluciona bien.
6. **Escalada y traslado:** criterios y acciones de estabilización para una unidad neonatal de nivel IIB.
7. **Fuentes y revisión:** referencia, fecha, versión y validación local.

Evitar definiciones largas, revisiones fisiopatológicas y bibliografías al inicio. Para problemas complejos, mantener una ruta rápida y otra de detalles complementarios.

## Añadir fichas clínicas

1. Copiar `plantillas/protocolo.md` a una subcarpeta de `docs/`.
2. Completar la **respuesta rápida** y contrastar las decisiones con fuentes vigentes.
3. Verificar de forma independiente dosis, perfusiones, intervalos, límites, criterios de ingreso y traslado.
4. Obtener validación clínica local e indicar responsable, versión y fecha.
5. Añadir el archivo a `nav:` en `mkdocs.yml` y publicar en `main`.

## Tecnología y publicación

- MkDocs Material con navegación por áreas y buscador, incluso para palabras sin tilde.
- Aplicación instalable (PWA) con información local para uso sin conexión.
- PDF A4 navegable, generado automáticamente con índice, miniíndices por ficha y marcadores.
- GitHub Actions compila web y PDF tras cada cambio en `main`.

La web es pública. No incluir datos de pacientes ni información asistencial institucional sin autorización.

## Fuentes de referencia

SENeo, recomendaciones nacionales vigentes, guías internacionales contrastadas y procedimientos locales validados. Ninguna ficha en borrador equivale a un protocolo asistencial aprobado.
