# SEAMP1 - Parpadeo de un LED con Raspberry Pi 3 B+

## Descripción

Programa en Python que hace parpadear un LED conectado al GPIO 18 (pin físico 12) usando la librería RPi.GPIO en modo BCM. El LED se enciende durante 1 segundo y se apaga durante 1 segundo, de forma continua, y la consola muestra el estado actual. El programa se detiene con Ctrl+C.

## Materiales

- Raspberry Pi 3 B+ con Raspberry Pi OS Lite 64-bit
- 1 LED
- 1 resistencia (por ejemplo 220 Ω)
- Cables de conexión (jumpers) y protoboard

## Conexión

| Componente | Conexión |
|---|---|
| GPIO 18 (pin físico 12) | Resistencia, luego pata larga (ánodo) del LED |
| Pata corta (cátodo) del LED | GND (por ejemplo, pin físico 14) |

## Cómo ejecutarlo

1. Conectarse a la Pi por SSH.
2. Activar el entorno virtual:

```
source 8s11/bin/activate
```

3. Ejecutar el programa:

```
python SEAMP1.py
```

## Salida esperada

```
Control de LED iniciado (Modo BCM)
Usando GPIO 18 (Pin físico 12)
Presiona Ctrl+C para salir
LED
