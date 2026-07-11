# Alexander Canon (alexaversion)

Soy **Estudiante de Ingeniería en Sistemas** y **Software & Cloud Infrastructure Engineer**. Inicié mi camino en el desarrollo backend enfocado en el ecosistema de Java y Spring, y naturalmente he evolucionado hacia la administración de sistemas Linux, automatización de tuberías CI/CD, ciberseguridad y el diseño de arquitecturas seguras y resilientes en la nube.

---

### 🛠️ Tecnologías & Herramientas

*   **Backend & Cloud Middleware:** Java, Spring Boot, REST APIs, Spring Cloud Gateway, RabbitMQ, gRPC (Bun).
*   **DevOps & Infraestructura:** Docker Compose, Kubernetes, CI/CD (GitHub Actions), AWS (EC2, ECR, S3, IAM, Parameter Store), Tailscale (Mesh VPN Overlay), Dokploy, Nginx, Servidores Linux.
*   **Bases de Datos:** PostgreSQL (HA Clusters), Patroni, etcd, pgBouncer, MongoDB (NoSQL), Supabase.
*   **Observabilidad:** Grafana Cloud, Grafana Alloy, Prometheus, Loki, Tempo (Métricas, Logs y Trazado Distribuido).

### 🌐 Idiomas
*   Español: Nativo
*   Inglés: Intermedio (C1) - Capaz de leer documentación técnica y mantener comunicación escrita.
---

### 📂 Proyectos Destacados

#### 🔹 [Neversion](https://alexandercanon.com/proyectos/neversion) — SaaS de Reventa de Credenciales Digitales
Plataforma SaaS multi-tenant diseñada para automatizar la gestión y venta de credenciales de servicios digitales.
*   **Arquitectura:** Monorepo con App del backend (Hexagonal + DDD) en Java y frontends SPA en Angular 17.
*   **Infraestructura:** Pipelines de CI/CD automatizados (GitHub Actions), empaquetado en Docker y despliegue sobre Dokploy/Docker Compose protegiendo los servicios internos.
*   **Servicios auxiliares:** Notificaciones locales gRPC ligeras en Bun/SQLite y almacenamiento/identidad delegado en Supabase y Resend.

#### 🔹 [OrionTicket](https://alexandercanon.com/proyectos/orionticket) — Plataforma White-Label de Venta de Boletos
Proyecto educativo universitario enfocado en demostrar resiliencia, alta concurrencia y tolerancia a fallos.
*   **Arquitectura:** Microservicios independientes en Java y Spring Boot aplicando patrones CQRS, segregación de bases de datos por servicio y consistencia eventual.
*   **Manejo de Concurrencia:** Bloqueo atómico de inventario de asientos en tiempo real y validación de entradas ("first-scan-wins") utilizando Redis.
*   **Mensajería & NoSQL:** Comunicación asíncrona mediante RabbitMQ y almacenamiento optimizado de reportes analíticos con MongoDB.

#### 🔹 [Arquitectura Multi-VPS](https://alexandercanon.com/proyectos/arquitectura-multi-vps) — Infraestructura Distribuida e Híbrida
Diseño de topología de red mallada multiplataforma para desplegar microservicios sin dependencia directa de servicios administrados costosos.
*   **Conectividad:** Red privada overlay interservidores en AWS, GCP y servidores locales configurada de manera segura con Tailscale (WireGuard).
*   **Alta Disponibilidad:** Clúster de base de datos PostgreSQL redundante gestionado con Patroni, prevención de split-brain con etcd y multiplexado de conexiones con pgBouncer y HAProxy.
*   **Observabilidad:** Monitoreo unificado de infraestructura y rendimiento enviando logs, métricas y trazas a Grafana Cloud a través de agentes locales Grafana Alloy.

---

### ✉️ Contacto y Enlaces

*   🌐 **Sitio Web Personal:** [alexandercanon.com](https://alexandercanon.com)
*   💼 **LinkedIn:** [linkedin.com/in/alexcanon64](https://linkedin.com/in/alexcanon64)
*   📧 **Email:** [hola@alexandercanon.com](mailto:hola@alexandercanon.com)
