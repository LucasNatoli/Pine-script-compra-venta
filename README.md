# Señales de Compra y Venta

Señales de compra y venta utilizando RSI y Bollinger Bands en TradingView.

## Cómo utilizarlo

Copiar el contenido del script [`señales.pine`](https://github.com/LucasNatoli/Pine-script-compra-venta/blob/main/sen%CC%83ales.pine) al editor Pine de TradingView. Grabar el script y agregarlo al Chart. 


![Agregar el script al editor, guardar y agregar al chart](pine-script-01.png?raw=true "Cómo utilizarlo")

## Funcionamiento

El script dibujara las señales de Compra (verde) y Venta (rojo) al grafico. 

La señal de venta se activa cuando el RSI se encuentra sobrecomprado y el precio de cierre de la vela es mayor o igual a la banda superior de Bollinger.

La señal de compra se activa cuando el RSI se encuentra sobrevendido y el precio de cierre de la vela es menor o igual a la banda inferior de Bollinger.

## Valores por defecto

### Bollinger Bands

* Origen: Precio de cierre
* Longitud: 20 periodos
* Desviación Standard: 2

### RSI
* Origen: cierre
* Longitud Rapida: 12
* Longitud Lenta: 26
* Señal: 9


## Integración con Tradingview

Puede utilizarse como alarma y para recibir alertas: popups, email, webhooks, etc.  

<img src="pine-script-02.png?raw=true" width="444">
