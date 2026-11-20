# Backlog — Sistema Comedor Industrial (Equipo 4)

Sistema de Gestión de Inventarios y Requisiciones para Comedor Industrial.
Product Owner: Jesús Bernardo Robles Gómez. Equipo 4, Proyecto II.

- Repositorio: https://github.com/jesusrobles6455/Sistema-inventario-comedor
- Tablero: https://trello.com/b/EljLQAt2/mi-tablero-de-trello
- Video: https://youtu.be/_eDgEgUAOxA

Estado al corte del 16 de noviembre de 2026 (Actividad 2). Fuente: documento del proyecto, Actividad 2.

## Product Backlog

| ID | Historia de usuario | Alias | Estado | Esfuerzo | Iteración | Prioridad |
|---|---|---|---|---|---|---|
| HU-01 | Como almacenista, quiero visualizar y actualizar el inventario con indicadores visuales (círculos verde, rojo, gris) para mantener el stock al día. | Actualización de stock | Terminado | 8 pts | Sprint 1 | Alta |
| HU-02 | Como gerente, quiero consultar la disponibilidad de insumos en tiempo real para planificar el resurtido. | Dashboard compras | Parcial | 5 pts | Sprint 1 | Alta |
| HU-03 | Como cocinero, quiero consultar la cantidad disponible de ingredientes para planificar la preparación del día. | Visualización cocina | Por hacer | 5 pts | Sprint 2 | Alta |
| HU-04 | Como cocinero, quiero emitir solicitudes de insumos mediante una alerta (ícono de campana) para notificar faltantes. | Solicitud y requisición | Por hacer | 5 pts | Sprint 2 | Media |
| HU-05 | Como gerente y almacenista, quiero recibir notificaciones automáticas cuando un insumo llegue a su nivel mínimo. | Alertas stock mínimo | Por hacer | 3 pts | Sprint 3 | Media |
| HU-06 | Como almacenista, quiero registrar la entrada de nuevo insumo cuando llega la compra para reabastecer el inventario. | Registro reabastecimiento | Por hacer | 3 pts | Sprint 3 | Baja |

Nota: la HU-03 tiene 5 pts en el Product Backlog y 3 SP en el Sprint Backlog. Es una diferencia ya señalada en el documento del proyecto.

## Sprint Backlog

### Sprint 1 — Actualización de Stock y Dashboard de Compras (4 al 25 de noviembre de 2026)

Historias: HU-01, HU-02. Total: 13 SP. Objetivo: realizar la actualización de stock de la materia prima así como el Dashboard de consulta para compras. Resultado: parcial. El avance verificado en el repositorio es el código subido el 7 de septiembre de 2026 (tabla de inventario con semáforos, lógica de estados y filtro por categoría). El 11 de noviembre de 2026 se retomó el código con Vite + React (Pull Request #1 fusionado a main). Del 11 al 16 de noviembre se completaron las tareas 1.3 y 1.4; HU-01 quedó cerrada. Corte del avance (Actividad 2): 16 de noviembre de 2026; las tareas 2.3 y 2.4 siguen por hacer (23 y 24 de noviembre).

| Elemento de trabajo | SP | Responsable | Estado | Tiempo est. | Tiempo real | Revisión |
|---|---|---|---|---|---|---|
| ID-01: Actualización de stock de materia prima | 8 SP | Equipo Scrum | Terminado | 16 hrs | 16 hrs | Módulo terminado: semáforos, lógica de estados, formulario de edición y pruebas unitarias verificados en el repositorio; HU-01 cerrada (Actividad 2, 16 de noviembre de 2026). |
| Tarea 1.1: Diseño de interfaz UI con indicadores | — | Frontend Dev | Terminado | 4 hrs | 4 hrs | Interfaz limpia, responsiva y funcional completada. |
| Tarea 1.2: Programar la lógica de estados de stock | — | Frontend Dev | Terminado | 6 hrs | 6 hrs | Manejo de estado en React implementado correctamente. |
| Tarea 1.3: Conectar formulario de edición | — | Frontend Dev | Terminado | 4 hrs | 4 hrs | Formulario de edición conectado y funcional (inputs controlados, handlers onChange/onSubmit); completado el 12 de noviembre de 2026. |
| Tarea 1.4: Realizar pruebas unitarias de estados | — | QA Engineer | Terminado | 2 hrs | 2 hrs | Pruebas unitarias sobre alteración de inventario (7 pruebas, Vitest); completadas el 13 de noviembre de 2026. |
| ID-02: Dashboard de consulta para compras | 5 SP | Equipo Scrum | Parcial | 10 hrs | 6 hrs | Vista parcial: filtro por categoría y tabla verificados en el repositorio; faltan el cálculo visual de insumos y la validación de consistencia. |
| Tarea 2.1: Diseñar vista Dashboard para gerencia | — | Frontend Dev | Parcial | 3 hrs | 3 hrs | Vista base con filtro y tabla; faltan las tarjetas de totales (tarea 2.3). |
| Tarea 2.2: Configurar filtros por categorías | — | Frontend Dev | Terminado | 3 hrs | 3 hrs | Filtros funcionales mediante .filter() operativos. |
| Tarea 2.3: Implementar cálculo visual de insumos | — | Frontend Dev | Por hacer | 3 hrs | 0 hrs | Pendiente: no hay cálculo visual de totales en el repositorio; se propone como avance de la Unidad 4. |
| Tarea 2.4: Validar consistencia de datos de stock | — | QA Engineer | Por hacer | 1 hr | 0 hrs | Pendiente: no hay validación de consistencia en el repositorio; se propone como avance de la Unidad 4. |
| TOTALES | 13 SP | — | Parcial | 26 hrs | 22 hrs | Sprint 1 parcial: 5 terminadas, 1 parcial y 2 por hacer; HU-01 cerrada (corte 16 de noviembre de 2026). |

### Sprint 2 — Unidad de Cocina y Requisiciones Urgentes (26 de noviembre al 9 de diciembre de 2026)

Historias: HU-03, HU-04. Total: 8 SP. Estado: 0% hecho.

| Elemento de trabajo | SP | Responsable | Estado | Tiempo est. | Tiempo real | Revisión |
|---|---|---|---|---|---|---|
| ID-03: Visualización para cocina | 3 SP | Equipo Scrum | Por hacer | 6 hrs | 0 hrs | Por ejecutar en iteración programada. Vista rápida ligera de consulta asignada para el personal de cocina. |
| Tarea 3.1: Diseñar pantalla responsiva para cocina | — | Frontend Dev | Por hacer | 2 hrs | 0 hrs | Estructura para tablets de cocina planificada. |
| Tarea 3.2: Programar buscador de ingredientes | — | Frontend Dev | Por hacer | 2 hrs | 0 hrs | Filtro dinámico por coincidencias de texto plano. |
| Tarea 3.3: Pruebas de la vista read-only de stock | — | QA Engineer | Por hacer | 2 hrs | 0 hrs | Vista read-only validada: bloqueo de eventos de escritura verificado. |
| ID-04: Solicitud y requisición de insumos | 5 SP | Equipo Scrum | Por hacer | 10 hrs | 0 hrs | Por ejecutar en iteración programada. Sistema de alertas de campana e intercomunicación hacia almacén. |
| Tarea 4.1: Crear modal de generación de solicitudes | — | Frontend Dev | Por hacer | 3 hrs | 0 hrs | Componente emergente de captura de requisiciones. |
| Tarea 4.2: Conectar el hook de estado de la campana | — | Frontend Dev | Por hacer | 3 hrs | 0 hrs | Lógica del disparador visual del icono de alerta. |
| Tarea 4.3: Enlazar estados lógicos con Almacén | — | Frontend Dev | Por hacer | 2 hrs | 0 hrs | Paso de propiedades (props) e interconexiones lógicas. |
| Tarea 4.4: Validar envío de alertas de emergencia | — | QA Engineer | Por hacer | 2 hrs | 0 hrs | Flujo y ciclo de vida de alertas integradas. |
| TOTALES | 8 SP | — | 0% hecho | 16 hrs | 0 hrs | Tareas por hacer (HU-03 y HU-04). |

### Sprint 3 — Automatizaciones y Registro de Compras (10 al 23 de diciembre de 2026)

Historias: HU-05, HU-06. Total: 6 SP. Estado: 0% hecho.

| Elemento de trabajo | SP | Responsable | Estado | Tiempo est. | Tiempo real | Revisión |
|---|---|---|---|---|---|---|
| ID-05: Alertas de stock mínimo | 3 SP | Equipo Scrum | Por hacer | 6 hrs | 0 hrs | Por ejecutar en iteración programada. Automatización de semáforo reactivo por límites configurados. |
| Tarea 5.1: Definir umbrales mínimos (minStock) | — | Frontend Dev | Por hacer | 2 hrs | 0 hrs | Atributo de cuotas mínimas en modelo de datos. |
| Tarea 5.2: Programar disparador en hook useEffect | — | Frontend Dev | Por hacer | 2 hrs | 0 hrs | Ciclo de vida condicional para evaluar límites. |
| Tarea 5.3: Validar encendido automático de campana | — | QA Engineer | Por hacer | 2 hrs | 0 hrs | Activación automática al cruzar el umbral crítico. |
| ID-06: Registro de reabastecimiento | 3 SP | Equipo Scrum | Por hacer | 8 hrs | 0 hrs | Por ejecutar en iteración programada. Módulo formal de entradas de facturas y órdenes de compra. |
| Tarea 6.1: Diseñar formulario de entrada de compras | — | Frontend Dev | Por hacer | 3 hrs | 0 hrs | Formulario controlado de carga de facturas recibidas. |
| Tarea 6.2: Programar función sumatoria sobre stock | — | Frontend Dev | Por hacer | 3 hrs | 0 hrs | Mutación aditiva segura del estado de inventario base. |
| Tarea 6.3: Validar sanidad de campos | — | QA Engineer | Por hacer | 2 hrs | 0 hrs | Bloqueos y manejo de excepciones numéricas negativas. |
| TOTALES | 6 SP | — | 0% hecho | 14 hrs | 0 hrs | Por realizar ID: HU-05 (Automatizaciones) y HU-06 (Registro de compras). |
