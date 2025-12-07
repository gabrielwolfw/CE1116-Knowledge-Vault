---
Fecha de creación: 2025-08-05 00:12
Fecha de Modificación: 2025-08-05 00:12
tags:
  - "#infrastructura"
  - cloud
Tema: control-ciclo-vida-producto
---


## 📚 Idea/Concepto 

El almacenamiento geo-redundante en el cloud está basado en replicar los datos entre regiones geográficas separadas este enfoque permite asegurar resiliencia y continuidad operativa ante fallos que podrían afectar a una región completa. Está solución mantiene una copia activa en la región primaria y replica de forma asíncrona una copia secundaria ubicada en otra región distante, permitiendo el aumento de la durabilidad del servicio a niveles extremadamente altos. Además, la réplica secundaria no es accesible, a menos, que la región principal tenga una interrupción. Existe la posibilidad de perder una fracción mínima de datos recientes, en caso de ocurrir una evento en la región principal que inhabilite la región principal, debido a sistema asíncrono. Este enfoque de almacenamiento es fundamental para garantizar la continuidad global de las operaciones y cumplir con requisitos regulatorios que demandan protección ante desastres de gran escala.
## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Trade off en el diseño y arquitectura de software]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 