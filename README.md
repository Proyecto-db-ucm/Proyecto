<!-- Shields -->
[![Java](https://img.shields.io/badge/Java-17%2B-ED8B00?logo=openjdk&logoColor=white)](https://openjdk.org/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.3%2B-6DB33F?logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![React](https://img.shields.io/badge/React-18.3%2B-61DAFB?logo=react&logoColor=white)](https://react.dev/)
[![Oracle DB](https://img.shields.io/badge/Oracle%20DB-19c%2B-F80000?logo=oracle&logoColor=white)](https://www.oracle.com/database/)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-En%20Desarrollo-28a745)](https://github.com/tu-usuario/residencial-del-maule-crud)

<p align="center">
  <img src="https://i.imgur.com/5qJ8vKp.png" alt="Residencial del Maule - Linares, Chile" width="800"/>
  <br>
  <em>Hostal Residencial del Maule - Linares, Región del Maule, Chile</em>
</p>

<h1 align="center">Residencial del Maule - Sistema CRUD</h1>

<p align="center">
  <strong>Sistema de gestión integral para hostal en Linares, Chile</strong>
</p>

<p align="center">
  <a href="#-tecnologías">Tecnologías</a> •
  <a href="#-inicio-rápido">Inicio Rápido</a> •
  <a href="#-docker">Docker</a> •
  <a href="#-estructura">Estructura</a> •
  <a href="#-contribuir">Contribuir</a>
</p>

---

## Descripción del Proyecto

Sistema **full-stack CRUD** desarrollado para el **Hostal Residencial del Maule**, ubicado en **Linares, Región del Maule, Chile**.  
Diseñado para pequeñas residenciales y hostales, con enfoque en **robustez, escalabilidad y soporte nativo para Oracle Database**.

Funcionalidades clave:
- Gestión de huéspedes
- Reservas con check-in/check-out
- Administración de habitaciones
- Control de pagos
- Reportes y estadísticas

> **Ideal para empresas chilenas que usan Oracle en producción.**

---

## Tecnologías Utilizadas

| Capa         | Tecnología                        | Versión         |
|--------------|-----------------------------------|-----------------|
| **Backend**  | **Java + Spring Boot 3**          | `17+` / `3.3+`  |
| **Frontend** | React + Vite + Tailwind CSS       | `^18.3.0`       |
| **DB**       | **Oracle Database (XE / 19c+)**   | `19c+`          |
| **ORM**      | Spring Data JPA + Hibernate       | `^3.3`          |
| **Build**    | Maven                             | `3.9+`          |
| **Despliegue**| Docker + Docker Compose           | `latest`        |

---

## Características Principales

- Registro completo de **huéspedes** (RUT, pasaporte, contacto)
- **Habitaciones** por tipo: individual, doble, suite
- **Reservas** con calendario y disponibilidad en tiempo real
- Check-in / Check-out con notificaciones
- **Pagos**: efectivo, transferencia, tarjeta (próximamente SII)
- Panel admin con **reportes PDF**
- Diseño **100% responsive**
- Integración nativa con **Oracle Database** (JDBC + ojdbc11)

---

## Inicio Rápido

### Prerrequisitos
```bash
- Java 17 (JDK)
- Node.js 18+ (npm)
- Oracle Database XE o instancia en la nube
- Maven 3.9+
- Git
