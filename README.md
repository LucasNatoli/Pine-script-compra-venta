# Señales de Compra y Venta

Script Pine para correr en TradingView. Deteta Señales de compra y venta utilizando RSI y Bollinger Bands como indicadores.

## Cómo utilizarlo

Copiar el script `señales.pine`al editor Pine en  un ventana de TradingView. Grabar el script y agregarlo la Chart.  

El script dibujara las señales de Compra (verde) y Venta (rojo) al grafico. 

Tambien puede utilizarse como alarma y recibir notificaciones.  

## Funcionamiento

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
