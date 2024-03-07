#  Introducción a los Sistemas Operativos y Arquitectura de Computadoras

## Introducción

La forma en que se operan y cómo se diseñan nos llevará a dos áreas de conocimiento fundamentales principales, y ambas contribuyen a nuestras experiencias diarias con la tecnología digital. Desde dispositivos móviles portátiles hasta aplicaciones en la nube impulsadas por servidores, los sistemas operativos están ahí, vinculando las funcionalidades del dispositivo en una experiencia fluida y segura para el usuario. En esta clase, exploraremos los conceptos básicos sobre los sistemas operativos y la arquitectura de computadoras, desde sus fundamentos teóricos hasta su aplicación práctica en el mundo real. Las cuestiones son complejas y fundamentales y se considerarán durante este curso a través de explicaciones detalladas, ejemplos prácticos y debates interactivos. A lo largo de nuestro viaje, nos sumergiremos en la esencia de los sistemas operativos, desde su definición hasta sus funciones principales, y examinaremos de cerca la arquitectura subyacente que les da vida. ¡Prepárense para adentrarse en el fascinante mundo de la informática!

```
Los sistemas operativos son programas de software que actúan como intermediarios entre el hardware de una computadora y el software de aplicación del usuario. Proporcionan una plataforma para que otros programas se ejecuten y utilizan recursos de hardware de manera eficiente. Además, los sistemas operativos ofrecen una variedad de servicios esenciales, como la gestión de archivos, la administración de memoria y la seguridad del sistema.
```

| Función                  | Descripción                                                                                           |
|--------------------------|-------------------------------------------------------------------------------------------------------|
| Gestión de recursos      | Administra y coordina el uso de los recursos de hardware, como la CPU, la memoria y los dispositivos. |
| Interfaz de usuario      | Proporciona una interfaz para que los usuarios interactúen con la computadora, ya sea CLI o GUI.      |
| Gestión de archivos      | Organiza y manipula archivos en el sistema de almacenamiento, permitiendo su creación, lectura y escritura. |
| Gestión de procesos      | Controla la ejecución de programas y procesos en la computadora, asignando recursos y prioridades.   |
| Gestión de memoria       | Administra la memoria disponible en la computadora, asignándola y liberándola según sea necesario.    |
| Comunicación entre procesos | Facilita la comunicación y la sincronización entre diferentes procesos en el sistema.                 |
| Administración de usuarios | Gestiona perfiles de usuarios, sus privilegios y su acceso a recursos del sistema.                    |
| Seguridad                | Protege el sistema y los datos contra accesos no autorizados, mediante autenticación y cifrado.       |


| Sistema Operativo | Empresa Desarrolladora | Año de Desarrollo |
|-------------------|------------------------|-------------------|
| Windows           | Microsoft              | 1985              |
| macOS             | Apple                  | 2001              |
| Linux             | Comunidad Open Source  | 1991              |
| Android           | Google                 | 2008              |
| iOS               | Apple                  | 2007              |
| Unix              | Varios                 | 1969              |


# Arquitectura de un Sistema Operativo

## Capas de un sistema operativo

La arquitectura de un sistema operativo se refiere a la manera en que se organiza el software del sistema operativo. La mayoría de los sistemas operativos se dividen en capas, donde cada capa tiene una función específica. Estas se ordenan jerárquicamente, con la capa más baja (el núcleo) proporcionando los servicios básicos a las capas superiores.

Las capas comunes en un sistema operativo son:

1. **Capa de hardware:** Esta capa interactúa directamente con el hardware de la computadora, como la CPU, la memoria y los dispositivos de E/S.
2. **Capa del núcleo:** Es la parte central del sistema operativo, encargada de las funciones más básicas, como la gestión de memoria, la gestión de procesos y la gestión de interrupciones.
3. **Capa de controladores de dispositivos:** Esta capa proporciona una interfaz estándar para que las aplicaciones interactúen con los diferentes dispositivos de E/S de la computadora.
4. **Capa de gestión de archivos:** Esta capa organiza los datos en el disco duro y permite a los usuarios acceder a ellos de manera organizada.
5. **Capa de red:** Esta capa permite que la computadora se comunique con otras computadoras a través de una red.
6. **Capa de interfaz de usuario:** Esta capa proporciona la interfaz gráfica o de comandos que permite al usuario interactuar con el sistema operativo.

## Diseño modular

Los sistemas operativos modernos suelen tener un diseño modular, lo que significa que se dividen en módulos independientes. Cada módulo tiene una función específica y puede ser desarrollado y mantenido de forma independiente.

Las ventajas de un diseño modular son:

- **Flexibilidad:** El sistema operativo puede adaptarse a diferentes necesidades y configuraciones de hardware.
- **Escalabilidad:** El sistema operativo puede ampliarse para agregar nuevas funciones.
- **Mantenimiento:** El sistema operativo es más fácil de mantener y actualizar.

## Tipos de arquitecturas

Existen diferentes tipos de arquitecturas de sistemas operativos, como:

- Arquitectura monolítica: Todos los componentes del sistema operativo se encuentran en un único módulo.
- Arquitectura por capas: El sistema operativo se divide en capas, como se describió anteriormente.
- Arquitectura microkernel: El núcleo del sistema operativo solo se encarga de las funciones básicas, mientras que las demás funciones se implementan como módulos independientes.

## Elección de una arquitectura

La elección de una arquitectura para un sistema operativo depende de varios factores, como:

- **Los requisitos del sistema operativo** Las funciones que debe proporcionar el sistema operativo.
- **El hardware de la computadora:** La arquitectura del hardware y los recursos disponibles.
- **Las preferencias del desarrollador:** Las habilidades y experiencia del equipo de desarrollo.

