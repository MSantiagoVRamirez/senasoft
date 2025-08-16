# PlanBert: Asistente Educativo Multimodal

![PlanBert](PlanBert.Profile.png)

## Descripción General

**PlanBert** es un agente educativo que combina la explicación de conceptos con la práctica mediante retos personalizados.  
Su enfoque **multimodal** adapta las explicaciones al estilo de aprendizaje de cada usuario (**visual, auditivo o kinestésico**) y refuerza el conocimiento con desafíos progresivos que simulan problemas reales del área de estudio.

Si el aprendiz no logra superar un reto, el agente aplicará las llamadas **"penitencias de aprendizaje"**: microejercicios, trivias rápidas o mini proyectos adicionales que refuercen la competencia antes de avanzar.

---

## Funciones Principales

- 📚 **Explicaciones adaptadas** a distintos estilos de aprendizaje.  
- 🎯 **Retos graduados** según nivel y tema.  
- ⚡ **Retroalimentación inmediata** y sugerencias de mejora.  
- 📊 **Registro de progreso** y evaluación del usuario.  
- 🔄 **Penitencias interactivas** para afianzar lo no aprendido.

---

## Estructura del Proyecto

- **[PlanBert_Prompt.md](PlanBert_Prompt.md)**  
  Contiene las instrucciones base y reglas de interacción del asistente.

- **[planbert_metricas.schema.json](planbert_metricas.schema.json)**  
  Define el esquema de datos para almacenar métricas como penitencias, estilos de aprendizaje y niveles de conocimiento.

- **[PlanBert_Metrics_Guide.md](PlanBert_Metrics_Guide.md)**  
  Guía de integración para saber cómo y cuándo registrar las métricas, asegurando una experiencia personalizada.

- **Imagen del personaje**  
  Representación visual híbrida entre **Albert Einstein** y **Platón**, usada como identidad visual del asistente.

---

## Flujo de Trabajo del Asistente

1. **Identificar** el tema, nivel y estilo de aprendizaje del usuario.  
2. **Explicar** el contenido adaptado al estilo preferido.  
3. **Proponer** un reto práctico ajustado al nivel actual.  
4. **Evaluar** la respuesta del usuario.  
   - Si es correcta → Felicitar y subir el nivel de dificultad.  
   - Si es incorrecta → Aplicar penitencia de aprendizaje.  
5. **Registrar** el progreso en base a `planbert_metricas.schema.json`.  
6. **Repetir** el ciclo con retos progresivos.

---

## Instalación y Uso

1. Clonar este repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd <CARPETA_DEL_REPOSITORIO>
   ```

2. Configurar el entorno según la plataforma de implementación (ChatGPT Custom GPT, API, etc.).

3. Cargar los archivos de configuración y el esquema de métricas.

4. Ejecutar el asistente en el entorno deseado.

---

## Créditos

- **Diseño del concepto y flujo**: Basado en metodología de aprendizaje adaptativo.  
- **Ilustración**: Imagen generada digitalmente con estilo semi-realista, combinando rasgos de Einstein y Platón.

---

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más información.

## Integrantes de Grupo
-Jose Ali Zapata
-Miguel Santiago Velasquez Ramirez
-Nicolás Tamayo Jiménez
