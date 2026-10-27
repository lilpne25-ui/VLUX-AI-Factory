# 02 · Pilot Zero v0.1 — Primera prueba de la Factory

**Estado:** propuesto · **Entorno:** aislado y sin datos reales de clientes

## Nuestra primera meta

Demostrar **una sola tarea pequeña**, desde su registro en GitHub hasta su revisión y cierre documentado. No necesitamos todavía una plataforma ni un servidor 24/7.

**Proyecto de prueba:** por seleccionar entre Ludwing y Rodrigo. Se sugiere una mejora menor en un repositorio interno existente, con datos ficticios. No tocar código ni infraestructura de clientes sin una autorización separada.

## Recorrido de la primera prueba

1. **Elegir el caso:** qué problema concreto resolveremos y cómo sabremos que está resuelto.
2. **Crear el GitHub Issue:** descripción, límites, responsable y criterios de aceptación.
3. **Preparar el entorno:** Levet/Bruno comprueba MSA v6 candidata, Claude Code y permisos mínimos. Si algo falta, lo registra.
4. **Especificar el átomo:** documento breve con lo que entra, lo que no entra y la prueba que debe pasar.
5. **Autorizar y ejecutar:** trabajo en rama de prueba, sin acceso a producción ni despliegue.
6. **Probar y revisar:** recopilar resultados verificables y errores. Una revisión del mismo agente no cuenta como independiente.
7. **Cerrar:** Ludwing revisa lo técnico; Rodrigo confirma que cumple lo solicitado. Registrar decisión y pendientes.

## Resultado que debemos poder enseñar

Un Issue, una especificación aprobada, una rama o cambio propuesto, pruebas con evidencia, revisión, horas humanas, consumo de IA (medido o marcado como estimado) y decisión final.

## Condiciones para declarar éxito

- Alcance confirmado antes de programar.
- Ningún dato real ni secreto expuesto.
- Cambios hechos exclusivamente en entorno permitido.
- Pruebas realmente ejecutadas, no solo declaradas.
- Fallos documentados y corregidos o escalados.
- Resultado aceptado por las personas designadas.
- Posibilidad de explicar y repetir el proceso sin depender de una conversación privada.

**Si falta evidencia, el estado es PENDIENTE; no PASS.** Ningún cierre técnico autoriza automáticamente fusionar código o desplegar.

## No incluye

Orquestador automático, dashboard, nuevos servicios pagos, integración con clientes ni prospección. Todo eso se evalúa **después** de la primera prueba.
