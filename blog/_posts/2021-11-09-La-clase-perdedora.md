---
titulo: "La clase perdedora"
---




# {{page.titulo}}

<!-->
# {{page.chuchu}}

{% for x in page.frutas %}
1. Me gusta mucho comer {{ x }}

{% endfor %}

<!-- {{ site.data.authors }}-->

<!-->
<table>
  {% for row in site.data.authors %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}
  
   {% tablerow pair in row %}
      {{ pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>


La respuesta a cuanto vale chuchu  {{ page.chuchu }}

{% if page.esmartes %}
## Aún quedan 3 dias

{% else %}
 ## Bueno ya queda menos

{% endif %} -->

# La clase perdedora
## José Luis Barbería 07/04/2009. El País


**Los alumnos de padres sin estudios tienen 20 veces más riesgo de fracaso**


**La educación no consigue eliminar las diferencias sociales**



Imaginemos el sistema educativo como una larga de carrera de obstáculos. Lo primero que salta a la vista es el alto grado de abandonos prematuros y de participantes descalificados por no haber cubierto la distancia mínima en el plazo establecido. Lo segundo que llama la atención es la extracción social de los que se quedan por el camino, ya en los primeros tramos, y cargan con los sambenitos estigmatizadores del "fracasado escolar" y de "repetidor". Quítese de la cabeza la convicción de que la escuela es, por excelencia, el espacio natural de la igualdad de oportunidades que consagra la Constitución. Hágase a la idea de que, pese a los buenos propósitos, el éxito académico no depende exclusivamente del esfuerzo y de la capacidad personal de su hijo.



La calidad de los centros privados se apoya en la selección de los estudiantes El 68% de jóvenes estudia bachillerato o FP; la media en la OCDE es del 81%
¿Cómo se explica, si no, que los perdedores pertenezcan de forma tan abrumadoramente mayoritaria a las familias de rentas más bajas? Por muchos casos de hermanos con rendimientos académicos dispares que se den, el análisis del problema establece que no estamos ante cuestiones personales. No es cierto que los alumnos partan de la línea de salida en condiciones idénticas y con competencias similares. Las diferencias están ya presentes en el kilómetro cero porque a la hora de matricularles por primera vez ya hay niños a los que se les ha inculcado el amor por la lectura y el conocimiento y otros a los que no. Por lo mismo, hay padres que acompañarán los estudios de sus hijos y velarán para que adquieran la mejor formación y otros que se inhibirán de esa tarea.



España partía hace sólo tres décadas de una situación muy alejada de los países desarrollados, también educativamente hablando, pero ha conseguido en ese tiempo ampliar la escolarización obligatoria hasta los 16 años, con uno de los sistemas educativos más equitativos de la OCDE, según el Informe Pisa -que evalúa el nivel de conocimientos de los jóvenes de 15 años de 55 países del mundo. El informe dice que si se eliminan los condicionantes socioeconómicos y culturales de los alumnos, las escuelas españolas públicas, privadas y concertadas dan unos resultados muy similares entre sí. Sin embargo, ese contexto sigue pesando enormemente. Los hijos de los trabajadores no cualificados tienen 4,5 veces menos de probabilidades de acceder al ámbito universitario que los vástagos de los profesionales de alto nivel. Sólo un tercio de los de familias obreras o de asalariados del campo cursará el Bachillerato y de ellos únicamente la mitad llegará a la universidad. Si usted no tiene estudios, le conviene saber que su chico cuenta con 20 veces más de posibilidades de incurrir en el fracaso escolar que el hijo de padres universitarios; exactamente, el 40% contra el 2%, según el estudio recientemente publicado por el profesor de Sociología de la Universidad de La Laguna, José Saturnino Martínez. 



