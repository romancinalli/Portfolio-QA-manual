# Portfolio de Testing

Este repositorio contiene la documentación y evidencias del proceso de testing aplicado a un sitio web.

## Contenido

- **Casos de prueba**
- **Informe de errores (bugs)**
- **Informe de resultados**
- **Evidencias en capturas de pantalla**
- **Pruebas sobre API REST y Auditoría Web**

## Detalles

Se realizaron 10 casos de prueba:

- 6 pruebas positivas
- 4 pruebas negativas

De los resultados:

- 6 pruebas pasaron
- 4 fallaron
- 2 errores fueron detectados en pruebas positivas
- 2 errores en pruebas negativas

**Conclusión:**  
Dada la cantidad de errores funcionales encontrados, se considera que el sitio *no está en condiciones de pasar a producción*.

---

## Pruebas funcionales de API con Postman

Se realizaron pruebas sobre distintos endpoints de la API de JSONPlaceholder, agrupadas por método HTTP:

- **GET**: Verificación de datos de usuarios, comentarios y fotos por ID.
- **POST**: Simulación de creación de recursos (posts y comentarios).
- **DELETE**: Simulación de eliminación de recursos.
- **PUT/PATCH**: No incluidas en esta etapa.

Cada prueba incluyó:

- Objetivo
- Procedimiento
- Captura de pantalla con resultados
- Conclusión

Las evidencias se encuentran en la carpeta `pruebas-postman`.

---

## Auditoría con Lighthouse

Se ejecutó una auditoría de rendimiento con Lighthouse sobre una página web (versión mobile y desktop).

**Resultados destacados:**
- Mobile: 91 puntos
- Desktop: 75 puntos

**Problemas detectados:**
- Bloqueo por archivos JS y CSS
- Uso de imágenes en formatos no optimizados
- Ausencia de dimensiones en imágenes
- Reglas CSS no utilizadas

Informe completo disponible en la carpeta `auditoria-lighthouse`.

---

## Análisis de solicitudes CRUD

Se realizó un análisis de las solicitudes del tipo Create, Read, Update y Delete utilizando una interfaz web.  
Se evaluó el funcionamiento completo del CRUD y se documentaron los resultados.

El detalle se encuentra en `analisis-crud`.

**Evidencia en video:**  
[Ver grabación en Google Drive](https://drive.google.com/file/d/1q28g8POIGbV71p8SORefQKWcQ7BWi8Ge/view?usp=drive_link)

---

**Autor:** Román Leandro Cinalli  
**Fecha:** Mayo 2025  
**Actualización:** Junio 2025
