# Me-We-It: El Protocolo Abierto para una IA responsable

Esta es una Sugerencia Abierta diseñada para clarificar el proceso de construcción 
de la IA exponiendo los pasos que conlleva crearla de forma responsable. Es una 
Sugerencia Abierta propuesta por personas que han visto el valor que la IA puede 
generar y el daño que puede causar. Entre estas personas se encuentran:

* especialistas experimentados en tecnología, ciencia de datos o investigación;
* interlocutores principales, incluidos los desarrolladores;
* usuarios preocupados por el impacto de la IA.

## ¿Cuál es el objetivo de esta norma abierta?

Tiene tres objetivos:

1. dar algunos consejos para construir una IA más ética para ayudar a la industria
   a empezar de nuevo sobre bases saludables,
2. ayudar al público a entender el proceso de construcción de una IA, y
3. crear un espacio en el que el público pueda plantear libremente cualquier pregunta
   a la comunidad de la IA y la ciencia de datos.

Esta Sugerencia Abierta vivirá como un foro en línea gratuito, e invitamos a nuevas 
sugerencias y enfoques bajo el importante lema de registrar la intención.

Necesitamos una comunicación clara y responsable para entablar un debate honesto y 
tomar las decisiones correctas. La creación de una IA implica un trabajo técnico 
significativo, pero este estándar abierto permite que cualquier persona interesada 
participe en las discusiones, independientemente de su nivel de conocimiento en 
ciencia de datos. Para ello, ofrece un marco sencillo para supervisar y validar 
los enfoques estándar para el entrenamiento de las máquinas y los resultados 
que producen.

Ahora más que nunca, es necesario compartir cómo aprende la IA para que podamos
responsabilizarnos unos a otros sin restringir gravemente la innovación. El 
desarrollo de la IA tiene el potencial de aportar importantes beneficios, como 
una mayor eficiencia, una mejor toma de decisiones, descubrimientos en materia de 
salud y la capacidad de abordar problemas que antes eran imposibles de resolver. 
Sin embargo, la IA también puede obligar a los moderadores humanos a presenciar 
contenidos horribles, perjudicar a los desfavorecidos, agravar los problemas de 
privacidad y seguridad de los datos, vulnerar derechos de propiedad intelectual 
no creada para el proceso y perpetuar sesgos nocivos. Sin una consideración y 
planificación cuidadosas, corremos el riesgo de crear sistemas de IA que empeoren 
los mismos problemas que pretendemos resolver.

## Primera versión de la norma abierta

Estas son las primeras preguntas y consideraciones que creemos que todo equipo de 
IA y todo constructor individual deberían plantearse cada día para garantizar que 
estamos lanzando modelos de IA más éticos. Están pensadas para ser comunicadas en un 
lenguaje sencillo, sin jerga técnica, para garantizar que el proceso pueda ser 
entendido por todos los públicos. Con el tiempo, se traducirá a todos los idiomas 
en los que podamos encontrar voluntarios. Sabemos que es poco probable que lo hagamos 
del todo bien, sobre todo cuando se trata de una tecnología que requiere un seguimiento 
continuo, pero con su ayuda cada iteración aportará mejoras significativas. Esta es 
la versión 1 de muchas versiones futuras que los desarrolladores pueden utilizar al 
evaluar nuestro trabajo. Podemos perfeccionar esta lista con su ayuda, gracias a las 
preguntas del público y las sugerencias de la comunidad científica de datos. Estas 
contribuciones nos ayudarán a dar cuenta de los pasos que hay que dar para aclarar 
y validar nuestras intenciones.

Los responsables políticos se afanan por recuperar el tiempo perdido en materia de 
regulación, y la legislación de la UE sobre inteligencia artificial podría añadir la 
IA de propósito general a la categoría de sistemas de IA de alto riesgo. Mientras 
tanto, le ofrecemos una solución para reducir los compartimentos estancos  y entablar 
un debate en grupo: una norma práctica, que cualquier equipo puede utilizar 
inmediatamente, y que aclara cómo se construye la IA. En lugar de una Carta Abierta,
esta es una Sugerencia Abierta de un grupo de tecnólogos experimentados, científicos
de datos, investigadores y personas preocupadas por el impacto de la IA.

Esta Sugerencia Abierta vivirá como un foro en línea gratuito, e invitamos a nuevas 
sugerencias y enfoques bajo la importante bandera de registrar la intención. Los 
pasos están aislados en función de los elementos centrales de la construcción de la 
IA (Formación, Construcción, Pruebas) y los actores que participan en el proceso para 
ayudar a aclarar la importancia de la reducción de compartimentos estancos: Me, We, It.

**Me** - Las preguntas que cada persona que trabaja en la IA debe hacerse antes de empezar 
y a medida que avanza en el proceso.

**We** - Las preguntas que debe plantearse el grupo, en particular para definir la diversidad 
necesaria para reducir al máximo los prejuicios humanos.

**It** - Las preguntas que debemos hacer a los individuos y al grupo en relación con el 
modelo que se está creando y el impacto que puede tener en nuestro mundo.

### Paso 1. Formación - Selección e introducción de datos

**Me** - Las preguntas necesarias que debo hacerme antes de iniciar esta parte del 
proceso. Las respuestas deben guardarse para volver la vista atrás y ver cómo 
evoluciona mi proceso de pensamiento.

* ¿Cuáles son las razones por las que he seleccionado estos datos de formación?
  ¿Cómo se ajusta esa selección a mi intención para este modelo?
* ¿Cómo se obtuvieron estos datos de formación?
* ¿Hay algún material protegido o con derechos de autor en los datos de formación,
  como información de identificación personal (PII), datos de la industria de tarjetas
  de pago (PCI) e información sanitaria protegida (PHI)?
* ¿He tenido en cuenta la legislación sobre protección de datos o privacidad (como
  GDPR y CPRA)?
* ¿He considerado otros sistemas de gestión de fuentes de datos?
* ¿Tengo experiencia en el uso de datos similares para modelos de IA o aprendizaje
  automático en el pasado o es la primera vez que utilizo esta fuente de datos?
* Si he utilizado estos datos anteriormente, ¿hubo algún problema derivado de los
  modelos que se ensayaron con estos datos históricamente?
* Si es la primera vez que utilizo estos datos, ¿cuáles son mis expectativas sobre
  el impacto que tendrán en los resultados de los modelos?
* ¿He utilizado una Ficha de Modelo para comunicar los riesgos? ¿Cómo se actualizará
  este documento con el equipo de colaboración?
* ¿Qué espero que aporten los datos a este modelo? ¿Cuál es mi intención respecto
  al resultado? ¿Cómo espero que los datos de formación influyan en ese resultado?
* ¿Existen características que puedan actuar como variables instrumentales (por ejemplo,
  datos granulares a nivel de barrio) para las poblaciones desfavorecidas? Si es así,
  ¿tengo suficientes controles para asegurarme de que no estoy perpetuando sesgos que
  puedan aprenderse de los datos de formación?
* ¿Puedo resumir lo que contienen estos datos de formación para captar su esencia de
   una manera que pueda entender un científico que no sea experto en datos?
* ¿Me siento apurado o presionado para introducir datos de fuentes dudosas?
* ¿Puedo citar la fuente de los datos de formación?
* ¿Qué sesgos pueden estar actuando en mi selección de estos datos?
* ¿Tengo en cuenta sesgos que no comprendo? ¿Comparto mi lógica con un grupo más amplio
  que pueda ayudarme a identificar mis sesgos al seleccionar los datos?
* ¿Cómo creo que estos datos de formación beneficiarán a este modelo?

**We** - Las preguntas que deberíamos hacernos como grupo de trabajo antes de iniciar 
esta parte del proceso. Las respuestas deben guardarse para que podamos volver la 
vista atrás y ver cómo evoluciona nuestro proceso de reflexión.

* ¿Cuál es la intención del grupo para adiestrar este modelo?
* ¿Quién ha colaborado en el proceso de elaboración de la estrategia y selección de los
  datos de formación?
* ¿Pertenece el equipo de personas que trabaja en la selección de los datos de formación
   a un conjunto diverso de antecedentes y experiencias para ayudar a reducir el sesgo
   en la selección de datos?
* ¿Cuáles son los posibles sesgos inherentes a este equipo que ha seleccionado los datos
   de formación?
* ¿Comprende todo el equipo de dónde proceden los datos de formación? ¿Pueden explicarlo
   con sus propias palabras?
* ¿Se emplea una Tarjeta Modelo para comunicar los riesgos? ¿Creó cada colaborador su
  propio documento que pueda compartirse con el resto del equipo?
* ¿Hemos tenido en cuenta la Ley de IA de la UE o cualquier otra normativa que se
  proponga o que ya esté en vigor?
* ¿Hay algún material protegido o con derechos de autor en los datos de formación,
  como información de identificación personal (PII), datos de la industria de tarjetas
  de pago (PCI) e información sanitaria protegida (PHI)?
* ¿Hemos tenido en cuenta la legislación sobre protección de datos o privacidad
  (como GDPR y CPRA)?
* ¿Hemos considerado otros sistemas de gestión de fuentes de datos?
* ¿Qué porcentaje de los datos de formación guardamos para las pruebas? ¿Cómo los estamos
  seleccionando?
  
**It** - Las preguntas que debemos hacernos sobre los algoritmos o modelos antes de 
empezar esta parte del proceso. Las respuestas deben guardarse para que podamos volver 
la vista atrás y ver cómo evoluciona nuestro proceso de pensamiento.

* ¿Tenemos medios para subsanar si en algún momento se descubre que parte de este
  conjunto de datos es ilegal, poco fiable o inaceptable?
* ¿Qué datos se necesitan para entrenar de forma reflexiva y consciente?
* ¿Es el conjunto completo de datos de origen conocido, explicable y beneficioso
  para el modelo?
* ¿Cuáles son los posibles sesgos inherentes a los datos?
* ¿Hay información personal identificable, datos protegidos o material protegido por
  derechos de autor?
* ¿Estoy preparado para asumir la responsabilidad del modelo si parte del conjunto de
  datos causa algún problema legal en el futuro?
* ¿Cuáles son los posibles usos o consecuencias no deseados, incluidos los resultados
  de nivel posterior que los datos de formación podrían enseñar al modelo?
* ¿Cuáles son los posibles sesgos que podrían amplificarse al añadir los datos de
  formación al modelo?

### Paso 2. Construcción - Creación o selección de algoritmos y modelos

**Me** - Las preguntas que debo hacerme antes de empezar esta parte del proceso. Las 
respuestas deben guardarse para que pueda volver la vista atrás y ver cómo evoluciona 
mi proceso de pensamiento.

* ¿Qué pretendo que haga este modelo? ¿Por qué lo estoy probando?
* Si estoy aplicando el aprendizaje por refuerzo, ¿cómo optimizará este modelo en el
  entorno real? ¿Es posible que mi selección de resultados a probar esté sesgada?
* Si estoy aplicando el aprendizaje por transferencia, ¿cuáles son los posibles sesgos
  que descubrirá el proceso de transferencia?
* Si estoy aplicando modelos de conjunto o sistemas que se enseñan entre sí, ¿existe
  la posibilidad de que se introduzcan en el sistema nuevos sesgos o malas prácticas
  de recopilación de datos?
* ¿Cuál creo que será el rendimiento de este modelo? ¿Cuáles son algunos ejemplos de
  los resultados que espero obtener?
* ¿Cuáles son los prejuicios humanos que han influido en mis objetivos y mi
  razonamiento?
* Si no he escrito el modelo desde cero, ¿de dónde procede? ¿Cómo se adiestró
  inicialmente?

**We** - Las preguntas que deberíamos hacernos como grupo de trabajo antes de iniciar
esta parte del proceso. Las respuestas deben guardarse para que podamos volver la 
vista atrás y ver cómo evoluciona nuestro proceso de reflexión.

* ¿Con quién colaboré en el proceso de formación de este modelo y de diseño de la
  estrategia?
* ¿Qué sesgos humanos hay en este grupo? ¿Hemos considerado si el grupo de trabajo
  es lo suficientemente diverso como para captar distintos puntos de vista?
* ¿Quiénes fueron los colaboradores que diseñaron el modelo y la estrategia?
* ¿Quiénes son las partes interesadas? ¿Participan todas las partes interesadas en
  esta fase del proceso?
* ¿Hemos tenido en cuenta la Ley de IA de la UE o cualquier otra normativa que se
  esté proponiendo o que ya esté en vigor?
* ¿Se han ensayado estos modelos en algún material protegido o con derechos de autor,
  como la información de identificación personal (PII), los datos de la industria de
  tarjetas de pago (PCI) y la información sanitaria protegida (PHI)?
* ¿Hemos tenido en cuenta la legislación sobre protección de datos o privacidad
  (como GDPR y CPRA)?
* ¿Hemos considerado otros sistemas de gestión de fuentes de datos?

**It** - Las preguntas que debemos hacernos sobre los algoritmos o modelos antes de empezar
esta parte del proceso. Las respuestas deben guardarse para que podamos volver la vista 
atrás y ver cómo evoluciona nuestro proceso de pensamiento.

* ¿De dónde procede el modelo o se ha desarrollado desde cero?
* ¿Cuál es el uso previsto del modelo una vez formado?
* Si no hemos creado el modelo nosotros mismos, ¿comprendemos la intención del creador
  original del modelo?
* ¿Cuáles son los posibles usos o consecuencias no deseados, incluidos los resultados
  de nivel posterior?
* ¿Cuáles son los posibles sesgos que podrían amplificarse a través del modelo?
* ¿Tenemos ejemplos de modelos con datos similares que se hayan utilizado anteriormente?
  ¿Cuáles fueron los resultados previstos y no previstos?
* ¿Cuáles son los posibles peligros del modelo? ¿Tenemos un plan para los peores
  escenarios?
* ¿Qué tipo de medidas de precaución hemos puesto en marcha?
* ¿Quién controla el modelo?
* ¿Cómo se controlará y aplicará el cumplimiento continuado de las leyes y normativas?
* ¿Cómo se descubrirán y resolverán los sesgos?
* ¿Cómo puede cerrarse el modelo? ¿En qué circunstancias?
* ¿Existen partes interesadas o circunstancias de financiación que puedan impedirlo?
* ¿Cuáles son los requisitos contractuales que dictarán la gestión y el uso de este modelo?

### Paso 3. Pruebas: gestión de los datos de prueba y etiquetado

**Me** - Las preguntas que debo hacerme antes de empezar esta parte del proceso. Las 
respuestas deben guardarse para que pueda volver la vista atrás y ver cómo evoluciona 
mi proceso de pensamiento.

* ¿Los datos que utilizo para las pruebas son suficientes para analizar el rendimiento
  del modelo?
* ¿Se está considerando la posibilidad de realizar pruebas con usuarios en un entorno
  real? ¿Cómo se adaptará el modelo si sucede que el resultado del comportamiento
  del usuario no es el deseado?
* ¿Cuál creo que es el mejor enfoque para evaluar el resultado de este modelo antes de
  hablar con un grupo más amplio sobre nuestro punto de vista?
* ¿Estoy seguro de que el equipo y yo somos conscientes del impacto que puede tener
  nuestro trabajo? ¿Hemos pensado en todos los resultados potencialmente negativos que
  podrían derivarse de nuestro trabajo y que deberíamos comprobar antes de ponerlo en
  marcha?
* ¿Creo que hemos sido minuciosos en nuestra estrategia de pruebas y despliegue para
  asegurarnos de que hemos anticipado cualquier problema que pudiera surgir de los
  resultados del modelo?
* ¿Los resultados de los datos de formación y los comentarios de los etiquetadores
  coinciden con la intención original que tuve al crear el modelo? Si no es así,
  ¿qué ha cambiado y cómo sé que ha cambiado?

**We** - Las preguntas que deberíamos hacernos como grupo de trabajo antes de iniciar 
esta parte del proceso. Las respuestas deben guardarse para que podamos volver la 
vista atrás y ver cómo evoluciona nuestro proceso de reflexión.

* ¿Cómo evaluamos el rendimiento y los resultados de este modelo?
* ¿Sabemos de dónde proceden los datos de prueba? ¿Son los datos de prueba adecuados
  para ser representativos en relación con la inmensidad de los datos de formación?
* Si los datos están etiquetados por personas, ¿quiénes son esas personas? ¿Reciben un
  trato humano?
* Antes de etiquetar los datos, ¿qué instrucciones han recibido los etiquetadores que
  puedan influir en su opinión?
* ¿Qué preguntas plantean los etiquetadores o el grupo de trabajo a los datos?
* ¿Coincide la estrategia de etiquetado con los datos de formación y la estrategia de
  creación de modelos?
* ¿Existe una diversidad adecuada en mi equipo de etiquetado de datos?
* ¿Qué sesgos humanos podrían afectar al proceso de etiquetado o de prueba?
* ¿Se recopilan datos de pruebas de usuarios en el entorno real? ¿Cómo se integrarán en
  un proceso iterativo?
* ¿El grupo de usuarios es diverso y representativo del futuro grupo total de usuarios?
* ¿Es posible que el sesgo sea un resultado programático del modelo?
* ¿Con quién colaboramos en el proceso de creación de la estrategia de datos de pruebas
  o etiquetado?
* ¿Participan los equipos de producto en el proceso de recuperación de datos de los
  usuarios y en la puesta en común de la lógica humana con el grupo más amplio?
* ¿Se ha cumplido el propósito del grupo de trabajo ahora que el modelo se ha ejecutado
  y probado? (En caso negativo, explíquelo detalladamente con datos cuantificables).

**It** - Las preguntas que debemos hacernos sobre los algoritmos o modelos antes de 
empezar esta parte del proceso. Las respuestas deben guardarse para que podamos volver 
la vista atrás y ver cómo evoluciona nuestro proceso de pensamiento.

* ¿Coinciden los resultados de la prueba o los datos etiquetados con lo que
  pretendíamos obtener con los resultados del modelo?
* Si estamos probando nuestros modelos para determinar su precisión, ¿en qué medida
  coinciden los resultados que estamos viendo con el propósito principal de lo que
  hará el modelo?
* ¿Ajustaremos ahora el modelo en función de los resultados de las pruebas o de
  los datos etiquetados? (Si es así, inicie el proceso desde el paso 1).
* Si desplegamos el aprendizaje por refuerzo, ¿cómo pueden los resultados del
  modelo amplificar el sesgo e influir en los nuevos datos de los usuarios?
* ¿Hemos tenido en cuenta los resultados del modelo en relación con la Ley de
  IA de la UE o cualquier otra normativa que se proponga o que ya esté en vigor?
* ¿Hemos comprobado la existencia de material protegido o con derechos de autor en
  los resultados del modelo, como la información de identificación personal (PII),
  los datos del sector de las tarjetas de pago (PCI) y la información sanitaria
  protegida (PHI)?
* ¿Hemos tenido en cuenta la legislación sobre protección de datos o privacidad
  (como GDPR y CPRA)?
* ¿Hemos considerado otros sistemas de gestión de fuentes de datos?
