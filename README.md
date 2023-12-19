# DataAnalytics
En este portafolio puedes encontrar algunos de los proyectos que he realizado para el área de data analytics.
Con el tiempo estaré actualizando este portafolio, y a su vez, agregando más proyectos.

Este repositorio está realizado en el lenguaje de programación de **Python** y es una vista hacia el potencial y las capacidades que poseo para realizar proyectos importantes en el área de la analítica de datos. El orden del portafolio es inverso, esto quiere decir que podrás ver los proyectos más recientes primero y los proyectos más antiguos al final de la hoja.

---
---

## Proyecto 5: Ice Gamestore

Trabajamos para la tienda online **Ice** que vende videojuegos por todo el mundo. Las reseñas de usuarios y expertos, los géneros, las plataformas (por ejemplo, Xbox o PlayStation) y los datos históricos sobre las ventas de juegos están disponibles en fuentes abiertas. Tenemos que identificar patrones que determinen si un juego tiene éxito o no. Esto nos permitirá detectar proyectos prometedores y planificar campañas publicitarias.

Tenemos datos que se remontan a 2016. Imaginemos que es diciembre de 2016 y estamos planeando una campaña para 2017.
(Lo importante es adquirir experiencia de trabajo con datos. Realmente no importa si estamos pronosticando las ventas de 2017 en función de los datos de 2016 o las ventas de 2027 en función de los datos de 2026.)

El dataset contiene la abreviatura ESRB. The Entertainment Software Rating Board (la Junta de clasificación de software de entretenimiento) evalúa el contenido de un juego y asigna una clasificación de edad como Adolescente o Adulto.

**HIPÓTESIS**

- Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.
- Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.

Explica:

- Cómo formulaste las hipótesis nula y alternativa.
- Qué criterio utilizaste para probar las hipótesis y por qué

[Ver Proyecto](https://github.com/juliocmi/DataAnalytics/blob/main/Projects_DA/ICE_Gamestore_Project_ESP.ipynb)

---
---

## Proyecto 4: Megaline Telecom

Trabajamos como analista para el operador de telecomunicaciones Megaline. La empresa ofrece a sus clientes dos tarifas de prepago, Surf y Ultimate. El departamento comercial quiere saber cuál de los planes genera más ingresos para ajustar el presupuesto de publicidad.

Vamos a realizar un análisis preliminar de las tarifas basado en una selección de clientes relativamente pequeña. Tendrás los datos de 500 clientes de Megaline: quiénes son los clientes, de dónde son, qué tarifa usan y la cantidad de llamadas que hicieron y los mensajes de texto que enviaron en 2018. Tu trabajo es analizar el comportamiento de los clientes y determinar qué tarifa de prepago genera más ingresos.

**HIPÓTESIS**

- El ingreso promedio de los usuarios de las tarifas Ultimate y Surf difiere.
- El ingreso promedio de los usuarios en el área de estados Nueva York-Nueva Jersey es diferente al de los usuarios de otras regiones. Decidiremos qué valor alfa usar.

Explicaremos:

- Cómo formulamos las hipótesis nula y alternativa.
- Qué criterio utilizamos para probar las hipótesis y por qué.

[Ver Proyecto](https://github.com/juliocmi/DataAnalytics/blob/main/Projects_DA/Megaline_Data_Analyst.ipynb)

---
---

## Proyecto 3: Crankshaft List

En este proyecto seremos analistas en **Crankshaft List**. Cientos de anuncios gratuitos de vehículos se publican en el sitio web cada día. Necesitamos estudiar los datos recopilados durante los últimos años y determinar qué factores influyen en el precio de un vehículo.

**INSTRUCCIONES**

- Estudiar los siguientes parámetros: precio, años del vehículo cuando se colocó el anuncio, millaje, número de cilindrada y condición.
- Trazar histogramas para cada uno de los parámetros.
- Estudiar cómo los valores atípicos afectan a la forma y legitimidad de los histogramas.
- Estudiar cuántos días los anuncios fueron mostrados `(days_listed)`. Trazaremos un histograma. Calcularemos la media y la mediana. Describiremos la vida útil habitual de un anuncio. Determinaremos cuándo se eliminan rápidamente los anuncios y cuándo son publicados por un tiempo anormalmente largo.
- Analizaremos el número de anuncios y el precio medio para cada tipo de vehículo. Trazaremos un gráfico mostrando la dependencia de los números de anuncios en cada tipo de vehículo. Seleccionaremos los dos tipos con un mayor número de anuncios.
- ¿Qué factores impactan más sobre el precio? Tomaremos cada uno de los tipos más populares que has detectado en la fase anterior y estudiaremos si el precio depende de la edad, millaje, condición, tipo de transmisión y color. Para las variables categóricas (tipo de transmisión y color), trazaremos gráficos de caja y bigotes, y crearemos gráficos de dispersión para el resto.

[Ver Proyecto](https://github.com/juliocmi/DataAnalytics/blob/main/Projects_DA/Crankshaft_Project_ES.ipynb)

---
---

## Proyecto 2: Puntuación de Crédito Bancario

Este proyecto consiste en preparar un informe para la división de préstamos de un banco. Deberemos averiguar si el estado civil y el número de hijos de un cliente tienen un impacto en el incumplimiento de pago de un préstamo. El banco ya tiene algunos datos sobre la solvencia crediticia de los clientes.

El informe se tendrá en cuenta al crear una puntuación de crédito para un cliente potencial. Se utiliza una puntuación de crédito para evaluar la capacidad de un prestatario potencial para pagar su préstamo.

**HIPÓTESIS**
1. ¿Hay alguna conexión entre tener hijos y pagar un préstamo a tiempo?
2. ¿Existe una conexión entre el estado civil y el pago a tiempo de un préstamo?
3. ¿Existe una conexión entre el nivel de ingresos y el pago a tiempo de un préstamo?
4. ¿Cómo afectan los diferentes propósitos del préstamo al reembolso a tiempo del préstamo?

[Ver Proyecto](https://github.com/juliocmi/DataAnalytics/blob/main/Projects_DA/Ana%CC%81lisis_de_Riesgo_Bancario_ESP.ipynb)

---
---

## Proyecto 1: Música de la Gran Ciudad
Siempre que realizamos un análisis tenemos que formular hipótesis que luego podamos poner a prueba. A veces aceptamos estas hipótesis; otras, las rechazamos. Para tomar las decisiones correctas, una empresa debe ser capaz de entender si está haciendo las suposiciones correctas.

En este proyecto, compararemos las preferencias musicales de las ciudades de **Springfield** y **Shelbyville**. Se examinarán datos reales de **Y.Music** para comprobar las hipótesis que se exponen a continuación y comparar el uso de los usuarios de estas dos ciudades.

**HIPÓTESIS**
1. La actividad de los usuarios difiere según el día de la semana y dependiendo de la ciudad.
2. Los lunes por la mañana, los habitantes de Springfield y Shelbyville escuchan diferentes géneros. Lo mismo ocurre con los viernes por la noche.
3. Los oyentes de Springfield y Shelbyville tienen preferencias distintas. En Springfield prefieren el pop mientras que en Shelbyville hay más aficionados al rap.

[Ver Proyecto](https://github.com/juliocmi/DataAnalytics/blob/main/Projects_DA/Y_Music_Project.ipynb)
