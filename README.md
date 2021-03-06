# Reto 1 java Misión tic
## Estudio De Prevención De Mortalidad

En Colombia se desea iniciar una investigación relacionada con las causas de mortalidad en la población.

En estudios previos se ha detectado que las siguientes enfermedades causan gran parte de la mortalidad en los pacientes: cáncer, cardiovasculares, respiratorias, cerebrovasculares, hipertensión y diabetes.

El objetivo de la investigación es realizar un estudio estadístico de las enfermedades anteriormente mencionadas con el fin de mitigar la mortalidad en la población y tomar decisiones en cuanto a los recursos disponibles para atacar cada una de ellas.

Para lo anterior, se tienen los siguientes datos de un conjunto de pacientes:

- Nombre completo
- Número de cédula
- Edad
- Ciudad
- EPS
- Enfermedad diagnosticada

Conforme a lo mencionado, se le ha contratado a usted para apoyar el proceso de investigación desarrollando un programa que implemente los siguientes requerimientos:

- Leer la cantidad de pacientes del estudio.
- Leer y almacenar el nombre, número de cédula, edad, ciudad, EPS, y enfermedad diagnosticada de cada uno de los pacientes.
 
Una vez leidos los datos.

- ¿Cuál es la ciudad en la cual se encuentra el mayor número de pacientes?

**Ejemplo:**
Se tienen los datos de los siguientes pacientes:

|Julian Andrade|723456   |45|Barranquilla|Sura   |cardiovasculares|
|--------------|---------|--|------------|-------|----------------|
|Andres Utria  |734673   |76|Barranquilla|Sanitas|Cáncer          |
|Eva Molina    |104312456|32|Bogotá      |Sura   |Cáncer          |

Ciudad con mayor número de pacientes: **Barranquilla**

Las entradas y salidas del programa deben corresponder con lo expresado en la siguiente tabla. Para la entrada, indicar en una primera línea el número de pacientes, luego indicar los datos del paciente separados por guión medio (cada paciente en una línea diferente), y por último las ciudades separadas por guión medio.

**Entrada Esperada**

<pre><code>3
Julian Andrade-723456-45-Barranquilla-Sura-cardiovasculares
Andres Utria-734673-76-Barranquilla-Sanitas-cancer
Eva Molina-104312456-32-Bogota-Sura-cáncer
Barranquilla-Bogota
</code></pre>

**Salida Esperada**
<pre><code>Barranquilla</code></pre>

