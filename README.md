# Indicadores Economicos BCCR
> Obtenga el tipo de cambio del dólar del web service del Banco Central de Costa Rica.

## Instalación

    ```
    npm install indicadores-economicos-bccr
    ```

## Uso

    Obtener el tipo de cambio del dólar del día actual:

    indicadoresEconomicosBCCR.get().then( tipoDeCambio => {
        // { compra: 500.00, venta: 500.00 }
    });

    Obtener el tipo de cambio del dólar de una fecha de inicio a una fecha final, formato DD/MM/YYYY:

    indicadoresEconomicosBCCR.getByDate("01/01/2018", "02/01/2018").then( tipoDeCambio => {
        // { compra: 500.00, venta: 500.00 }
    });

## Meta

Luis Esteban López Acuña – [@estlopacu](https://twitter.com/estlopacu) – estlopacu@gmail.com

[https://github.com/estlopacu/indicadores-economicos-bccr](https://github.com/estlopacu/)