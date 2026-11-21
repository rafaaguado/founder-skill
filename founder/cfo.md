# CFO: Derecho sin tapujos (vista caja, con el tiempo aparte)

> Corrección del 21/11/2026, a raíz de la pregunta de Rafa. Las "pérdidas" de los cálculos anteriores eran casi todas **el tiempo de Rafa valorado a 40 €/h** (8 h semanales de producción y un 50% de los honorarios como coste de llevar cada encargo). Ese tiempo no sale de la caja: Rafa ya ejerce y tiene ingresos. Por eso ahora el modelo cuenta **solo dinero que entra y sale**, y el tiempo va en horas en una sección propia. Solo sería un coste si quitara horas a trabajo que ya se factura. La versión anterior está en `cfo-coste-tiempo.md` y la primera en `cfo-mezcla.md`. Datos de Rafa: consulta a 50 € y encargo de 1.500 a 3.000 €. El resto son estimaciones (`cfo-sources.md`). La herramienta imprime "$": son euros. No es asesoramiento financiero ni fiscal.

## Nota del CFO

- **Caja del año 1: +16.430 €** de ingresos netos atribuibles al podcast, sobre 16.693 € facturados. Son unas 23 consultas y unos 7 encargos, con un 30% de conversión a encargo (estimación) y 2.250 € de honorario medio.
- **Lo que sale de caja:** 400 € de arranque (micrófono para invitados y portada) y unos 20 €/mes de alojamiento y software. **Se recupera en el mes 3.** Basta con una consulta que acabe en encargo en todo el año para cubrir el gasto anual.
- **El tiempo, aparte:** unas **416 horas al año** de producción (8 h/semana, estimación) más las horas de los encargos nuevos, que ya se pagan con sus honorarios. Por cada hora de producción, el podcast trae del orden de **40 € de facturación neta** en el escenario base.
- **Cuándo el tiempo sí es un coste:** solo si las horas del podcast o de los encargos nuevos desplazan trabajo que ya se factura. Si tu agenda está llena con los referidos, el límite no es el dinero, es la capacidad. En ese caso conviene bajar horas de producción (formato de 1 h, edición con apoyo) antes que dejar el podcast.
- **La línea que más mueve el resultado** sigue siendo la conversión de consulta a encargo con público que llega en frío. Con un 20% y 1.500 € el año 1 deja 7.796 €; con un 40% y 3.000 €, 28.518 €.

## Escenarios de caja del año 1 (unas 23 consultas en el año)

| Consulta → encargo | Encargos en el año | 1.500 € | 2.250 € | 3.000 € |
|---:|---:|---:|---:|---:|
| 20% | 4,6 | 7.796 € | 11.249 € | 14.703 € |
| **30%** | **6,9** | 11.249 € | **16.430 €** | 21.611 € |
| 40% | 9,2 | 14.703 € | 21.611 € | 28.518 € |

Fuera del modelo, y todo a favor: el curso de IA, los encargos que lleguen años después por referencias de oyentes y el valor del podcast en la vuelta a redes y web (`monetizacion.md`).

## Tres formas de mejorar

1. **Conversión a encargo:** con la consulta descontable del encargo, que es lo que pedía el panel. Pasar del 30% al 40% con 2.250 € suma 5.181 € en el año 1.
2. **Menos horas por episodio:** no mejora la caja, pero libera capacidad si la agenda aprieta.
3. **Audiencia antes:** con los clips en el canal Rafa Aguado y la web. Las consultas crecen con las escuchas, y el mes 12 dobla al mes 8 (4,5 consultas frente a 2,25).

## Condiciones del consejo sobre dinero

- [x] Hay una vía con precio y valor medible: la consulta y el encargo.
- [ ] Oferta con nombre y garantía compatible con la deontología: pendiente, pasa a `/founder-offer`.
- [ ] Medir la conversión real en los primeros 8 a 12 episodios: pendiente de lanzar.

---

# Unit economics: Derecho sin tapujos: consultas captadas por el podcast, VISTA CAJA (el tiempo de Rafa va aparte, ver cfo.md)

Every number below comes from the input file. Nothing is looked up or guessed.

## One consulta captada

| line | per consulta captada |
| --- | ---: |
| Price | €725.00 |
| Comisiones de pago [estimación] | -€1.00 |
| **Contribution** (what each consulta captada leaves to pay the fixed costs) | **€724.00** (100%) |

## The margin that matters

Fixed costs: €20 a month (Alojamiento del podcast y software [estimación] €20).

- **Break-even: 1 consulta captadas a day.** Below that you lose money every month.
- **Profit margin at your plan** (0 a day): **99%** of every sale, after every cost.

## Year 1, month by month

| month | consulta captadas a day | revenue | profit | cumulative (after €400 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 0 | €163 | €143 | -€257 |
| 2 | 0 | €272 | €252 | -€6 |
| 3 | 0 | €435 | €414 | €409 |
| 4 | 0 | €652 | €632 | €1,040 |
| 5 | 0 | €870 | €849 | €1,889 |
| 6 | 0 | €1,088 | €1,066 | €2,955 |
| 7 | 0 | €1,359 | €1,338 | €4,293 |
| 8 | 0 | €1,631 | €1,609 | €5,902 |
| 9 | 0 | €1,957 | €1,935 | €7,836 |
| 10 | 0 | €2,284 | €2,261 | €10,097 |
| 11 | 0 | €2,719 | €2,695 | €12,792 |
| 12 | 0 | €3,262 | €3,238 | €16,030 |

- **Year 1 operating profit: €16,430** on €16,693 of revenue.
- After the €400 startup spend: €16,030.
- Startup money earned back: month 3.
- Cash you need before it pays for itself: **€400**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 99% | 1 | €16,430 |
| Price -10% | 99% | 1 | €14,761 |
| Volume -20% | 99% | 1 | €13,096 |
| Unit costs +15% | 99% | 1 | €16,427 |

No red flags in these numbers. They are only as good as the inputs: check every cost against a real quote.
