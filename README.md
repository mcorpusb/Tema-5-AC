# Tema 5. Rendimiento de la jerarquía de memoria

> Repositorio académico para la asignatura de Arquitectura de Computadores.

## Descripción

Este repositorio contiene el desarrollo completo del **Tema 5: Rendimiento de la jerarquía de memoria**, basado en el contenido canónico de Hennessy & Patterson y actualizado con información de arquitecturas modernas (Apple Silicon, ARM Cortex, RISC-V).

## Estructura del repositorio

```
.
├── index.md   ← Documento principal (todas las secciones)
├── README.md                     ← Este archivo
├── referencias.md                ← Bibliografía ampliada y enlaces
├── build_report.md               ← Informe de construcción del repositorio
├── checklist_validacion.md       ← Lista de verificación de calidad
└── assets/
    ├── svg/                      ← Diagramas vectoriales (SVG)
    │   ├── jerarquia_memoria.svg
    │   ├── principio_localidad.svg
    │   ├── correspondencia_directa.svg
    │   ├── asociativa_conjuntos.svg
    │   ├── completamente_asociativa.svg
    │   ├── write_through_vs_back.svg
    │   ├── cache_multinivel.svg
    │   ├── tipos_fallos.svg
    │   ├── memoria_entrelazada.svg
    │   ├── traduccion_direcciones_tlb.svg
    │   ├── memoria_virtual.svg
    │   ├── comparacion_moderna.svg
    │   └── descomposicion_direccion.svg
    ├── figuras/
    ├── originales_pdf/
    ├── redibujadas/
    ├── png/
    ├── tablas/
    └── diagramas/
```

## Contenido del documento principal

| Sección | Título |
|:---|:---|
| 5.1 | Introducción: brecha procesador-memoria, localidad, compromiso coste-velocidad-capacidad |
| 5.2 | Jerarquía de memoria: definiciones, TMA, tamaño de bloque |
| 5.3 | Memoria caché: organizaciones, etiqueta/índice/desplazamiento, escritura, multinivel, 3 C |
| 5.4 | Mejoras de la memoria principal: memoria ancha, entrelazada, bancos independientes |
| 5.5 | Memoria virtual: paginación, TLB, fallos de página, protección |
| 5.6 | Arquitecturas actuales: Apple Silicon, ARM Cortex, RISC-V |

Incluye además:
- Ejercicios resueltos (5 niveles de dificultad, 8 ejercicios con resolución detallada)
- Ejercicios propuestos (12 ejercicios sin solución)
- Resumen final, glosario, preguntas de repaso/examen
- Sección "Qué ha cambiado" (clásico vs moderno)

## Diagramas

Se han generado 13 diagramas SVG que cubren:
- Jerarquía piramidal de memoria
- Principio de localidad (temporal y espacial)
- Correspondencia directa, asociativa por conjuntos y completamente asociativa
- Descomposición de dirección (etiqueta, índice, desplazamiento)
- Write-through vs write-back
- Caché multinivel (L1-I, L1-D, L2, L3)
- Tipos de fallos (3 C)
- Memoria entrelazada con bancos
- Traducción de direcciones y TLB
- Memoria virtual (espacio virtual a físico)
- Comparación de arquitecturas modernas

## Cómo usar este material

1. Leer el documento principal de forma secuencial (las secciones se construyen unas sobre otras).
2. Detenerse en cada analogía cotidiana para consolidar el concepto antes de avanzar.
3. Trabajar los ejercicios resueltos antes de intentar los propuestos.
4. Usar el glosario como referencia rápida.
5. La sección 5.6 y "Qué ha cambiado" amplían la perspectiva más allá del examen.

## Fuentes principales

- Hennessy & Patterson, *Computer Architecture: A Quantitative Approach*, 6.ª ed.
- Patterson & Hennessy, *Computer Organization and Design*, 5.ª/6.ª ed.
- Documentación oficial: Apple Developer, Arm Developer, RISC-V International.

Ver [referencias.md](referencias.md) para la bibliografía completa.

## Limitaciones

- No se disponía de los PDFs del temario original; el contenido se ha construido a partir del conocimiento canónico de la materia.
- Los datos de Apple Silicon no publicados oficialmente están marcados como "inferidos" en el texto.
- Las fórmulas clásicas (TMA, CPI) asumen modelo de stalls completo; en procesadores OoO son cotas superiores.

## Licencia

Material académico de uso educativo.
