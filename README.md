# OS.imulation
<div align="center">Trabajo de simulación de un sistema operativo básico... muy básico.</div><br/>
  Usando la programacion orientada a objetos, se intentará replicar/simular el comportamiento de un "kernel" básico, sin incluir la detección de hardware o software, pareciendose a un gestor de tareas/procesos y de archivos, con sus permisos, tamaños y ubicaciones en la memoria, junto a las acciones de manejo fundamentales para la memoria.
<br/>
Específicamente el programa contará con:<br/>
  -Gestor de procesos (CPU).<br/>
  -Gestor de memoria principal (RAM).<br/>
  -Gestor de almacenamiento secundario (HDD).<br/>
  -Sistema de Archivos.<br/>
  
El programa NO contará con:<br/>
  -Sistema de Entrada y Salida.<br/>
  -Sistema de proteccion.<br/>
  -Sistema de comunicaciones.<br/>
  -Programas del sistema.<br/>
  -Gestor de recursos (Porque no habra ninguno más que la memoria).<br/>
  
El gestor de procesos podrá:<br/>
  -Crear y destruir procesos.<br/>
  -Parar y reanudar procesos.<br/>
  
El gestor de memoria principal podrá:<br/>
  -Conocer y mostrar qué partes de la memoria están siendo utilizadas y por quién.<br/>
  -Decidir qué procesos se cargarán en memoria cuando haya espacio disponible.<br/>
  -Asignar y reclamar espacio de memoria cuando sea necesario.<br/>

El gestor de memoria secundario podrá:<br/>
  -Planificar los discos.<br/>
  -Gestionar el espacio libre.<br/>
  -Asignar el almacenamiento.<br/>
  -Verificar que los datos se guarden en orden.<br/>
  
El sistema de Archivos podrá:<br/>
  -Construir, eliminar archivos y directorios.<br/>
  -Ofrecer funciones para manipular archivos y directorios.<br/>
  -Establecer la correspondencia entre archivos y unidades de almacenamiento.<br/>

  Idealmente cada una de estas partes del sistema deberian trabajar conjuntamente, pero posiblemente haya inconvenientes que serán documentados dentro del código de cada programa. Se usara el compilador de DevC++ versión 5.11 y el lenguaje C++.
  
  Se colocará en un archivo xml y un diagrama de clases la conceptualización o abstracción de los objetos necesarios para el programa, a su vez se encontrarán todas las versiones (mejoras) del programa.
