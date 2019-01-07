# OS.imulation
Trabajo de simulación de un sistema operativo básico... muy básico.
  Usando la programacion orientada a objetos, se intentará replicar/simular el comportamiento de un "kernel" básico, sin incluir la detección de hardware o software, pareciendose a un gestor de tareas/procesos y de archivos, con sus permisos, tamaños y ubicaciones en la memoria, junto a las acciones de manejo fundamentales para la memoria. 

Específicamente el programa contará con:
  -Gestor de procesos (CPU).
  -Gestor de memoria principal (RAM).
  -Gestor de almacenamiento secundario (HDD).
  -Sistema de Archivos.
  
El programa NO contará con:
  -Sistema de Entrada y Salida.
  -Sistema de proteccion.
  -Sistema de comunicaciones.
  -Programas del sistema.
  -Gestor de recursos (Porque no habra ninguno más que la memoria).
  
El gestor de procesos podrá:
  -Crear y destruir procesos.
  -Parar y reanudar procesos.
  
El gestor de memoria principal podrá:
  -Conocer y mostrar qué partes de la memoria están siendo utilizadas y por quién.
  -Decidir qué procesos se cargarán en memoria cuando haya espacio disponible.
  -Asignar y reclamar espacio de memoria cuando sea necesario.

El gestor de memoria secundario podrá:
  -Planificar los discos.
  -Gestionar el espacio libre.
  -Asignar el almacenamiento.
  -Verificar que los datos se guarden en orden.
  
El sistema de Archivos podrá:
  -Construir, eliminar archivos y directorios.
  -Ofrecer funciones para manipular archivos y directorios.
  -Establecer la correspondencia entre archivos y unidades de almacenamiento.

  Idealmente cada una de estas partes del sistema deberian trabajar conjuntamente, pero posiblemente haya inconvenientes que serán documentados dentro del código de cada programa. Se usara el compilador de DevC++ versión 5.11 y el lenguaje C++.
  
  Se colocará en un archivo xml y un diagrama de clases la conceptualización o abstracción de los objetos necesarios para el programa, a su vez se encontrarán todas las versiones (mejoras) del programa.
