---
layout: default
title: "Diario Quant 002 | Primera compra y venta en Alpaca Paper"
permalink: /quant-lab/primera-operacion-paper/
---

[← Volver al portafolio](/)

# Primera compra y venta simulada: SPY en Alpaca Paper
**Diario Quant · 30 de octubre de 2026 · Prueba operativa**

Hoy completé la primera operación de ida y vuelta del laboratorio: comprar una participación de SPY y venderla en Alpaca Paper Trading. El resultado fue una pérdida simulada de **USD 0,02**. La cuenta terminó sin posiciones abiertas.

## Registro de ejecución

| Operación | Cantidad | Límite USD | Precio ejecutado USD | Hora del panel (UTC−05:00) | Estado |
|---|---:|---:|---:|---|---|
| Compra SPY | 1 | 757,00 | 756,84 | 18:53:44 | Filled |
| Venta SPY | 1 | 756,00 | 756,82 | 18:54:21 | Filled |

Saldo paper inicial: **USD 100.000,00**. Saldo final mostrado: **USD 99.999,98**. Diferencia entre precios: −USD 0,02 por una participación, aproximadamente −0,0026% del importe comprado. No se ha auditado aquí un desglose separado de comisiones o tasas.

Fuente de las ejecuciones: historial del panel autenticado de Alpaca, consultado después de ambas órdenes. No se usó dinero real ni se abrió una posición corta.

## Qué probé y qué no demuestra

El propósito fue comprobar selección del activo, límites de precio, envío, confirmación y cierre de la posición. No fue una operación swing validada ni una prueba de rentabilidad.

El panel mostraba cotización **SIP retrasada 15 minutos**; las órdenes fueron limitadas y admitidas para sesión extendida. El precio mostrado antes de enviar no se confundió con el precio realmente ejecutado. La simulación puede diferir de una operación real, como explica [Alpaca sobre paper trading](https://docs.alpaca.markets/us/docs/paper-trading).

QS-001 conserva sus reglas de medias 20/50 y ejecución al cierre siguiente. Esta prueba breve fuera de la sesión regular se registra aparte, como **PT-001**, para no atribuirle resultados que no le corresponden.

## Más allá de tres ETF: una segunda capa de investigación

El laboratorio inicial observó SPY, QQQ e IWM, que son ETF. Ahora ampliaré la lista de estudio a acciones individuales usando información pública de inversores institucionales, además de precio, tendencia, volumen, resultados empresariales y riesgo.

El informe de [Berkshire Hathaway al 30 de junio de 2026](https://www.berkshirehathaway.com/qtrly/2ndqtr26.pdf), nota 4, identifica entre sus mayores posiciones a Alphabet, American Express, Apple, Bank of America y Coca-Cola. Son ideas para investigar, no compras nuevas identificadas hoy.

La [ficha de Pershing Square Holdings de septiembre de 2026](https://assets.pershingsquareholdings.com/wp-content/uploads/2026/10/14141351/PSH-Fact-Sheet-September-2026-Website.pdf), publicada el 14 de octubre, incluye Amazon, Microsoft, Meta, Uber y Visa entre las compañías divulgadas de su cartera. Tampoco revela el precio de entrada ni que se hayan comprado hoy.

Los [formularios 13F pueden presentarse hasta 45 días después del cierre trimestral](https://www.sec.gov/files/divisions/investment/13ffaq.htm) y omiten las posiciones cortas. Para inferir compras o ventas entre trimestres habrá que comparar cantidades de títulos y ajustes corporativos; un cambio en el valor de mercado no basta.

## Siguiente evaluación

La lista institucional pasa a vigilancia, no a órdenes automáticas. Antes de una nueva operación paper revisaré datos actuales, catalizadores y calendario de resultados, liquidez y tamaño de posición; registraré el motivo de entrada y de salida antes de enviar la orden.

Hoy la evidencia es concreta: **dos ejecuciones simuladas confirmadas, una pequeña pérdida y posición final cero**. El diario conservará los resultados negativos y las sesiones sin operaciones.

*Investigación y simulación educativa. No son recomendaciones personalizadas ni promesas de rentabilidad.*

[Documentación oficial de Alpaca](https://docs.alpaca.markets/)
