# Informe de construcción del repositorio

## Datos generales

| Campo | Valor |
|:---|:---|
| **Tema** | 5. Rendimiento de la jerarquía de memoria |
| **Asignatura** | Arquitectura de Computadores |
| **Fecha de generación** | 2025 |
| **Fuentes PDF disponibles** | Ninguna — no se encontraron PDFs en el workspace |
| **Base de conocimiento** | Contenido canónico de Hennessy & Patterson (CAQA 6.ª ed., COD 5.ª/6.ª ed.) + documentación oficial de plataformas modernas |

## Proceso de construcción

### Fase 1: Inspección del workspace
- Se examinó la estructura del directorio de trabajo.
- **No se encontraron PDFs** en ninguna ubicación del workspace.
- Se decidió proceder con el contenido académico canónico del tema.

### Fase 2: Creación de la estructura de directorios
- Se creó la estructura `assets/{figuras, originales_pdf, redibujadas, svg, png, tablas, diagramas}` y `tools/`.
- Los directorios `originales_pdf` y `redibujadas` quedaron vacíos al no haber PDFs de origen.

### Fase 3: Generación de diagramas SVG
- Se generaron **13 diagramas SVG** con contenido técnico inline.
- Cada diagrama se diseñó como SVG standalone con dimensiones, colores y etiquetas adecuados para visualización en GitHub.

| Diagrama | Archivo | Contenido |
|:---|:---|:---|
| Jerarquía piramidal | `jerarquia_memoria.svg` | 6 niveles con latencias y capacidades |
| Localidad | `principio_localidad.svg` | Temporal vs espacial con ejemplos visuales |
| Corresp. directa | `correspondencia_directa.svg` | 8 bloques → 4 líneas con conflictos |
| Asoc. conjuntos | `asociativa_conjuntos.svg` | 2 vías con comparación en paralelo |
| Compl. asociativa | `completamente_asociativa.svg` | Comparación de todas las etiquetas |
| Write-through/back | `write_through_vs_back.svg` | Lado a lado con pros y contras |
| Caché multinivel | `cache_multinivel.svg` | L1-I, L1-D, L2, L3 con latencias |
| Tipos de fallos | `tipos_fallos.svg` | 3 C con analogías y mitigaciones |
| Mem. entrelazada | `memoria_entrelazada.svg` | 4 bancos con distribución de direcciones |
| Traducción TLB | `traduccion_direcciones_tlb.svg` | TLB hit/miss con page table walk |
| Memoria virtual | `memoria_virtual.svg` | Mapeo virtual → físico con swap |
| Comparación moderna | `comparacion_moderna.svg` | Apple Silicon vs ARM vs RISC-V |
| Descomp. dirección | `descomposicion_direccion.svg` | 32 bits: etiqueta/índice/desplazamiento |

### Fase 4: Redacción del documento principal
- Se redactó `index.md` con todas las secciones (5.1-5.6).
- Cada sección sigue el método didáctico: definición → explicación intuitiva → explicación técnica → ejemplo técnico → analogía cotidiana → importancia → mini conclusión.
- Se incluyeron las fórmulas con definición completa de variables e interpretación.
- Se referenciaron los diagramas SVG con rutas relativas.

### Fase 5: Ejercicios
- **8 ejercicios resueltos** distribuidos en 5 niveles de dificultad (1: comprensión básica → 5: síntesis).
- Formato de 9 ítems: enunciado, qué se pide, datos, conceptos, resolución paso a paso, resultado, interpretación, error típico, mini variante.
- **12 ejercicios propuestos** sin solución, con pistas.

### Fase 6: Archivos auxiliares
- `README.md`: descripción del repositorio, estructura, instrucciones de uso.
- `referencias.md`: 22 fuentes bibliográficas categorizadas con nivel de fiabilidad.
- `build_report.md`: este archivo.
- `checklist_validacion.md`: verificación de cumplimiento de requisitos.

## Decisiones tomadas

| Decisión | Justificación |
|:---|:---|
| Escribir sin PDFs de referencia | No se encontraron PDFs en el workspace; el contenido canónico del temario es bien conocido. |
| Incluir Apple Silicon, ARM y RISC-V en la sección 5.6 | Requisito explícito del prompt de construcción. |
| Separar ISA de microarquitectura | Imprescindible para evitar confusiones en la sección moderna. |
| Marcar datos no confirmados oficialmente | Rigor académico; se indica nivel de confianza de cada fuente. |
| Usar write-back como política "moderna dominante" | Consistente con la documentación de ARM, Apple y la literatura reciente. |
| Ejercicios con 5 niveles progresivos | Requisito explícito; cobertura desde comprensión básica hasta síntesis/razonamiento. |

## Limitaciones conocidas

1. **Sin PDFs de origen:** todo el contenido se basa en conocimiento canónico y documentación pública. Si se añadieran los PDFs del temario, se podría refinar la terminología y la estructura para que sea 100% consistente con las transparencias del profesor.

2. **Datos de Apple Silicon:** los tamaños de caché L1 y L2 son de alta fiabilidad (documentación oficial + análisis de terceros). Las latencias exactas son inferidas.

3. **RISC-V:** el ecosistema es joven; las implementaciones concretas citadas pueden quedar desactualizadas rápidamente.

4. **Modelo clásico de stalls:** se ha explicado que es una simplificación (cota superior) y que los procesadores OoO ocultan parte de los stalls, pero no se ha cuantificado la diferencia.

5. **Ejercicios:** los 8 ejercicios resueltos cubren los 5 niveles, pero los niveles 4 y 5 tienen solo 1-2 ejercicios cada uno. Para un uso completo como material de examen, podrían añadirse más.

## Estadísticas del documento principal

| Métrica | Valor aproximado |
|:---|:---|
| Secciones principales | 6 (5.1-5.6) |
| Tablas | 20+ |
| Figuras SVG referenciadas | 13 |
| Ejercicios resueltos | 8 |
| Ejercicios propuestos | 12 |
| Entradas de glosario | 35 |
| Preguntas de repaso | 12 |
| Referencias bibliográficas | 22 |
