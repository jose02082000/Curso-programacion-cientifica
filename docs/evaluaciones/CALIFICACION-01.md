# Retroalimentación — Taller evaluativo 01: Python y estructuras de datos

**Estudiante:** José David Muñoz Restrepo · **Taller:** Taller evaluativo 01 — Python y estructuras de datos
**Fecha límite:** 2026-10-15 23:59 · **Versión revisada:** commit `26680c5`

Muy buen trabajo: todos los ejercicios están bien resueltos y sus resultados coinciden con los esperados.

## Nota

| Criterio | Puntos |
|---|---|
| Variables, tipos y operadores (Ej. 1 a 4) | 20 / 20 |
| Condicionales y clasificación (Ej. 5) | 15 / 15 |
| Bucles, acumuladores y control de flujo (Ej. 6 a 8) | 30 / 30 |
| Estructuras de datos nativas (Ej. 9) | 15 / 15 |
| Ejecución sin errores | 6 / 10 |
| Documentación en celdas de texto | 4 / 5 |
| Entrega correcta | 5 / 5 |
| **Total** | **95 / 100** |
| **Nota (0–5)** | **4.75** |

Este taller aporta **14.3 %** de los 15 % del momento evaluativo.

## 1. Variables, tipos y operadores (20 / 20)
**Lo que hizo bien:**
- Las siete variables del Ejercicio 1 tienen el tipo exacto pedido y los verificó con `type()`.
- La conversión y los tres errores del Ejercicio 2 salen de operadores, no de valores escritos a mano.
- El Ejercicio 3 usa solo `//` y `%` y da 25 horas, 5 lecturas sobrantes, 1 día y 1 hora.
- El Ejercicio 4 usa `and` y `not`, sin `if`, y da los booleanos correctos.

## 2. Condicionales y clasificación (15 / 15)
**Lo que hizo bien:**
- Una sola cadena `if` / `elif` / `else`, ordenada de menor a mayor, sin huecos ni solapes.
- La lectura de 41.8 queda en "Dañina para grupos sensibles", como se esperaba.

## 3. Bucles, acumuladores y control de flujo (30 / 30)
**Lo que hizo bien:**
- Ejercicio 6: `continue` salta los dos datos faltantes antes de acumular; da 10 lecturas válidas y promedio 22.55.
- Ejercicio 7: máximo 58.3, mínimo 7.5, con dos recorridos y sin `max()`, `min()` ni `sum()`.
- Ejercicio 8: el `while` actualiza la concentración dentro del bloque y termina en 10 horas.

## 4. Estructuras de datos nativas (15 / 15)
**Lo que hizo bien:**
- Accede a cada dato por su clave y desempaqueta las coordenadas en `latitud` y `longitud`.
- Usa `get` con "no disponible", así que las estaciones sin humedad no producen error.
- Calcula y clasifica el promedio de cada estación correctamente.

## 5. Ejecución sin errores (6 / 10)
**Lo que hizo bien:**
- El notebook corre completo, de principio a fin, sin ningún error.

**Lo que puede mejorar:**
- Falta la celda de verificación final que entrega la guía. Sin ella no aparece el mensaje "Verificación completada sin errores." y no se pudo comprobar esa parte.

## 6. Documentación en celdas de texto (4 / 5)
**Lo que hizo bien:**
- Cada uno de los nueve ejercicios tiene su celda de texto previa que explica qué hace.
- Los nombres de variables son claros y están en `snake_case`.

**Lo que puede mejorar:**
- Falta la celda de texto inicial con el título del taller, su nombre completo y la fecha. La primera celda solo trae el botón de Colab.

## 7. Entrega correcta (5 / 5)
**Lo que hizo bien:**
- El notebook está en `ejercicios/` con el nombre exacto indicado, en la rama `main`.

## ¿El notebook funciona?
Sí, corre completo sin errores y los resultados coinciden con los valores esperados. Lo único que falta es la celda de verificación final, por lo que no aparece el mensaje de cierre.

## Para el próximo taller
- Copie siempre al final del notebook la celda de verificación que trae la guía, sin modificarla.
- Empiece el notebook con una celda de texto con el título, su nombre completo y la fecha.
- Antes de subir, use "Reiniciar y ejecutar todas" y confirme que el mensaje final aparece.
- Revise la lista de requisitos de la guía contra su notebook antes de entregar.
