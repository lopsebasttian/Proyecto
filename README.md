# Proyecto EDD #1

Grafos:
Requerimientos funcionales
1.  General
      Cargar archivo: El usuario puede seleccionar a través de JFileChooser un archivo txt (archivo de texto plano) para ser cargado en el sistema, el cual contará con la información necesaria para la creación del grafo,  es decir: usuarios y relaciones de amistad. Cuando el usuario cargue un nuevo archivo, el sistema debe enviar un mensaje de alerta indicando al usuario la necesidad de guardar los datos actualmente cargados en memoria. La estructura del archivo de datos (archivo de texto plano) se indicará posteriormente. 
     
      Actualizar repositorio:  Esta función permitirá que la información cargada en memoria, referente a los usuarios y sus relaciones de amistad. Es decir, los cambios realizados a cualquiera de estos deben de actualizarse en el archivo texto de tal forma que cuando se vuelva a cargar ese archivo contenga  todos los cambios realizados. Al iniciarse el programa por primera vez debe cargarse el archivo de texto dado al final del enunciado (debe de mantener el mismo formato).
      
      Mostrar grafo: El sistema deberá mostrar una representación visual del grafo según la información contenida en la memoria, es decir, las relaciones entre los usuarios y su información. Si existen islas, entonces deberá mostrar tales islas de manera gráfica, mostrando los valores de los nodos  y de los arcos.
      
      Mostrar la cantidad de Islas: que se obtendrá mediante el recorrido en anchura (BFS) o el recorrido de profundidad (DFS). El usuario podrá seleccionar entre los dos métodos. 
      
      Identificación de puentes: un arco es un puente si al ser removido del grafo original, aumenta la cantidad de componentes (islas) desconectados. Esta función debe indicar en pantalla una lista de los puentes presentes en el grafo general. En el caso que nos atañe, Esta funcionalidad equivale a identificar a aquellos usuarios que son enlaces entre subgrupos o subcomunidades.
      
      Modificar grafo:  el usuario podrá seleccionar usuarios para ser eliminados. De igual forma, el usuario podrá agregar un nuevo usuario, indicando la relación que tenga con otros usuarios dentro del grafo.
      
      Requerimientos técnicos
      
      La solución debe ser implementada con base en un grafo, que a su vez puede ser implementado mediante una matriz de adyacencia o una lista de adyacencia.
      
      Puede utilizar cualquier otra estructura auxiliar de ser necesario. Sin embargo, NO podrá utilizar librerías para la implementación del tipo de dato abstracto, solo podrá utilizar librerías para lo relativo a la representación gráfica del grafo.
      
      El programa debe poder representar el grafo correspondiente de manera gráfica. 
      
      La aplicación debe ofrecer una interfaz gráfica al usuario.
      
      El programa debe poder cargar un archivo de texto para la lectura de datos. Para ello, es requerido el uso del componente JFileChooser.
      
      Debe documentar el proyecto con Javadoc.
      
      Junto al programa, cada equipo deberá presentar un Diagrama de clases (arquitectura detallada) que explique la solución obtenida.  
      
      La estructura de los archivos es la siguiente: para la sección de los usuarios, el primer campo es el ID, el segundo es el usuario. Para la sección de relaciones (de amistad), los campos son usuario1, usuario2, tiempo de amistad. El grafo no es dirigido
