# Referencias bibliográficas — Tema 5

## Libros de texto principales

1. **Hennessy, J. L. y Patterson, D. A.** (2019). *Computer Architecture: A Quantitative Approach*, 6.ª edición. Morgan Kaufmann.
   - Capítulo 2: Memory Hierarchy Design.
   - Apéndice B: Review of Memory Hierarchy.
   - ISBN: 978-0128119051.

2. **Patterson, D. A. y Hennessy, J. L.** (2021). *Computer Organization and Design RISC-V Edition: The Hardware/Software Interface*, 2.ª edición. Morgan Kaufmann.
   - Capítulo 5: Large and Fast: Exploiting Memory Hierarchy.
   - ISBN: 978-0128203316.

3. **Patterson, D. A. y Hennessy, J. L.** (2014). *Computer Organization and Design: The Hardware/Software Interface*, 5.ª edición (ARM Edition). Morgan Kaufmann.
   - Capítulo 5: Large and Fast: Exploiting Memory Hierarchy.
   - ISBN: 978-0124077263.

## Libros complementarios

4. **Stallings, W.** (2022). *Computer Organization and Architecture*, 11.ª edición. Pearson.
   - Capítulos 4 (Cache Memory) y 17 (Virtual Memory).
   - ISBN: 978-0135381052.

5. **Null, L. y Lobur, J.** (2019). *The Essentials of Computer Organization and Architecture*, 5.ª edición. Jones & Bartlett.
   - Capítulo 6: Memory.

6. **Tanenbaum, A. S. y Austin, T.** (2013). *Structured Computer Organization*, 6.ª edición. Pearson.
   - Capítulo 4: The Microarchitecture Level (secciones de caché).

## Documentación oficial de plataformas

### Apple Silicon

7. **Apple Developer.** *Apple Silicon CPU Optimization Guide*.
   - URL: [developer.apple.com/documentation/apple-silicon](https://developer.apple.com/documentation/apple-silicon)
   - Contiene: guías de optimización, información sobre jerarquía de memoria y modelo de memoria.

8. **Apple.** Fichas técnicas oficiales de M1, M2, M3, M4.
   - URL: [apple.com/shop/product](https://www.apple.com)
   - Contiene: tamaños de caché, configuraciones de memoria, especificaciones del SoC.

9. **Apple Developer.** *WWDC Sessions on Apple Silicon*.
   - Sesiones relevantes: "Meet the M-series chips", "Optimize for Apple Silicon".

### ARM

10. **Arm Developer.** *ARM Architecture Reference Manual for A-profile architecture (ARM ARM)*.
    - URL: [developer.arm.com/documentation](https://developer.arm.com/documentation)
    - Versiones: ARMv8-A, ARMv9-A.
    - Contiene: modelo de memoria, instrucciones de barrera (DMB, DSB, ISB), esquemas de paginación.

11. **Arm Developer.** *Cortex-X4 Technical Reference Manual (TRM)*.
    - URL: [developer.arm.com/documentation](https://developer.arm.com/documentation)
    - Contiene: tamaños de caché, organización, TLB, opciones configurables.

12. **Arm Developer.** *DynamIQ Shared Unit (DSU) Technical Reference Manual*.
    - URL: [developer.arm.com/documentation](https://developer.arm.com/documentation)
    - Contiene: caché L3 compartida, coherencia, configuraciones.

13. **Arm Developer.** *Cortex-A720 / Cortex-A520 Technical Reference Manuals*.
    - URL: [developer.arm.com/documentation](https://developer.arm.com/documentation)

### RISC-V

14. **RISC-V International.** *The RISC-V Instruction Set Manual, Volume I: Unprivileged ISA*, versión ratificada.
    - URL: [riscv.org/specifications](https://riscv.org/specifications/)
    - Contiene: instrucciones FENCE, extensión Zicbop (Cache-Block Operation Prefetch).

15. **RISC-V International.** *The RISC-V Instruction Set Manual, Volume II: Privileged Architecture*, versión ratificada.
    - URL: [riscv.org/specifications](https://riscv.org/specifications/)
    - Contiene: esquemas de paginación Sv39/Sv48/Sv57, instrucciones SFENCE.VMA, FENCE.I.

16. **SiFive.** *SiFive P870 Product Brief*.
    - URL: [sifive.com](https://www.sifive.com)
    - Contiene: especificaciones de caché y pipeline del núcleo de alto rendimiento.

17. **T-Head (Alibaba).** *C910 Documentation*.
    - Contiene: especificaciones de la implementación RISC-V con caché multinivel.

## Artículos y análisis técnicos

18. **Smith, A. J.** (1982). "Cache Memories." *ACM Computing Surveys*, 14(3), pp. 473–530.
    - Artículo clásico de referencia sobre diseño de caché.

19. **Hill, M. D.** (1987). "Aspects of Cache Memory and Instruction Buffer Performance." PhD dissertation, UC Berkeley.
    - Introduce la taxonomía de las tres C (Compulsory, Capacity, Conflict).

20. **Wulf, W. A. y McKee, S. A.** (1995). "Hitting the Memory Wall: Implications of the Obvious." *ACM SIGARCH Computer Architecture News*, 23(1), pp. 20–24.
    - Artículo seminal sobre el "memory wall".

## Recursos de análisis de microarquitectura

21. **Chips and Cheese.** Análisis detallados de microarquitectura de Apple M-series, ARM Cortex, RISC-V.
    - URL: [chipsandcheese.com](https://chipsandcheese.com)
    - Nota: fuente de ingeniería inversa; datos de alta fiabilidad pero no oficiales.

22. **Anandtech.** Análisis de plataformas Apple Silicon y ARM.
    - URL: [anandtech.com](https://www.anandtech.com)
    - Nota: publicación cerrada en 2024; archivo disponible. Datos históricamente fiables.

## Nota sobre calidad de las fuentes

| Categoría | Fiabilidad | Notas |
|:---|:---|:---|
| Libros de texto (1-6) | Máxima | Revisados por pares, múltiples ediciones |
| Documentación oficial ARM / RISC-V (10-17) | Máxima | Especificaciones normativas del fabricante / organización |
| Documentación oficial Apple (7-9) | Alta | Publicada por Apple pero selectiva en detalles internos |
| Artículos académicos (18-20) | Máxima | Publicaciones en revistas y conferencias con revisión por pares |
| Análisis de terceros (21-22) | Alta | Ingeniería inversa meticulosa; contrastar con fuentes oficiales cuando sea posible |
