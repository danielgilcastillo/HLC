Instrucciones en el README.md que explican cómo ejecutar y probar el código:
 Proyecto Refactorizado con Principios SOLID

Este proyecto implementa un sistema de calefacción y termostato basado en los principios SOLID para mejorar su estructura, cohesión y flexibilidad.



Instrucciones para Clonar y Ejecutar el Proyecto

1. **Clonar el repositorio**:
   Abre la terminal y ejecuta el siguiente comando para clonar el repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
Reemplaza <URL_DEL_REPOSITORIO> con la URL real del repositorio.

Abrir el proyecto en NetBeans:

Abre NetBeans.
Ve a File > Open Project y navega hasta la carpeta donde clonaste el repositorio.
Selecciona la carpeta del proyecto y haz clic en Open Project.
Ejecutar el Proyecto:

Una vez abierto en NetBeans, haz clic derecho sobre el proyecto en el Explorador de Proyectos.
Selecciona Run o presiona Shift + F6 para ejecutar el proyecto.
El programa ejecutará la clase principal (ExamenSolidPrueba), mostrando en consola el encendido y apagado de la calefacción, además de los logs correspondientes.
Estructura del Proyecto
Este proyecto sigue una arquitectura modular, dividida en interfaces y clases según los principios SOLID. Aquí una breve descripción:

Idispositivo: Interfaz que define el estado del dispositivo.
Iiluminar: Interfaz que define métodos para encender y apagar el dispositivo.
Iguardar: Interfaz para el guardado de logs.
Calefaccion: Clase que implementa Idispositivo y gestiona el estado de encendido/apagado.
DispositivoIluminar: Clase que implementa Iiluminar para manejar el encendido/apagado del dispositivo.
DispositivoLog: Clase que implementa Iguardar y se encarga del guardado de logs.
Termostato: Clase que utiliza las interfaces para controlar el dispositivo y el guardado de logs.
Cómo Probar el Código
Para probar el funcionamiento:

Prueba básica de encendido/apagado:

Ejecuta el proyecto y verifica en la consola que al presionar el termostato, el dispositivo alterna entre encendido y apagado, y se genera un log correspondiente.
Modificar estado inicial de Calefaccion:

Abre la clase ExamenSolidPrueba.
Cambia el parámetro de Calefaccion (de true a false o viceversa) para ver cómo afecta el estado inicial.
Ampliar funcionalidad:

Crea una nueva clase que implemente Idispositivo para agregar un nuevo dispositivo.
Puedes agregar más clases que implementen Iguardar o Iiluminar para personalizar los logs o la lógica de encendido/apagado.
Este diseño modular y basado en principios SOLID permite extender el sistema sin modificar las clases existentes.

