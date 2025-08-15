# Lectura de Cadena RNA
Una lectura de la cadena de la RNA
Caso clínico: Lectura de cadena RNA (Valor 2.0) a. Contexto:
En genética clínica, la detección de mutaciones puntuales en cadenas de RNA permite diagnosticar enfermedades hereditarias como la anemia falciforme. En este caso, un transmisor biomédico envía secuencias de mRNA codificadas con el prefijo /data:. Cada secuencia corresponde a un paciente o a una medición. La mutación clásica de anemia falciforme implica el cambio del codón GAG (ácido glutámico) a GUG (valina) en el gen HBB.
Se recibe una única cadena que contiene varias secuencias separadas por /data: El programa debe:
• Extraer todas las secuencias posteriores a /data:.
• Tomar la primera secuencia como referencia.
• Comparar todas las demás con la de referencia para identificar diferencias.
• Imprimir el número total de secuencias, la secuencia de referencia, las
secuencias diferentes y un diagnóstico:
o Si existe al menos una secuencia diferente → Imprimir “Probable
enfermedad hereditaria”.
o Si todas son iguales → Imprimir “Sin indicios de variación
hereditaria”.
