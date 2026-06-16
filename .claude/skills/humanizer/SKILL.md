---
name: humanizer
description: Reescribe texto generado por IA para que suene natural y humano. Usar cuando el usuario pida "humanizar", "/humanizer" o reescribir un texto para que no parezca escrito por una IA.
---

# Humanizer

Reescribe el texto que te pase el usuario (por argumento o pegado en el mensaje) para que suene como si lo hubiera escrito una persona, conservando el significado original.

## Qué cambiar

- Variar la longitud y el ritmo de las oraciones; evitar que todas tengan la misma estructura.
- Eliminar muletillas típicas de IA: "es importante destacar que", "en conclusión", "cabe mencionar", "sin duda", excesivos conectores formales.
- Reducir el uso de listas y encabezados cuando no son necesarios; preferir prosa corrida si el original era una lista artificial.
- Quitar paralelismos forzados y repeticiones de estructura (ej. tríadas "no solo X, sino también Y").
- Usar vocabulario concreto y específico en vez de genérico o vago.
- Mantener (o introducir con moderación) pequeñas imperfecciones naturales: alguna oración más informal, contracciones, orden de palabras menos perfecto.
- Conservar el idioma original del texto (si está en español, responder en español; si está en inglés, en inglés).
- No agregar información nueva ni cambiar el significado, hechos o cifras del texto original.

## Qué no hacer

- No agregar disclaimers ni explicaciones sobre el proceso de humanización.
- No usar emojis ni formato markdown excesivo si el original no lo tenía.
- No exagerar a tal punto que el texto pierda claridad o profesionalismo si el contexto lo requiere (ej. un texto técnico o formal debe seguir siendo correcto, solo menos "robótico").

## Salida

Devolver únicamente el texto reescrito, sin comentarios adicionales, a menos que el usuario pida explícitamente una comparación o explicación de los cambios.
