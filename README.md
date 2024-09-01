ntroducción al Control Digital
1. Señales digitales vs analógicas

Definición:

Señal analógica: Continua, puede tomar cualquier valor en el dominio del tiempo.
Señal digital: Tiene solo dos posibles valores o estados, su forma de onda es cuadrada.



2. ¿Por qué control digital?

Definición: Ventajas del control digital sobre el analógico.

Exactitud
Errores de implementación
Flexibilidad
Velocidad
Costos



3. Estructura del controlador


Subsección: Controlador analógico

Definición: Estructura básica de un controlador analógico.
Ejemplo:

Diagrama: Controlador -> Planta





Subsección: Controlador digital

Definición: Estructura básica de un controlador digital.
Ejemplo:

Diagrama: A/D -> Computadora Digital -> D/A -> Planta





4. Conversión Análoga a Digital

Subsección: Procedimiento de conversión

Definición: Proceso de convertir una señal analógica a digital.
Pasos:

Muestreo: Medir valores de voltaje cada cierto tiempo.
Cuantización: Convertir la señal análoga en una serie de valores discretos.
Codificación: Asignar valores binarios a los valores cuantizados.





5. Ejemplo de conversión

Ejemplo:

Señal analógica: [0, 3] V
Bits de representación: 2 bits
Rango analógico: 3V
Representación: 0.75V por símbolo



6. Conversión Digital a Análoga

Definición: Proceso de convertir una señal digital a analógica.
Ecuación:

Resolución: Depende de los bits de representación.
Ejemplo: Para FS=15V, con 4 bits, la resolución es 1V.



7. Métodos de conversión


Subsección: Resistores ponderados

Definición: Método de conversión digital a analógica.
Ejemplo:

Diagrama: Circuito con resistores ponderados.





Subsección: Red en escalera R-2R

Definición: Método más exacto de conversión digital a analógica.
Ejemplo:

Diagrama: Circuito con red en escalera R-2R.





8. Modelo Matemático

Definición: Modelos matemáticos para conversores A/D y D/A.
Ecuación:

Zero-Order Hold (ZOH):


GZOH​(s)=(s1−e^sT)/s​
