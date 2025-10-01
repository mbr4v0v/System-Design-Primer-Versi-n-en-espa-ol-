# System Design Primer (Versión en Español)

> 📘 Traducción al español del repositorio original [System Design Primer](https://github.com/donnemartin/system-design-primer) de Donne Martin.
> Los ejemplos, diagramas y enlaces permanecen iguales, solo se ha traducido el texto al español para facilitar el estudio.

---

## 📌 Introducción

Este repositorio tiene como objetivo ayudarte a **aprender a diseñar sistemas a gran escala**.  
El diseño de sistemas es un tema amplio que abarca muchos conceptos: escalabilidad, disponibilidad, balanceo de carga, almacenamiento en caché, bases de datos distribuidas, entre otros.

Este material también está pensado como **guía de preparación para entrevistas técnicas**, ya que muchas compañías tecnológicas incluyen preguntas de diseño de sistemas en sus procesos de selección.

Aquí encontrarás:

- 📖 Conceptos fundamentales de diseño de sistemas.
- 🖼 Diagramas y ejemplos prácticos.
- 🧠 Tarjetas de memoria (flashcards) con [Anki](https://apps.ankiweb.net/) para ayudarte a memorizar.
- 📚 Recursos adicionales recomendados.

---

## 📑 Tabla de Contenidos

- [Introducción](#-introducción)
- [Cómo usar este repositorio](#-cómo-usar-este-repositorio)
- [Escalabilidad](#-escalabilidad)
- [Alta disponibilidad y tolerancia a fallos](#-alta-disponibilidad-y-tolerancia-a-fallos)
- [Patrones comunes de diseño](#-patrones-comunes-de-diseño)
- [Estudios de caso](#-estudios-de-caso)
- [Ejercicios prácticos](#-ejercicios-prácticos)
- [Recursos adicionales](#-recursos-adicionales)
- [Preguntas frecuentes](#-preguntas-frecuentes)

---

# ⚡ Escalabilidad

La **escalabilidad** es la capacidad de un sistema de manejar una carga creciente de trabajo de manera eficiente o su habilidad para expandirse y adaptarse a un mayor volumen de datos o tráfico.

## Escalado Vertical (Scale Up)

- Consiste en **aumentar los recursos de un solo servidor** (más CPU, más RAM, más almacenamiento).
- Es relativamente sencillo de implementar.
- Existe un **límite físico** que impide crecer indefinidamente.
- Puede resultar **costoso** en hardware especializado.

## Escalado Horizontal (Scale Out)

- Consiste en **añadir más servidores** para dividir la carga de trabajo.
- Requiere sistemas distribuidos y mecanismos de coordinación.
- Ofrece mayor **flexibilidad y tolerancia a fallos**.

## Balanceadores de carga (Load Balancers)

![Load Balancer](images/load-balancer.png)

## Cachés

Ejemplos: **CDN**, **Redis**, **Memcached**.

## Bases de Datos (SQL vs. NoSQL)

![SQL vs NoSQL](images/sql_vs_nosql.png)

# 🌐 Bases de datos distribuidas

## Replicación

![Replication](images/replication.png)

## Particionamiento (Sharding)

![Sharding](images/sharding.png)

# 💡 Alta disponibilidad y tolerancia a fallos

## Fail-over (Conmutación por error)

![Failover](images/fail-over.png)

## Desacoplamiento y Colas de Mensajes

![Message Queue](images/message-queue.png)

# 🧩 Patrones comunes de diseño

## Content Delivery Network (CDN)

![CDN](images/cdn.png)

# 📚 Estudios de Caso

## 1. Acortador de URLs

![URL Shortener](images/url-shortener.png)

## 2. Sistema de mensajería

![Chat System](images/chat-system.png)

## 3. Feed de Noticias

![News Feed](images/news-feed.png)

## 4. Motor de búsqueda

![Search Engine](images/search-engine.png)

## 5. Servicio de almacenamiento de archivos

![Dropbox](images/dropbox.png)

## 6. Servicio de video en streaming

![Video Streaming](images/video-streaming.png)

# 📝 Ejercicios prácticos

- Diseñar un sistema de reservas de vuelos
- Diseñar un sistema de pagos en línea
- Sistema de almacenamiento de imágenes
- Sistema de mensajería en tiempo real

# 📚 Recursos adicionales

- [High Scalability](http://highscalability.com/)
- [Designing Data-Intensive Applications](https://dataintensive.net/)
- [Awesome Scalability](https://github.com/binhnguyennus/awesome-scalability)
- [System Design Primer (Original)](https://github.com/donnemartin/system-design-primer)

# ❓ Preguntas frecuentes

- ¿Por qué aprender diseño de sistemas?
- Diferencia entre SQL y NoSQL
- Escalabilidad vertical vs horizontal
- Qué es fail-over
- Qué son microservicios
- Cómo usar este repositorio para entrevistas
