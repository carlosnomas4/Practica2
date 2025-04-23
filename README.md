# Actividad2

Este proyecto es parte de la Actividad 2 de la asignatura Programación Visual. Se desarrolló una aplicación en Java utilizando Maven y la asistencia de una LLM (modelo de lenguaje) para generar ejemplos funcionales con las librerías `commons-cli` y `log4j`.

## Estructura del Proyecto

- **Maven**: Manejo de dependencias y empaquetado.
- **Generación de JAR**: Ejecutable con `java -jar`.
- **Dependencias**:
  - `commons-cli`: Para parseo de argumentos de línea de comandos.
  - `log4j`: Para registrar logs.

## Ejecución

```bash
# Empaquetar
mvn clean package

# Ejecutar con argumento
java -jar target/Actividad2-1.0-SNAPSHOT.jar -n "TuNombre"
```

## Uso de la LLM

Se solicitó a una LLM generar ejemplos simples de uso para `commons-cli` (parseo de argumentos) y `log4j` (logging de eventos y errores), los cuales fueron integrados al código principal en `App.java`.

## Subida a GitHub

El repositorio fue subido y se brindó visibilidad al usuario **ale-vz**.

---
