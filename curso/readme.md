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
La seguridad de la informacion, se constituye por tres perspectivas que van incidir en la completitud y calidad de esta: su __confidencialidad__, su __integridad__ y su __disponibilidad__[^1]. las amenazas a la seguridad de la informacion, van a afectar a una, dos o todas éstas perspectivas, en la eventualidad que se materialicen.
Por ejemplo un ataque Ransomware afecta a las 3 por igual dado que impide el acceso a la información, puede filtrar la informacion al dominio publico, y puede modificarla a su entera discreción.
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

[^1]: Estos conceptos son conocidos como **TRIADA CID** En el ámbito de la seguridad de la información.

## Contraseñas, gestores y MFA

Ranking 2026 Contraseñas mas usadas en Chile
============================================

![ranking](https://raw.githubusercontent.com/jcargen-cmd/aula/main/curso/ranking.png)

### El problema de la Autenticación

<div style="display:flex; flex-direction:row;">
<div>

![tessera](https://raw.githubusercontent.com/jcargen-cmd/aula/main/curso/tesselas.png)

</div>
<div style="font-size: 16px; width:20em; padding: 15px;">
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
</div>

