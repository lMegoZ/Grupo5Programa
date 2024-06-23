#             PROYECTO BIBLIOTECA         #

Este proyecto es una aplicación de consola en Java que permite gestionar una biblioteca de personas, libros y juegos. La aplicación ofrece funcionalidades para agregar, eliminar, editar, listar y buscar elementos en cada categoría.

---------------------------------------
# ESTRUCTURA DEL PROYECTO #
------------------------------------------

1. **vistacontrol**
   - **Index**: Clase principal que contiene el menú principal y el método main.
   - **IndexJuegos**: Clase que gestiona la biblioteca de juegos.

2. **utils**
   - **Lectura**: Clase que facilita la lectura de entradas desde la consola.
   - **Utilidades**: Clase que contiene métodos de utilidad utilizados en todo el proyecto.

--------------------------
# DETALLE DE CLASES #
----------------------------

### vistacontrol.Index ###
- **Descripción**: Clase principal del proyecto. Gestiona el menú principal y las opciones seleccionadas por el usuario.
- **Métodos**:
  - `menu()`: Muestra el menú principal.
  - `inicio()`: Controla el flujo del programa basado en la opción seleccionada.
  - `main(String[] args)`: Método principal para ejecutar la aplicación.

### vistacontrol.IndexJuegos ###
- **Descripción**: Clase encargada de gestionar la biblioteca de juegos.
- **Métodos**:
  - `juegosPrecargados()`: Pre-carga juegos en la biblioteca.
  - `agregar()`: Permite agregar un nuevo juego a la biblioteca.
  - `eliminar()`: Elimina un juego existente de la biblioteca.
  - `editar()`: Edita los detalles de un juego existente.
  - `listar()`: Lista todos los juegos en la biblioteca.
  - `buscar()`: Busca juegos en la biblioteca.
  - `menu()`: Muestra el menú de opciones para gestionar juegos.
  - `inicio()`: Controla el flujo de la gestión de juegos.

### utils.Lectura ###
- **Descripción**: Clase que facilita la lectura de entradas desde la consola.
- **Métodos**:
  - `cadena(String texto)`: Lee una cadena de texto.
  - `cadenaMayusculas(String texto)`: Lee una cadena y la convierte a mayúsculas.
  - `cadenaMinusculas(String texto)`: Lee una cadena y la convierte a minúsculas.
  - `enteroEnCadena(String texto)`: Lee una cadena de texto que representa un entero.
  - `enteroEnCadena(String texto, int digitos)`: Lee una cadena de texto que representa un entero con una longitud especificada.
  - `entero(String texto)`: Lee un número entero.
  - `decimal(String texto)`: Lee un número decimal.
  - `letra(String texto)`: Lee un carácter.
  - `cerrarLectura()`: Cierra el scanner.

### utils.Utilidades ###
- **Descripción**: Clase que contiene métodos de utilidad utilizados en todo el proyecto.
- **Métodos**:
  - `salir()`: Muestra un mensaje de despedida.
  - `volver()`: Muestra un mensaje de retorno al menú principal.
  - `lineasEnBlanco()`: Imprime líneas en blanco.
  - `lineasEnBlanco(int cantidad)`: Imprime una cantidad específica de líneas en blanco.
  - `error(int tipo)`: Muestra un mensaje de error basado en el tipo.
  - `lineaSeparatoria()`: Imprime una línea separatoria.
  - `lineaSeparatoria(int cantidad)`: Imprime una cantidad específica de líneas separatorias.
  - `formatear(String cadena, int max)`: Formatea una cadena de texto a una longitud máxima.
  - `listarArreglo(String[] arreglo, String loQueEs)`: Lista los elementos de un arreglo.
  - `numeroMes(int num)`: Devuelve el nombre del mes correspondiente a un número.
  - `seleccionarDeArreglo(String[] arreglo, String loQueEs)`: Menú de selección de un arreglo.
  - `tiene(String cadena, String[] arreglo)`: Verifica si un arreglo de cadenas contiene una cadena específica.
  - `tiene(int entero, int[] arreglo)`: Verifica si un arreglo de enteros contiene un entero específico.
  - `tiene(double decimal, double[] arreglo)`: Verifica si un arreglo de decimales contiene un decimal específico.
  - `buscarIndices(String[] arreglo, String texto)`: Busca los índices de un texto en un arreglo de cadenas.

XD
!1
