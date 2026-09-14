# Programa de Fidelización — Grupo New Farmacias

**Estatus:** Borrador v1 — diseñado para lanzarse con presupuesto casi cero y sin sistema de CRM, usando lo que ya existe (WhatsApp, hojas de cálculo, personal de caja).
**Se conecta con:** Plan de Marketing v1 (`docs/marketing-plan/plan-grupo-new-farmacias.md`), Sección 6 (Retención) y Sección 8 (Ingresos).

---

## 1. Objetivo (una sola cosa)

Dar al cliente crónico (y al cliente frecuente en general) **una razón tangible para no irse a San Anselmo o Farmatodo por $2 menos** — sin que el programa le cueste al negocio más de lo que le devuelve en recurrencia y ticket promedio.

**No es el objetivo:** ser el programa con más beneficios del mercado. Es el objetivo: ser simple de operar en 6 sucursales sin CRM, y que el cliente lo entienda en 10 segundos.

---

## 2. Nombre del programa (elige o ajusta)

Tres opciones — usa la que mejor encaje con tu marca; si no tienes preferencia, la opción 1 es la más simple de comunicar:

1. **Club New Farmacias** — directo, fácil de decir en caja ("¿ya eres del Club?").
2. **New Contigo** — enfatiza cercanía/relación, coherente con el posicionamiento del plan.
3. **Tarjeta Amiga New Farmacias** — más cálido, funciona bien si el programa se apoya en tarjeta física.

*(Asunción: uso "Club New Farmacias" en el resto de este documento — reemplázalo si eliges otro nombre.)*

---

## 3. Mecánica (dos capas — simple y sin fricción)

Un solo programa, pero con dos capas de beneficio porque el negocio tiene dos tipos de cliente muy distintos (ver Sección 2 del plan de marketing):

### Capa A — Todos los miembros (acumulación por compra)

- **Cómo se gana:** 1 punto por cada $1 (o el monto que definas) en compras, en cualquiera de las 6 sucursales.
- **Cómo se canjea:** al llegar a un umbral (ej. 100 puntos), el cliente recibe $X de descuento o un producto de bajo costo gratis en su próxima compra.
- **Bono de bienvenida:** puntos dobles en la primera compra tras inscribirse — da un motivo inmediato para inscribirse en caja, no "después".

### Capa B — Beneficio de constancia para tratamientos crónicos

Esta es la capa que realmente mueve la aguja del plan (retención de crónicos), y es distinta de la acumulación por monto:

- **Cómo se activa:** el cliente identificado con tratamiento crónico (hipertensión, diabetes, etc. — ver Sección 5 del plan) que compra su tratamiento dentro de su ciclo esperado **3 meses seguidos**, recibe un beneficio extra el 4to mes (ej. producto de cuidado personal gratis, un % adicional de descuento en esa compra, o puntos triples).
- **Por qué separado de la Capa A:** recompensa la *constancia*, no el monto — que es exactamente el comportamiento que queremos reforzar (que no se salte un mes ni compre en otro lado "por probar").
- **Efecto secundario útil:** esta racha de 3 meses es, en sí misma, el dato que necesitas para saber si el recordatorio de recompra (Sección 6 del plan) está funcionando.

**Regla de simplicidad para el lanzamiento:** si operar dos capas desde el día 1 es demasiado para el equipo actual, lanza solo la Capa A el primer mes y añade la Capa B en el mes 2 — no esperes a tener las dos perfectas para lanzar.

---

## 4. Cómo se identifica y registra al cliente (sin CRM)

El reto real de un programa en 6 sucursales sin sistema central es que el cliente debe poder acumular y canjear **en cualquier sucursal**, no solo donde se inscribió.

**Solución de arranque (Fase 1 — mes 1-3):**
- El identificador del cliente es su **número de teléfono** (no una tarjeta física numerada) — así cualquier sucursal puede buscarlo.
- Registro centralizado en una **hoja de cálculo compartida** (Google Sheets, editable desde el teléfono/computadora de cada sucursal): columnas mínimas — teléfono, nombre, sucursal de inscripción, fecha de inscripción, ¿tiene tratamiento crónico? (sí/no + cuál), puntos acumulados, fecha de última compra registrada.
- En caja, el cajero pregunta el teléfono, lo busca o lo registra, y anota la compra. Esto añade fricción operativa — ver guion en la Sección 6 para minimizarla.
- Tarjeta física opcional (con el teléfono impreso/escrito a mano) como recordatorio visual para el cliente, pero **el teléfono es la fuente de verdad**, no la tarjeta — así no se pierde el historial si se olvida la tarjeta.

**Fase 2 (cuando haya presupuesto — Q2/Q3 del plan):**
- Migrar a una herramienta de fidelización ligera integrada al punto de venta (muchos sistemas de punto de venta para farmacias/retail en Latinoamérica ya incluyen módulo de puntos — vale la pena revisar si el sistema de punto de venta actual de New Farmacias ya tiene uno antes de comprar algo nuevo) o a un bot simple de WhatsApp que consulte puntos automáticamente.
- Esto es una decisión abierta — ver Sección 8 de este documento.

---

## 5. Guion para el personal de caja (inscripción y registro)

**Inscripción (cliente nuevo, primera vez):**
> "¿Ya eres parte del Club New Farmacias? Es gratis — acumulas puntos con cada compra y en tu segunda compra ya tienes descuento. Solo necesito tu número de teléfono."

**Registro (cliente ya inscrito):**
> "¿Me repites tu número para sumar tus puntos de hoy?"

**Detección de tratamiento crónico (al inscribir o en compra de antihipertensivo/antidiabético):**
> "Veo que llevas [tratamiento]. Te podemos avisar por WhatsApp unos días antes de que se te acabe, para que no te quedes sin él — ¿te parece si te lo activamos?"

**Al llegar al umbral de canje:**
> "Tienes [X] puntos acumulados — hoy puedes usarlos para [beneficio]. ¿Quieres aplicarlo a esta compra?"

Mantener el guion corto es intencional: cada segundo extra en caja es fricción real en un negocio de alto tráfico. Si en la práctica toma demasiado tiempo, es señal de que hace falta pasar a Fase 2 antes de lo planeado.

---

## 6. Economía del programa (a validar con datos reales)

*Esta sección tiene números de ejemplo — reemplázalos con tus datos reales antes de fijar las tasas definitivas. Es la decisión abierta de mayor riesgo financiero de este documento.*

| Variable | Valor de ejemplo | Nota |
|---|---|---|
| Tasa de acumulación | 1 punto = $1 gastado | Ajustable |
| Valor de canje | 100 puntos = $3-5 de descuento | Debe representar ~3-5% del ticket promedio, no más, para no erosionar margen |
| Costo del bono de bienvenida | Puntos dobles 1 vez | Costo controlado — ocurre una sola vez por cliente |
| Costo del beneficio de constancia (Capa B) | 1 producto de bajo costo o % extra al 4to mes consecutivo | Debe salir de la línea de productos con mejor margen (cuidado personal), no de las líneas crónicas de bajo margen |

**Regla de oro para no perder dinero con el programa:** el costo total del beneficio (Capa A + Capa B) por cliente no debería superar lo que el negocio gana en margen adicional por su mayor recurrencia y ticket. Como el CAC y el ticket promedio real todavía no están medidos (decisiones abiertas #1 y #5 del plan de marketing), **lanza con una tasa conservadora los primeros 2 meses** y ajústala cuando tengas los primeros datos reales de canje — es más fácil subir el beneficio después que quitarlo una vez que el cliente se acostumbró.

Vale la pena correr estos números junto con la skill `anthropic-skills:comprador-farmaceutico`, que ya tiene contexto de márgenes por línea de producto de Grupo New Farmacias.

---

## 7. Comunicación del lanzamiento

- **En tienda:** cartel simple en caja/vitrina con el nombre del programa y la mecánica en una frase ("Acumula puntos en cada compra. Pregúntale a tu farmacéutico.").
- **Redes sociales:** anuncio del lanzamiento como parte del calendario de contenido (Sección 4 del plan) — usar la skill `copywriting` o `social` para redactar el post.
- **WhatsApp a clientes existentes:** mensaje corto a los clientes que ya tienen WhatsApp registrado informando del lanzamiento y cómo inscribirse en su próxima visita.

*Plantillas de estos tres mensajes: puedo escribirlas ahora mismo si quieres — dímelo.*

---

## 8. Plan de lanzamiento (se integra al plan de 90 días)

| Semana | Acción | Responsable |
|---|---|---|
| 3-4 | Definir nombre final, tasa de puntos y umbral de canje con datos reales de ticket promedio | Gerente General |
| 3-4 | Crear la hoja de cálculo compartida y capacitar a cajeros de las 6 sucursales en el guion (Sección 5) | Coordinador(a) de Marketing |
| 5 | Lanzar Capa A (acumulación por compra) en las 6 sucursales | Coordinador(a) de Marketing |
| 6 | Publicar en redes + cartel en tienda + primer mensaje a base de WhatsApp existente | Coordinador(a) de Marketing |
| 7-8 | Activar Capa B (beneficio de constancia para crónicos), una vez que el recordatorio de recompra (Sección 6 del plan) esté funcionando | Coordinador(a) de Marketing |
| 12 | Primera revisión: # de inscritos, # de canjes, costo real vs. estimado | Gerente General |

---

## 9. Métricas a seguir

- **# de clientes inscritos** (meta Q1 del plan: al menos 100).
- **% de clientes inscritos que vuelven a comprar dentro de 30-35 días** (la métrica que realmente prueba si el programa retiene).
- **# de canjes realizados** y su costo total acumulado — para validar la economía de la Sección 6.
- **% de clientes crónicos que alcanzan la racha de 3 meses (Capa B)** — proxy directo de si el recordatorio de recompra está funcionando.

---

## 10. Decisiones abiertas de este documento

1. **Nombre final del programa** — elegir entre las 3 opciones de la Sección 2 o proponer otro.
2. **Tasa de acumulación y umbral de canje reales** — depende del ticket promedio y margen real (Sección 6) — hoy son números de ejemplo.
3. **¿El sistema de punto de venta actual ya tiene módulo de fidelización?** — vale la pena revisarlo antes de construir la hoja de cálculo manual; podría ahorrar el paso de Fase 1.
4. **¿Tarjeta física sí o no?** — no es indispensable (el teléfono es suficiente), pero puede ayudar a que el cliente recuerde el programa visualmente. Decisión de preferencia, no técnica.

---

*Programa de Fidelización — Club New Farmacias (borrador). Preparado por Claude (fCMO virtual), 2026-09-14. Complementa el Plan de Marketing v1.*
