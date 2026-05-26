<!--
author:   Juan Salvador Carrasco Génova
email:    juan.carrasco@hegc.gob.cl
date:     19/05/2026
version:  1.0
language: es
narrator: none
mode:     presentation
edit:     false
repository: https://github.com/jcargen-cmd/aula
logo:     https://raw.githubusercontent.com/jcargen-cmd/aula/main/curso/logo_trasnp.png
icon:     https://raw.githubusercontent.com/jcargen-cmd/aula/main/curso/logo_trasnp.png
comment:  Este módulo corresponde al tercer modulo del curso de ciberseguridad TIC
script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js
link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css
link:     https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css
link:     https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100..900;1,100..900&display=swap
font:     Noto Sans
-->

## Repaso

Revolución Digital[^1]
==================

<div style="display:flex; flex-direction:row;">
<div style="font-size: 16px; width:25em; padding: 15px;">
Hoy vivimos el periodo entre la tercera y la cuarta revolución industrial. Vivimos una época marcada por sucesivas revoluciones tecnólogicas. Partiendo por la invención de Internet, la explosión de las redes sociales, la evolución del Software como herramienta indispensable y recientemente la irrupcion acelerada de las IAs para apoyo y automatización de actividades

---

Con estos avances surgen tambien nuevos riesgos y amenazas
* Crimen cibernético y Ciberterrorismo.
* Filtración de datos privados y confidenciales
* Suplantación de Identidad 
* Ataques de software malicioso y ransomware
* Ataques de Ingeniería Social 

---

Cuando la información de una organización se ve comprometida, su reputación y las finanzas de la misma se ven gravemente afectadas. En el caso de nuestro hospital, la informacion que se gestiona tanto de pacientes como de funcionarios y colaboradores, resulta muy atractiva para el mercado ilegal, donde se llegan a transaccionar miles de millones de dolares al año por bases de datos robadas. Abrazar la **seguridad de la información**, como activo de la organización entrega a nuestro establecimiento un fuerte prestigio y reputación dentro del ***ecosistema digital de salud*** y de cara a la demanda de las personas.

</div>
<div>

![cid](https://raw.githubusercontent.com/jcargen-cmd/aula/main/curso/ecodig.png)

</div>
</div>


[^1]: La **Cuarta** Revolución Industrial se basa en la Revolución Digital, la cual representa nuevas formas en que la tecnología se integra en las sociedades e incluso en el cuerpo humano. Está marcada por los **avances tecnológicos** emergentes en varios campos, que incluyen: robótica, inteligencia artificial, nanotecnología, computación cuántica, biotecnología, Internet de las cosas (IoT), impresión 3D y vehículos autónomos. Anteriores, que se caracterizaron principalmente por los avances en tecnología. Estas tecnologías tienen un gran potencial para continuar conectando a miles de millones de personas a la web, mejorar drásticamente la eficiencia de las empresas y organizaciones y ayudar a regenerar el entorno natural a través de una mejor **gestión de activos** ...

  -- [Wikipedia](https://es.wikipedia.org/wiki/Cuarta_Revoluci%C3%B3n_Industrial)


### Principios de la seguridad de la informacion

<div style="font-size: 18px;">
La seguridad de la informacion, se constituye por tres perspectivas que van a incidir en la completitud y calidad de esta: su __confidencialidad__, su __integridad__ y su __disponibilidad__[^2]. Las amenazas a la seguridad de la informacion, van a afectar a una, dos o todas éstas perspectivas, en la eventualidad que se materialicen.
Por ejemplo un ataque Ransomware afecta a las tres por igual dado que impide el acceso a la información, puede filtrar la información al dominio público, y puede modificarla a su entera discreción.
</div>

<div style="display:flex; flex-direction:row; font-size: 18px;">
<div style="padding: 20px;">
🔒 __Confidencialidad:__
Garantía de que los datos guardados en el sistema no se divulgan
a otras entidades o personas sin acceso autorizado
>__Buenas Prácticas__<br>
>* Bloquea tu pc con <kbd>ctrl</kbd> + <kbd>l</kbd> cuando abandones tu puesto de trabajo
>* Usa 2FA o MFA cuando vayas a iniciar sesión en un sistema sea escritorio o web
>* Revisa detalladamente los destinatarios de correo cuando respondas una consulta, eliminando aquellos que no estan autorizados a ver la información que compartirás
>>[!CAUTION] 🔥 Cuidado
>>Evita deja contraseñas pegadas en los PCs, esto puede favorecer que intrusos accedan al equipo y la información que contiene
</div>

<div style="padding: 20px;">
🗂️ __Integridad:__
Los datos no deben manipularse, la información recogida debe ser exacta y solo se puede modificada
por un usuario por orden expresa de una autoridad competente
>__Buenas Prácticas__<br>
>* Evita traspasar a mano datos importantes (que requieran exactitud) entre un sistema y otro
>* Apóyate de sistemas que entregan información fidedigna cuando trabajes con datos, como por ejemplo __Fonasa__
>* Manten siempre un respaldo de tu informacion, al que puedas recurrir en caso de que tus datos sufran modificaciones accidentales
>>[!CAUTION] 🔥 Cuidado
>>Desconfía de las instrucciones "informales" cuando debas aprender un nuevo sistema. Siempre solicita que se te capacite __formalmente__ para que puedas gestionar adecuadamente la información.

</div>
<div style="padding: 20px;">
📈 __Disponibilidad:__
Toda información recogida en el sistema debe estar siempre a disposición de los
usuarios autorizados en cualquier momento que requieran acceso
>__Buenas Prácticas__<br>
>* Manten tus contraseñas seguras, guardadas en un lugar donde puedas consultarlas sin problemas 
>* Revisa y asegúrate de que los sitios en linea donde trabajarás son genuinos 
>* Prefiere usar sistemaa en linea y colaborativos para gestionar tu información, por ejemplo __"Teams"__
>>[!CAUTION] 🔥 Cuidado
>>Evita tener grandes cantidades de información importante en un solo dispositivo (PC, disco o pendrive), ya que puede dañarse y perder todo

</div>
</div>

![cid](https://raw.githubusercontent.com/jcargen-cmd/aula/main/curso/cid_up.png)

[^2]: Estos conceptos son conocidos como **TRIADA CID** En el ámbito de la seguridad de la información.

## Contraseñas, gestores y MFA

Ranking 2026 Contraseñas mas usadas en Chile
============================================

![ranking](https://raw.githubusercontent.com/jcargen-cmd/aula/main/curso/ranking.png)


### El Derecho a la privacidad en Chile

<div style="font-size: 16px; text-align: justify;">
Nuestro pais estipula en su carta constituyente el derecho a la protección de la vida privada. Entendemos para efectos de este curso, que existe una separación entre la información de uso privado y la información de uso público. Esta delimitación responde a la idea de reconocer una esfera personal donde cada individuo tiene facultad y potestad de excluir a los demas del conocimiento contenido en esa esfera. Lo que concierne al espacio familiar individual, es protegido por el estado, salvo que esa esfera atente contra la integridad y dignidad de otro.
</div>

Referencias del Marco Legal en Chile
------------------------------------
<div style="display:flex; flex-direction:row;">
<div style="font-size: 16px; text-align: justify;">

![privacidad](https://raw.githubusercontent.com/jcargen-cmd/aula/main/curso/privada.jpg "imagen: macroscopio.com")


Al comparar los ámbitos de lo íntimo, lo privado y lo público según el nivel de acceso que otras personas pueden tener sobre ellos, se puede entender que lo íntimo corresponde al espacio más reservado de una persona, al que nadie más debería acceder. En el extremo opuesto, lo público se caracteriza por estar abierto y disponible para todos. Entre ambos se encuentra lo privado, que corresponde a un espacio de acceso limitado o parcial, donde ciertas personas pueden acceder bajo determinadas condiciones.[^3]

</div>

<div style="font-size: 16px; padding: 15px; text-align: justify;">
Si bien existen mas leyes y un marco regulatorio mas extendido en la materia, se hará referencia a lo siguiente:

>**Constitución Política[^4]:** (Art. 19 Nº4): Consagra el derecho a la protección de la vida privada y la honra.

>**Ley Nº 19.628:** (Sobre Protección de la Vida Privada): Marco original sobre el tratamiento de datos personales en registros o bancos de datos. Regula el tratamiento, almacenamiento, uso y transmisión de datos personales en el país, asegurando que las personas tengan control sobre su propia información

>**Ley Nº 21.719:** (Actualización 2024/2025): Es la norma moderna que modifica la antigua Ley N° 19.628. Eleva los estándares de seguridad, exige protección desde el diseño y regula las transferencias internacionales de datos.
</div>
</div>


[^3]: Francisco Javier Sanz Salguero - 2018, Delimitación de las Esferas de la Vida Privada, Privacidad e Intimidad, frente al ámbito de lo público, Conclusiones. 
[^4]: ~~Artículo 19.-~~ La Constitución asegura a todas las personas: **4º.-** El respeto y protección a la vida privada y a la honra de la persona y su familia, y asimismo, la protección de sus datos personales. El tratamiento y protección de estos datos se efectuará en la forma y condiciones que determine la ley.

### El problema de la Autenticación

<div style="font-size: 18px; padding: 15px;  text-align: justify;">
Si nos remontamos a la época del imperio romano y las culturas célticas, para viajar a traves de las tierras no era obligatorio para los ciudadanos y miembros del imperio llevar consigo un documento que acreditas su identificación. Esto significaba un problema para individualizar viajeros cuando había que verificar asuntos del gobierno o reconocimientos de familiares, es decir, que existía una complejidad a la hora de *estableecer un marco adecuado de gestión de la privacidad*. De entre las muchas soluciones que se desarrollaron tales como diplomas, salvoconductos o la ciudadanía romana, entre otros, surge la **"Tessera Hospitalis"**.
</div>

<div style="display:flex; flex-direction:row;">
<div>

![tessera](https://raw.githubusercontent.com/jcargen-cmd/aula/main/curso/tesselas.png)

</div>
<div style="font-size: 16px; width:28em; padding: 15px;">

La tessera hospitalis (o tésera de hospitalidad) era un objeto de metal, hueso o madera que los pueblos antiguos—especialmente celtíberos y romanos—utilizaban como sello y contraseña de un pacto de amistad o alianza. Este símbolo servía como un contrato social y salvoconducto de gran valor:
* **Mecanismo:** La pieza se dividía en dos partes idénticas o encajables. Cada una de las partes se quedaba con una mitad, y al reencontrarse, las encajaban para demostrar su identidad y el pacto de protección mutua.
* **Diseño:** A menudo tenían forma de dos manos entrelazadas y llevaban inscripciones que detallaban los nombres de los firmantes o las comunidades involucradas.
* **Origen de la palabra símbolo:** El término proviene del griego symbolon, que significa literalmente "hacer coincidir o encajar" (la acción de unir las dos mitades de la tésera).

---

En la actualidad, también navegamos por extensos territorios en el ciberespacio. Usamos diversos sitios web o aplicaciones en linea para acceder a información pública, pero tambien tenemos espacios personales (o familiares) donde la privacidad es esencial. El problema de la autenticación *(identificación de la identidad)* en estos espacios es resuelto de forma análoga a las tesseras. Usamos mecanismos de identificación como contraseñas o factores de autenticación que coinciden con aquello que un sitio, que está solicitando la autenticación, espera recibir (esa pieza que calza perfectamente).
</div>
</div>

### El desafío de la Revolución Tecnológica

<div style="font-size: 16px; padding: 15px; text-align: justify;">
El desarrollo de la capacidad de procesamiento de información que una computadora puede alcanzar, ya ha superado hace varios años a la capacidad de los seres humanos en términos de procesamiento de datos y comprensión de la información; Particularmente en algunas materias como matemáticas o en un juego de ajedrez. Actividades como elaborar análisis estadísticos y matemáticos son mas efectivos con el apoyo de un procesador computarizado, en vez de muchas personas trabajando juntas manualmente. La ventaja es un mejor alcance del conocimiento en menor tiempo, con mejores oportunidades para tomar mejores decisiones. El riesgo recae en el uso inadecuado de estas tecnologías para obtener ventajas que van a perjudicar la integridad y dignidad de otras personas. La propia naturaleza del ser humano invitablemente provoca que surjan nuevas amenazas como la ciberdelincuencia,  estafas digitales y robos de activos de información.
</div>

<div style="display:flex; flex-direction:row;">
<div style="font-size: 14px; width:25em; padding: 15px;">

>Hitos clave en el procesamiento de datos:
>---------------------------
>* 1945 (Cálculo matemático): La primera computadora digital electrónica (ENIAC) realizó en sus primeros años más cálculos de los que toda la humanidad había logrado en su historia hasta ese momento.
>* 1997 (Estrategia): La supercomputadora Deep Blue de IBM derrotó por primera vez al campeón mundial de ajedrez Garry Kasparov.
>* 2011 (Procesamiento de Lenguaje Natural): El sistema IBM Watson superó a los mejores humanos en el programa de concursos Jeopardy!.
>* 2016 (Intuición y complejidad): El programa AlphaGo de Google DeepMind derrotó al campeón mundial Lee Sedol en el milenario juego de Go, superando la capacidad de razonamiento intuitivo humano.
>* Actualidad (2019-2026): Diversos modelos de inteligencia artificial han superado consistentemente el rendimiento humano en pruebas estandarizadas de comprensión lectora, reconocimiento visual, comprensión general y razonamiento matemático.
</div>
<div style="font-size: 16px; text-align: justify;">
![El **AMD Ryzen 7 9800X3D** es considerado actualmente como el procesador más rápido del mundo para gaming](https://raw.githubusercontent.com/jcargen-cmd/aula/main/curso/ryzen.png)	

Un ejercicio realizado con la IA de google que consistió en consultar el tiempo aproximado que tomaría leer toda la biblioteca nacional de Chile a una persona vs un procesador, arrojó que con una media promedio de lectura ocular de 150 milisegundos[^5] una persona demoraría 3200 ~ 4000 años en alcanzar todos los libros de la bilioteca (4 millones), si la lectura fuese inintuerrumpida 24 horas al dia, mientras que un procesador de ultima generacion demoraría menos de un minuto si todos esos libros estuviesen digitalizados (aproximadamente 6TB de información).
</div>
</div>

[^5]: >El estudio, publicado en Nature Communications, se centró en los movimientos sacádicos y permitió a la ciencia entender mejor la relación entre percepción y procesamiento cerebral. Según investigaciones del Cluster of Excellence Science of Intelligence de la Universidad Técnica de Berlín (TU Berlín), estos movimientos pueden durar entre 20 y 200 milisegundos, dependiendo de la distancia recorrida por la mirada. Durante la lectura, por ejemplo, el tiempo promedio entre palabra y palabra es de apenas 20 a 30 milisegundos.
 -- [Nature](https://www.nature.com/articles/s41467-025-58659-9)
