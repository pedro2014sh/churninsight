# 🚀 Churn Insight - Backend de Predicción de Clientes

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=java"/>
  <img src="https://img.shields.io/badge/Spring_Boot-3-green?style=for-the-badge&logo=springboot"/>
  <img src="https://img.shields.io/badge/Spring_Security-JWT-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge&logo=mysql"/>
  <img src="https://img.shields.io/badge/Flyway-Migrations-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Maven-Build-C71A36?style=for-the-badge&logo=apachemaven"/>
</p>

---

## 📌 Descripción

**Churn Insight** es una API REST desarrollada con **Spring Boot** que permite analizar el comportamiento de clientes y predecir si existe riesgo de cancelación (*churn*).

El sistema utiliza un modelo basado en reglas para calcular una probabilidad y determinar si el cliente cancelará el servicio.

---

## 🎯 Objetivo

Construir un backend capaz de:

- 📊 Analizar datos de clientes  
- 🤖 Predecir cancelación  
- 📈 Calcular probabilidad  
- 💾 Guardar resultados  
- 🔐 Proteger endpoints con JWT  

---

## 🧠 ¿Qué es Churn?

El **churn** representa la probabilidad de que un cliente abandone el servicio.

- `true` → el cliente va a cancelar  
- `false` → el cliente NO va a cancelar  

---

## ⚙️ Tecnologías

| Tecnología | Uso |
|----------|------|
| Java 17 | Lenguaje principal |
| Spring Boot | Framework backend |
| Spring Security | Autenticación |
| JWT | Seguridad |
| JPA / Hibernate | Persistencia |
| MySQL | Base de datos |
| Flyway | Migraciones |
| Maven | Build |

---
## 🔮 Lógica de Predicción

El sistema evalúa variables como:

- Retrasos en pagos  
- Tickets de soporte  
- Uso del servicio  
- Antigüedad  
- Tipo de plan  

