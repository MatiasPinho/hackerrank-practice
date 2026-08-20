# Convenciones para diagramas de flujo

Usar una convención consistente en todos los ejercicios.

| Símbolo | Uso |
|---|---|
| Óvalo | Inicio / Fin |
| Paralelogramo | Entrada / Salida |
| Rectángulo | Proceso, asignación o cálculo |
| Rombo | Decisión o condición |
| Flecha | Dirección del flujo |
| Círculo | Conector cuando sea necesario |

## Reglas prácticas

- Mantener el flujo principal de arriba hacia abajo.
- Escribir condiciones claras dentro de los rombos.
- Etiquetar las ramas de decisión, normalmente con `Sí` y `No`.
- Evitar cruces innecesarios de flechas.
- No meter varios pasos conceptualmente distintos dentro de un mismo rectángulo.
- El diagrama debe representar el algoritmo, no la sintaxis específica del lenguaje.

## Secuencia recomendada

```text
Enunciado
  ↓
Entradas / Salidas
  ↓
Variables y restricciones
  ↓
Solución en lenguaje natural
  ↓
Diagrama de flujo
  ↓
Prueba de escritorio
  ↓
Pseudocódigo
  ↓
Código
  ↓
Pruebas
```
