📘 Traducción al español del repositorio original [System Design Primer](https://github.com/donnemartin/system-design-primer) de Donne Martin.
> Los ejemplos, diagramas y enlaces permanecen iguales, solo se ha traducido el texto al español para facilitar el estudio.


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

Existen dos enfoques principales:

## Escalado Vertical (Scale Up)

- Consiste en **aumentar los recursos de un solo servidor** (más CPU, más RAM, más almacenamiento).
- Es relativamente sencillo de implementar.
- El problema es que existe un **límite físico**.
- Puede resultar **costoso** en hardware especializado.

## Escalado Horizontal (Scale Out)

- Consiste en **añadir más servidores** para dividir la carga de trabajo.
- Requiere sistemas distribuidos y mecanismos de coordinación.
- Ofrece mayor **flexibilidad y tolerancia a fallos**.

## Balanceadores de carga (Load Balancers)

![Load Balancer](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/load-balancer.png)

## Cachés

Ejemplos: **CDN**, **Redis**, **Memcached**.

## Bases de Datos (SQL vs. NoSQL)

![SQL vs NoSQL](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/sql_vs_nosql.png)

# 🌐 Bases de datos distribuidas

## Replicación

![Replication](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/replication.png)

## Particionamiento (Sharding)

![Sharding](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/sharding.png)

# 💡 Alta disponibilidad y tolerancia a fallos

## Fail-over (Conmutación por error)

![Failover](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/fail-over.png)

## Desacoplamiento y Colas de Mensajes

![Message Queue](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/message-queue.png)

# 🧩 Patrones comunes de diseño

## Content Delivery Network (CDN)

![CDN](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/cdn.png)

# 📚 Estudios de Caso

## 1. Acortador de URLs

![URL Shortener](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/url-shortener.png)

## 2. Sistema de mensajería

![Chat System](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/chat-system.png)

## 3. Feed de Noticias

![News Feed](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/news-feed.png)

## 4. Motor de búsqueda

![Search Engine](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/search-engine.png)

## 5. Servicio de almacenamiento de archivos

![Dropbox](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/dropbox.png)

## 6. Servicio de video en streaming

![Video Streaming](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/video-streaming.png)

# 📝 Ejercicios prácticos

# 📚 Recursos adicionales

# ❓ Preguntas frecuentes
