# Aprendizaje_Automatico_Supervisado
Sistema de clasificacion basado en reglas en Python para procesar registros de actividad de usuarios y evaluacion frente a ML.

# Clasificador de Acciones de Usuarios

Proyecto simple en Python que implementa un **sistema de clasificacion basado en reglas** (if-elif-else) para categorizar logs de interaccion de usuarios.

---

## Resumen del Trabajo

El proyecto evalua un conjunto de datos de eventos de usuarios segun sus atributos (accion, duracion, resultado) para asignarles una categoria (ej. *Combate Ganado*, *Exploracion Exitosa*, *Actividad Social*).

### Puntos clave:
1. **Logica aplicada:** Condiciones explicitas sobre la accion realizada y su resultado.
2. **Resultado:** Clasificacion precisa para los escenarios previstos en el dataset.
3. **Limitaciones:** Sistema rigido, sensible a errores de escritura y que no aprovecha variables continuas como duracion.
4. **Mejora con ML:** Se propone usar **Arboles de Decisión** o **Random Forest** para generalizar mejor, descubrir patrones automaticamente e incorporar el analisis de tiempos (duracion).
