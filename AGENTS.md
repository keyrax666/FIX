# FIX — Reglas de colaboración entre agentes de IA

## Autoridad
- El fundador es CEO, director creativo y propietario. Ningún agente puede asumir facultades financieras, legales o administrativas.
- Los agentes proponen cambios y se revisan mutuamente. No se atribuye autonomía real a un modelo sin configurar previamente una integración y un ejecutor.
- Prohibido publicar, habilitar compras, modificar permisos, integrar servicios de pago o usar datos de usuarios reales sin aprobación del propietario.

## Roles funcionales (no proveedores asignados todavía)
1. **Producto y UX:** convierte las ideas del CEO en historias de usuario y prototipos; mantiene la identidad FIX.
2. **Ingeniería:** implementa frontend, backend, pruebas y documentación.
3. **Seguridad y privacidad:** revisa autenticación, permisos, manejo de ubicación, exposición de datos y riesgos.
4. **QA:** realiza pruebas funcionales, responsividad, accesibilidad y regresión.
5. **Integración:** compara alternativas, verifica compatibilidad y prepara pull requests explicados para el CEO.

Los roles se pueden desempeñar con distintos modelos y herramientas tras pruebas comparativas. No atribuir a Claude, Gemini, Codex u otros una participación que no haya ocurrido.

## Flujo de comunicación
1. Registrar una tarea con criterios de aceptación y prioridad.
2. Un agente implementador trabaja en una rama independiente.
3. Otro agente revisa el cambio; seguridad revisa cualquier modificación a cuentas, contactos o localización.
4. Ejecutar pruebas automatizadas y manuales de recorridos críticos.
5. Abrir pull request con resumen legible para el CEO, capturas cuando proceda, riesgos y resultados.
6. Mantener cambios de alto impacto sin fusionar hasta aprobación explícita del CEO.

## Reglas de calidad
- No inventar perfiles, calificaciones o verificaciones como si fueran reales.
- Los datos de demostración deben aparecer etiquetados como ficticios.
- Preservar búsquedas sin cuenta para clientes.
- No publicar ubicaciones precisas sin autorización.
- No añadir el signo "." al logotipo FIX.
- Revisar cambios y evitar alterar archivos no relacionados.
- Escribir instrucciones entendibles para una persona sin conocimientos de programación.
- Documentar limitaciones: «prototipo», «demo», «pendiente» frente a «producción».

## Etiquetas recomendadas para tareas
product, ux, frontend, backend, security, qa, documentation, ai-agents

## Seguridad operacional
- Secretos solo en sistemas de secretos apropiados; nunca en código, issues o mensajes.
- Privilegios mínimos para agentes y tokens.
- No conceder acceso de escritura simultáneo sobre la rama principal sin revisiones.
- Conservar historial y un procedimiento de reversión.
