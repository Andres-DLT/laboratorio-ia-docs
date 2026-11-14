# Roadmap del laboratorio de IA

- Fecha del documento: 2026-11-06.
- Estado: propuesta; generar este registro no ejecuta ni autoriza los experimentos.
- Consultar primero [el estado documentado](ESTADO.md).

## Hito 1: inventario actual de solo lectura

- Confirmar hardware, versiones y modelos disponibles sin modificar servicios.
- Registrar diferencias frente a los experimentos historicos.
- Seleccionar un solo candidato inicial con base en pruebas actuales, no por el nombre o por un resultado antiguo.
- Acordar limites de recursos, alcance y autorizacion antes de comenzar.

## Hito 2: piloto directo y aislado

- Proponer una tarea pequena en un espacio de trabajo nuevo, sin datos personales.
- Comenzar por la entrada directa de OpenCode con confirmaciones para las acciones.
- No montar directorios personales completos ni otorgar acceso innecesario a servicios o credenciales.
- Definir pruebas funcionales y de recuperacion antes de evaluar la entrega.

## Hito 3: comparacion acotada

- Definir tres tareas comparables y la misma metodologia para los candidatos.
- Probar un modelo a la vez y conservar condiciones, versiones y limites de cada intento.
- Separar respuesta valida, pruebas de logica, integracion y aceptacion de uso real.
- Registrar fallos y reintentos; no convertir el resultado en un ranking general.

## Hito 4: decidir la integracion web

- Evaluar Open WebUI y Computer solo si el piloto directo cumple sus criterios.
- Revisar aprobaciones, permisos, aislamiento y comportamiento desatendido.
- El plan historico contempla una ruta web sin confirmacion por cada comando; no habilitarla como si tuviera las mismas garantias de la entrada directa.
- Una guardia de tarea escritora unica organiza concurrencia, pero no es un sandbox del sistema operativo.
- Pedir autorizacion separada para cambios de servicios, red, datos o acceso.

## Hito 5: reproducibilidad y continuidad

- Registrar recuperacion, persistencia y restauracion antes de afirmar que el laboratorio es operativo.
- Mantener evidencia por sistema y hardware probado; no extrapolar automaticamente a otro equipo.
- Conservar artefactos y respaldos fuera del registro documental.

- [Inicio](README.md).
- [Evidencias y limites de partida](EVIDENCIA.md).
