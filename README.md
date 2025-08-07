# 📱 Proyecto de Pruebas Funcionales – App Móvil Urban.Lunch

Este proyecto documenta el proceso de pruebas funcionales realizado sobre la aplicación móvil **Urban.Lunch**, una plataforma para ordenar alimentos con seguimiento y recogida en puntos establecidos. El objetivo fue validar el correcto funcionamiento de los principales flujos de usuario a través de pruebas manuales organizadas por pantallas.

---

## 🎯 Objetivo

Verificar que la aplicación móvil funcione correctamente en sus diferentes pantallas y funcionalidades principales, incluyendo:

- Flujo de selección de punto de recogida  
- Elección de platillos  
- Visualización de detalles de platillo  
- Seguimiento y entrega del pedido  
- Manejo de errores y notificaciones  

---

## 🔧 Herramientas utilizadas

- **Dispositivo físico:** Android (pruebas manuales)  
- **Emulador:** Android Studio Emulator  
- **Gestor de pruebas:** Google Sheets y Reportes en Jira  
- **Gestor de bugs:** Jira Software (ficticio para este caso)  
- **Documentación:** Markdown (`README.md`) para portafolio  

---

## 📂 Estructura de pruebas

Las pruebas se organizaron en secciones funcionales según la navegación de la app:

1. Selección del punto de recogida  
2. Elección de platillos  
3. Detalles del platillo  
4. Pantalla de seguimiento del pedido  
5. Pantalla de entrega del pedido  
6. Notificaciones de error  
7. Reporte de errores detectados  

Cada funcionalidad fue validada mediante una lista de comprobación que incluyó:

- Descripción clara del comportamiento esperado  
- Resultado observado  
- Estado de aprobación  
- Enlace al reporte de error (si aplica)  

---

## 📁 Carpeta de Imágenes

Este repositorio incluye una carpeta llamada `imagenes/` donde se almacenan capturas de pantalla y gráficos relevantes de la aplicación móvil **Urban.Lunch** durante las pruebas. Estas imágenes sirven para complementar la documentación y facilitar la comprensión visual de los casos de prueba, resultados y reportes de errores.

> **Nota:** La carpeta `imagenes/` está ignorada en el control de versiones para evitar subir archivos pesados o temporales. Si deseas agregar imágenes importantes al repositorio, asegúrate de confirmar su inclusión manualmente.

---

## ✅ Resultados Generales

- **Total de casos probados:** 23  
- **Casos aprobados:** 19  
- **Casos no aprobados:** 4  

---

## ❌ Casos Fallados

A continuación se listan los errores funcionales detectados. Los enlaces a los reportes de Jira son **ficticios y usados con fines de portafolio**:

| Nº | Descripción del error                        | Módulo               | Estado           | Bug ID |
|-----|---------------------------------------------|----------------------|------------------|---------|
| 1   | El zoom está habilitado en el emulador      | Elección de platillos | ❌ NO APROBADO   | ENP5-3  |
| 2   | El botón “Siguiente” no se activa tras agregar platillo | Detalles del platillo | ❌ NO APROBADO   | ENP5-1  |
| 3   | No se muestra el tiempo restante de preparación | Seguimiento de pedido | ❌ NO APROBADO   | ENP5-6  |
| 4   | Ícono incorrecto en pantalla de entrega      | Pedido entregado      | ❌ NO APROBADO   | ENP5-9  |

---

## 🧑‍💻 Tester responsable

**Evelyn Nava García**  
GitHub: [@Eve-nava](https://github.com/Eve-nava)

---

## 📌 Notas finales

- Todos los casos fueron ejecutados de forma manual.  
- Las pruebas se realizaron en un entorno estable de pre-producción.  
- Los enlaces a Jira incluidos en los errores son ficticios y fueron generados únicamente para fines de presentación en portafolio profesional.

---




