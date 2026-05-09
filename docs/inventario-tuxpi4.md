# Inventario de `tuxpi4`

Snapshot tomado desde `nujev@tuxpi4`.

## Estado del sistema

- Hostname: `tuxpi4`
- Sistema operativo: Debian GNU/Linux 13 (trixie)
- Arquitectura: `arm64`
- Kernel: `6.12.75+rpt-rpi-v8`
- Usuario principal: `nujev`
- Shell: `/bin/bash`
- Disco raíz: 28 GB ext4, ~18 GB libres
- Memoria: 3.7 GiB RAM, 2.0 GiB swap

## Red y acceso

- `eth0` activo con IP `192.168.68.141/24`
- `wlan0` apagado
- `tailscale0` activo con IP `100.70.193.55`
- SSH habilitado y accesible
- Tailscale activo con MagicDNS y hostname `tuxpi4.tail60681a.ts.net`
- `gh` autenticado con la cuenta `nujev`

## Herramientas base detectadas

- Python 3.13.5
- pip 25.1.1
- `gh`
- `build-essential`
- utilidades de red y administración del sistema

## Historial de shell relevante

Se ha visto actividad previa de:

- actualización y mantenimiento del sistema con `apt update`, `apt upgrade`, `autoremove` y `autoclean`
- instalación y configuración de Tailscale
- instalación de `gh` y autenticación contra GitHub
- clonación de repositorios de trabajo
- creación y uso de entornos virtuales de Python
- instalación de dependencias con `pip`
- arranque de aplicaciones web con `uvicorn`
- creación y edición de archivos `.env`
- uso de `ssh-copy-id`

## Repositorios presentes

### `~/github/acciones`

Repositorio de un bot de trading para BMV / Hey Banco.

- Rama actual: `main`
- Árbol limpio sin cambios locales
- Stack principal: Python, Flask, SQLite, Telegram, `yfinance`, `pandas`, `pandas-ta`
- Contiene scripts de arranque, validación, servicios systemd, cron y documentación extensa
- Incluye Docker y pruebas/recursos de soporte

### `~/github/criptos`

Repositorio de un bot HFT para Binance Futures USDC.

- Rama actual: `main`
- Árbol limpio sin cambios locales
- Stack principal: Python, FastAPI, Uvicorn, SQLite asíncrono, pytest, Playwright
- Contiene aplicación, configuración, herramientas de backtesting, frontend y batería amplia de tests
- Incluye Docker, `package.json`, `pytest.ini`, `mypy.ini` y configuración de estilos/lint

## Resumen operativo

`tuxpi4` ya está listo para usarse como equipo de trabajo: acceso SSH operativo, Tailscale activo, GitHub autenticado y dos repositorios principales montados y limpios.
