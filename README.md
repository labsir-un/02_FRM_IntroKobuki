<div align="center">
<picture>
    <source srcset="https://imgur.com/5bYAzsb.png" media="(prefers-color-scheme: dark)">
    <source srcset="https://imgur.com/Os03JoE.png" media="(prefers-color-scheme: light)">
    <img src="https://imgur.com/Os03JoE.png" alt="Escudo UNAL" width="350px">
</picture>

<h3>Curso de Fundamentos de Robótica Móvil 2026-I</h3>

<h1>Introducción a Robot Kobuki</h1>


<h4>Pedro Fabián Cárdenas Herrera<br>
    Ricardo Emiro Ramírez Heredia<br>
    </h4>

<p>
  <img alt="Nivel" src="https://img.shields.io/badge/Nivel-Introductorio-2ea44f">
</p>

</div>

<div align="justify"> 

## Tabla de contenidos
- [Introducción](#introducción)
- [Objetivos](#objetivos)
- [Requisitos previos](#requisitos-previos)
- [Instalación de herramientas previas](#instalación-de-herramientas-previas)
  - [1. Doxygen](#1-api-doxygen)
  - [2. ROS](#2-ros)
- [Caracteristicas Robot Kobuki](#características-robot-kobuki)
- [Recursos útiles](#recursos-útiles-para-seguir-aprendiendo)
- [Referencias](#referencias)

---

## Introducción

El robot móvil Kobuki es utilizado en entornos académicos para el estudio del control y la navegación robótica. La comunicación entre el software del usuario y el hardware del robot puede realizarse de diferentes maneras. Una de ellas es mediante una API (Application Programming Interface), que proporciona funciones para enviar comandos de movimiento y acceder a la información de los sensores de forma estructurada, sin interactuar directamente con el hardware de bajo nivel.

Esta API se encuentra integrada dentro de un SDK (Software Development Kit), el cual reúne las librerías y herramientas necesarias para el desarrollo de aplicaciones de control. Otra forma de interacción con el robot Kobuki es a través de ROS (Robot Operating System), que permite el control del robot mediante una arquitectura basada en nodos y mensajes, facilitando la integración con algoritmos de navegación y procesamiento.

El desarrollo del software se realiza en un IDE (Integrated Development Environment), mientras que la documentación de las interfaces de programación se apoya en herramientas como Doxygen, las cuales permiten generar documentación automática a partir del código fuente.


## Objetivos

- Proporcionar una guía clara y funcional para el uso del robot Kobuki
- Asegurar que el entorno de desarrollo esté correctamente configurado para trabajar con el robot Kobuki.
- Verificar el correcto funcionamiento y la correcta adquisición de datos de los sensores de contacto, caída, giroscopio y encoders del robot Kobuki..
---

## Requisitos

- Tener conexión a internet.
- Robot Kobuki.

---

## Instalaciones de herramientas

### 1. Doxygen
Doxygen es una herramienta utilizada para documentar la API, permitiendo conocer las funciones disponibles para el control del robot. Para hacer uso de estas funciones, es necesario contar con conocimientos de programación en C++. En el siguiente enlace se encontrará la información para usar la API:
 

[Uso de la API del Kobuki](https://github.com/labsir-un/FRM_Lab_1_Intro_Robot_Moviles/blob/main/Kobuki/API_kuboki.md)


### 2. ROS
Otra manera de controlar el robot es mediante ROS, el cual permite la comunicación a través de paquetes de software que hacen uso de la API proporcionada por el fabricante. Para obtener información acerca de esta modalidad, en el siguiente enlace se encuentra la información correspondiente.

[Uso de ROS para el robot Kobuki](https://github.com/labsir-un/FRM_Lab_0_Intro_software/blob/main/Secciones/ROS/Recursos/Kuboki.md)


---

## Características Robot Kobuki  

## 🧠 ¿Qué es el Kobuki?

El **Kobuki** es una **base móvil diferencial** que permite a investigadores y estudiantes **desarrollar, probar y validar algoritmos de control, localización y navegación**, sin necesidad de diseñar el hardware desde cero.

Su enfoque está en la **robótica móvil autónoma**, más que en la robótica modular educativa.

---

## 🔧 Componentes principales

### 1. Base móvil Kobuki (plataforma robótica)

- Sistema de **tracción diferencial** con dos ruedas motrices  
- Rueda loca trasera para estabilidad  
- Controlador interno para motores y sensores  
- Diseño compacto y robusto para uso en laboratorio  

---

### 2. Sensores integrados

Permiten que el robot **perciba el entorno y su propio movimiento**:

- ✋ **Sensores de contacto (bumpers)**  
  Detectan colisiones frontales (izquierda, centro y derecha).

- ⚠️ **Sensores de caída (cliff sensors)**  
  Detectan escalones o desniveles, evitando caídas.

- 🌀 **Giroscopio (IMU – eje Z)**  
  Mide la velocidad angular para estimar orientación y rotación.

- 🔄 **Encoders de ruedas**  
  Miden el giro de las ruedas para calcular velocidad, distancia y odometría.

---

### 3. Sistema de movimiento

- **Dos motores DC** con reductores  
- Encoders integrados para control preciso  
- Permiten movimiento **adelante, atrás y giros sobre su eje**

---

### 4. Alimentación y conectividad

- Batería recargable integrada  
- Interfaz de comunicación para conexión con un computador externo  
- Compatibilidad con **ROS (Robot Operating System)** para el uso y visualización de datos sensoriales


## Recursos útiles (para seguir aprendiendo)

<details>
  <summary>🐢🤖 kobuki</summary>

- [kobuki_core](https://github.com/kobuki-base/kobuki_core)
- [Robots ros Kobuki](https://robots.ros.org/kobuki/)
- [Wiki kobuki](https://kobuki.readthedocs.io/en/devel/about.html)
</details>

## Referencias

1. Kobuki Development Team. (s.f.). Kobuki Mobile Robot Wikipage. WikiKobuki. https://wiki.ros.org/kobuki


</div>
