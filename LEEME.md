# FIN443 – Victoria ✏️APELLIDO (grupo ✏️NÚMERO)

Proyecto del curso Programación en Finanzas (UAI, 2026).

## Pregunta
¿Supera una cartera optimizada de Markowitz (mínima varianza) a la
diversificación ingenua 1/N, fuera de muestra (backtest con rebalanceo
mensual), usando acciones del IPSA?

## Datos
- Precios de cierre diarios de acciones del IPSA.
- Fuente y período: ✏️ (ej.: Yahoo Finance, 2015-01-01 a 2025-12-31).
- Los datos originales van en datos/ y no se editan a mano.

## Cómo se ejecuta
    Rscript codigo/proyecto.R datos/precios_ipsa.csv resultados 0.03

- 1.er argumento: archivo de precios
- 2.º argumento: carpeta donde se escriben las salidas
- 3.er argumento: tasa libre de riesgo anual, en fracción (opcional)

## Estructura
- datos/: precios originales
- codigo/: programas en R
- resultados/: salidas (pesos y métricas)

