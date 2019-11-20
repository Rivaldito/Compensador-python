# Diseño de un compensador de retardo.

El fin de compensar un sistema, es poder mejorar su comportamiento transistorio y estacionario. Un compensador en retardo se integra
a un sistema en lazo cerrado, para poder mejorar el error que presenta en estado estacionario

El controlador implementado es de la forma Gc(s)=KB(TS+1)/(TBS+1)

Para diseñar este compensador se usaran la constante de Error de poscion (Kp), como valores de T, de tal forma que los polos y ceros de
este compensador queden situados muy cercas del origen y no modifiquen tan drasticamente la respuesta del sistema a una entrada particular,
en nuestro caso una entrada escalon. B del controlador representa el incremento que se tiene que hacer a la constante de error Kp para que
el error sea el deseado.

## Uso de Python para el diseño.

Para el diseño del controlador se empleara Python como una herramienta, con el motivo de visualizar el comportamiento del sistema.
Para esto se empleo el uso de librerias como

- Python control system library, esta libreria posee una syntaxis similar a MATLAB. su documentacion es:
[Python-control-system](https://python-control.readthedocs.io/en/0.8.2/conventions.html)

- Matlplotlib, esta libreria nos facilita crear graficas de la data obtenida con la libreria de Python control system, su documentacion es:
[Matplotlib](https://matplotlib.org/contents.html)





S.A.R
