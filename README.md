# imagen de la interfaz de menús
![image](https://github.com/MariaGisselie/ProyectoMenu/assets/169214799/c3c5c5d0-9576-4a69-bb49-a1674acb0caa)

# Menú Editar
![image](https://github.com/MariaGisselie/ProyectoMenu/assets/169214799/d6faf0d6-815e-4e1a-a5d5-e8c021369981)

# Menú Ayuda  
![image](https://github.com/MariaGisselie/ProyectoMenu/assets/169214799/916dafdc-7a56-48d7-b8f0-c1176ac1e683)

# Establecer en acción
El método setOnAction se utiliza para adjuntar un controlador de acciones a un control en JavaFX. Cuando se activa el control (por ejemplo, se hace clic en un botón), se invoca el controlador de acciones, lo que le permite ejecutar código personalizado en respuesta a la interacción del usuario.
        nuevoMenuItem.setOnAction(event -> System.out.println("Nuevo archivo creado"));
        abrirMenuItem.setOnAction(event -> System.out.println("Abrir archivo"));
        guardarMenuItem.setOnAction(event -> System.out.println("Guardar archivo"));
        cortarMenuItem.setOnAction(event -> System.out.println("Cortar texto"));
        copiarMenuItem.setOnAction(event -> System.out.println("Copiar texto"));
        pegarMenuItem.setOnAction(event -> System.out.println("Pegar texto"));
        salirMenuItem.setOnAction(event -> System.exit(0));
        acercaDeMenuItem.setOnAction(event -> mostrarAcercaDe());
# Imagen de Ejecución del menu acerca de...
![image](https://github.com/MariaGisselie/ProyectoMenu/assets/169214799/a851bb3c-1396-4d7a-b37d-b3f95309a44b)



