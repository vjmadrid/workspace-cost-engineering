# Suite de Agentes de Cost Engineering y AI FinOps

Esta carpeta contiene agentes especializados en coste, eficiencia, gobierno y sostenibilidad de sistemas con IA.

Este documento recoge los agentes disponibles en `.github/agents`

## Agentes incluidos

| Agente | Uso breve | Fichero |
| --- | --- | --- |
| Token Cost Guardian | Detecta riesgo de consumo excesivo de tokens antes de ejecutar tareas con IA. | `token-cost-guardian.md` |
| AI Cost Optimizer | Compara alternativas y evita usar IA generativa cuando una solución más simple basta. | `ai-cost-optimizer.md` |

## Estructura estándar de un agente

Cada agente define, cuando aplica:

- `Contexto`
- `Misión`
- `Casos de uso`
- `Estilo de comunicación`
- `Idioma`
- `Reglas`
- `Criterios a evaluar`
- `Principios`
- `Niveles`
- `Salida esperada`
- `Formato de respuesta`

Los ficheros usan nombres descriptivos sin prefijo numérico. Si un entorno de Copilot requiere explícitamente el sufijo `.agent.md` para descubrir agentes, estos ficheros pueden duplicarse o renombrarse manteniendo el contenido.

## Uso recomendado

Estos agentes se han diseñado para ser usados como copilotos desde Visual Studio Code pero sus prompts de definición (system prompts) podrían ser utilizados desde cualquier IA conversacional.

La cabecera técnica de este tipo de agentes esta pensada para ser interpretada por GitHub Copilot, por lo que cualquier otra IA no lo interpretará con esa funcionalidad, lo interpretará como más texto que formará parte del contexto.

## Workflow recomendado

Usa estos agentes como una capa de revisión previa antes de ejecutar tareas con IA, aprobar arquitecturas, desplegar features con LLMs o escalar soluciones agentic.

- Usa `token-cost-guardian.md` antes de tareas grandes o ambiguas
- Usa `ai-cost-optimizer.md` para comparar alternativas y evitar el uso innecesario de IA generativa
