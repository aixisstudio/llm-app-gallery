# Ai For Developers

[English](README.md) | [Français](README.fr.md) | **Español** | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

Cómo los devs usan la IA

## 🧰 Where AI actually helps devs
Silencioso en la tarea
|---|---|
Las pruebas de ← Boilerplate Generar, revisar, comprometer — la mayor victoria diaria
← Comprensión del código de Legacy ANTEPaste un archivo, pide un paseo
"Extraer esto, simplificar eso" — repasar la excusa
← Debugging ← Pegar el trazo + código, obtener hipótesis clasificadas
Silencio Docs &gt; comentarios Silencio Primeros borradores - pulir usted mismo
← Prototipos ← Horas → minutos en el código desechable

## 🔄 Flujos de trabajo que funcionan
- **Plan → agente → comentario** - usted escribe la especificaciones, el agente escribe el código, usted lee cada línea
- **Revisión Oleada** - nunca aceptar ciego; pida al modelo que explique su propio diff
* * Comprobación multimodelo* – segunda opinión sobre los cambios de riesgo
- **Primero aviso** - pedir pruebas antes de la aplicación

## 🧱 Los patrones de integración
TEN TERRITOR SON SON TEN ANTE
|---|---|
Silencioso finalización de la charla
Ø Función llamando a Silencio Deja que el modelo llame a tus APIs
Respuesta de *su* docs/data
← Agentes TENIDO tareas multi-paso con herramientas
Las pruebas de regresión de imprevisto/versión

## ⋅ Anti-patterns
- Blind-pasting código generado para prod
- Llevar secretos/PII a los avisos - ver dónde van sus datos ([Snitch](https://github.com/aixisstudio/Snitch) muestra cada conexión de salida 😉)
- Prompting whole codebases en lugar de contexto estrecho
- Pruebas de saltar porque "la AI lo escribió"

## 🚀 Nave más rápido con AI

TEN TERRITORIO TERRITORIO ANTERIOR
|---|---|
Ø Intección de API Ø `litellm` → cualquier proveedor
Silencio Producción estructurada ← `instructor` (Pydantic)
Silencio Caching Silencio `diskcache` + prompt hash Silencio
TENIDO RAG TENIDO `chromadb` + incrustaciones
Evals Silencioso `promptfoo` / Braintrust
Silenciosos Agentes Silencio `pydantic-ai` / LangGraph

## The 80/20

La mayoría de las aplicaciones de IA = streaming + salida estructurada + un índice RAG. Maestro esos tres antes de tocar a los agentes.

---
## Contribuir

Los pull requests son bienvenidos: abre una PR y será revisada y fusionada. Mantenido por [aixisstudio](https://github.com/aixisstudio), autor de [Snitch](https://github.com/aixisstudio/Snitch), firewall de aplicaciones open source.

## Licencia: MIT
