# LAB-Observatorio-del-Reloj-de-Sol

**In englesh:**
WebVerse Sundial Observatory LAB


**Context:**
The Sundial Observatory has been meeting on the second Saturday of every month since 1987 in a converted former park ranger station located on the Cascade Plateau. Pavel, a retired aerospace technician, manages the website from his garage. He is bothered by leaks, yet he believes—on principle—that politely asking search engines not to index the page is equivalent to keeping it private.

**Vulnerability:**

This challenge primarily involves an information disclosure vulnerability.


1. Start the LAB and access the vulnerable website.

![Screenshot 1](VirtualBox_kali-linux-2025.4-virtualbox-amd64_07_09_2026_21_06_35.png)

(Before proceeding, let's clarify something.
What is robots.txt?
It is a text file that hides certain folders from search engine bots, although it is mostly used to protect sensitive folders—for example, /Panel-Admin/.)

2. On the webpage, append the following path to the URL after the forward slash: `robots.txt`

![Screenshot 2](Captura%20de%20pantalla%202026-09-07%20205641.png)

3. In this text file, we can see multiple folder paths; for this LAB, the solution lies in the first path (though when analyzing potential vulnerabilities, it is best to investigate all possible folders in detail).

4. Access the path, scroll down, and there is our flag.

![Screenshot 3](Captura%20de%20pantalla%202026-09-07%20205708.png)



**En español:**

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

