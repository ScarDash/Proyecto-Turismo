# Sistema gestor de guía turística
Es una plataforma digital diseñada para planificar, coordinar y automatizar los recursos, reservas, equipos y contenidos de una actividad o destino turístico especificamente para un jefe  presidente de transporte que utiliza este sistema para configurar el tipo de transporte,  terminales, horario de salida, horario de termino , destinos, cantidad de destinos en ruta. 

Asegurandose que los 4 horarios generados no  colisionen entre dos grupos de turistas en el mismo destino para evitar que dos grupos distintos no se encuentren en el mismo destino.



# Requerimientos:
A diferencia de una página html convencional  donde hacer click en un boton lleva a diferentes ventanas se usaran ventanas SPAS Single Page Application, o Aplicación de Página Única es una aplicación o sitio web que carga una sola página HTML inicial y va actualizando su contenido de manera dinámica a medida que el usuario interactúa con ella, sin necesidad de recargar la página completa del navegador.

Habran dos SPA en el proyecto 
SPA principal: Panel principal del sistema  en ella se buscara información de la base de conocimientos

categoria 1: Guias
              turistas asignado a cada guia 

categoria 2: Destinos
             Generar ruta turistica (reglas de estancia de 50 minutos por lugar , asignar ruta a guia, maximo 4 destinos,numero maximo de turistas)
             turista que ha visitado mas el destino

categoria 3: Mas informacion  
             lleva a segundo Spa (autores del sistema , ayuda acerca de (ventana modal)
             ver estadisticas (abre una ventana modal)
             cambio de tema ( guardar configuración en un Json)

# RESTRICCIONES

- [x] No utilizar librerias 
- [ ] Utilizar version php 8.2 
- [ ]

## Lista Tareas Del Proyecto
- [x] Configurar el repositorio inicial
- [ ] Crear la base de datos
- [ ] Diseñar la interfaz de usuario



