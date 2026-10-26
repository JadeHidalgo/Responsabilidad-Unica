# Responsabilidad-Unica
En este proyecto, las responsabilidades se distribuyen entre dos clases: Libro y Guardar.
La clase Libro se encarga de representar los datos de un libro, como su título y su autor. Su responsabilidad es administrar esa información mediante sus atributos, getters y setters.
Por otro lado, la clase Guardar se encarga de la persistencia del libro, es decir, de gestionar la operación relacionada con su almacenamiento. De esta manera, cada clase tiene una función específica y puede modificarse de forma independiente cuando sea necesario.
En el archivo main.cpp se observa esta separación cuando se crea un objeto de tipo Libro, se establece su título y autor y, posteriormente, se pasa ese objeto al método GuardarLibro() de la clase Guardar.
Así, la clase Libro no necesita conocer los detalles de cómo se almacena su información, mientras que la clase Guardar utiliza los datos del libro sin encargarse de administrarlos directamente.
