# Producto — BoltLabHub

## Propuesta
Panel interno de control de TheBoltLab para coordinar múltiples apps sin depender de conversaciones dispersas.

## MVP
- Tarjeta por app.
- Versión y estado de código.
- Estado CI.
- Fase del workflow.
- Próxima acción.
- Enlace al repositorio.
- Indicadores globales.

## Después
- Sincronización segura con GitHub.
- Historial de releases.
- Google Play: test cerrado, producción y rollout.
- Bugs/incidencias.
- Métricas de usuarios, crashes e ingresos cuando existan fuentes conectadas.

## Seguridad
No exponer PAT, secrets ni credenciales en código cliente. Repos privados requieren integración de servidor/GitHub App o generación segura de datos.
