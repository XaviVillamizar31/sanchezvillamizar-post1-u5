## Gestión de Tareas con Servlet
Programación Web — Unidad 5: Fundamentos de Java Web (Servlets y JSP)
Universidad Internacional de Santander (UDES) — Ingeniería de Sistemas 2026

## Descripción
Aplicación web mínima para gestionar una lista de tareas en memoria. Implementa un Servlet funcional que procesa peticiones HTTP GET y POST, gestiona parámetros de formularios HTML, aplica validación en el servidor y transfiere datos a una vista JSP mediante RequestDispatcher, siguiendo el patrón Post/Redirect/Get.

## Prerrequisitos
Java Development Kit (JDK) 17 o superior
Apache Tomcat 10.x
IntelliJ IDEA
Maven 3.8+
Navegador web moderno (Chrome, Firefox) con DevTools


## Instrucciones de ejecución
Clonar el repositorio y abrir en IntelliJ
Ejecutar mvn clean package en la terminal
Configurar Tomcat: Run → Edit Configurations → + → Tomcat Server → Local
En Deployment agregar el artefacto .war exploded
Ejecutar y abrir http://localhost:8080/gestion-tareas/tareas

## Capturas de Pantalla
Sin conexion a ServLet
<img width="1912" height="914" alt="1" src="https://github.com/user-attachments/assets/0df3f2d1-aa31-45f2-b5fa-47f21b053134" />
Ventana de la Lista de Tareas
<img width="1912" height="914" alt="2" src="https://github.com/user-attachments/assets/d085c5ba-d050-4be2-b364-5f3dc2461d95" />
Agregar Tarea
<img width="1912" height="914" alt="3" src="https://github.com/user-attachments/assets/428c20da-a29f-4161-bb16-4f722e4ce8af" />
Eliminar Tarea
<img width="1912" height="914" alt="4" src="https://github.com/user-attachments/assets/a0fdb3d7-ce60-46d0-a5cc-4c3ebc4a0bcd" />
