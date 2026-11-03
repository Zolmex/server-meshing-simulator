# server-meshing-simulator

Simulador interactivo de Server Meshing en un único HTML sin dependencias externas. Incluye tres modos:

- **Estático**: la cuadrícula de servidores no se mueve.
- **Dinámico**: los límites de las zonas se desplazan según la carga.
- **Escalado elástico**: divide y fusiona servidores automáticamente, con arranque, drenaje, traspasos, cooldowns y registro de eventos.

## Uso

Abre `server-meshing.html` en un navegador. No requiere servidor ni instalación.

Parámetros opcionales:

- `?seed=NUMERO`: fija la semilla del generador pseudoaleatorio para reproducir una partida.