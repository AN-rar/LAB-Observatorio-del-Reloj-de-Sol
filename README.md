# LAB-Observatorio-del-Reloj-de-Sol
LAB-Observatorio del Reloj de Sol de WebVerse


**Contexto:**
El Observatorio del Reloj de Sol se reúne el segundo sábado de cada mes desde 1987 en una antigua estación de guardaparques reconvertida, situada sobre la meseta de Cascade.Pavel, un técnico aeroespacial jubilado, gestiona la página web desde su garaje. Le molestan las filtraciones, pero cree, por principio, que pedir amablemente a los motores de búsqueda que no indexen la página es lo mismo que mantenerla privada.

**Vulnerabilidad:**

Este desafío es principalmente una vulnerabilidad de divulgación de información.


1.iniciamos el LAB y accedemos a la web vulnerable

![Captura de pantalla 1](VirtualBox_kali-linux-2025.4-virtualbox-amd64_07_09_2026_21_06_35.png)

(Antes de seguir aclaremos algo.
¿Que es robots.txt?
Es archivo en formato de texto que oculta ciertas carpetas a los robots de busquedas, aun que mayormente se usa para guardar carpetas sencibles ejemplo /Pnale-Admin/)

2.dentro de la pagina en la URL seguido del / ponemos la siguiente ruta: robots.txt

![Captura de pantalla 2](Captura%20de%20pantalla%202026-09-07%20205641.png)

3. en esta archivo de texto podemos ver multiples rutas  de carpetas en este LAB la solucion esta en la primera ruta (En el analizis de posibles vulnerabilidades es mejor investigar todas las carpetas posibles y a detalle)

4. Accedemos a la ruta hacemos scroll hacia bajo y ahi esta nuestra bandera

![Captura de pantalla 3](Captura%20de%20pantalla%202026-09-07%20205708.png)

