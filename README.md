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


# La Nube

<img src="https://tynmedia.com/tynmag/wp-content/uploads/sites/3/2019/06/El-futuro-empresarial-est%C3%A1-en-la-nube-e1560566724502.png" width="200" height="100">
- ## ¿Qué es la nube?
La definición de la nube puede parecer poco clara, pero, básicamente, es un término que se utiliza para describir una red mundial de servidores, cada uno con una función única. La nube no es una entidad física, sino una red enorme de servidores remotos de todo el mundo que están conectados para funcionar como un único ecosistema. Estos servidores están diseñados para almacenar y administrar datos, ejecutar aplicaciones o entregar contenido o servicios, como streaming de vídeos, correo web, software de ofimática o medios sociales. En lugar de acceder a archivos y datos desde un equipo personal o local, accede a ellos en línea desde cualquier dispositivo conectado a Internet, es decir, la información está disponible dondequiera que vaya y siempre que la necesite.

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

