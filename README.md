# pablo-rilo-visualizacion-y-exploracion-datos
Pablo Rilo Mariñas


Repositorio para entrega de práctica

-Realización de Dashboard de tableau con Kpi´s relacionados con los importes facturdos, nº de huéspedes, barrio y puntuación. Destinado a un perfil de
un usuario de airbnb.
  
  A.Diseño en el que he introducido dos hojas de dashboard:
      1)Uno con el contenido principal con gráficas y un pequeño mapa de Madrid conectados a través de los filtros,.
      2)Otro con el mapa ampliado y tres Kpi´s. Ambos se actualizan en base al filtro de la página principal
    Ambas interconectadas con un icono que se encuentra en la parte inferior derecha de los mapas
    
  B.Filtros. Funcionalidad en ambos dashboards:
      1)Precio/noche
      2)nº de huéspedes
      3)Barrio
      4)Fianza:1 SI/NO
      5)Puntuación
      
  C.Acciones en dashboard.
      1)Resaltar:   He realizado múltiples acciones de  para interconectar los gráficos y el mapa. 
      2)Ir a la hoja: para realizar la conexión entre el dashboard principal y el Mapa
      3)Ir a la URL: He realizado dicha acción para que los vínculos que se encuentran en las descripciones te vinculen con la supuesta página del alojamiento
      4)Filtro: He introducido un botón para resetear los filtros del dashboard principal que se ejecuta a través de esta acción
      
  D.Cálculos avanzados: He creado varios para realizar las conversiones a float de las coordenadas, y para realizar cálculos de interés 
  
  
Consideraciones: 
      1) Puesto que uno de los Kpi´s relevantes es la puntuación del alojamiento (Reviews Score Value) y existian muchos que no tenían, los he eliminado de la base de datos igual que los que no tenian valor en Price
      2) Otro Kpi con valores nulos es el del importe de la limpieza(Cleaned fee) y la fianza(Security Deposit), en este caso, aunque entiendo que no sería lo 
      correcto, dichos valores los he tomado como cero, es decir, en los que no se cobra. Puesto que la finalidad de la práctica es valorar el manejo de Tableau       consideré dicha opción
      3) No he realizado la conexión de Nveces alquilado por que está vinculada a los id de los anfitriones y no sería de gran utilidad en mi caso
