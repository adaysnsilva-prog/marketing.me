# Preparación de Negociación — Proveedor/Laboratorio Biotech

**Estatus:** Guía de preparación v1 — para estructurar la negociación antes de sentarte con el proveedor.
**Rol:** Comprador de Grupo New Farmacias (6 sucursales, Valencia y Naguanagua, Carabobo).
**Objetivo de esta negociación:** conseguir mejores condiciones (precio, bonificación, pago o ambas) en la línea biotech, sin comprometerte a un trato que no puedas defender con números frente a San Anselmo/Farmatodo ni frente a tu propio margen mínimo (20%).

> Nota: no tengo todavía tus datos reales de costos, catálogo o ventas — este documento es el marco y el checklist para prepararte. En cuanto me compartas los archivos (ver Sección 1), lo convierto en el análisis numérico real con `scripts/analizar_compras.py` de la skill `comprador-farmaceutico`.

---

## 1. Qué preparar antes de la reunión (checklist)

No entres a negociar con la oferta del proveedor como único punto de referencia — eso te deja negociando contra ti mismo. Antes de la reunión, junta:

### A. Tu historial con este proveedor (o con la línea biotech en general)
- [ ] Qué le compras hoy a este proveedor (o a quien te surte esa línea biotech actualmente): productos, costos, moneda.
- [ ] Volumen de compra mensual/anual de esa línea — en unidades y en $.
- [ ] Condiciones actuales: plazo de pago, moneda de pago (USD/Bs), descuentos ya otorgados, bonificaciones (unidades gratis), política de devoluciones/vencidos.
- [ ] % que representa esta línea biotech sobre tu gasto total de compras — esto te dice cuánto peso real tienes para negociar (no es lo mismo negociar el 2% del gasto que el 15%).

### B. Rotación real de esos productos (no negociar a ciegas)
- [ ] Ventas propias de esos productos en las 6 sucursales (unidades vendidas en los últimos meses).
- [ ] Clasificación de rotación (Alta/Media/Baja) — la skill puede hacer esto con `scripts/clasificar_rotacion.py` si me compartes tus ventas.
- [ ] Si tienes reporte de faltantes de piso de venta: revisa si estos productos biotech aparecen seguido como "pedido y no había" — eso es demanda real que hoy se está perdiendo, y es un argumento de peso frente al proveedor ("necesito que esto no se quiebre, denme mejor precio por compromiso de volumen constante").

### C. Punto de comparación (tu BATNA — mejor alternativa si no llegas a acuerdo)
- [ ] Al menos **una cotización de otra droguería/distribuidor** para los mismos productos biotech (o equivalentes terapéuticos del mismo laboratorio). Sin esto, no tienes forma de saber si lo que te ofrecen es realmente bueno.
- [ ] Si el laboratorio tiene más de un distribuidor autorizado en Venezuela, vale la pena cotizar con al menos 2.
- [ ] Precio de venta actual de San Anselmo y Farmatodo para estos mismos productos — para saber si hoy ya estás compitiendo bien, mal, o ni siquiera estás en el rango.

### D. Tu propia posición de venta
- [ ] Precio de venta actual de New Farmacias para estos productos y margen resultante.
- [ ] ¿Estos productos son de tratamiento crónico o alto costo? (cambia la prioridad — ver Sección 3 del flujo de la skill: crónicos y alto costo son sensibles a precio y de alta prioridad de negociación).

---

## 2. Tus palancas de negociación como cadena de 6 sucursales

Un laboratorio biotech negocia distinto con una farmacia independiente que con una cadena — pero solo si tú le muestras la diferencia con números, no solo diciendo "somos 6 sucursales". Palancas concretas, de más a menos fuertes típicamente:

1. **Volumen consolidado en un solo pedido/contrato.** En vez de que cada sucursal compre por separado (si es que eso pasa hoy), negocia como un solo volumen de 6 sucursales. Muéstrale al proveedor el gasto total anual consolidado — es tu número más persuasivo.

2. **Compromiso de volumen a futuro (forecast), no solo lo ya comprado.** Un proveedor valora más una proyección creíble de compra mensual constante (basada en tu rotación real, punto B arriba) que el histórico solo — porque le da previsibilidad a él también.

3. **Consolidar gasto que hoy está repartido.** Si compras productos similares o de la misma categoría terapéutica a varios proveedores distintos, muéstraselo: "hoy repartimos $X entre 3 proveedores en esta línea — si consolidamos contigo, tu volumen sube Y%". Esto es exactamente lo que la skill llama "concentración por laboratorio" — vale la pena correr ese análisis si tienes el catálogo completo del proveedor.

4. **Visibilidad/exhibición en punto de venta a cambio de mejor precio.** 6 sucursales con tráfico de clientes crónicos es algo que el laboratorio puede valorar más allá del margen — exhibición preferente, material POP, o mención en tus redes sociales (que ya vas a activar según el plan de marketing) puede ser una moneda de cambio que no te cuesta dinero directo.

5. **Condiciones de pago como palanca, no solo precio.** A veces el proveedor tiene más margen para moverse en plazo de pago o bonificación (unidades gratis por volumen) que en el precio de lista. Pide que te cotice las tres formas por separado: descuento directo, bonificación en unidades, y plazo de pago extendido — y compáralas en $ real, no en la forma en que te las presenten.

6. **Exclusividad de línea (úsala con cuidado).** Ofrecer que New Farmacias sea el punto de venta preferente de esa línea biotech en Valencia/Naguanagua puede valer una mejor condición — pero solo tiene sentido si esos productos ya tienen buena rotación o si confías en poder impulsarla (branding + fidelización + recordatorio de recompra ya están en tu plan de marketing). No la ofrezcas si no la puedes sostener.

7. **Riesgo cambiario compartido.** En Venezuela, ofrecer pago pronto en USD (si tu flujo de caja lo permite) suele ser una palanca fuerte porque le quita al proveedor el riesgo de devaluación mientras espera el pago — a veces vale más que el volumen mismo.

**Antes de la reunión, decide cuál de estas 7 vas a priorizar** — no llegues a pedir las 7 a la vez, eso diluye la negociación. Elige 2-3 según lo que tu análisis de rotación y gasto te muestre que es más fuerte en tu caso.

---

## 3. Cómo comparar la oferta del proveedor contra alternativas (para no comprometerte a un mal trato)

Sigue este orden — es el mismo que usa la skill `comprador-farmaceutico` para cualquier análisis de compra, aplicado aquí a una sola negociación:

1. **Normaliza todo a una sola moneda.** Si la oferta viene en Bs, confirma la tasa BCV del día antes de comparar nada — una oferta en Bs puede parecer barata solo porque la lista está desactualizada frente a la inflación/tasa del día. Desconfía de cualquier precio que parezca "demasiado bueno".

2. **Calcula el costo neto real, no el descuento anunciado.** Un "20% de descuento" con plazo de pago corto puede salir más caro en la práctica que un "12% de descuento" con bonificación de unidades y plazo largo. Pide al proveedor que te desglose: precio de lista, descuento, bonificación, y condición de pago — y calcula tú el costo neto por unidad en cada escenario.

3. **Compáralo contra tu cotización alternativa (punto C de la Sección 1).** Sin este punto de comparación, no sabes si la oferta del proveedor biotech es buena o solo parece buena porque es la única que tienes sobre la mesa.

4. **Corre el precio de venta resultante a distintos márgenes (20%, 25%, 30%, 35%) y compáralo con San Anselmo y Farmatodo.** Si con el nuevo costo negociado tu precio de venta ya le gana a la competencia incluso al margen alto (30-35%), tienes espacio para negociar más agresivo en el margen o para invertir esa diferencia en el programa de fidelización. Si ni al margen mínimo (20%) le ganas a la competencia, díselo al proveedor directamente — es el argumento más fuerte que puedes usar ("con este costo no puedo competir en precio, necesito X% adicional o Y bonificación para que tenga sentido meterle volumen a tu línea").

5. **No negocies duro por productos de baja rotación.** Si algunos de los productos de esta línea biotech son de rotación baja/C, no vale la pena gastar capital de negociación ahí — concéntrate en los de alta rotación (A) o alto costo, que son los que de verdad mueven el gasto y el margen.

---

## 4. Ficha resumen para llevar a la reunión (plantilla)

Rellena esto con tus datos reales antes de sentarte — es tu "hoja de ruta" de la negociación, para no perder el hilo ni ceder más de lo planeado:

| Campo | Tu dato |
|---|---|
| Volumen de compra actual (mensual/anual, $) | |
| % del gasto total de compras que representa | |
| Proveedor(es) alternativo(s) cotizado(s) y su precio | |
| Rotación de los productos principales de esta línea (A/B/C) | |
| Precio de venta actual vs. San Anselmo / Farmatodo | |
| Palancas que vas a usar (elige 2-3 de la Sección 2) | |
| Condición mínima aceptable (tu límite antes de levantarte de la mesa) | |
| Condición ideal (tu punto de partida al pedir) | |

---

## 5. Próximo paso

Si me compartes:
1. Los costos/condiciones actuales de este proveedor biotech (o su cotización nueva),
2. Tu(s) cotización(es) alternativa(s) de otra droguería para los mismos productos, y
3. Tus ventas propias de esos productos (para calcular rotación real),

puedo correr el análisis completo (costo neto real, rotación, comparación con San Anselmo/Farmatodo, y precio de venta recomendado por producto) con las herramientas de la skill `comprador-farmaceutico` y dejarte un resultado con números concretos en vez de este marco general. Si son pocos productos, te lo entrego directo en el chat; si es un catálogo largo, te lo dejo en Excel.

---

*Preparación de Negociación — Proveedor Biotech. Grupo New Farmacias. Preparado por Claude (Comprador), 2026-09-16.*
