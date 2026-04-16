# Checklist de validación — Tema 5

## Estructura y organización

- [x] Índice completo con enlaces internos
- [x] Objetivos de aprendizaje (10 objetivos con verbos de Bloom)
- [x] Mapa general del tema con tabla resumen
- [x] Secciones 5.1 a 5.5 (contenido clásico completo)
- [x] Sección 5.6 (arquitecturas modernas: Apple Silicon, ARM, RISC-V)
- [x] Ejercicios resueltos con 5 niveles de dificultad
- [x] Ejercicios propuestos sin solución
- [x] Resumen final (10 puntos clave)
- [x] Glosario (35 entradas)
- [x] Preguntas de repaso / examen (test + desarrollo + cálculo)
- [x] Bibliografía con cautelas documentales
- [x] Sección "Qué ha cambiado" (clásico vs moderno)

## Método didáctico

- [x] Definición formal de cada concepto
- [x] Explicación intuitiva / analogía cotidiana
- [x] Explicación técnica con nivel universitario
- [x] Ejemplos técnicos con datos numéricos
- [x] Retorno de la analogía al concepto técnico
- [x] Mini conclusiones al final de cada sección principal

## Fórmulas y cálculos

- [x] TMA = t_a + m × p_f (con todas las variables definidas e interpretadas)
- [x] CPI_total = CPI_ideal + CPI_memoria
- [x] T_CPU = N_i × CPI × T_ciclo
- [x] Descomposición de dirección: etiqueta + índice + desplazamiento
- [x] Global miss rate = m_L1 × m_local_L2
- [x] TMA multinivel (L1 + L2)
- [x] Fórmulas con definición completa de cada variable
- [x] Interpretación del resultado numérico en cada ejercicio

## Tablas requeridas

- [x] Tabla comparativa de tecnologías de memoria (SRAM, DRAM, SSD/disco)
- [x] Tabla de organizaciones de caché (directa, asociativa, completamente asociativa)
- [x] Tabla de write-through vs write-back
- [x] Tabla de tipos de fallos (3 C) con causas y soluciones
- [x] Tabla de efecto de parámetros en rendimiento
- [x] Tabla de equivalencia caché ↔ memoria virtual
- [x] Tabla comparativa Apple Silicon / ARM / RISC-V
- [x] Tabla "Qué permanece vs qué ha cambiado"

## Diagramas SVG

- [x] Jerarquía piramidal de memoria
- [x] Principio de localidad (temporal y espacial)
- [x] Correspondencia directa
- [x] Correspondencia asociativa por conjuntos
- [x] Correspondencia completamente asociativa
- [x] Write-through vs write-back
- [x] Caché multinivel
- [x] Tipos de fallos (3 C)
- [x] Memoria entrelazada
- [x] Traducción de direcciones con TLB
- [x] Memoria virtual (espacio virtual → físico)
- [x] Comparación de arquitecturas modernas
- [x] Descomposición de dirección

## Ejercicios resueltos

- [x] Nivel 1: comprensión básica (Ej. 1.1 hit/miss, Ej. 1.2 localidad)
- [x] Nivel 2: identificación y clasificación (Ej. 2.1 descomposición, Ej. 2.2 política escritura)
- [x] Nivel 3: cálculo guiado (Ej. 3.1 TMA, Ej. 3.2 TCPU, Ej. 3.3 comparación)
- [x] Nivel 4: análisis intermedio (Ej. 4.1 tamaño bloque, Ej. 4.2 local vs global miss rate)
- [x] Nivel 5: síntesis (Ej. 5.1 diseño integral, Ej. 5.2 clásico vs moderno)
- [x] Formato de 9 ítems (enunciado, qué se pide, datos, conceptos, resolución, resultado, interpretación, error típico, variante)

## Sección 5.6 — Arquitecturas modernas

- [x] Distinción explícita ISA vs microarquitectura
- [x] Apple Silicon: UMA, SLC, tamaños de caché, fuentes
- [x] ARM Cortex: TRMs, DynamIQ, big.LITTLE, coherencia
- [x] RISC-V: ISA abierta, RVWMO, Sv39/48/57, implementaciones
- [x] Tabla comparativa detallada (10+ aspectos)
- [x] Coherencia y consistencia de memoria
- [x] Prefetching
- [x] Marcado de nivel de documentación (oficial, inferido, no confirmado)

## Archivos auxiliares

- [x] README.md con descripción, estructura y guía de uso
- [x] referencias.md con 22 fuentes categorizadas y nivel de fiabilidad
- [x] build_report.md con proceso de construcción y decisiones
- [x] checklist_validacion.md (este archivo)

## Estilo y formato

- [x] Registro formal académico (sin tutear, sin emojis, sin coloquialismos)
- [x] Markdown compatible con GitHub
- [x] Fórmulas en KaTeX/LaTeX inline y display
- [x] Tablas con formato Markdown estándar
- [x] Referencias a SVGs con rutas relativas
- [x] Márgenes conceptuales señalados con > (blockquote)
- [x] Errores típicos señalizados en ejercicios

## Limitaciones documentadas

- [x] Ausencia de PDFs de origen (señalado en build_report.md)
- [x] Datos de Apple Silicon: nivel de confianza indicado
- [x] Modelo clásico de stalls vs realidad OoO: advertencia incluida
- [x] RISC-V: ecosistema emergente, datos sujetos a cambio rápido
