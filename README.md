# Invasión Espacial - Pygame

Videojuego arcade 2D estilo *shoot 'em up* desarrollado íntegramente en Python. Este proyecto es una aplicación práctica de arquitectura de software orientada a videojuegos, dejando de lado la consola de comandos (CLI) para gestionar una interfaz gráfica completa y eventos en tiempo real.

## Inventario de Habilidades Técnicas

Desarrollar un juego desde cero obliga a manejar conceptos que son la base de cualquier software interactivo:

* **Game Loop (Bucle Principal):** Implementación del ciclo infinito que mantiene el juego vivo, actualizando la pantalla y escuchando acciones del usuario a 60 FPS constantes.
* **Manejo de Eventos (Event Handling):** Captura de *inputs* del teclado en tiempo real para el movimiento fluido de la nave y el disparo de proyectiles.
* **Matemática de Colisiones:** Uso de fórmulas de distancia geométrica (módulo `math`) para calcular el momento exacto en el que la *hitbox* de un láser intercepta a la de un enemigo.

---

## Cómo ejecutar el juego (Source Code)

> **Nota del Desarrollador:** Este proyecto se distribuye exclusivamente mediante su código fuente (`.py`). No se incluyen archivos `.exe` precompilados. Esto garantiza la total transparencia del código y evita los falsos positivos o bloqueos por políticas de seguridad (Device Guard / SmartScreen) comunes en entornos Windows al usar herramientas de empaquetado como PyInstaller.

Para jugar en tu máquina local, sigue estos pasos:

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/TuUsuario/NombreDelRepo.git](https://github.com/TuUsuario/NombreDelRepo.git)

2. Instala el motor gráfico (utilizamos la versión Community Edition para máxima compatibilidad con versiones recientes de Python):
```bash
pip install pygame-ce
```

3. Ejecuta el archivo principal:
```bash
python main.py
```
Controles
Flecha Izquierda / Derecha: Mover la nave.

Barra Espaciadora: Disparar láser.
