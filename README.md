# Guía de estudio para la certificación az-900 con azure
# Conceptos previos sobre el funcionamiento de la computación, sistemas operativos e internet.

## 1. Componentes básicos en el hardware de una computadora
 1. **Placa madre**:es lo que une a todo como chips de entrada y salida, conexiones usb, ethernet, internet, etc.
 2. **Procesador**: el cerebro. Se mueve con 1’s y 0’s.
 3. **Ventilación**: para el calor que genera la carga eléctrica del procesador.
 4. **Memoria temporal (RAM), memoria de almacenamiento (ROM).**
 5. **Fuente de alimentación.**
 6. **CPU ó GPU**. El GPU entre mas hz/s más rápido se refresca la imagen en la pantalla.

 ## ¿Qué es la arquitectura de procesadores?
 La forma en la que están acomodados y cómo procesan la información y reciben instrucciones.


 ## 2. Componentes básicos del software

 Los sistemas operativos como Windows, Linux, iOS o Android tienen la siguiente arquitectura:

 1.	**Kernel en la capa 1**: lo que controla directamente al hardware. Ejemplo: botón de encendido o conectas algo.
 2.	**Manejo de memoria en la capa 2**: maneja RAM y ROM. Donde escribe y dónde lee. Por medio de cargas magnéticas se pone la información y se almacena.
 3.	**Entrada y salida en la capa 3**: detectar dispositivos que se conectan.
 4.	**Sistema de archivos en la capa 4**: almacenar y mantener congruencia en todos los datos que se tengan.
 5.	**Interfaz de usuario en la capa 5**: donde se usan los programas/aplicaciones como Teams, Chrome, etc.


 ## 3. Redes
 Las redes son conexiones entre computadoras.

 Hay 2 tipos de redes:
 1. **Por cable:** más confiable y rápida.
 2. **Satelital:** generalmente donde no hay infraestructura de red. (Para barcos, aviones, GPS,etc).

 Niveles de redes de la capa OSI son los que definen todo lo que se necesita para mandar la información de punto A a punto B.

 1.	**Capa física:** cable ethernet, fibra óptica, etc.
 2.	**Capa de datos:** protocolo comunicación física, estándar de wifi,etc.
 3.	**Capa de red:** determina el camino de punto A a punto B.
 4.	**Capa de transporte:** protocolo para comunicarnos como TCP/IP ó UDP. (externamente)
 5.	**Capa de sesión:** transporte de datos en la red. (internamente)
 6.	**Capa de presentación:** la información que se manda como HTML, CSS, PDF, un video. Donde se e el tipo de archivo.
 7.	**Capa de aplicación:** correos o cualquier página.

 *Nota: Los tipos de ataque en las redes puede ocurrir en la capa de transporte y red.

# Conceptos acerca de la nube, qué es, cómo funciona y beneficios además de los modelos de servicio que existen.



![Nube](https://tynmedia.com/tynmag/wp-content/uploads/sites/3/2019/06/El-futuro-empresarial-est%C3%A1-en-la-nube-e1560566724502.png)
- ## ¿Qué es la nube?
La definición de la nube puede parecer poco clara, pero, básicamente, es un término que se utiliza para describir una red mundial de servidores, cada uno con una función única. La nube no es una entidad física, sino una red enorme de servidores remotos de todo el mundo que están conectados para funcionar como un único ecosistema. Estos servidores están diseñados para almacenar y administrar datos, ejecutar aplicaciones o entregar contenido o servicios, como streaming de vídeos, correo web, software de ofimática o medios sociales. En lugar de acceder a archivos y datos desde un equipo personal o local, accede a ellos en línea desde cualquier dispositivo conectado a Internet, es decir, la información está disponible dondequiera que vaya y siempre que la necesite.

<img src= "https://steemitimages.com/p/vM1pGHgNcyCXUWJECrZbvn1NMPj1oFGUo3gYfF3NNPRD9aDqm7juy9RFifmPuvS5ncMqWPej5qUuZTT6YRNoLn6udcyhSaUGLPj4BEX9KAu9PMv8ZPTrqum1bAWJFNR3S4AkzTP?format=match&mode=fit" width= 500>


Las empresas utilizan cuatro métodos diferentes para implementar recursos en la nube. Hay una nube pública, que comparte recursos y ofrece servicios al público a través de Internet; una nube privada, que no se comparte y ofrece servicios a través de una red interna privada, normalmente hospedada en el entorno local; una nube híbrida, que comparte servicios entre nubes públicas y privadas, según su finalidad; y una nube comunitaria, que comparte recursos solo entre organizaciones, por ejemplo, con instituciones gubernamentales.
***
- ## ¿Cómo funciona el almacenamiento en la nube?
El almacenamiento en la nube se compra a un proveedor de la nube externo que posee y opera capacidad de almacenamiento de datos y la distribuye a través de Internet con un modelo de pago por uso. Estos proveedores de almacenamiento en la nube administran la capacidad, la seguridad y la durabilidad para lograr que sus aplicaciones de todo el mundo tengan acceso a los datos.
Las aplicaciones obtienen acceso al almacenamiento en la nube mediante protocolos de almacenamiento tradicionales o directamente mediante una API. Muchos proveedores ofrecen servicios complementarios diseñados para ayudar a recopilar, administrar, proteger y analizar datos a gran escala

<img src= "https://blog.dataprius.com/wp-content/uploads/2016/08/capacidad-ilimitada-nube.jpg" wigth=400>

 ***   
 
- ## Beneficios del almacenamiento en la nube
### El almacenamiento de datos en la nube permite a los departamentos de TI transformar tres aspectos:

***Costo total de la propiedad.***
Con el almacenamiento en la nube, no es necesario comprar hardware, almacenar para aprovisionar o invertir capital en situaciones que pueden darse "algún día". Puede agregar o eliminar capacidad bajo demanda, modificar las características de desempeño y retención con rapidez y pagar solamente por el almacenamiento que utilice. Incluso puede trasladar los datos a los que se accede con menos frecuencia a capas de menor costo de acuerdo con las reglas auditables, para aprovechar la economía de escala.

***Tiempo de implementación.***
Cuando los equipos de desarrollo están listos para la ejecución, la infraestructura no debería detenerlos. El almacenamiento en la nube permite al departamento de TI proporcionar con rapidez la cantidad de almacenamiento necesaria en el momento necesario. Eso permite al departamento de TI concentrarse en resolver problemas de aplicación complejos en lugar de tener que administrar sistemas de almacenamiento.

***Gestión de la información.***
Centralizar el almacenamiento en la nube aporta un gran beneficio para nuevos casos de uso. Al utilizar políticas de administración del ciclo de vida del almacenamiento en la nube, puede realizar potentes tareas de administración de la información, incluida la separación por niveles automatizada o el bloqueo de datos para cumplir con los requisitos de conformidad.
<img src = "https://d1.awsstatic.com/cloud-storage/payasyougo_graph.ae4828313cc5c2c6d885b1a03b2a696a0db0db3b.png" width=600>
***
- ## ¿Qué son los modelos de servicios en la nube?
La computación en la nube pertenece a uno de los siguientes modelos de computación. Si ha estado en la computación en la nube por un tiempo, probablemente haya visto los términos infraestructura como servicio (IaaS), plataforma como servicio (PaaS) y software como servicio (SaaS) para los diferentes modelos de servicios en la nube. Estos modelos definen los diferentes niveles de responsabilidad compartida del que son responsables un proveedor de nube y un inquilino de nube.

***___Los modelos de servicios consisten en:___***

**Software como servicio (SaaS):** | **Plataforma como servicio (PaaS):** | **Infraestructura como servicio (IaaS):** | **Función como servicio (FaaS):** |
------------ | ------------- | ------------ | ------------- |
en lugar de que los usuarios instalen una aplicación en su dispositivo, las aplicaciones de SaaS se alojan en servidores en la nube y los usuarios pueden acceder a ellas a través de Internet. El SaaS es como alquilar una casa: el arrendador sigue siendo el propietario de la casa, pero el arrendatario tiene derecho a usarla como si fuera suya. Ejemplos de aplicaciones de SaaS incluyen Salesforce, MailChimp y Slack. | en este modelo, las empresas no pagan por las aplicaciones alojadas, sino que pagan por lo que necesitan para desarrollar sus propias aplicaciones. Los proveedores de PaaS proporcionan todo lo necesario para crear una aplicación, incluyendo herramientas de desarrollo, infraestructura y sistemas operativos, todo a través de Internet. El PaaS se puede comparar con alquilar todas las herramientas y equipamiento necesarios para construir una casa, en lugar de alquilar la casa en sí. Algunos ejemplos de PaaS incluyen Heroku y Microsoft Azure.| en este modelo, una empresa alquila los servidores y el almacenamiento que necesita de un proveedor de nube. Luego, utilizan esa infraestructura en la nube para desarrollar sus aplicaciones. IaaS es como una empresa que alquila un terreno en el que se puede construir lo que se quiera, pero tienen que proporcionar su propio equipamiento y materiales de construcción. Los proveedores de IaaS incluyen DigitalOcean, Google Compute Engine y OpenStack. |  FaaS, también conocida como computación sin servidor, divide las aplicaciones en la nube en componentes todavía más pequeños que solo se ejecutan cuando son necesarios. Imagínate que fuera posible alquilar una casa por partes: por ejemplo, el arrendatario solo paga por el comedor a la hora de la cena, el dormitorio a la hora de dormir, el comedor cuando ve la TV, y cuando no esté usando ninguna de ellas, no tendrán que pagar el alquiler de las mismas. | 

<img src = "https://docs.microsoft.com/en-gb/learn/azure-fundamentals/intro-to-azure-fundamentals/media/iaas-paas-saas-expanded.png#lightbox" wigth=400>

- ## ¿Qué son las nubes públicas, privadas e híbridas?

Hay tres modelos de implementación para la computación en la nube: nube pública , nube privada y nube híbrida . Cada modelo de implementación tiene diferentes aspectos que debe considerar al migrar a la nube.

**Modelo de implementación** |	**Descripción** |
-----------------------------|-------------------|
***Nube pública*** |	Los servicios se ofrecen a través de la Internet pública y están disponibles para cualquier persona que desee adquirirlos. Los recursos en la nube, como los servidores y el almacenamiento, son propiedad y están operados por un proveedor de servicios en la nube externo y se entregan a través de Internet.|
***Nube privada*** |	Los recursos informáticos son utilizados exclusivamente por usuarios de una empresa u organización. Una nube privada puede ubicarse físicamente en el centro de datos en el sitio de su organización. También puede ser alojado por un proveedor de servicios externo.|
***Nube híbrida*** |	Este entorno informático combina una nube pública y una nube privada al permitir que los datos y las aplicaciones se compartan entre ellos.`|

La siguiente imagen ilustra varios de los conceptos de computación en la nube que se presentan en esta unidad. En este ejemplo, se demuestran varios factores cuando está considerando dónde implementar un servidor de base de datos en un entorno de nube híbrida. A medida que sus recursos se trasladan de las instalaciones a las fuera de las instalaciones, sus costos se reducen y sus requisitos de administración disminuyen.

<img src="https://docs.microsoft.com/en-gb/learn/azure-fundamentals/intro-to-azure-fundamentals/media/cloud-computing-continuum.png" wigth= 500>

# ¿Qué es Azure?
 De la mano de Microsoft , Azure es un conjunto de servicios en la nube en expansión constante que ayudan a la organización a cumplir los desafíos empresariales actuales y futuros
 
 <img src="https://xentic.com.pe/wp-content/uploads/2019/02/azure-gif.gif" wigth= 300>
 
 ## ¿Qué puedo hacer con Azure?
 Azure proporciona más de cien servicios que permiten hacer todo tipo de cosas: desde ejecutar las aplicaciones existentes en máquinas virtuales hasta explorar nuevos paradigmas de software, como bots inteligentes, inteligencia artificial y aprendizaje automático, y realidad mixta.
También facilita soluciones de almacenamiento que crecen dinámicamente para dar cabida a grandes cantidades de datos. 

<img src="https://www.hiberus.com/crecemos-contigo/wp-content/uploads/2019/07/1-1.png" wigth= 450>

### Estas son algunas de las categorías que se usan con más frecuencia:

### Proceso
Azure proporciona una amplia gama de opciones para hospedar aplicaciones y servicios. 
### Redes
La funcionalidad de red de Azure incluye una gama de opciones para conectar el mundo exterior a servicios y características de los centros de datos globales de Azure.
### Móvil
Con Azure, los desarrolladores pueden crear servicios de back-end móviles para aplicaciones iOS, Android y Windows de forma rápida y sencilla. 
### Almacenamiento
Permite almacenar archivos desde cualquiera de tus dispositivo compatible con Azure a la nube
### Bases de datos
Azure proporciona varios servicios de base de datos para almacenar una gran variedad de volúmenes y tipos de datos. Y con la conectividad global, los usuarios disponen de estos datos al instante.
### Web
Azure incluye soporte técnico de primera clase para compilar y hospedar aplicaciones web y servicios web basados en HTTP. 
### IoT
Los asistentes digitales personales llevaron a los smartphones y ahora existen relojes inteligentes, termostatos inteligentes e incluso frigoríficos inteligentes. Los equipos estaban a la orden del día. Ahora, Internet permite que cualquier objeto capaz de conectarse tenga acceso a valiosa información. Esta capacidad de los dispositivos de obtener y luego retransmitir información para el análisis de datos se conoce como IoT (Internet de las cosas).
### Macrodatos
Los datos se presentan en cualquier formato y tamaño. Cuando hablamos sobre macrodatos, nos referimos a grandes volúmenes de datos. Los datos de los sistemas del tiempo, sistemas de comunicaciones, investigación genómica, plataformas de imágenes y muchos otros escenarios generan cientos de gigabytes de datos. Esta cantidad de datos hace que resulte difícil analizar y tomar decisiones. A menudo es tan grande que las formas de procesamiento y análisis tradicionales ya no son adecuadas.
Se han desarrollado tecnologías de clúster de código abierto para tratar con estos grandes conjuntos de datos. Azure admite una amplia gama de tecnologías y servicios para proporcionar soluciones de análisis y macrodatos.
### Inteligencia Artificial 
En el contexto de la informática en la nube, la inteligencia artificial se basa en una amplia gama de servicios, donde el principal es el aprendizaje automático. El aprendizaje automático es una técnica de ciencia de datos que permite a los equipos utilizar datos existentes para prever tendencias, resultados y comportamientos futuros. Mediante el aprendizaje automático, los equipos aprenden sin necesidad de programarlos explícitamente.
### DevOps
DevOps reúne a individuos, procesos y tecnología mediante la automatización de la entrega de software para ofrecer un valor continuo a los usuarios. Con Azure DevOps puede crear, compilar y publicar canalizaciones que proporcionan integración, entrega e implementación continuas a las aplicaciones. Puede integrar los repositorios y las pruebas de aplicaciones, realizar la supervisión de aplicaciones y trabajar con artefactos de compilación. También puede trabajar con elementos de trabajo pendiente para realizar el seguimiento, automatizar la implementación de la infraestructura e integrar una gama de herramientas y servicios de terceros como Jenkins y Chef. Todas estas funciones y muchas más están estrechamente integradas con Azure para permitir implementaciones coherentes y reproducibles para que las aplicaciones proporcionen unos procesos de compilación y lanzamiento optimizados.

# Inteligencia Artificial

La Inteligencia Artificial (o I.A.) es la capacidad de una máquina o sistema informática de emular en parte el comportamiento de la mente humana desarrollando capacidades que hasta hace poco solo estaban alcance del cerebro humano, como la creatividad o el análisis complejo en base de datos incompletos. Como bien se denomina, su emulación es a través de modelos matemáticos que se expresan de la forma en la que aprendemos y pensamos los seres humanos. También, existen diversas formas las cuales una IA puede aprender, pero se relaciona más centrado al aprendizaje de un niño pequeño.

<img src="https://www.cic.es/wp-content/uploads/2018/05/imagen_blog-1100x605.png" width= 500>

## Tipos de Inteligencia Artificial
                                                   
El funcionamiento de la Inteligencia Artificial depende en gran medida de los algoritmos y proceso empleados para desarrollarla o de los objetivos que se persiguen con ella, por ello podemos hablar de diferentes tipos de IA.
Una primera diferencia la podemos hacer entre los sistemas de IA débil e IA fuerte. Los primeros, también conocidos como IA estrecha, son sistemas diseñados y entrenados para realizar una única tarea. Mientras que los segundos, también llamados como inteligencia general artificial, son sistemas que cuentan con habilidades cognitivas humanas generalizadas, de manera que tienen la capacidad de encontrar por sí mismas la solución a una tarea planteada.
Una segunda forma de distinguir entre tipos de IA la encontramos en la categorización que hizo Arend Hintze, profesor de biología integradora e ingeniería y ciencias de la computación en la Universidad Estatal de Michigan. Hintze distingue entre 4 tipos de IA, tanto existentes hoy en día como todavía por desarrollarse. Los vemos en detalle a continuación.

<img src= "https://aprendeia.com/wp-content/uploads/2019/10/tipos-de-inteligencia-artificial.png" width=600>
     
## Máquinas Reactivas    
                                                       
Las máquinas reactivas son el tipo más básico de Inteligencia Artificial; se basan en decisiones sobre el presente, es decir, no tienen memoria y, por lo tanto, no pueden mirar al pasado para aprender de experiencias pasadas y son incapaces de evolucionar.
Un ejemplo de este tipo de IA lo encontramos en Deep Blue, el ordenador que ganó al ajedrez al campeón Kasparov. Este ordenador era capaz de reconocer las figuras en el tablero y procesar 200 millones de movimientos en un segundo, pero ese era su único objetivo, procesar la información y los datos en busca del mejor movimiento en tiempo real en función a las jugadas de su oponente.
                                            
## Memoria Limitada  
                                                       
Las máquinas de IA de memoria limitada son capaces de mirar al pasado, pero de una forma limitada y temporal. De esta manera, pueden almacenar la información que recogen durante cierto tiempo y añadirla a su programación para crear nuevos patrones de comportamiento y respuesta para un futuro no lejano. Es decir, que no son capaces de realizar representaciones completas y perdurables en el tiempo.
Como ejemplo de este tipo de Inteligencia Artificial tenemos los coches autónomos.

## Teoría de la Mente

La teoría de la mente presenta sistemas o máquinas cuya IA les permite entender cómo funciona su entorno, es decir, las personas, objetos y otros sistemas que les rodean. Son sistemas capaces de aprender en base a nuestros comportamientos y deducir y saber cuáles son nuestros gustos, necesidades, deseos o hasta cómo esperamos ser tratados.
Este tipo de Inteligencia Artificial tendría la capacidad de entender el mundo que le rodea y cuando esté desarrollada plenamente, será capaz de realizar una interacción social más cercana a la de un ser humano.

## Autoconciencia
                                                           
Hemos llegado a lo que todavía es terreno de la ciencia ficción, porque actualmente no existe ningún tipo de IA con autoconciencia. Se trataría de una Inteligencia Artificial que ha desarrollado conciencia de sí misma y es capaz de reconocerse como una entidad independiente, que puede tomar sus propias decisiones, diferenciando entre ella y los objetos, personas y sistemas que la rodean. Sería el primer paso en lo que ha denominado la singularidad de la tecnológica.

## Aplicaciones de la Inteligencia Artificial

Como decíamos, la Inteligencia Artificial se emplea en muchos ámbitos actuales y sin duda son muchas las aplicaciones de la misma que pueden aprovechar las empresas para mejorar sus procesos de ventas, reclutamiento o en sus servicios de atención al cliente, como vamos a ver en los siguientes puntos.

## Marketing y Ventas

En un mercado cada vez más competitivo, donde se hace necesario ofrecer productos o servicios con un valor añadido para poder diferenciarse de la competencia, el análisis de datos y la elaboración de perfiles de consumidores son clave y es aquí donde entra la Inteligencia Artificial aplicada al marketing y las ventas, puesto que permite automatizar procesos como la minería y análisis de la información extraída.
La IA aplicada al marketing permite predecir futuras necesidades a través del empleo de herramientas capaces de analizar condutas y elaborar patrones de comportamiento en base a la huella que los usuarios dejan en Internet. Así, pueden elaborar perfiles de usuarios, segmentar la audiencia y poder así ofrecerles productos según sus necesidades y deseos.
Ejemplos
Algunos ejemplos de Inteligencia Artificial aplicada al campo del marketing y las ventas los tenemos en:
•	Publicidad programática: Son plataformas que permiten la compra de espacios publicitarios en función de las audiencias a las que se desea llegar, y se hace de forma completamente automatizada.
•	Creación de contenido: Ya podemos encontrar programas capaces de generar contenido completamente original en base a determinados conceptos y palabras clave.
•	Curación de contenido: Se trata de sistemas de IA capaces de analizar el comportamiento de los usuarios en Internet y en base a ello ofrecerles contenidos acorde a su perfil.
•	Email marketing: Se basa en la automatización y algunas de las herramientas que emplea pueden usar el procesamiento del lenguaje natural para redactar asuntos más llamativos o cuerpos de email personalizados.

## Atención al cliente

Los departamentos de atención al cliente también pueden beneficiarse del empleo de sistemas de Inteligencia Artificial, puesto que pueden delegar algunas tareas en asistentes virtuales. Pero no solo eso, como en el caso del marketing, pueden analizar el comportamiento de los usuarios y poder ofrecerles la ayuda que buscan prácticamente en tiempo real.
La atención al cliente genera una gran cantidad de datos que los sistemas de IA pueden ayudar a analizar para crear servicios predictivos con los que las empresas puedan adelantarse a las consultas y necesidades de sus clientes, ofreciéndoles una atención más personalizada.
Ejemplos
El ejemplo más claro de la aplicación de la Inteligencia Artificial en el departamento de atención al cliente lo tenemos en los chatbots. Se trata de una aplicación informática que simula la conversación con cliente. Los hay muy básicos, con respuestas estándar a preguntas concretas, pero también existen chatbots realmente complejos, capaces de procesar un gran volumen de mensajes, aprender durante el proceso y prácticamente mantener una conversación natural con los usuarios.

## Recursos Humanos

Los departamentos de recursos humanos también pueden servirse de los sistemas de Inteligencia Virtual para llevar a cabo los procesos de selección y reclutamiento de trabajadores o llevar a cabo otras tareas relacionadas con el análisis y la gestión de los datos de la empresa, de manera que la IA agrupe estos datos y proporcione diferentes resultados respecto a diferentes áreas, como la evolución del talento, la productividad o los conflictos.
Pero donde sin duda la IA representa una ventaja para Recursos Humanos es en la eliminación de los llamados prejuicios cognitivos, es decir, la eliminación de valoraciones erróneas que puede hacer una persona sobre otra en base a su aspecto, apariencia, conducta, etc., puesto que la IA no hace juicios de valor de este tipo.
Ejemplos
Ejemplos del empleo de Inteligencia Artificial en Recursos Humanos podemos verlos en la automatización de algunos procesos, como la entrada y categorización de curriculums.
También puede emplearse para analizar el absentismo laboral en una empresa, determinar sus posibles causas y presentar soluciones. Así mismo puede analizar el comportamiento de los trabajadores encontrar los que tienen un mejor rendimiento  son buenos líderes de equipo. Análisis que también se puede emplear para buscar perfiles similares para contratar nuevos trabajadores.

## Ventajas y Desventajas de la Inteligencia Artificial

Como toda la tecnología actual y aquella que aún sigue en desarrollo, la Inteligencia Artificial cuenta con una serie de ventajas y desventajas que la sociedad en su conjunto debe valorar.
Como Ventajas de la Inteligencia Artificial , entre otras, tenemos:

•	Aumenta la eficacia de los procesos y los lleva a cabo de forma más rápida.
•	Permite automatizar procesos repetitivos.
•	Al estar basada en procedimientos computacionales, no comete errores humanos.
•	Es incansable, puede trabajar todos los días a todas horas.
•	Puede facilitar el día a día de las personas con herramientas como los asistentes virtuales.
•	Es capaz de analizar enormes cantidades de datos, extraer información relevante y crear perfiles o modelos predictivos en muchos ámbitos (medicina, comportamiento social, medioambiente, etc.).
•	Puede realizar tareas que para los humanos serían peligrosas o imposibles.
En cuanto a las _**desventajas o peligros que puede entrañar la IA_** encontramos:
•	Cuanto más sofisticados y complejos se vuelven los sistemas de Inteligencia Artificial, más probable se hace que puedan sustituir a los trabajadores humanos, impactando negativamente en el mercado laboral.
•	Puesto que aún carecen de creatividad y capacidad de improvisación, sus soluciones y respuestas están basadas en algoritmos y análisis de información preexistente, lo que limita su capacidad de tomar decisiones más allá de los datos.
•	Su carencia de empatía o sentimientos la hace «inútil» para desempeñar tareas en las que el factor humano es fundamental.
•	Se puede emplear con fines ilegales, como la creación y distribución de malware o la suplantación de identidad.
•	Plantea dudas éticas en cuanto a su evolución hacia IA autoconscientes.
