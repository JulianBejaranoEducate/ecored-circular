# EcoRed Circular

Caso de estudio para construir una aplicación mínima con una arquitectura inicial **monolítica**, orientada a la economía circular en Colombia.

## 📌 Descripción del proyecto

**EcoRed** es una iniciativa enfocada en la economía circular en Colombia.  
Su propósito es crear una plataforma digital que articule a los actores vinculados al:

- aprovechamiento de materiales,
- circulación de recursos,
- valorización de materiales reciclables o reutilizables.

Este repositorio documenta y desarrolla una versión mínima funcional (MVP) con enfoque pedagógico y de implementación progresiva.

---

## 🧱 Arquitectura base del caso de estudio

La aplicación está planteada con una arquitectura inicial monolítica compuesta por:

- **Frontend:** React
- **Backend:** Django + Django REST Framework
- **Autenticación:** Firebase Authentication
- **Base de datos (persistencia):** MongoDB Atlas

---

## 🛠️ Estado actual del desarrollo (2 de 5 fases)

Actualmente se han completado **2 fases de 5** en la configuración inicial del proyecto:

### ✅ Fase 1: Configuración del repositorio

Se realizó la configuración base del repositorio, principalmente relacionada con el manejo de variables de entorno:

- Archivos `.env` para el **backend**
- Archivos `.env` para el **frontend**

> Objetivo de esta fase: centralizar y aislar la configuración sensible y de entorno para facilitar despliegue, desarrollo local y buenas prácticas de seguridad.

### ✅ Fase 2: Configuración en Firebase y MongoDB Atlas

Se avanzó en la configuración de servicios externos:

- Configuración inicial de **Firebase** (autenticación)
- Configuración inicial de **MongoDB Atlas** (persistencia de datos)

> Objetivo de esta fase: dejar preparados los servicios de autenticación y almacenamiento para su integración con la aplicación.

---

## ⏳ Pendiente (próximas fases)

Está pendiente la etapa de integración entre:

- **Backend ↔ Frontend**
- **Backend ↔ Firebase**
- **Backend ↔ MongoDB Atlas**
- Flujo completo de autenticación y persistencia de datos extremo a extremo

En otras palabras, ya existe la base de configuración, pero aún falta la conexión funcional entre los componentes de la arquitectura.

---

## 🎯 Objetivo del siguiente hito

Lograr la conexión completa entre frontend, backend y servicios externos para habilitar:

1. autenticación de usuarios,
2. consumo de API desde el frontend,
3. persistencia real de información en MongoDB Atlas.

---

## 🧪 Enfoque del repositorio

Este repositorio se construye por fases para documentar el proceso técnico de forma incremental y reproducible, sirviendo como referencia para:

- aprendizaje de arquitectura web full stack,
- integración de React + Django REST,
- uso de Firebase Authentication,
- conexión con MongoDB Atlas en un caso aplicado.

---

## 📍 Nota de avance

> **Avance actual:** 40% de la configuración base (2/5 fases).  
> **Estado general:** infraestructura inicial lista; integración funcional en progreso.
