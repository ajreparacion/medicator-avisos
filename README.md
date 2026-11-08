# MEDICATOR · Avisos

Temporizador gratuito que, cada 5 minutos, pide a MEDICATOR que revise las pastillas y citas y envíe los avisos al móvil.

Como GitHub no cumple las tareas programadas cada 5 minutos, cada ejecución se queda unas 6 horas revisando cada 5 minutos y, al terminar, lanza ella misma la siguiente. Las programadas cada 30 minutos son solo de reserva.

- Archivo: `.github/workflows/avisos.yml`
- Necesita el secreto `CRON_TOKEN` (Settings → Secrets and variables → Actions).
- Para pausarlo: pestaña **Actions** → «Avisos MEDICATOR» → **Disable workflow**.

By Neogest Lab
