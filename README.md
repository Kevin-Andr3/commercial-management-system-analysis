# 🏪 commercial-management-system-analysis
<p align="center">
  <img src="https://img.shields.io/badge/Modelio%205-5F2D87?style=for-the-badge&logo=eclipse&logoColor=white" alt="Modelio" />
  <img src="https://img.shields.io/badge/UML%202.5-0073B7?style=for-the-badge&logo=enterprise&logoColor=white" alt="UML" />
  <img src="https://img.shields.io/badge/BPMN%202.0-FF6F00?style=for-the-badge&logo=camunda&logoColor=white" alt="BPMN" />
</p>

Este proyecto presenta el análisis, diseño y modelado de procesos de negocio para optimizar la gestión de inventario, ventas y compras de una bodega local. Desarrollado como parte del proyecto universitario para la asignatura de **Diseño y Arquitectura de Software** (Ciclo VII).

## 🎯 Objetivos del Proyecto
* **Optimizar procesos:** Rediseñar el flujo de ventas e inventario para reducir mermas.
* **Automatización:** Proponer un modelado robusto que sirva como base para el posterior desarrollo de un sistema de software.
  
## 📂 Estructura del Repositorio
<img src="diagrams/Estructura_Repositorio.JPG" alt="Estructura" width="100%"/>

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Herramienta de Modelado:** Modelio 5.x (UML / BPMN).
* **Gestión de Requerimientos:** Casos de Uso UML.
* **Documentación:** Markdown, Microsoft Word (Informe adjunto).

## 📊 Arquitectura y Diagramas Clave

  1. Diagrama General de Caso de Uso del Negocio (CUN):
  Representación de los procesos de negocio clave de la bodega y los actores externos que interactúan con ellos.
  <img src="diagrams/Diagrama_General_CUN.JPG" alt="DGCUN" width="100%"/>

  2. Diagrama General de Caso de Uso del Sistema (CUS):
  Define el límite del sistema de software propuesto, detallando cómo los diferentes roles de usuario (Cajero, Administrador, etc.) interactúan con las funcionalidades de la aplicación para automatizar los procesos de la bodega.
  <img src="diagrams/Diagrama_General_CUS.JPG" alt="DGCUS" width="100%"/>

  3. Modelo Conceptual:
  Abstracción del dominio del problema que representa las entidades clave del negocio de la bodega, sus atributos principales y las relaciones lógicas existentes entre ellos.
  <img src="diagrams/Modelo_Conceptual.JPG" alt="Conceptual" width="100%"/>

  4. Diagrama de Secuencia (Flujo Básico)(Caso de Uso: **Registrar Venta**):
  Muestra de Diseño Detallado del flujo de interacción y ciclo de vida de los objetos del sistema durante el escenario ideal de la transacción.
  <img src="diagrams/Diagrama_Secuencia_1.JPG" alt="Secuencia1" width="100%"/>
  <img src="diagrams/Diagrama_Secuencia_2.JPG" alt="Secuencia2" width="100%"/>

  5. Diagrama de Despliegue y Componentes:
  Representación de la arquitectura física y lógica del sistema, ilustrando la distribución de los componentes de software (frontend, backend, base de datos) en los nodos de hardware correspondientes.
  <img src="diagrams/Diagrama_Despliegue_Componentes.JPG" alt="Despliegue" width="100%"/>

## 🚀 Cómo Visualizar el Proyecto de Modelado
1. Descarga e instala **Modelio Open Source**.
2. Clona este repositorio: `git clone https://github.com/tu-usuario/tu-repositorio.git`
3. Comprime a .zip la carpeta `/modeling_project`
4. Abre Modelio e importa la carpeta comprimida .zip `/modeling_project` como un proyecto existente.

## 👥 Colaboradores

Este proyecto fue desarrollado con fines académicos de manera colaborativa por estudiantes de Ingeniería de Sistemas (puede encontrarlos en el informe del proyecto).
El repositorio se publica como muestra de portafolio con el reconocimiento correspondiente al trabajo en equipo.
Mi participación estuvo enfocada en el análisis y diseño, siendo responsable directo de la elaboración de los siguientes artefactos clave:
* **Modelado del Negocio:**
  * Diagrama General de Caso de Uso del Negocio (CUN).
  * Diagramas de Realización del Negocio (módulos seleccionados).
* **Ingeniería de Requisitos:**
  * Tabla con los Requisitos del Sistema (Funcionales y No Funcionales).
  * Diagrama General de Caso de Uso del Sistema (CUS).
* **Análisis y Diseño de Software:**
  * Diagrama General de Caso de Uso del Sistema según el análisis.
  * Diagramas de Análisis de Clases (módulos seleccionados).
  * Diagramas de Clases del Diseño (módulos seleccionados).
  * Diagramas de Comunicación - Flujo Básico (módulos seleccionados).
  * Diagramas de Secuencia - Flujo Básico (módulos seleccionados).
