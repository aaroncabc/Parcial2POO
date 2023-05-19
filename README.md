# Parcial 2 POO
Programación Orientada a Objetos – 2023-10 Departamento de Ingeniería de Sistemas y Computación - Universidad del Norte

# TrashCity - Sistema de Administración de Residuos

TrashCity es un sistema de información desarrollado para la empresa de manejo de residuos "TrashCity" con el objetivo de administrar su operación. El sistema permite gestionar la recolección de residuos, asignar camiones y turnos, realizar seguimiento de rutas y almacenar información sobre la carga recolectada.

## Características

El sistema TrashCity cuenta con las siguientes características principales:

### Gestión de Empleados

El sistema permite contratar y despedir empleados encargados de la recolección de residuos. Cada empleado tiene un identificador único, nombre, número de teléfono y dirección.

### Gestión de Camiones

Se pueden agregar y eliminar camiones del sistema. Cada camión está asociado a una ruta específica y cuenta con un conductor y un equipo de asistentes de recolección.

### Gestión de Rutas

El sistema permite definir rutas de recolección para los camiones. Cada ruta está compuesta por una serie de puntos geográficos que determinan el recorrido del camión.

### Realización de Turnos

Se pueden programar turnos para los camiones, definiendo la fecha y hora de inicio y finalización. Durante el turno, se registra la localización geográfica del camión en cada punto de la ruta.

### Clasificación de Carga

Al finalizar un turno, la carga recolectada por el camión se clasifica en un centro de acopio. Se registra la cantidad de toneladas de vidrio, papel, plástico, metal y residuos orgánicos recolectados en cada turno.

## Uso del Código

El código proporcionado contiene las clases necesarias para implementar el sistema TrashCity. A continuación, se describen las principales clases y sus funciones:

- `TrashCity`: Representa el sistema TrashCity y proporciona métodos para contratar y despedir empleados, agregar y eliminar camiones, y obtener la carga recolectada en un día específico.

- `Empleado`: Representa a un empleado de la empresa, con atributos como el identificador, nombre, teléfono y dirección.

- `Camion`: Representa un camión de recolección, con su identificador, ruta asignada, conductor y asistentes.

- `Ruta`: Representa una ruta de recolección, que contiene una lista de puntos geográficos por los que debe pasar el camión.

- `PuntoGeografico`: Representa un punto geográfico en la ruta, con atributos de dirección, latitud y longitud.

- `Turno`: Representa un turno de trabajo para un camión, con su identificador, camión asociado, horarios de inicio y finalización, y carga recolectada.

Para utilizar el código, puedes crear instancias de las clases y utilizar los métodos correspondientes para interactuar con el sistema TrashCity. Puedes llamar a los métodos como `contratarEmpleado`, `agregarCamion`, `cargaDiaN`, entre otros, según tus necesidades.

## Pruebas Unitarias

Se han proporcionado pruebas unitarias básicas para verificar el funcionamiento de las funciones `cargaDiaN` e `Iterar`. Estas pruebas se pueden ejecutar para asegurar que el código se comporte como se espera. Puedes ejecutar las pruebas unitarias para verificar el funcionamiento correcto del sistema.

Nota: Este código está hecho para correr en un cuaderno de Google Colab. Si desea ejecutarse en otro ambiente, será necesario que se instalen las librerías y/o extensiones necesarias.
