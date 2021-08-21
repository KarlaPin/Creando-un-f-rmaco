Conoce a las reglas de Lipinski



Hace veinte años, un químico curioso y apasionado por su trabajo, revolucionó el descubrimiento de nuevos fármacos. Su nombre es Crhistopher Lipinski y su Regla de los cinco constituye hoy en día el primer paso para evaluar el potencial de cualquier compuesto para ser procesado de manera adecuada por el cuerpo humano.


El Dr. Lipinski es un ejemplo del poder de una persona que disfruta su profesión. En 2005 publicó "Advanced Drug Delivery Reviews", texto que se ha convertido en el texto químico más citado en la actualidad, principalmente haciendo referencia a la Regla de los cinco, misma que llego a la comunidad científica en este documento.


Cinco, el número de la suerte


La hoy famosa Regla de los cinco, establece las reglas empíricas que un fármaco debe cumplir para llegar a ser utilizado como medicina. Las reglas establecen que:

Debe tener un peso molecular inferior a 500 g/mol.
No debe tener más de cinco donadores de puentes de hidrógeno.
No debe tener más de 10 aceptores de puentes de hidrógeno.
Debe tener un partición octanol-agua (logP) inferior a 5.


Como se puede observar, cada regla incluye un parámetro que es múltiplo de cinco, factor que dio origen al nombre de la regla misma. Esta regla, se ha convertido en la base para la evaluación del potencial de un fármaco para convertirse en medicina. Su importancia radica en que permite diferenciar fácilmente los compuestos sin probabilidad de éxito de aquellos que son viables, lo que a su vez brinda la posibilidad de enfocar las pruebas físicas y biológicas en fármacos que el cuerpo humano es capaz de procesar y utilizar para su beneficio


Evaluar para elegir, elegir para decidir


Debido a la relevancia de la Regla de los cinco, hemos desarrollado un pequeño programa que permite evaluar cada factor establecido por el Dr. Lipinski. Está desarrollado en lenguaje Python, por lo que puede utilizarse fácilmente.


Calculadora de Factores Lipinski

Esta calculadora, pretende facilitar la evaluación del potencial de un compuesto para llegar a ser un fármaco exitoso, de acuerdo a las cualidades que el Dr. Lipinski ha identificado como indispensables para que tenga los efectos esprados en el cuerpo humano.

#Variable que guarda la regla de donadores de enlaces de hidrógenos
dH = input('Número de donadores de enlaces de hidrógenos: ')
dH = int(dH)
if dH <= 5:
  print('Cumple con las reglas')
else:
  print('No cumple con las reglas')

#Variable que guarda la regla de aceptores de enlaces de hidrógenos
aH = input('Número de aceptores de enlaces de hidrógenos: ')
aH = int(aH)
if aH <= 10:
  print('Cumple con las reglas')
else:
  print('No cumple con las reglas')

#Variable que guarda la regla del peso molecular
pM = input('Peso molecular en Da: ')
pM = int(pM)
if pM <= 500:
  print('Cumple con las reglas')
else:
  print('No cumple con las reglas')

#Variable que guarda el coeficiente de reparto octanol-agua
logP = input('Coeficiente de partición logP: ')
logP = int(logP)
if logP <= 5:
  print('Cumple con las reglas')
else:
   print('No cumple con las reglas')

