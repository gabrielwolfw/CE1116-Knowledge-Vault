---
Fecha de creación: 2025-08-05 00:10
Fecha de Modificación: 2025-08-05 00:10
tags:
  - "#arquitectura"
Topic:
  - estilos-arquitectura-software
---


## 📚 Idea/Concepto 

El Broker en arquitecturas Event Driven es el componente que retransmite eventos de forma asíncrona y descentralizada a los consumidores suscritos, usando el patrón Pub/Sub. Se utiliza principalmente cuando el flujo de procesamiento es simple y no requiere orquestación centralizada, ya que el control lo tienen los procesadores de eventos, quienes generan y anuncian nuevos hechos para que el sistema siga reaccionando. Es imprescindible que los procesadores sean idempotentes para evitar problemas por reintentos y duplicados en entornos distribuidos. El monitoreo y la depuración pueden ser más complejos porque la cadena de eventos no la controla un único coordinador, sino que depende de los módulos que participan en el flujo.
## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Latencia]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 