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

**Actualización (confirmado con la gerencia):** Grupo New Farmacias ya opera con **Profit** como sistema administrativo/punto de venta en las 6 sucursales. Esto cambia — y simplifica — el plan de arranque:

**Solución de arranque (Fase 1 — mes 1-3):**
- El identificador del cliente sigue siendo su **número de teléfono** — pero ahora se captura directamente en Profit en cada venta, no en una hoja aparte. Esto requiere una sola orden operativa: que Profit pida/registre el teléfono en cada transacción (o al menos en la primera compra del cliente) en las 6 sucursales.
- **No hace falta la hoja de cálculo manual de la Fase 1 original.** En su lugar, el reporte por punto de venta que exporte Profit (idealmente semanal o quincenal al inicio) es la fuente de datos: quién compró, en qué sucursal, qué monto, y con qué frecuencia — suficiente para calcular puntos y detectar la racha de 3 meses de la Capa B de forma retroactiva/periódica, sin necesitar que el sistema calcule los puntos en tiempo real todavía.
- **Cómo se ve en caja al inicio:** el cajero pide el teléfono (ya sea porque Profit lo solicita en el flujo de venta, o como paso adicional del guion de la Sección 5) — el cálculo de puntos y la detección de canjes se procesan por lotes (tú o el/la Coordinador(a) de Marketing revisan el reporte y determinan quién califica para beneficio), no en el momento exacto de cada compra. Es un paso intermedio razonable mientras se decide si vale la pena automatizar el cálculo dentro de Profit o con una hoja de cálculo que se alimente del reporte.
- Tarjeta física opcional sigue siendo válida como recordatorio visual, pero el teléfono en Profit es la fuente de verdad.

**Fase 2 (cuando haya presupuesto o cuando el volumen de datos lo justifique — Q2/Q3 del plan):**
- Evaluar con el proveedor/soporte de Profit si el sistema tiene (o puede añadir) un módulo nativo de puntos/fidelización — si ya existe, es preferible a construir algo aparte.
- Si Profit no lo soporta de forma nativa, considerar un bot simple de WhatsApp o una hoja de cálculo semi-automatizada que se alimente del reporte de Profit y calcule puntos y canjes automáticamente.
- Esto sigue siendo una decisión abierta — ver Sección 10 de este documento.

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

Tres piezas, cada una con su rol: el **cartel** captura al cliente que ya está en tienda, el **post de redes** genera expectativa y alcance orgánico, y el **WhatsApp** activa de inmediato a los clientes que ya tienen relación con la farmacia (la conversión más fácil, porque ya confían en ustedes).

Todas usan el nombre de trabajo **"Club New Farmacias"** — reemplázalo si eliges otro nombre (Sección 2).

### 7.1 Cartel en tienda (punto de venta / vitrina)

Formato sugerido: una sola idea, tipografía grande, legible desde la fila de caja. Dos versiones — elige la que mejor combine con tu diseño (o dame el logo/colores y te ayudo a maquetarlo como imagen):

**Versión A — enfoque beneficio:**
> **CLUB NEW FARMACIAS**
> Acumula puntos en cada compra.
> Tu 2da compra ya tiene descuento.
> Pregúntale a tu farmacéutico. Es gratis.

**Versión B — enfoque crónicos (para sucursales con más tráfico de tratamientos):**
> **¿Tratamiento de todos los meses?**
> Únete al Club New Farmacias y no te quedes sin él.
> Te avisamos, acumulas puntos y en el mes 4 tienes un beneficio extra.
> Pregunta en caja.

### 7.2 Post de lanzamiento en redes sociales (Instagram/Facebook)

**Copy (versión corta, para carrusel o imagen única):**

> 🎉 Ya llegó el Club New Farmacias
>
> Desde hoy, cada compra en cualquiera de nuestras 6 sucursales suma puntos para ti.
>
> ✅ Acumulas en cada compra
> ✅ Descuento desde tu 2da visita
> ✅ Si llevas un tratamiento de todos los meses, te lo recordamos por WhatsApp para que nunca te quedes sin él
>
> Inscríbete gratis en tu próxima visita — solo necesitas tu número de teléfono.
>
> 📍 Valencia y Naguanagua
>
> #NewFarmacias #ClubNewFarmacias

**Idea visual:** foto del equipo en una de las sucursales entregando un producto, o una tarjeta/gráfico simple con el nombre del club y los 3 checks del copy. (Si quieres, uso la skill `image` para generar una propuesta gráfica.)

**Variante para Stories (más corta, con sticker de pregunta "¿Ya te inscribiste?"):**
> Desde hoy acumulas puntos en cada compra 🎉 Pregunta por el Club New Farmacias en cualquiera de nuestras 6 sucursales.

### 7.3 Mensaje de WhatsApp a clientes existentes

**Para la base general de contactos ya guardados:**
> Hola [Nombre] 👋 Somos New Farmacias.
>
> Te contamos que ya lanzamos el *Club New Farmacias*: desde ahora acumulas puntos en cada compra y tienes descuento desde tu segunda visita.
>
> Si llevas un tratamiento de todos los meses, también podemos avisarte antes de que se te acabe — para que nunca te quedes sin él.
>
> Solo pásate por cualquiera de nuestras sucursales e inscríbete, es gratis 🙂

**Variante específica para clientes ya identificados como crónicos (más dirigida):**
> Hola [Nombre] 👋 Desde hoy, tu farmacia de siempre tiene el *Club New Farmacias*.
>
> Como sabemos que llevas un tratamiento mensual, te avisaremos por aquí unos días antes de que se te acabe, para que no tengas que buscarlo en otro lado.
>
> Además acumulas puntos en cada compra. Solo confírmanos tu inscripción en tu próxima visita.

**Nota de tono:** los mensajes evitan sonar a publicidad masiva (no hay "¡OFERTA!" ni urgencia artificial) — es coherente con la voz de marca definida en el plan (cercana, de confianza, como el farmacéutico que te conoce). Ajusta el nivel de formalidad ("tú" vs "usted") según cómo hable normalmente el equipo con los clientes.

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
3. **¿Profit tiene o puede tener módulo nativo de puntos/fidelización?** — confirmado que Profit captura el teléfono y da reporte por punto de venta (resuelve la parte de identificación de cliente); falta confirmar con el proveedor si puede automatizar el cálculo de puntos/canjes o si eso se sigue procesando por fuera (hoja de cálculo alimentada por el reporte) al menos en Fase 1.
4. **¿Tarjeta física sí o no?** — no es indispensable (el teléfono es suficiente), pero puede ayudar a que el cliente recuerde el programa visualmente. Decisión de preferencia, no técnica.

---

*Programa de Fidelización — Club New Farmacias (borrador). Preparado por Claude (fCMO virtual), 2026-09-14. Complementa el Plan de Marketing v1.*
