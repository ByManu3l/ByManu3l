# Juan Manuel Romero Pineda

**Ingeniero de software full-stack** · Neiva, Colombia

Diseño, construyo y opero software en producción de extremo a extremo: modelo de datos, API, interfaz, pruebas, CI/CD y despliegue. Me importan la seguridad en la base de datos, el código que se puede probar y los sistemas que siguen funcionando cuando falla la red.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)

---

## Proyecto principal

### [GritBase](https://gritbase.app): gestión para gimnasios que funciona sin internet

SaaS multi-gimnasio en producción, con clientes que pagan, para gimnasios de barrio en Colombia. Cubre clientes, cobros, asistencia, medidas, rutinas, reportes y cumplimiento de la Ley 1581 de protección de datos. Es mi producto: lo diseño, desarrollo y opero solo, desde el modelo de datos hasta los releases firmados (**1.300+ commits**). El código es privado.

- **Multiplataforma:** web instalable (PWA), programa de Windows con actualizaciones automáticas firmadas y app de Android.
- **Funciona sin internet:** el gimnasio sigue atendiendo aunque se caiga la conexión, y todo se sincroniza al volver.
- **Datos aislados por gimnasio:** el aislamiento lo garantiza la propia base de datos, no solo la aplicación, y se verifica automáticamente en cada cambio.
- **Pagos en línea** con pasarelas reales, incluidos confirmaciones, reversos y comprobantes.
- **Calidad y operación:** TypeScript estricto, pruebas unitarias y end-to-end, CI/CD con despliegue continuo, respaldos diarios con pruebas de restauración y migraciones que nunca rompen hacia atrás.

`Next.js` `React` `TypeScript` `PostgreSQL` `Supabase` `Tauri` `Cloudflare`

[![Ver en vivo](https://img.shields.io/badge/Ver_en_vivo-gritbase.app-000000?style=for-the-badge&logo=googlechrome&logoColor=white)](https://gritbase.app) [![Descargar para Windows](https://img.shields.io/badge/Descargar-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ByManu3l/gritbase-releases/releases/latest)

## Otros proyectos

| Proyecto | Qué es | Lo destacable | Stack |
| --- | --- | --- | --- |
| **Pacandé** | E-commerce full-stack listo para adaptar a cualquier negocio: catálogo, carrito, cupones, opiniones, checkout y panel de administración. | 189 pruebas automáticas contra Postgres real, control de stock ante compras simultáneas, importes en decimal exacto y cero infracciones WCAG 2.1 AA. | Next.js · TypeScript · Prisma · PostgreSQL · Auth.js · Playwright |
| **Plataforma bancaria** | API REST para administrar clientes, cuentas de ahorro y corriente, y transacciones (consignaciones, retiros y transferencias), con frontend web. | 90 pruebas y 94,8 % de cobertura, transacciones ACID con control de concurrencia, patrón Strategy, cálculo del GMF y migraciones con Flyway. | Java 17 · Spring Boot 3 · JPA · PostgreSQL · React · Docker |
| **STOCKERR** | Sistema de inventario por microservicios (proyecto académico en equipo, Scrum). | API Gateway y 10 servicios (autenticación, usuarios, productos, categorías, inventario, proveedores, códigos de barras, exportación, configuración y auditoría) con JWT/RBAC. | Node.js · Express · PostgreSQL · Docker · React |

## Stack técnico

**Lenguajes** · TypeScript · JavaScript · Java · SQL · Python

**Frontend** · React · Next.js (App Router) · Tailwind CSS · PWA · accesibilidad (WCAG)

**Backend y datos** · Node.js · Express · Spring Boot · APIs REST · PostgreSQL · Supabase · Prisma

**Escritorio y móvil** · Tauri · PWA · Android

**Infraestructura y calidad** · Docker · GitHub Actions (CI/CD) · Cloudflare Workers · Vercel · Turborepo · Vitest · Playwright · JUnit

**Prácticas** · arquitectura limpia y por capas · SOLID · Conventional Commits · Scrum · ISO/IEC 25010

## Formación e idiomas

**Universidad Surcolombiana**: Ingeniería de Software, 11.° semestre (Neiva, Colombia).

**Idiomas**: español (nativo) e inglés (B2).

## Ahora mismo

Llevando GritBase a más gimnasios y terminando la carrera. **Abierto a oportunidades full-stack y backend.**

## Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juan-manuel-romero-pineda) [![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jumarop2225@gmail.com)
