Lista de ideas y/o apuntes generales de cosas a mejorar
=======================================================

* Cambiar INSTRUCCIONES por letra en todos los repartidos menos en el 1 (newrep1)

* De ahora en más **pueden** modificar el código fuera de los límites, pero avisamos que para la corrección **todo lo que está afuera se descarta**.

(Tal vez:
* Agregar el uso de "nombres de usuario/emails" en la función `evaluar`. Ej:

    username <- function() {
      cat("Ingrese su nombre de usuario por favor: ")
      usname <- readLines(n = 1)
      cat("Ingrese su password: ")
      pw <- readLines(n = 1)
      cat("Ingrese su e-mail: ")
      email <- readLines(n = 1)
      list(username = usname, password = pw, email = email)
    }
)

* *Aclarar desde el principio que el sistema de corrección puede necesitar fixes*!!!!!!.

* Agregar ejercicios en funciones, más simples y más diversos:
  - cambiar última y primer fila de una matriz;
  - ordenar una matriz según los valores de cualquier columna, según número o nombre.

* Ejercicio de programación:
  - for: hacer un script que cuente por fila de una matriz la cantidad de elementos que cumplan una condición (mayores que 0, por ejemplo)

* Cambiar parte d del útimo parcial: si el bus tiene el máximo de pasajeros no sube a más nadie y si tiene el mínimo (0) no baja nadie.

* Poner lugar para que pongan el nombre en los parciales o cualquier script de ejercicios...

* > As someone said, if you want to understand something, explain it to another person, but if you really want to understand it, explain it to a computer.  ("Si quieres entender algo, explícaselo a otra persona, pero si realmente quieres entenderlo, explícaselo a una computadora.")

* Agregar la función "stack" en la parte de manipulación de datos.

* [Para la idea del paquete imser, aprovechar que ahora .Rprofile y .Renviron funcionan en windows! (tienen que ir en ~)(ver: http://www.biostat.wisc.edu/~kbroman/Rintro/). De esta forma se puede agregar fácilmente un path determinado (o cambiarlo cuando sea necesario) para la carpeta del curso.]

* En ejercicio 6 del cuestionario 6.2 (el de los gatos) y en general en ese tipo de ejercicio (relleno), utilizar errores más comunes del 2012 para anticipar respuestas equivocadas y dar un feedback!

* Mensajes de error: cambiar "no es el valor correcto" por "no es el valor esperado", en todos los casos que esto aplique.

* INSISTIR MUCHO, POR EJEMPLO EN LA LETRA DE REPARTIDOS, CON LO DE LAS SOLUCIONES GENÉRICAS!!! (SOBRE TODO EN EL REP 1)
  El año que viene debería haber una lección "cómo hacer el repartido"!!

* Recomendar que tengan una configuración de teclado fácil (que los símbolos que se ven en las teclas son los que se escriben en la consola). Esto se puede agregar en alguno de los documentos de guía del curso.

* También estaría bueno unificar todos los documentos de guía.

* Foro: decirles que escriban el código en el foro, pero que después lo borren si está la duda solucionada.

* Unificar todos los documentos en 1!

* Lista de estándares:

  - mensajes de aviso o error deben empezar con minúscula y sin espacios al principio. si son de warning debe indicar el número de ejercicio ("ej. 1.a: se detectó un problema con ...").
  - los archivos de los ejercicios deben empezar con el número de ejercicio: 1.a-aprobados.R

* Aclarar mejor el uso de is.na, is.null e is.nan

* Aclarar en las letras de los repartidos que muchas cosas que se piden son para que funcione bien la correción automática. Esto sobre todo con el repartido 1. Se agregaría al video y la lección que se va a hacer (mejorar) para repartidos.

* Mejorar corrección del 1.b del repartido 4: http://imser2013.ribbot.com/posts/51b0ecac203f03000200065d

* Aclarar que en los videos no va a estar todo para que resuelvan los repartidos; tienen que indagar en la ayuda u otras fuentes (foros, google, etc)

* Diversificar las aplicaciones de los repartidos (ej: ejemplos relativos a sociología; se puede preguntar a exestudiantes a ver si se quieren colaborar elaborando problemas nuevos).

### Unidad 5

* Agregar en la unidad 5 (funciones) cuestionarios más parecidos a los de la unidad 6 (aquellos en los que hay que agregar errores, fill in the blanks, etc).

* Chequear que en ejercicios anteriores el estudiante haya hecho bien las funciones para usar sus versiones en los subsiguientes (ej: funciones filtroc y aplicar en 2.c).

* Nuevo ejercicio: 2.d "gráficos personalizados". Ver los archivos tmp.Rmd y 2.d-plot.edu.R

### Unidad 6

* Ejercicio 2.a del repartido... ver http://imser2013.ribbot.com/posts/51d334917b0a57000200067b

Para el final del curso
-----------------------

* Hacer una encuesta a parte de la evaluatoria final con las siguientes consultas y afines:
	- ud. le gustaria que el curso dure menos tiempo ?
	- ud. considera que hubiera podido realizar los modulos en una semana ?
	- ud. considera que si le dan dos semanas por modulo pero es capaz de realizarlo en una, utilizaría igualmetne las dos semanas?


Nuevo Repartido I:
==================

- No tendrá nota. Es decir, no se usará esa nota en el cálculo de la nota final.
- Será más un tutorial que un repartido.
- Tendrá las soluciones en escrito y en video. El video será además una demostración de cómo usar la interfaz de RStudio (es redundante con la lección 1.2?).
- Los ejercicios existentes del repartido I los repartimos entre el nuevo repartido I y el repartido II (o incluso otros?).

