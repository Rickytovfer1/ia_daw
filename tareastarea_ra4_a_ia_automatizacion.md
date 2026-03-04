# Práctica IA (RA4 · a) — Automatización y optimización

## 1) Proceso elegido
- Nombre del proceso: Gestión y clasificación de tickets de soporte IT
- Contexto (empresa/servicio web/IT): Empresa tecnológica que ofrece soporte técnico a clientes a través de una plataforma web de incidencias.
- Rol/es implicados:
  - Usuario/cliente
  - Agente de soporte nivel 1
  - Técnico especialista nivel 2
  - Responsable de IT / Service Manager
## 2) ANTES (sin IA)
- Pasos (5–7):
  1. El usuario envía un ticket describiendo el problema a través del portal web o por correo electrónico.
  2. Un agente de soporte revisa manualmente el ticket.
  3. El agente clasifica la incidencia.
  4. El agente asigna el ticket al técnico correspondiente.
  5. El técnico analiza el problema y solicita información adicional si es necesario.
  6. El técnico resuelve la incidencia y documenta la solución.
  7. Se cierra el ticket y se notifica al usuario.
- Tiempo aproximado por caso:Entre 25 y 40 minutos por ticket.
- Problemas / cuellos de botella:
  - Clasificación incorrecta por error humano.
  - Retrasos en la asignación cuando hay muchos tickets.
  - Sobrecarga del soporte nivel 1.
  - Tiempos de respuesta variables según volumen de trabajo.
  - Falta de priorización eficiente en momentos de alta demanda.

## 3) DESPUÉS (con IA)
- ¿Qué automatiza la IA?
  - Clasificación y priorización automática del ticket.
  - Asignación al técnico adecuado y sugerencia de soluciones frecuentes.
- ¿Qué queda para humanos?
  - Resolución de incidencias técnicas.
  - Supervisión y validación de casos críticos.
- Datos necesarios (tipos de datos, sin datos personales):
  - Texto del ticket.
  - Historial de incidencias y soluciones.
- Modelo/técnica (NLP, clasificación, recomendación, visión, etc.):
  - NLP para analizar el texto.
  - Modelo de clasificación supervisada.

## 4) Optimización (mejora medible)
Define 3 métricas con valores antes/después:
- Tiempo:
  Antes: 30 minutos por ticket  
  Después: 10 minutos por ticket  
- Coste:
  Antes: 15€ por ticket gestionado  
  Después: 8€ por ticket gestionado  
- Calidad:
  Antes: 75% de tickets bien clasificados  
  Después: 92% de tickets bien clasificados  

## 5) Diagrama del flujo (Mermaid)
    A[Usuario envía ticket] --> B[IA analiza texto]
    B --> C[Clasifica y prioriza]
    C --> D[Asigna a técnico]
    D --> E[Técnico resuelve incidencia]
    E --> F[Cierre del ticket]

## 6) Riesgos y mitigación
- Riesgo 1:
  Clasificación incorrecta de tickets por errores del modelo.
- Mitigación 1:
  Supervisión humana en casos críticos y reentrenamiento periódico del modelo.
- Riesgo 2:
  Dependencia excesiva de la automatización.
- Mitigación 2:
  Mantener revisión humana y protocolos manuales como respaldo.
  
## 7) Fuente oficial
- Enlace: 
  https://learn.microsoft.com/
