# CFO: Derecho sin tapujos

> Todos los números son **estimaciones** salvo los precios, la frecuencia y la audiencia de partida, que dio Rafa (`cfo-sources.md`). La herramienta imprime "$": son euros. No es asesoramiento financiero ni fiscal; la estructura y los impuestos, con tu gestor.

## Nota del CFO

- **El margen:** cada venta (mezcla de consulta y curso) deja **47,02 €** tras sus costes directos (63%). El problema no es el margen por venta, es el volumen.
- **El punto de equilibrio:** con tu tiempo valorado a 40 €/h (8 h/semana, 1.386 €/mes), hacen falta **unas 30 ventas al mes** (1.406 € fijos / 47,02 €). Al ritmo estimado, el mes 12 hay unas 6. Con una conversión del 1%, eso pide del orden de **3.000 escuchas por episodio**, y el modelo llega a 600 en el mes 12.
- **El año 1:** **−15.428 €** de resultado operativo si cuentas tu tiempo como coste; **+1.894 €** en caja si no lo cuentas (vista `cfo-caja.md`). El dinero de arranque (400 €) se recupera en el mes 7 en esa vista de caja.
- **La línea que más mueve el resultado:** **lo que vale un cliente después de la consulta.** El modelo solo cuenta los 50 € de la consulta; no cuenta el encargo que puede venir detrás porque no tengo ese dato. Si una parte de las consultas acaba en encargo, el podcast puede pagarse solo como captación aunque nunca sea rentable como producto.
- **Cash:** con tu tiempo no hay casi desembolso (400 €); el coste real son unas 8 h a la semana durante un año antes de tener audiencia.

## Tres formas de mejorar el margen

Sin el dato del encargo medio no puedo correr la palanca principal. Las que sí se pueden medir con la herramienta:

1. **Subir el peso del curso** (vender a despachos o como formación bonificable a 300 € en vez de 149 €). Cada punto de mezcla hacia el curso sube la contribución por venta.
2. **Bajar las horas por episodio** (formato de entrevista de 1 h con menos edición, clips sacados por un freelance o con IA). Pasar de 8 h a 5 h por semana baja los fijos a unos 886 €/mes y el equilibrio a unas 19 ventas al mes.
3. **Volumen:** los episodios temáticos por problema (despido, alquiler, herencia) son los que el panel dice que convierten.

## Condiciones del consejo sobre dinero

- [ ] Oferta con nombre y precio: a medias (precios sí, oferta no; pasa a `/founder-offer`).
- [ ] Medir conversión en los primeros 8 a 12 episodios: pendiente de lanzar.

---

# Unit economics: Derecho sin tapujos: podcast + consultas Orbius Legal + curso IA (ESTIMACIONES, ver cfo-sources.md)

Every number below comes from the input file. Nothing is looked up or guessed.

## One venta (mezcla: 75% consulta a 50 €, 25% curso a 149 €)

| line | per venta (mezcla: 75% consulta a 50 €, 25% curso a 149 €) |
| --- | ---: |
| Price | €74.75 |
| Tiempo de Rafa en la consulta (0,75 h a 40 €/h, en el 75% de ventas) [estimación] | -€22.50 |
| Comisión de plataforma del curso (10% de 149 €, en el 25% de ventas) [estimación] | -€3.73 |
| Comisiones de pago (~2%) [estimación] | -€1.50 |
| **Contribution** (what each venta (mezcla: 75% consulta a 50 €, 25% curso a 149 €) leaves to pay the fixed costs) | **€47.02** (63%) |

## The margin that matters

Fixed costs: €1,406 a month (Tiempo de Rafa produciendo: 8 h/semana a 40 €/h [estimación] €1,386, Alojamiento del podcast y software [estimación] €20).

- **Break-even: 1 venta (mezcla: 75% consulta a 50 €, 25% curso a 149 €)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (0 a day): **-251%** of every sale, after every cost.

## Year 1, month by month

| month | venta (mezcla: 75% consulta a 50 €, 25% curso a 149 €)s a day | revenue | profit | cumulative (after €400 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 0 | €22 | -€1,392 | -€1,792 |
| 2 | 0 | €37 | -€1,382 | -€3,174 |
| 3 | 0 | €60 | -€1,368 | -€4,543 |
| 4 | 0 | €90 | -€1,350 | -€5,892 |
| 5 | 0 | €120 | -€1,331 | -€7,223 |
| 6 | 0 | €150 | -€1,312 | -€8,535 |
| 7 | 0 | €187 | -€1,288 | -€9,823 |
| 8 | 0 | €224 | -€1,265 | -€11,088 |
| 9 | 0 | €269 | -€1,237 | -€12,325 |
| 10 | 0 | €314 | -€1,209 | -€13,534 |
| 11 | 0 | €374 | -€1,171 | -€14,705 |
| 12 | 0 | €448 | -€1,124 | -€15,828 |

- **Year 1 operating profit: -€15,428** on €2,295 of revenue.
- After the €400 startup spend: -€15,828.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **€15,828**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | -251% | 1 | -€15,428 |
| Price -10% | -290% | 2 | -€15,658 |
| Volume -20% | -329% | 1 | -€15,717 |
| Unit costs +15% | -256% | 2 | -€15,556 |

## Red flags

- Year 1 loses money on operations (-€15,428).
- The startup spend is not earned back within year 1.
