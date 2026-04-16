# MAYA Ahorra Agua

Juego educativo para el uso responsable del agua

Facultad de ingenierías

Politécnico Colombiano Jaime Isaza Cadavid

Técnico Profesional en Programación de Sistemas de Información


**Laura Cristina Giraldo Monsalve**
**Santiago Vanegas Henao**
**Camila Osorio Suarez**


Identificación de estándares para la documentación y construcción de informes

2026

---

## __PROBLEMA INTERÉS O NECESIDAD - PIN__

Actualmente enfrentamos un desafío global por problemáticas tales como el cambio
climático, la sobreexplotación de recursos naturales, la deforestación, etc., que amenazan el
bienestar ambiental de las futuras generaciones; lo que hace necesario implementar
estrategias de desarrollo sostenible.

Para este proyecto nos enfocaremos específicamente en el alto consumo de agua en los
hogares, lo que se considera una problemática crítica que repercute directamente en el
deterioro del medio ambiente. En latinoamérica, el consumo promedio por hogar oscila entre
los 120 y 200 litros diarios, siendo la ducha y el inodoro los lugares donde se ve reflejado el
mayor consumo; lo que supera significativamente los niveles recomendados por la
Organización Mundial de la Salud (OMS) que indica que 100 litros diarios son suficientes
para cubrir las necesidades básicas (Padilla, 2022), esto intensifica el riesgo a que las futuras
generaciones no puedan disponer de este recurso. Se estima que, para el año 2050, muchas
zonas del mundo tendrán que afrontar una escasez severa de este recurso si no se toman
medidas.

El consumo excesivo de agua no solo afecta la naturaleza, sino que también impacta
negativamente la economía, la salud, y la estabilidad social. Esta situación refleja la
necesidad de fomentar cambios en los hábitos cotidianos (Naciones Unidas, 2015).
Respecto a lo anterior se puede denotar una falta de conciencia en las personas por lo que se
hace necesario abordar a las futuras generaciones, es decir a los niños; y proporcionarles
herramientas lúdicas que ayuden a educarlos y sensibilizarlos sobre el uso responsable del
agua con el fin de que cumplan un rol como agentes del cambio.

---

## __OBJETIVO GENERAL__

Desarrollar un juego lúdico y educativo que permita a los niños mayores de 5 años aprender a
optimizar el consumo del agua en su hogar para reducir así el impacto ambiental que el
consumo excesivo de este recurso genera.


## __OBJETIVOS ESPECÍFICOS__

- Diseñar un juego educativo que permita enseñar el uso responsable del agua en las
actividades diarias de los hogares.
- Identificar cómo impacta el juego en los niños para el cambio de hábitos sobre el
recurso hídrico.
- Promover la conciencia ambiental al usuario mediante experiencias dentro del juego.
- Diseñar la interfaz visual a través de storyboards que presente el contexto educativo.
- Desarrollar los módulos del juego utilizando estructuras de control (secuencias,
condicionales, iteraciones) y funciones.
- Realizar pruebas sobre los niveles del juego para validar la lógica de programación,
corregir posibles errores y asegurar que el mensaje sobre el ahorro del agua sea
comprensible.

---

## __ALCANCE__

Se pretende desarrollar un juego lúdico enfocado en la educación sobre sostenibilidad; más
precisamente sobre el ahorro de recursos hídricos en el diario vivir de los hogares, dirigido
principalmente a niños mayores de 5 años.
Se pretende con este juego acercar la teoría escolar con la práctica diaria en casa, con el fin
de educar sobre el uso responsable del agua, mostrando cómo pequeños cambios en sus
rutinas y las de sus familias pueden contribuir a la conservación de este recurso.
El proyecto contempla el diseño y desarrollo de este juego lúdico de carácter educativo en
computador, el cual se enfoca en el ahorro de recursos hídricos en el hogar mediante la toma
de decisiones en situaciones típicas de la vida real.
El juego se estructurará de la siguiente manera:
1. Introducción (Storyboard): Narrativa visual que presenta a “Maya” y el contexto en el
que se desenvuelve el juego.
2. Tres niveles de juego:
 - Cada nivel abre nuevos espacios en el hogar para resolver retos relacionados
con el ahorro de agua.
 - Todos los niveles se componen de un cronómetro para cumplir el objetivo
presentado en cada uno.
 - Cada nivel presenta una barra de agua que disminuye con el tiempo, ciertos
retos suman agua, y otros cuyo objetivo es impedir que el agua se agote..
3. Pantallas de carga con mensajes tipo “Sabías qué...” alusivos al consumo y el ahorro
del agua. (se presentan entre niveles)
4. Pantallas “Game Over” presentes al no completar un nivel que muestran un mundo
devastado por la falta de agua.
5. Conclusión (Storyboard): Cierre presentando como Maya ha logrado el objetivo y con
un mensaje que motive al jugador a implementar cambios en su hogar y en su rutina.
Para el funcionamiento lógico del juego se implementarán las bases de programación bajo el
lenguaje python de la siguiente manera:
 - Secuencias: Para determinar el orden lógico de las escenas, niveles, y diálogos
presentes en el juego.
 - Condicionales: Cruciales para evaluar decisiones del jugador (Por ejemplo: si el
jugador completo reto para ganar agua, la barra sume el agua ganada)
 - Iteraciones: Se usarán ciclos por ejemplo para mantener el juego activo mientras haya
agua y tiempo disponibles.
 - Funciones: Creación de bloques de código para tareas repetitivas, cómo puede ser la
actualización de los indicadores del agua ahorrada en cada nivel.

El desarrollo del juego integra un sistema de almacenamiento de información mediante
archivos planos, para registrar y guardar el progreso del jugador con el fin de que se pueda
retomar partida dónde se dejó previamente, específicamente se guardarán datos como
posición, y puntos.

Se utilizarán herramientas como Python, Gimp y Tiled.

---

## __PREGUNTA DE INVESTIGACIÓN__

¿Cómo una aplicación lúdica influye en el aprendizaje de hábitos de ahorro de agua en los
niños mayores de 5 años?

## __HIPÓTESIS__

Una aplicación lúdica y educativa influye positivamente en el aprendizaje, por parte de niños
mayores de 5 años, de hábitos de optimización de consumo de agua.

---

## __EDT__

### Aplicación lúdica y educativa: Maya ahorra agua

| Fase        | Actividades                                                                 |
|-------------|------------------------------------------------------------------------------|
| ANÁLISIS    | - Definición de requerimientos                                              |
| DISEÑO      | - Diseño de guion y storyboard<br>- Diseño de niveles<br>- Diseño de pantallas de carga<br>- Diseño de pantallas "Game Over"<br>- Diseño de estructura de archivos |
| CODIFICACIÓN| - Desarrollo de interfaz<br>- Desarrollo de niveles<br>- Desarrollo de pantallas de carga<br>- Desarrollo de pantallas "Game Over"<br>- Desarrollo de módulo de persistencia |
| PRUEBAS     | - Pruebas de funcionalidad<br>- Pruebas de datos                            |
| CIERRE      | - Documentación final<br>- Manual de usuario<br>- Sustentación              |