# Refugio Felino
Se desea diseñar un diagrama de clases en UML que recoja la información de una empresa dedicada al refugio y adopción de diferentes tipos de felinos.
La información está estructurada de la siguiente manera:

- Guardaremos en la base de datos el nombre del refugio, su dirección, y su teléfono de contacto.
- En el refugio laboran dos tipos de trabajadores principalmente: los que se encargan de manejar los servicios administrativos y los cuidadores de animales, que tendrán una o varias especialidades determinadas. Además, queremos guardar el nombre, apellido, y salario de cada trabajador. 
- Hay diferentes tipos de felinos. Se dividen en dos clases: los que se podrán adoptar, es decir felinos que han sido proclamados domésticos, y los que han sido rescatados pero son salvajes y se quedan en el refugio por un tiempo indefenido.
- Cada cuidador se podrá encargar del cuidado y de la supervisión de varios felinos, y cada felino podrá ser atendido por varios cuidadores ya que habrá que alimentarlos, limpiarlos, entretenerlos, etc...
- Los felinos que estén listos para adoptar tendrán que haber pasado ciertas pruebas de seguridad. Esto lo reflejaremos con el método listoParaAdoptar. Además, necesitarán llevar un chip de localización. Se verá reflejado en el diagrama con el método tenerChip.
- Hay dos tipos de felinos domésticos: Gatos y Caracales. Guardaremos la raza de cada gato.
- Los felinos domésticos podrán ser adoptados por personas externas. Para ello, esta gente deberá pasar una rigurosa entrevista donde se mostrará que es válido para el cuidado de un felino. No cualquiera podrá adoptar. Estará reflejado con el método isValid. Guardaremos el nombre, apellido, y si ya ha sido aceptado para adoptar un animal. Un adoptante podrá adoptar varios felinos, pero un felino pertenece únicamente a un adoptante.
- Por último, guardaremos el tipo de comida de cada felino salvaje y su hábitat, es decir el sitio donde se encuentran en el refugio. No a todos los felinos salvajes les sirve el mismo tipo de alimento para estar nutridos por completo. Por ahora hay tres tipos de felinos salvajes: los tigres, los jaguares, y los guepardos.



## Solución al problema propuesto:
![image](https://user-images.githubusercontent.com/114931679/224363620-1066d3b9-9a84-4b21-b965-aebf5b67624f.png)
***Note: Cada atributo tiene sus getters y setters correspondientes, pero para no abarrotar el diagrama de clases se muestran solamente unos pocos.**

