# DeberPilaresLascano
4 PILARES DE LA PROGRAMACIÓN ORIENTADA A OBJETOS
Lascano Aldahir

ABASTRACCIÓN:
El término hace referencia a la acción de simplificar y representar entidades complejas a través de la identificación de características fundamentales y la eliminación de detalles que no son relevantes.
Ejemplo
![image](https://github.com/LascanoAldahir/DeberPilaresLascano/assets/139184732/47c900a0-8ca1-4938-8761-8e97a5e09b07)
En la representación de formas geométricas se emplea la abstracción. La clase Forma es abstracta y posee un método llamado calcularArea(), el cual no cuenta con una implementación específica en la clase base. La clase Circulo, que es una clase concreta, hereda de Forma y se encarga de proporcionar una implementación precisa para calcular el área de un círculo.

ENCAPSULAMIENTO
La encapsulación consiste en esconder los detalles internos de un objeto y ofrecer una forma controlada de acceder y modificar sus datos. Esto se logra mediante el uso de modificadores de acceso y métodos para interactuar con los datos del objeto.
Ejemplo
![image](https://github.com/LascanoAldahir/DeberPilaresLascano/assets/139184732/7d490b8c-d860-4c39-98c1-4b6d618966bd)
![image](https://github.com/LascanoAldahir/DeberPilaresLascano/assets/139184732/fa5ec3aa-eddf-40b4-b487-b33b67fa1ebe)

En este caso de muestra, la información de nombre y edad se encuentra protegida por medio de variables privadas dentro de la clase Persona. Para poder acceder a dicha información desde fuera de la clase, se han creado los métodos getNombre() y getEdad(), los cuales permiten un acceso controlado a los datos.

HERENCIA
La herencia posibilita la adquisición de propiedades y métodos de una clase previa, lo que facilita la reutilización de código y establece una estructura jerárquica entre las clases.
EJEMPLO:
![image](https://github.com/LascanoAldahir/DeberPilaresLascano/assets/139184732/543b4165-5bbe-4485-b09e-a900a27b1c46)
![image](https://github.com/LascanoAldahir/DeberPilaresLascano/assets/139184732/1603bba0-90b6-4cb2-aef1-3d4beb31ca19)
En este caso, la clase Coche adquiere los atributos y métodos de la clase Vehiculo, de la cual hereda, y los utiliza para exponer información detallada sobre el coche, como su marca y la cantidad de puertas que tiene.

Polimorfismo
La programación orientada a objetos permite que objetos de distintas clases puedan ser considerados como si fueran de una misma clase gracias a la implementación de interfaces y métodos compartidos. Esto se logra mediante la herencia y la definición de interfaces.
EJEMPLO
![image](https://github.com/LascanoAldahir/DeberPilaresLascano/assets/139184732/ab579797-9e9b-4cf1-8506-745612d9bc50)
![image](https://github.com/LascanoAldahir/DeberPilaresLascano/assets/139184732/161ae9bf-d0cc-4c2a-bc7e-67cd170d6ddb)

En este ejemplo se trata a diversas subclases como si fuesen objetos de la clase base, lo que permite manipular y procesar de manera más sencilla distintos tipos de objetos.








