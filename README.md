# UTN-TUPaD-OE-TPI-N4
#### ORGANIZACIÓN EMPRESARIAL | TRABAJO PRÁCTICO INTEGRADOR N°4

##### TITULO: PROCESOS, TRABAJO COLABORATIVO Y CONTROL INTEGRADOR
##### ALUMNO: JOAQUÍN IGNACIO GONZÁLEZ

Descripción: En esta cuarta entrega realizo el diagrama BPMN correspondiente al proceso 
de Samsung HEMS (Home Energy Management System), un módulo de software que mediante análisis
de inteligencia artificial puede optimizar y reducir el consumo eléctrico de dispositivos del hogar
integrados en el ecosistema de SmartThings.

Declaración de uso de IA: 
Prompt exacto en Google Gemini (usé el prompt en una conversación que ya habia usado para investigar sobre HEMS): 
"Siguiendo con el modulo HEMS de Samsung: debo modelar un diagrama de procesos de negocio del software mencionado.  Utiliza la notacion estandar BPMN, estructurado en pools y lanes, y contemplando compuertas lógicas de decision."

La IA me dió una lista con las tareas indicando las pools y lanes correspondientes, por ese lado no tuve que corregir.
Lo que si corregí  y agregué, es que en el Lane de motor HEMS agregaba dos compuertas seguidas, una exclusiva y una paralela,
la exclusiva estaba bien, por que indicaba si el limite de energia era superado, pero la compuerta paralela no era necesaria,
en lugar de eso establecí dos tareas conectadas por lineas normales siguiendo el flujo del diagrama. Además agregué un Final
en una de las salidas de la compuerta exclusiva, que en caso de que el límite de energía no sea superado, el sistema solo deberá actualizar los gráficos en la aplicación de SmartThings y termine el proceso de manera normal.

NOTA: La revisión del PR fué realizada por el propio autor por tratarse de un trabajo individual, los comentarios y correcciones quedan documentados en el PR.