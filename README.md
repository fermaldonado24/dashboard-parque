# Dashboard de medios tradicionales — Parque del Recuerdo

Dashboard de la campaña **Parque del Recuerdo · Aniversario 33 años** (set–oct 2026): un plan de medios tradicionales de **Radio + TV** con foco en el target **ABC1 · +45 años / senior**. Muestra inversión, cobertura geográfica, presión publicitaria (GRP sobre target) y eficiencia $/GRP, con el respaldo del cuadro comparativo de rating por segmento.

Mismo marco y metodología que el dashboard de GETNET (`v3-final`), adaptado a este plan.

## Contenido

- **`index.html`** — dashboard autocontenido. Se abre con doble click en cualquier navegador; no requiere instalación ni build. Carga Chart.js y la tipografía (Open Sans) desde CDN.

## Estructura del plan

| Medio | Detalle | Salidas | Inversión UYU | USD |
|---|---|---|---|---|
| Radio · Sarandí 690 AM | Informativo Sarandí (7–9h) + Las Cosas en su Sitio (9–12h) | 88 | $198.000 | 4.950 |
| Radio · Del Sol 99.5 FM | No Toquen Nada (8–12h), 2 salidas/día | 88 | $179.520 | 4.488 |
| Radio · Azul FM 101.9 | Mapa del Día (7–9h) + La Pecera (9–12h) | 88 | $105.600 | 2.640 |
| TV · Canal 10 | Laterales en Subrayado mediodía (~163"/día hábil, 44 días) | 240 | $600.000 | 15.000 |
| **Total propuesta** | | **504** | **$1.083.120** | **27.078** |

Sin vía pública ni producción en este plan.

## Métricas y fuentes

- **Costos, salidas de spot y segundos:** primera pestaña del Excel del plan (Campaña Plan Aniversario — Radio · TV, set/oct 2026).
- **Rating por segmento** (Total L-V, ABC1, ABC1 mañana 07–12h, 50–59 y ≥60 años): Cuadro comparativo de performance de **Factum 2025**, área metropolitana.
- **GRP de radio** = rating ABC1 de la franja mañana (07–12h) × salidas de spot — las tres emisoras corren en esa franja, que es donde se concentra el target ABC1 +45.
- **TV** = estimado proxy (laterales en Subrayado mediodía); no hay rating real por inserción.

## Despliegue en Vercel

Repositorio pensado para un proyecto estático de Vercel: al ser `index.html` en la raíz, Vercel lo sirve directo en la URL del proyecto sin configuración adicional. Cada push a `main` dispara un nuevo deploy.

> ⚠️ Contiene cifras reales de inversión y condiciones comerciales. Mantener el repositorio **privado**.
