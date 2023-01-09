para instalar el backend es npm install y para correrlo es npm 
start
Examen de PATRONES DE DISEÑO 
Problema 1: Un cliente requiere utilizar sendgrid para envíos de email, pero otro cliente
requiere enviarlos por mandril. Se quiere evitar el uso de IF, y realizar un diseño en donde
podamos utilizar más servicios en caso de que un cliente requiera alguno en específico ¿Qué
patrón de diseño utilizarías y por qué?
Opción 1: Strategy
Opción 2: Factory Method
Opción 3: Adapter

Usaría un adaptador  ya que adapta código existente dentro de una nueva interface, y asi hacer que la comunicación de las interfarces se pueda hacer uso de ello sin ningún problema



Problema 2: Explica en tus propias palabras la diferencia entre Factory Method y Abstract
Factory. Y proporciona un caso de uso.
En las dos se definen por clases abstractas en lo que se diferencian son en que la abstracta define un método para llegar ala clase base y en el otro se define  un conjunto de métodos relacionados entre si en la cual el método abstracto se puede crear sin especificaciones de las implementaciones concretas en método se debe crear subclases para la implementación del método

Casos de uso abtrac método
 Crear un objeto que tiene muchas dependencias o configuración que debe hacerse al inicializarlo, o en donde hay diferentes formas o algoritmos para crear le objeto
Factory método
 Crear un objeto que tiene muchas dependencias o configuración que debe hacerse al inicializarlo, o en donde hay diferentes formas o algoritmos para crear le objeto






