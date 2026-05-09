# Instrucciones para Copilot

## Comandos de build, test y lint

- Actualmente el repositorio no define comandos de build, test ni lint en archivos versionados.
- Tampoco existe todavía una forma de ejecutar una prueba individual, porque no hay suite de tests, manifiestos de dependencias, `Makefile` ni flujos de CI registrados.
- Antes de proponer comandos nuevos, revisar primero si ya quedaron declarados en archivos añadidos más adelante al repositorio.

## Arquitectura de alto nivel

- Este repositorio está pensado como un repositorio de **dotfiles y configuración** para una **Raspberry Pi 4B+**.
- La intención es que actúe como **fuente de verdad** para poder reconstruir una instalación desde cero, restaurar la máquina tras una incidencia o reaplicar la configuración base de forma consistente.
- A día de hoy el contenido versionado sigue siendo mínimo, así que la arquitectura real todavía está emergiendo. Cuando se añadan más archivos, hay que interpretar su papel dentro de ese objetivo de bootstrap, recuperación y mantenimiento del sistema.

## Convenciones clave

- Todo el contenido y la documentación del repositorio deben mantenerse en **español**.
- Tratar cada cambio como parte de un repositorio de **reinstalación y recuperación**: priorizar archivos, scripts y configuraciones que permitan recrear el estado de la Raspberry desde cero.
- Para no perder avances, cada mejora o hito útil debe **quedar versionado en Git y publicarse en remoto** en cuanto esté listo.
- No asumir herramientas, lenguaje principal ni layout técnico hasta que existan archivos versionados que lo definan explícitamente.
- Cuando se introduzcan scripts o configuraciones base, documentar en el propio repositorio cómo se aplican o restauran para que futuras sesiones puedan reutilizar el flujo correcto sin depender de suposiciones.
