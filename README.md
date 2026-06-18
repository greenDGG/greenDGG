# greenDGG

Backend, automation, bots, full-stack. Si corre en un servidor, lo puedo construir.

---

## Áreas de trabajo

Armo sistemas completos — backend, APIs, bases de datos, WebSockets, microservicios. El stack principal es **NestJS + Node.js + TypeScript**, con **MongoDB** y **PostgreSQL** como bases y **Redis** para caché, colas y rate limiting.

Frontend también, con **React** (web y React Native). Lo que no hago es diseñar — maquetar, armar componentes, conectar APIs, eso sí.

Escribo bots. Muchos. Discord, Instagram, WhatsApp, trading, juegos, automatización. Si se puede automatizar, probablemente haya un script para eso.

---

## Proyectos destacados

### [Fluxa](https://github.com/greenDGG/dex-wallet-platform) — Crypto Wallet + Swaps
Billetera crypto con integración DEX (PancakeSwap), notificaciones push en tiempo real y autenticación 2FA.
- **Backend:** NestJS 11, MongoDB, ethers.js v6, Web3 v4
- **DEX:** PancakeSwap SDK para swaps en BSC
- **Tiempo real:** Socket.IO para notificaciones de transacciones
- **Push:** Firebase Cloud Messaging (FCM)
- **Seguridad:** Speakeasy 2FA, cifrado de claves
- **Frontend:** React 19, TypeScript, TailwindCSS
- **Stack completo.** Incluye tests unitarios y E2E.

### [Bank Core](https://github.com/greenDGG/bank-core-platform) — Microservicios Bancarios
Sistema bancario simulado con contabilidad de doble entrada, ledger inmutable y prevención de double-spend.
- **Stack:** Java 21, Spring Boot 3.3.5, Kafka, PostgreSQL 16, Redis
- **Patrones:** Saga, outbox, CQRS parcial, JWKS, SELECT FOR UPDATE NOWAIT
- **Infra:** Spring Cloud Gateway, Prometheus, Grafana, Kubernetes network policies
- **Testing:** Test de concurrencia con Testcontainers

### [guards-nestjs](https://github.com/greenDGG/guards-nestjs) — 39 Guards de Seguridad para NestJS
Librería completa de seguridad: rate limiting adaptativo, detección de bots, risk scoring multi-señal, anti-timing-attack, circuit breaker, seguridad Web3, emergency lock, detección de session hijack.
- Cada guard está documentado, testeado y listo para copiar a producción
- Arquitectura en 6 capas con SecurityContext compartido

### [ado-ecomerce](https://github.com/greenDGG/ado-ecomerce) — E-Commerce Full-Stack
Plataforma de e-commerce con carrito, órdenes, panel admin y autenticación JWT.
- **Backend:** NestJS 11, PostgreSQL 15, Redis 7, TypeORM
- **Frontend:** React 19, Material UI 9, Vite
- **Seguridad:** Rate limiting granular (3/login, 5/auth, 60 global), bcrypt 12 rounds, CSP, soft-delete
- **Documentación:** ARCHITECTURE.md con diseño completo del sistema (642 líneas)

---

## Stack real

| Categoría | Tecnologías |
|-----------|------------|
| **Backend** | NestJS, Express, Node.js, TypeScript, Python |
| **Databases** | MongoDB, PostgreSQL, Redis, SQLite |
| **Blockchain** | ethers.js, Solidity, Hardhat, Solana Web3, TronWeb, bitcoinjs-lib |
| **Frontend** | React, React Native (Expo), TailwindCSS, Material UI |
| **Infra** | Docker, AWS (KMS, Lambda, Secrets Manager) |
| **Mensajería** | Kafka, BullMQ, Socket.IO, RabbitMQ |
| **Automation** | Discord.js, Playwright, whatsapp-web.js, ADB, OpenCV, YOLO |
| **Trading** | Binance API, Bybit API |

---

## Enfoque profesional

- Backend es mi fuerte, pero armo frontend completo cuando hace falta. Lo que no hago es diseñar.
- La seguridad no es opcional — rate limiting, KMS, 2FA, cifrado, guards por defecto.
- Los bots no son juguetes: sesiones persistentes, rate limiting, circuit breakers, anti-detección.
- Escribo código que funciona, no código que impresiona. Si está en producción, tiene logs, manejo de errores y monitorización.

---

## Contacto

- GitHub: [github.com/greenDGG](https://github.com/greenDGG)
