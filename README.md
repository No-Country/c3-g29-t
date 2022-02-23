# C3-G29-T: Forecasting "Demanda de Energía"
## Introducción
<i>
  Proyecto a lograr como objetivo durante el curso de aceleración a la inserción laboral de No Country.<br>
  Se usarán dos modelos de pronóstico para un mismo set de datos de energía activa [kW], para luego comparar la eficiencia de los mismos.
</i>

--Estado del Projecto: En curso...<br>

## Motivaciones y definición de problemas
Consideramos la función de pronosticar sucesos/eventos/valores como una de las áreas de investigación con mayor impacto en profesiones como marketing, financieras, energías renovables y electrónica (entre otras).
 
El pronóstico de la demanda de energía es muy relevante para una red eléctrica eficiente. La previsión mejorada es beneficiosa para el despliegue de energía renovable, la planificación de días de carga alta/baja y la reducción del desperdicio de contaminantes.

#### Objetivos del proyecto
<ol>
  <li>Proveer al clientes datos de uso útil respecto al comportamiento de los usuarios en la red eléctrica.</li>
  <li>Aviso sobre la capacidad de entrega del transformador que alimenta la/s manzana/s donde se tienen medidores.</li>
</ol>

#### Descripción del problema
Los datos se obtienen desde Galvez, Sta Fe. Los mismos están compuestos por 5 años de recolección de la demanda de energía activa (el resto de energía no caben en el modelo dado que apriorí no tienen un uso provechoso). <br>
Se posee solo del último año con datos del clima, sumado a los días de feriados en Argentina.<br>
El intervalo de toma de datos es igual a 15 minutos.<br>
El consumo de energía esperado se pronostica en base al periodo brindado.

### Métodos usados
<ul>
  <li>Holt-Winters</li>
  <li>Prophet</li>  
</ul>

### Tecnologías
<ul>
  <li>Python</li>
  <li>Pandas, Numpy, Jupyter Lab</li>
  <li>Statsmodels, Scikit-Learn</li>
  <li>Prophet</li>
</ul>

## Bibliografía
<ul>
  <li> Docs Oficiales (muy utiles): __[PROPHET_DOCS](https://facebook.github.io/prophet/docs/quick_start.html)__ </li>
  <li>Teoría: __[Forecasting at Scale(pdf)](https://www.kaggle.com/robinteuwens/forecasting-energy-demand/notebook)__</li>
  <li>Practica: __[Forecasting con Prophet](https://nextjournal.com/eric-brown/forecasting-with-prophet)__</li>
  <li>Teoría: __[Suavización exponencial](https://economipedia.com/definiciones/suavizacion-exponencial.html)__</li>
  <li>Teoría: __[Holt Winter](http://cienciauanl.uanl.mx/?p=7948#:~:text=El%20m%C3%A9todo%20Holt%2DWinters%20es,de%20pron%C3%B3sticos%20a%20corto%20plazo.)__</li>  
</ul> 
