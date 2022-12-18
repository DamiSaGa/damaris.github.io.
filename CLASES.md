> December, 2022

# Clase 6 - User centric y Facct

Los sistemas basados en Inteligencia Artificial y que son alimentados por grandes volúmenes de datos, tienen una serie de implicaciones en variadas industrias, que inciden directamente en la vida humana. Estos sistemas filtran, clasifican, califican, recomiendan, personalizan y dan forma a la experiencia humana, tomando decisiones con alto impacto en la cotidianeidad. Así como esto conlleva a múltiples beneficios, también se ve enfrentado a riesgos, entre ellos el sesgo. Es por esto, que es indispensable estudiar estos sistemas y evaluarlos bajo diversas perspectivas, lo cual da origen a Facct (justicia, explicabilidad y transparencia).

El sesgo se puede presentar de diferentes formas, tales como: sesgo de género, racial, demogáfico, económico, entre otros, desfavoreciendo a las minorías o bien a aquellos grupos que no se encuentran bien representados en los datos utilizados para entrenar modelos. Un ejemplo de esto, en 2018, se descubrió que Amazon utilizaba una herramienta de inteligencia artificial para reclutamiento, la cual asignaba puntaje de 1 a 5 estrellas a los currículums, sin embargo, se percataron (un año después de usarla) que no calificaba a los candidatos para puestos técnicos o de desarrollador de manera neutral en cuanto al género, es decir, que mostraba prejuicios contra las mujeres. Esto debido a que los modelos fueron entrenados para examinar a los solicitantes mediante la observación de patrones en los currículums enviados a la empresa durante un período de 10 años, donde la mayoría provino de hombres, lo cual es un reflejo del dominio masculino en la industria tecnológica.

Entonces, ¿es posible que los sistemas puedan ser afectados?, totalmente. Los sistemas recomendadores ayudan a filtrar el ruido e identificar ítems relevantes desde grandes espacios de información. Usualmente son optimizados en base a métricas, tal como Amazon editó los programas para hacerlos neutrales a estos términos particulares, más no, en justicia. Por lo que aun no existe un modo de garantizar en su totalidad que el algoritmo sea justo, realmente interpretable y explicable.

Entonces, ¿cómo se puede regular esto en la práctica? Existe una regulación desde 2018, llamada General Data Protection Regulation (GDPR) la cual no solo aplica a organizaciones ubicadas dentro de la Unión Europea, sino también a organizaciones fuera de ella que ofrezcan servicios a sujetos que sean parte de ella y en esta regulación existen algunos artículos tales como: Art.15: El derecho a acceso por parte del sujeto, Art.22: la relación que tiene el individuo con el sistema de la toma de decisiones, incluyendo a aquellos que los perfilan. Además, se han creado varias iniciativas para estudiar el uso de algoritmos para tomar decisiones y los efectos que pueden tener de daño individual o daño colectivo.

Algunas definiciones que se deben tener en cuenta son: Fairness, que es la propiedad de ser justos o equitativos, lo cual está en contra de invalidad o estar a favor de un grupo por sobre el otro; Accountable, que se define como la responsabilidad del sujeto de reportar, explicar o justificar algo; y Transparencia, el cual, es el principio de que los factores que influyen en las decisiones tomadas por los algoritmos sean visibles o transparentes. Se puede dar el hecho de que algo sea explicativo, pero no así transparente. Otro término relevante es la Interpretabilidad, donde si un humano tiene la percepción de predecir lo que hará el sistema después, entonces es interpretable.

Bajo la necesidad de la explicabilidad para recomendadores, en 2017, se crea el término Explainable Artificial Intelligence (XAI), cuyo objetivo es para la aplicación en dominios críticos, tales como Transporte, Seguridad, Medicina, Finzas, Legales y Militares donde el usuario pueda responder preguntas tales como: ¿por qué hizo eso?, ¿por qué no hizo otra cosa?, ¿cuándo le va bien?, ¿cuándo falla?, ¿cuándo se puede confiar en el sistema? Y ¿cuándo se puede corregir un potencial error? 

Es fundamental poder explicar por qué un algoritmo de inteligencia artificial hizo una predicción para ayudar a las personas a entenderla y para esto, los campos de visualización de información e interacción humano-computadora, tienen mucho que ofrecer. De modo que se usa la visualización como un componente interactivo para explicabilidad y control de los usuarios en los sistemas de recomendación. Por ejemplo, en uso de listas ordenadas en recomendadores de música y películas, al usuario se le presenta un conjunto de mosaicos que sugieren múltiples salidas del recomendador que pueden ser relevantes y se le permite elegir fácilmente entre ellas; en el comercio electrónico también explican el contexto social que alimentó las recomendaciones “otros que compraron este artículo también llevaron…”. Aplicándolo en el área de salud, es muy útil por ejemplo para un médico, ya que tiene mucho más valor un modelo de IA que explica por qué se tomo la decisión, cuándo y cómo podría fallar y el nivel de incertidumbre de su predicción, en comparación con la tecnología de que solo entrega el resultado.

Retomando el concepto inicial, ¿de dónde proviene las fuentes de inequidad y discriminación cuando se hace modelo de inteligencia artificial propio de machine learning? Se asume que viene sesgado desde los datos, pero en el tutorial Sigir (2019) se identifica que la discriminación del sesgo puede venir de cualquiera de las etapas: 
####	De los datos del mundo:
  -	Diferentes tamaños de grupos (el modelo aprende predicciones más precisas para el grupo mayoritario)
  - Discriminación histórica y actual (Produce distribuciones antinaturales, posición social, estatus socioeconómico, educación, etc)
  
####	De las fuentes de información:
  - Estrategia de muestreo (¿quién está incluido en los datos?)
  - Sesgo de respuesta
  - Selección de proxy
  - Varianza del instrumento de medición (si es o no consistente en todas las subpoblaciones)
  - Definiciones de métricas
  
#### Del modelo y su entrenamiento:
  -	Uso de información confidencial de forma directa y negativa
  - Optimización del algoritmo (eliminación de “ruido” que podría perjudicar a algunos grupos de usuarios)
  
#### De la evaluación del modelo:
  - Definición de éxito (¿Para quién es beneficioso y cómo se mide? ¿Quién lo decidió?)
  - ¿Cómo se miden y agregan los subgrupos relevantes en la evaluación?

#### De cómo se interpretan los resultados
  - ¿La salida del modelo sesga la respuesta humana de manera diferente?
  - Los factores sociales pueden sesgar la respuesta
  - La respuesta “alimenta” el siguiente entrenamiento 
  - La respuesta afecta al mundo


Es posible revertir, en cierta forma, esta situación, de modo que existen artículos con mecanismos para “des-sesgar” en sistemas recomendadores. Sin embargo, aun quedan desafíos abiertos en esta línea, por ejemplo, siempre hay información de usuario e ítem rating desconociendo el género del usuario o si pertenece o no a grupos discriminados, por lo que se ignora si el sistema se encuentra o no sesgado y por otro lado, como sociedad aun no hemos llegado a un consenso de qué es lo que sería una sociedad no discriminada o sin sesgo.



# Clase 8 - Interactive and Conversational Recommender Systems




