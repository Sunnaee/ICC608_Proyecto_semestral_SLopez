# ICC608 - Proyecto final
##### Estudiante: Sabrina López

# Aprendizaje por Refuerzo para Detección de Anomalías

Aplicación web interactiva que explica y simula algoritmos de Q-Learning aplicados a la detección de anomalías, desarrollada como recurso educativo para la asignatura ICC608-1 - Sistemas Inteligentes.

## Contenido

La aplicación incluye:
- Introducción teórica al aprendizaje por refuerzo.
- Explicación de conceptos fundamentales (agente, entorno, estado, acción, recompensa, política).
- Proceso de aprendizaje con balance exploración/explotación.
- Demostración del algoritmo Q-Learning con tabla Q interactiva.
- Caso práctico de optimización de semáforos con simulaciones en tiempo real.
- Conclusiones y referencias bibliográficas.

## Requisitos

- Docker (versión 20.10 o superior)
- Docker Compose (versión 2.0 o superior)

## Instrucciones de ejecución

1. **Construir la imagen y levantar el contenedor**  
   Abre una terminal en la carpeta del proyecto y ejecuta:
   ```bash
   docker-compose up -d --build