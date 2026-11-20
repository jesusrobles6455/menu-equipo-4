# Backlog — Sublisant (EcoTrend)

Proyecto de sublimación con tinta ecológica de baja densidad: EcoTrend, e-commerce de productos sustentables de sublimación.
Desarrollador: Alejandro Rafael Plascencia Lopez. Trabajado por el equipo en la Unidad 3.
Profesora: Deisy Acosta Ham.

- Repositorio: https://github.com/alex99-ai/proyecto-sublisant
- Tablero: https://alejandro-plascencia.atlassian.net/jira/software/projects/SCRUM/boards/1
- Video: https://youtu.be/kX7IeUPLceU

Estado al corte del 10 de noviembre de 2026 (cierre del Sprint 3). Fuente: documento del proyecto.

## Product Backlog

| ID | Historia de usuario | Alias | Estado | Esfuerzo | Iteración | Prioridad |
|---|---|---|---|---|---|---|
| ID-01 | Como cliente nuevo, quiero registrar mis datos en la plataforma para crear una cuenta personal. | Registro de Cliente | Terminado | 2 SP | Sprint 1 | Alta |
| ID-02 | Como usuario registrado, quiero iniciar sesión de forma segura para acceder a mis datos guardados. | Login Seguro | Terminado | 2 SP | Sprint 1 | Alta |
| ID-03 | Como visitante, quiero navegar por una cuadrícula responsiva de productos eco-friendly disponibles. | Catálogo Virtual | Terminado | 3 SP | Sprint 2 | Alta |
| ID-04 | Como comprador, quiero añadir o eliminar artículos sustentables dentro de un carrito de compras. | Carrito Interactivo | Terminado | 3 SP | Sprint 1 (remanente cerrado en Sprint 2) | Alta |
| ID-05 | Como cliente en checkout, quiero que el sistema calcule el costo de envío e IVA automáticamente. | Motor de Costos | Terminado | 3 SP | Sprint 2 | Media |
| ID-06 | Como comprador, quiero pagar el total de mi pedido con tarjeta de débito o crédito mediante Stripe. | Pasarela de Pagos | Terminado | 5 SP | Sprint 3 | Media |
| ID-07 | Como usuario en pasarela, quiero ver una pantalla clara que me confirme el éxito o error de mi pago. | Confirmación de Pago (éxito/error) | Terminado | 3 SP | Sprint 3 | Media |
| ID-08 | Como comprador, quiero recibir una notificación con el número de guía para rastrear mi paquete externamente. | Conexión Logística | Terminado | 3 SP | Sprint 3 | Baja |
| ID-09 | Como cliente, quiero poder facturar mis compras en la misma página. | Facturación | Por hacer | 3 SP | Sprint 4 (11 al 24 de noviembre) | Baja |
| ID-10 | Como cliente, quiero ver en el pie de página un contacto con la empresa. | Contacto | Por hacer | 3 SP | Sprint 4 (11 al 24 de noviembre) | Baja |

Resumen del backlog: 30 SP en total · 24 SP terminados · 0 SP en progreso · 6 SP por hacer.

## Sprint Backlog

### Sprint 1 (30 de septiembre al 13 de octubre de 2026)

Historias planeadas al inicio: ID-01 e ID-02 (4 SP) y, de forma anticipada, ID-04 Carrito (3 SP): 7 SP en total. Meta: registro y login seguros y un carrito con persistencia y validación de stock. Resultado: cumplida de forma parcial; el backend del carrito y su persistencia quedaron listos, la interfaz del carrito pasó a remanente. Resultado: 4 de 7 SP terminados (ID-01 e ID-02) y 30 de 34 horas planeadas completadas.

| Elemento de trabajo | SP | Responsable | Estado | Tiempo est. | Tiempo real | Revisión |
|---|---|---|---|---|---|---|
| ID-01: Registro de Cliente | 2 SP | Equipo Scrum | Terminado | 11 hrs | 11 hrs | Se finalizó la base de datos y se comprobó su funcionamiento. |
| Tarea 1.1: Diseño de formulario | — | Frontend Dev | Terminado | 3 hrs | 3 hrs | Interfaz práctica, responsiva y bien organizada. |
| Tarea 1.2: API Endpoint | — | Backend Dev | Terminado | 4 hrs | 4 hrs | El endpoint opera y mantiene la conexión con la base de datos. |
| Tarea 1.3: Pruebas de integración | — | QA Engineer | Terminado | 4 hrs | 4 hrs | Pruebas de detección de correos repetidos. |
| ID-02: Login Seguro | 2 SP | Equipo Scrum | Terminado | 11 hrs | 11 hrs | La autenticación se ejecuta adecuadamente en el servidor. |
| Tarea 2.1: Encriptación BCrypt | — | Backend Dev | Terminado | 3 hrs | 3 hrs | Las contraseñas se resguardan con hash. |
| Tarea 2.2: Flujo de tokens JWT | — | Backend Dev | Terminado | 4 hrs | 4 hrs | Manejo y validación de sesiones activas. |
| Tarea 2.3: Interfaz visual de Login | — | Frontend Dev | Terminado | 4 hrs | 4 hrs | Pantalla de inicio de sesión conectada con el backend. |
| ID-04: Carrito Interactivo | 3 SP | Equipo Scrum | Parcial (remanente) | 12 hrs | 8 hrs | 2 de 3 tareas terminadas al 13/10. No se contabilizan SP: la historia no cumple aún la definición de Hecho. |
| Tarea 4.1: Interfaz del carrito | — | Frontend Dev | Remanente → Sprint 2 | 4 hrs | 0 hrs | No se alcanzó a integrar al cierre; se re-planifica en el Sprint 2. |
| Tarea 4.2: Verificación de stock | — | Backend Dev | Terminado | 5 hrs | 5 hrs | Endpoint de validación listo; responde 409 si se excede el inventario. |
| Tarea 4.3: LocalStorage | — | Frontend Dev | Terminado | 3 hrs | 3 hrs | Carrito sincronizado con LocalStorage; conserva la sesión al recargar. |
| TOTALES (Sprint 1) | 7 SP | — | 4 SP Done (57%) | 34 hrs | 30 hrs | Tareas terminadas: 30 de 34 hrs planeadas (88%). ID-01 e ID-02 cumplidas; ID-04 queda como remanente. |

### Sprint 2 (14 al 27 de octubre de 2026)

Se incorporó el remanente del carrito (Tarea 4.1) junto con las historias ID-03 e ID-05. Meta cumplida; el Sprint se cerró el 27 de octubre de 2026. Total: 6 SP + remanente · 27 hrs (100%).

| Elemento de trabajo | SP | Responsable | Estado | Tiempo est. | Tiempo real | Revisión |
|---|---|---|---|---|---|---|
| ID-04: Carrito Interactivo (remanente) | — | Equipo Scrum | Terminado | 4 hrs | 4 hrs | Remanente del Sprint 1 cerrado el 19 de octubre de 2026 (PR #5). |
| Tarea 4.1: Interfaz del carrito | — | Frontend Dev | Terminado | 4 hrs | 4 hrs | Interfaz del carrito con total y verificación de disponibilidad; cerrada el 19 de octubre de 2026. |
| ID-03: Catálogo Virtual | 3 SP | Equipo Scrum | Terminado | 11 hrs | 11 hrs | Cuadrícula responsiva, API de productos e imágenes optimizadas con carga diferida. |
| Tarea 3.1: Cuadrícula | — | Frontend Dev | Terminado | 4 hrs | 4 hrs | Maquetación con CSS Grid, adaptable a móvil y escritorio. |
| Tarea 3.2: API de productos | — | Backend Dev | Terminado | 5 hrs | 5 hrs | Servicio GET /api/productos. |
| Tarea 3.3: Optimizar imágenes | — | Frontend Dev | Terminado | 2 hrs | 2 hrs | loading="lazy" y decoding="async": carga diferida de imágenes. |
| ID-05: Motor de Costos | 3 SP | Equipo Scrum | Terminado | 12 hrs | 12 hrs | Cálculo en tiempo real: subtotal, peso, IVA (16%) y envío por región y código postal. |
| Tarea 5.1: Lógica de cálculo | — | Backend Dev | Terminado | 5 hrs | 5 hrs | Subtotal, peso total (0.35 kg por artículo) e IVA al 16%. |
| Tarea 5.2: API de paqueterías | — | Backend Dev | Terminado | 4 hrs | 4 hrs | Tarifas por región y código postal; cargo por kg adicional; envío gratis arriba de $1,200 MXN. |
| Tarea 5.3: Resumen de orden | — | Frontend Dev | Terminado | 3 hrs | 3 hrs | Resumen de orden en tiempo real al cambiar cantidades y código postal. |
| TOTALES (Sprint 2) | 6 SP | — | 100% hecho | 27 hrs | 27 hrs | 27 hrs (100%): 11 hrs de ID-03, 12 hrs de ID-05 y 4 hrs de la Tarea 4.1, absorbiendo el remanente del carrito. |

### Sprint 3 (28 de octubre al 10 de noviembre de 2026)

Historias: ID-06 (Pasarela de Pagos), ID-07 (Confirmación de Pago) e ID-08 (Conexión Logística). Total: 11 SP (5 + 3 + 3) · 38 horas estimadas · 38 horas reales. Meta: cerrar el ciclo comercial integrando la pasarela de pagos Stripe y automatizando la generación de las guías de envío. Resultado: 11 de 11 SP terminados (38 de 38 hrs). Se completó el flujo transaccional y post-venta y se fusionó en la rama main (PR #9).

| Elemento de trabajo | SP | Responsable | Estado | Tiempo est. | Tiempo real | Revisión |
|---|---|---|---|---|---|---|
| ID-06: Pasarela de Pagos | 5 SP | Equipo Scrum | Terminado | 18 hrs | 18 hrs | Integración de Stripe bajo los lineamientos de PCI-DSS: los datos de tarjeta se capturan con Stripe Elements. |
| Tarea 6.1: SDK de Stripe | — | Backend Dev | Terminado | 4 hrs | 4 hrs | Configuración del SDK de Stripe y variables de entorno seguras en el servidor Express. |
| Tarea 6.2: Intenciones de pago | — | Backend Dev | Terminado | 5 hrs | 5 hrs | Endpoint POST /api/checkout/crear-intento-pago para crear PaymentIntents desde el servidor. |
| Tarea 6.3: Formulario seguro | — | Frontend Dev | Terminado | 5 hrs | 5 hrs | Formulario seguro de tarjeta en Carrito.jsx con Stripe Elements. |
| Tarea 6.4: Pruebas transaccionales | — | QA Engineer | Terminado | 4 hrs | 4 hrs | Pruebas con tarjetas de prueba (4242 exitosa y 0002 declinada) y casos de error. |
| ID-07: Confirmación de Pago (éxito/error) | 3 SP | Equipo Scrum | Terminado | 10 hrs | 10 hrs | Mitigación de la duplicación de cobros. |
| Tarea 7.1: Endpoint receptor (webhook) | — | Backend Dev | Terminado | 3 hrs | 3 hrs | Endpoint receptor de eventos de cobro POST /api/webhook/stripe. |
| Tarea 7.2: Actualización BD | — | Backend Dev | Terminado | 3 hrs | 3 hrs | Actualización del pedido a "Pagado", descuento de stock y prevención de doble cobro. |
| Tarea 7.3: Pantalla de éxito/error | — | Frontend Dev | Terminado | 4 hrs | 4 hrs | Pantalla de confirmación de éxito o error del pago, con opción de reintento. |
| ID-08: Conexión Logística | 3 SP | Equipo Scrum | Terminado | 10 hrs | 10 hrs | Conectividad con las compañías de mensajería. |
| Tarea 8.1: API de Guías | — | Backend Dev | Terminado | 4 hrs | 4 hrs | Generación automática del número de guía por paquetería (Estafeta, FedEx, DHL). |
| Tarea 8.2: Notificación automatizada | — | Backend Dev | Terminado | 3 hrs | 3 hrs | Notificación al correo del comprador con el comprobante y la guía. |
| Tarea 8.3: Interfaz de tracking | — | Frontend Dev | Terminado | 3 hrs | 3 hrs | Interfaz de tracking conectada a GET /api/logistica/rastreo/:guia. |
| TOTALES (Sprint 3) | 11 SP | — | 11 SP Done (100%) | 38 hrs | 38 hrs | Tareas terminadas: 38 de 38 hrs (100%): 18 hrs de ID-06, 10 hrs de ID-07 y 10 hrs de ID-08, ejecutadas durante las 2 semanas del Sprint. |

### Sprint 4 (11 al 24 de noviembre de 2026, planificado)

Historias: ID-09 (Facturación) e ID-10 (Contacto), añadidas por petición del cliente en la Sprint Review del Sprint 1. Total: 6 SP (3 + 3) · 22 horas estimadas. Meta: permitir al cliente facturar en la misma página y conocer los datos de contacto de la empresa, para reforzar la confianza y la imagen comercial.

| Elemento de trabajo | SP | Responsable | Estado | Tiempo est. | Tiempo real | Revisión |
|---|---|---|---|---|---|---|
| ID-09: Facturación | 3 SP | Equipo Scrum | Por hacer | 12 hrs | 0 hrs | Inclusión simplificada del flujo fiscal en la misma página. |
| Tarea 9.1: Diseño de formulario web | — | Frontend Dev | Por hacer | 4 hrs | 0 hrs | Maquetación limpia en la misma página de compras. |
| Tarea 9.2: API Endpoint y captura de datos | — | Backend Dev | Por hacer | 4 hrs | 0 hrs | Procesamiento local seguro de la información del cliente. |
| Tarea 9.3: Pruebas de flujo y validación | — | QA Engineer | Por hacer | 4 hrs | 0 hrs | Validación de campos obligatorios y formato de correo. |
| ID-10: Contacto en pie de página | 3 SP | Equipo Scrum | Por hacer | 10 hrs | 0 hrs | Módulo de confianza y soporte al cliente. |
| Tarea 10.1: Maquetación visual del footer | — | Frontend Dev | Por hacer | 3 hrs | 0 hrs | Enlaces de redes sociales, teléfonos y correos. |
| Tarea 10.2: Formulario dinámico de soporte | — | Frontend Dev | Por hacer | 3 hrs | 0 hrs | Interfaz para el envío de dudas o reportes directos. |
| Tarea 10.3: Servicio de correos (notificación) | — | Backend Dev | Por hacer | 2 hrs | 0 hrs | Envío automático hacia la bandeja de la empresa. |
| Tarea 10.4: Pruebas de seguridad y recepción | — | QA Engineer | Por hacer | 2 hrs | 0 hrs | Control de spam y verificación de entregas exitosas. |
| TOTALES (Sprint 4) | 6 SP | — | 0% hecho | 22 hrs | 0 hrs | Sprint calendarizado con las historias añadidas por el cliente. |
