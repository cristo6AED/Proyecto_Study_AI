# Proyecto_Estudy_AI

# Integrantes: Cristhian Torrico y Jeremy Aguilar

# ESTUD-IA

Convierte diapositivas + audio en apuntes estructurados automáticamente.

## ¿Qué hace este proyecto?

ESTUD-IA toma:

- 📄 un **PDF de diapositivas**
- 📄 un **documento Word con apuntes del usuario**
- 🎙️ una **transcripción del audio**

y genera:

- 🧩 una **explicación por cada diapositiva**
- 📘 un **documento final** más claro para estudiar

## Flujo del sistema

```text
PDF de diapositivas + Transcripción de audio
                  ↓
        Extracción y limpieza de texto
                  ↓
     Segmentación de la transcripción
                  ↓
     Alineación diapositiva ↔ audio
                  ↓
   Generación de explicación por slide
                  ↓
       Creación del documento final
