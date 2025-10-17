---
Fecha de creación: 2025-10-16 17:55
Fecha de Modificación: 2025-10-16 17:55
tags:
  - criterios
  - estandares
  - metricas
Tema:
---


## 📚 Idea/Concepto 
La latencia es un requerimiento no funcional clave en arquitectura de software que sirve para medir cuánto tiempo tarda el sistema en responder una solicitud que le llega. Se compone de dos partes: la latencia de red, que es el tiempo que tardan los datos en viajar por la red, y la latencia de procesamiento, que es lo que tarda el sistema en procesar la petición. Para saber cómo lo viven los usuarios, se usan métricas como los percentiles P90 y P99, que muestran los casos más lentos y reales. Cuando la latencia es demasiado alta, es como si el sistema no existiera para el usuario. Es una preocupación importante en el diseño de la Process View y siempre aparece en los trade-offs con otras cosas como la consistencia y el throughput, que mide cuánto trabajo se puede procesar en cierto tiempo. Además, todas las decisiones que se tomen para mejorar la latencia deberían quedar registradas y justificadas, porque ayudan a mantener la trazabilidad y el sentido de las elecciones arquitectónicas en el futuro.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Requerimientos No Funcionales]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 