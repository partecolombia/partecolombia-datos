# Metodología

**Parte Colombia** lleva el conteo de **neutralizaciones** de integrantes de grupos armados
organizados (GAO) por la **Fuerza Pública** colombiana, para medir la promesa del gobierno de
acabar con esos grupos.

## Qué es una "neutralización"
Sumamos cuatro categorías, con soporte verificable:
- **Bajas** (dados de baja en operación)
- **Capturas**
- **Sometimientos** a la justicia
- **Desmovilizaciones** / entregas

## Reglas
- **Cada cifra va con su fuente.** Ver `data/operaciones.json` / `.csv`, campo `fuentes` (URLs).
- **Conteo conservador.** Ante duda o doble reporte, no se suma. `total` (191) ≤ `total_crudo`.
- Cada operación trae `reportado_oficialmente` e `incluido_en_conteo` para total transparencia.
- **Correcciones** públicas cuando una fuente se rectifica (`correcciones` en el dataset completo).

## Fases
- **Calibración** (hasta el 6-ago-2026): línea base y afinamiento del método.
- **Conteo oficial**: arranca el **7 de agosto de 2026** (posesión presidencial). `fecha_inicio_conteo` en `meta.json`.

## No somos gobierno ni oposición
Somos el marcador. Los mismos datos sirven para reconocer avances y para exigir resultados.
