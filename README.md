# ✈️ Proyecto Around - Red Social de Viajes | Pruebas Manuales QA 🧪

## 📑 Índice
- [🏷️ Título del proyecto](#️-título-del-proyecto)
- [📝 Descripción general del proyecto](#-descripción-general-del-proyecto)
- [🎯 Objetivos](#-objetivos)
- [🔍 Alcance de las pruebas](#-alcance-de-las-pruebas)
- [🧠 Estrategia de pruebas](#-estrategia-de-pruebas)
- [🏷️ Tipos de pruebas](#️-tipos-de-pruebas)
- [🛠️ Herramientas y tecnologías](#️-herramientas-y-tecnologías)
- [📊 Casos de prueba](#-casos-de-prueba)
- [🐛 Reporte de defectos](#-reporte-de-defectos)
- [📈 Resultados y métricas](#-resultados-y-métricas)
- [📂 Evidencias](#-evidencias)
- [📁 Estructura del repositorio](#-estructura-del-repositorio)
- [💡 Principales aprendizajes](#-principales-aprendizajes)
- [🚀 Mejoras futuras](#-mejoras-futuras)

---

## 🏷️ Título del proyecto
**Around - Red Social de Viajes (Pruebas Manuales Funcionales y UI)**

---

## 📝 Descripción general del proyecto
El proyecto **Around** consiste en la ejecución de pruebas manuales exhaustivas para la aplicación web de la red social de viajes *Around*. El objetivo principal es validar el flujo completo de usuario, la interfaz gráfica y el comportamiento de la plataforma frente a entradas válidas e inválidas, identificando fallos y reportando incidencias para garantizar una experiencia de usuario sólida y libre de errores.

---

## 🎯 Objetivos
- 📌 Validar el correcto funcionamiento de los flujos principales de la plataforma (autenticación, perfil de usuario e interacción social).
- 📌 Diseñar y ejecutar listas de comprobación (*checklists*) y casos de prueba detallados aplicando técnicas de diseño de pruebas como **Clases de Equivalencia** y **Valores Límite**.
- 📌 Documentar y clasificar errores e inconsistencias detectadas mediante reportes formales de defectos priorizados según su severidad e impacto.

---

## 🔍 Alcance de las pruebas
El alcance de las pruebas abarca la verificación manual de los siguientes módulos y funcionalidades:

1. 🔐 **Inicio y cierre de sesión:** Validación de credenciales de acceso, persistencia de sesión y flujo de salida seguro.
2. 📝 **Formulario de registro:** Creación de cuenta, validación de formatos de campos (correo, contraseña) e inputs requeridos.
3. 👤 **Perfil y edición de datos:** Comprobación de límites de caracteres, edición de fotos de perfil y visibilidad adecuada del nombre de usuario.
4. ❤️ **Interacción social:** Funcionalidad de agregar a favoritos, dar/quitar "Me gusta" (*like*) en las tarjetas de viaje.
5. 🎨 **Verificación de UI:** Comparación de la interfaz web implementada frente a los diseños y prototipos de Figma.
6. 📐 **Validación de campos de entrada:** Aplicación de clases de equivalencia y análisis de valores límite (*Boundary Value Analysis*) en formularios.

---

## 🧠 Estrategia de pruebas
La estrategia de QA manual fue ejecutada en las siguientes fases:
- 📋 **Análisis de requerimientos y diseño Figma:** Revisión detallada de la especificación técnica y maquetas visuales.
- 📐 **Técnicas de diseño de pruebas:** Creación de condiciones de prueba utilizando Partición de Equivalencia y Análisis de Valores Límite para optimizar la cobertura.
- 📜 **Elaboración de Checklists y Test Cases:** Redacción de listas de comprobación para pruebas exploratorias y casos de prueba formales paso a paso.
- 🐛 **Gestión de defectos:** Registro de bugs detectados clasificando su nivel de **Severidad** y **Prioridad** para el equipo de desarrollo.

---

## 🏷️ Tipos de pruebas
- 🔄 **Pruebas Funcionales:** Evaluación de las reglas de negocio y flujos completos de trabajo.
- 🎨 **Pruebas de Interfaz de Usuario (UI / UX):** Comprobación visual, alineación de elementos y respuesta responsiva.
- 🧪 **Pruebas de Valor Límite y Clases de Equivalencia:** Cobertura de límites mínimos, máximos e inputs inválidos en campos de texto.
- 🔍 **Pruebas de Regresión:** Verificación manual de correcciones de errores detectados previamente.

---

## 🛠️ Herramientas y tecnologías
- 🌐 **Navegadores web:** Google Chrome, Microsoft Edge
- 🛠️ **Inspección Web:** Google Chrome DevTools (Consola, Red, Elementos)
- 📐 **Diseño y Prototipado:** Figma
- 📊 **Documentación y Casos de Prueba:** Google Sheets / Microsoft Excel
- 🐞 **Gestión de Errores y Proyectos:** Jira (o plantillas de reporte formal)

---

## 📊 Casos de prueba
Los casos de prueba y listas de comprobación se organizaron detalladamente incluyendo ID, precondiciones, pasos de ejecución, datos de prueba, resultado esperado y resultado obtenido:

- 📋 **Matriz de Casos de Prueba y Checklists:** *[Enlace a tu documento de Google Sheets o Excel]*

---

## 🐛 Reporte de defectos
Cada discrepancia o fallo detectado fue documentado en un reporte de errores individual, especificando:
- 🆔 **ID y Título del bug**
- 📌 **Pasos detallados para reproducir**
- 🎯 **Resultado esperado vs. Resultado real**
- ⚖️ **Matriz de Severidad y Prioridad** (Bloqueante, Alta, Media, Baja)
- 📸 **Captura o evidencia visual**

---

## 📈 Resultados y métricas
- 📊 **Casos de prueba diseñados e identificados:** [Número de casos/checklists]
- ✅ **Flujos funcionales aprobados:** 100% de los flujos críticos validados.
- 🐛 **Defectos reportados:** Documentados e ingresados con clasificación de severidad.

---

## 📂 Evidencias
Se recopilaron capturas de pantalla, inspecciones de consola de DevTools y documentos de prueba:
- 📁 **Documento de Evidencias y Reporte de Bugs:** *[Enlace a tu archivo de evidencias]*

---

## 📁 Estructura del repositorio
```text
├── 📊 Casos_de_Prueba_Around.xlsx   # Matriz de casos de prueba y checklists
├── 🐛 Reporte_de_Defectos.pdf        # Informe estructurado de errores y bugs
├── 🎨 Evidencias_UI_DevTools/        # Capturas de pantalla e inspección de errores
└── 📘 README.md                      # Documentación principal del proyecto
```

---

## 💡 Principales aprendizajes
- 🧠 Aplicación práctica de **Clases de Equivalencia** y **Valores Límite** para optimizar la cantidad de casos de prueba sin perder cobertura.
- 🛠️ Manejo de **DevTools** para inspeccionar la red y consola al buscar errores ocultos de frontend/backend.
- 📐 Comparación precisa entre prototipos de **Figma** y la aplicación web para hallar inconsistencias de interfaz.
- 📝 Clasificación estratégica e imparcial de la **Severidad** y **Prioridad** al reportar incidencias.

---

## 🚀 Mejoras futuras
- ⚙️ Automatización de la regresión de flujos principales mediante Selenium / Cypress / Playwright.
- 🔌 Incorporar pruebas de API manuales con Postman para validar los endpoints de autenticación y perfil.
- 📱 Extender la matriz de pruebas hacia dispositivos móviles (iOS y Android).
