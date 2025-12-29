# Power Adapter – FlatSat Nano 70/30 ⚡🛰️

Placa de distribución y protección de alimentación para el entorno **FlatSat híbrido**, desarrollada en el **Instituto Gulich** en colaboración con el proyecto **CubeSat Nano 70/30** de la **FCEFyN – Universidad Nacional de Córdoba**, en el marco de las **Prácticas Profesionales Supervisadas (PPS)**.

El diseño está orientado a alimentar y validar los subsistemas de **COMMS** y **OBC** durante tareas de integración y ensayo.

---

## 📘 Descripción general

Este repositorio documenta el diseño del **Power Adapter**, una placa de alimentación desarrollada para su uso en el entorno FlatSat híbrido del proyecto CubeSat Nano 70/30.

La placa actúa como interfaz entre la fuente de laboratorio y los subsistemas del satélite, permitiendo una distribución segura de potencia, la incorporación de protecciones eléctricas y la instrumentación necesaria para tareas de prueba, validación e integración del sistema.

![FlatSat_híbrido](/images/1.jpg)

![FlatSat](/images/3.jpg)


---

## 🎯 Objetivos del proyecto

- Diseñar una placa de **distribución de alimentación robusta y segura**.
- Proveer las tensiones requeridas por los subsistemas de **COMMS** y **OBC**.
- Incorporar **protecciones eléctricas** adecuadas para entorno de laboratorio.
- Facilitar la **medición de tensiones y corrientes** durante ensayos.
- Integrar el módulo al flujo de trabajo del **FlatSat híbrido**.
- Documentar el diseño de forma clara y reproducible.

---

## ⚙️ Características principales

- Distribución de múltiples rieles de alimentación.
- Separación entre alimentación lógica y potencia del transmisor.
- Protección mediante fusibles y supresión de transitorios.
- Puntos de test para mediciones eléctricas.
- Diseño implementado íntegramente en **KiCad**.

---

## 🛰️ Subsistemas involucrados

- **COMMS**: NanoCom U482C (Transceptor UHF)
- **OBC**: NanoMind A712C (On-Board Computer)
- **Ground Segment**: TNC1 y estación terrestre de pruebas
- **Entorno de control**: MOC virtual

---
## 📂 Estructura del repositorio

'''
power-adapter-flatsat-nano7030/
├── hardware/ # Diseño KiCad del PCB
├── docs/ # Documentación y referencias técnicas
├── test/ # Resultados de pruebas y validaciones (futuro)
└── README.md
'''
---

Cada carpeta incluye su propio README con información específica.

---

## 🛠️ Herramientas utilizadas

- **KiCad** (esquemático y PCB)
- Instrumentación electrónica de laboratorio
- Git y GitHub para control de versiones

---

## 📄 Licencia

Este proyecto se distribuye bajo licencia **MIT**.  
La documentación de terceros incluida como referencia conserva su licencia original.

---

## 📬 Notas finales

El repositorio se publica con fines de documentación técnica y aprendizaje.  
El diseño puede evolucionar a medida que se incorporen nuevas pruebas o revisiones del sistema.
Se agradecen los comentarios y contribuciones constructivas.