# Retroalimentación — Taller evaluativo 02: Funciones y POO

**Estudiante:** Jose David Muñoz Restrepo · **Taller:** Taller evaluativo 02 — Funciones y POO
**Fecha límite:** 2026-10-21 00:00 · **Versión revisada:** commit `26680c5`

Excelente trabajo: casi todo el taller quedó resuelto correctamente.

## Nota

| Criterio | Puntos |
|---|---|
| Funciones: parámetros, valores por defecto y retorno (Ej. 1 a 3) | 20 / 20 |
| `map`, `filter` y `lambda` (Ej. 4) | 10 / 10 |
| Clases, atributos y métodos (Ej. 5 y 7) | 15 / 15 |
| Encapsulamiento y validación (Ej. 6) | 15 / 15 |
| `__repr__` y `__str__` (Ej. 6 a 8) | 10 / 10 |
| Integración de funciones y clases (Ej. 8) | 10 / 10 |
| Ejecución sin errores | 10 / 10 |
| Documentación | 4 / 5 |
| Entrega correcta | 5 / 5 |
| **Total** | **99 / 100** |
| **Nota (0–5)** | **4.95** |

Este taller aporta **14.9 %** de los 15 % del momento evaluativo.

## 1. Funciones: parámetros, valores por defecto y retorno (20 / 20)
**Lo que hizo bien:**
- `calibrar_lectura` tiene los valores por defecto en la firma, usa `return` y da 11.5 y 12.0 como se esperaba.
- `es_lectura_valida` clasifica bien -999.0, 600.0, 25.0 y 0.0.
- `promedio_valido` reutiliza `es_lectura_valida`, usa solo variables locales, da 27.0 y devuelve `None` cuando no hay lecturas válidas.

## 2. `map`, `filter` y `lambda` (10 / 10)
**Lo que hizo bien:**
- Obtuvo las 5 lecturas calibradas (de 11.5 a 61.9) y las 2 excedencias, sin bucles ni comprensiones.

## 3. Clases, atributos y métodos (15 / 15)
**Lo que hizo bien:**
- `Lectura` guarda sus tres datos con valores por defecto y convierte bien los mg/m3 (25.2).
- `Estacion` guarda objetos `Lectura` y `valores()` usa `a_microgramos()` sin tocar sus atributos.

## 4. Encapsulamiento y validación (15 / 15)
**Lo que hizo bien:**
- `Sensor` lanza `ValueError` con código vacío o pendiente menor o igual a cero, antes de guardar datos.
- Guarda `_pendiente` e `_intercepto` como datos internos y `calibrar` reutiliza `calibrar_lectura`.
- No dejó celdas de prueba que fallen.

## 5. `__repr__` y `__str__` (10 / 10)
**Lo que hizo bien:**
- Los textos de `Sensor`, `Estacion` e `InformeEstacion` coinciden exactamente con lo pedido.

## 6. Integración de funciones y clases (10 / 10)
**Lo que hizo bien:**
- `InformeEstacion` da 31.9 y "Moderada" reutilizando las funciones y el método `calibrar` del sensor.
- `categoria_pm25` usa una sola cadena `if / elif / else` y cubre las cuatro categorías.

## 7. Ejecución sin errores (10 / 10)
**Lo que hizo bien:**
- El notebook corre completo sin errores y la celda final imprime el mensaje esperado.

## 8. Documentación (4 / 5)
**Lo que hizo bien:**
- Los ocho ejercicios tienen su celda de texto y todas las funciones, clases y métodos tienen docstring.
- Los nombres siguen `snake_case` y `PascalCase`.

**Lo que puede mejorar:**
- Falta la celda de texto inicial con el título del taller, su nombre completo y la fecha; el notebook empieza solo con el botón de Colab.
- Quedó una celda de texto vacía después del Ejercicio 3.

## 9. Entrega correcta (5 / 5)
**Lo que hizo bien:**
- El notebook está en `ejercicios/` con el nombre exacto y se ve en GitHub antes del plazo.

## ¿El notebook funciona?
Sí. Corre completo de principio a fin sin errores, la celda de verificación imprime "Verificación completada sin errores." y todos los resultados coinciden con los esperados.

## Para el próximo taller
- Incluya siempre la celda inicial con el título, su nombre completo y la fecha.
- Borre las celdas de texto vacías antes de entregar.
- Siga reiniciando y ejecutando todo antes de subir el notebook, como lo hizo aquí.
