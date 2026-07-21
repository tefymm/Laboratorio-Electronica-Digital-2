# Laboratorio 1 - Contador de Décadas y Binario

**Universidad del Valle de Guatemala**  
**Curso:** Electrónica Digital 2  
**Estudiante:** Stephany Mejía Morataya

## Descripción

Este proyecto implementa un contador utilizando un **ESP32**, cuatro LEDs y tres botones.

Cuenta con dos modos de funcionamiento:

- **Modo 0:** Contador de décadas (0–9).
- **Modo 1:** Contador binario (0–15).

Al cambiar de modo, el contador se reinicia en **0**.

## Botones

| Botón | Función |
|--------|---------|
| **Bmas** | Incrementa el contador |
| **Bmenos** | Disminuye el contador |
| **Bmod** | Cambia entre los dos modos |

## Conexiones

### LEDs

| LED | GPIO |
|-----|------|
| LED0 | 4 |
| LED1 | 16 |
| LED2 | 17 |
| LED3 | 18 |

### Botones

| Botón | GPIO |
|--------|------|
| Bmas | 39 |
| Bmenos | 34 |
| Bmod | 35 |

## Herramientas

- ESP32
- PlatformIO
- Visual Studio Code
- Framework Arduino
- GitHub
