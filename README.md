## Jean Carlos Guillén Gatica

Desarrollador de soluciones de negocio. Construyo aplicaciones web que la gente usa todos los días para trabajar.

Ahora mismo tengo **cinco sistemas propios en producción**: una red de 77 farmacias los usa para pedir insumos y aprobar pagos, un centro médico controla con ellos su inventario por lote y vencimiento, y cinco comercios venden a diario con mi punto de venta.

El código de esos sistemas es privado porque pertenece a los clientes. Lo que publico aquí es el método y las técnicas.

### En qué trabajo

- **Google Apps Script** — Web Apps con Google Sheets como base de datos
- **Firebase** — Firestore, Authentication, Hosting
- **IA aplicada** — ingeniería de prompts, evaluación Side-by-Side (SxS), integración de modelos en productos reales
- **Desarrollo asistido por agentes** — Claude Code sobre sistemas en producción

### Algunas cosas que resolví

- Llevé una carga en frío de **10.650 lecturas de Firestore a 1**, con caché e invalidación por sello de versión. Antes, la cuota diaria se agotaba y dejaba a los operarios sin servicio.
- Implementé **inicio de sesión único (SSO)** entre dos sistemas independientes, con catálogos conciliados sobre 77 códigos comunes.
- Diseñé un control de inventario médico con rotación **FEFO** por lote y vencimiento, tres roles de permisos separados y auditoría completa sin borrado físico de registros.

### Repositorios

- **[claude-code-en-produccion](https://github.com/jeangaticag/claude-code-en-produccion)** — reglas, plantilla de contexto y checklist para operar un agente de codificación sobre sistemas en uso.
- **[pdf-a-datos](https://github.com/jeangaticag/pdf-a-datos)** — extrae filas estructuradas de un PDF con Gemini y verifica que la extracción esté completa cuadrando totales.
  **[agente-inventario](https://github.com/jeangaticag/agente-inventario)** — un agente con herramientas sobre un inventario de ejemplo: el bucle, los guardarraíles y los límites.

### Contacto

Mérida, Venezuela · Disponible para trabajo remoto a tiempo completo

jeangaticag@gmail.com · [LinkedIn](https://www.linkedin.com/in/jean-carlos-guillen-gatica/)
