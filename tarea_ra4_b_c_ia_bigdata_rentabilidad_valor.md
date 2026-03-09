# Práctica IA (RA4 · b+c) — Big Data, análisis, rentabilidad y valoración IA

# Práctica IA (RA4 · b+c) — Big Data, análisis, rentabilidad y valoración IA

## 1) Caso y objetivo de negocio
- Empresa/sector (real o ficticia): ShopSmart, una tienda online ficticia dedicada a la venta de productos electrónicos, accesorios tecnológicos y gadgets.
- Problema a resolver: La empresa recibe muchas visitas en su web, pero una gran parte de los usuarios no finaliza la compra. Además, los clientes no siempre encuentran productos que se ajusten a sus intereses.
- Objetivo de negocio (rentabilidad): Aumentar las ventas mediante la recomendación inteligente de productos personalizados y mejorar la experiencia de usuario para reducir el abandono del carrito.

## 2) Big Data: recogida masiva de datos
Describe por qué es Big Data (volumen, velocidad, variedad).

- Fuente 1: Datos de navegación de los usuarios en la web.
- Fuente 2: Historial de compras de los clientes.
- Fuente 3: Opiniones y reseñas de productos escritas por los usuarios en la plataforma.

- Volumen/velocidad (estimación): Miles de usuarios visitan la web diariamente, generando millones de eventos de navegación y registros de actividad que se almacenan y procesan en tiempo casi real.

- Formatos (texto, eventos, series temporales, imágenes, etc.): 
  - Eventos de navegación: clics, búsquedas, visitas a productos
  - Texto: reseñas y comentarios de clientes
  - Series: temporales historial de compras a lo largo del tiempo
  - Imágenes: fotografías de los productos en el catálogo

## 3) Tratamiento/análisis: pipeline de datos
Explica el flujo de forma ordenada:

- Ingesta (captura/eventos):  
Los datos se capturan automáticamente cuando los usuarios interactúan con la web. Cada clic, búsqueda, producto visto o compra genera un evento que se envía al sistema de recogida de datos en tiempo real.

- Limpieza/normalización:  
Se eliminan datos duplicados o incompletos, se corrigen formatos incorrectos y se estandarizan los nombres de productos, usuarios y categorías para que todos los datos sean coherentes.

- Almacenamiento (data lake/warehouse):  
Los datos procesados se almacenan en un data lake donde se guardan grandes volúmenes de información. Posteriormente, los datos más relevantes se organizan en un data warehouse para facilitar su análisis.

- Preparación de variables (features):  
Se crean variables útiles para el modelo de IA, como el número de productos vistos por usuario, categorías favoritas, frecuencia de compra o tiempo medio entre compras.

- Análisis/BI (opcional):  
Los analistas utilizan herramientas de Business Intelligence para visualizar tendencias, analizar el comportamiento de los clientes y detectar oportunidades de mejora en las ventas.

## 4) IA aplicada: modelo y decisión

- Tipo de IA/técnica (clasificación, predicción, recomendación, anomalías, NLP...):  
Sistema de recomendación basado en aprendizaje automático para sugerir productos personalizados a cada usuario.

- Entrada del modelo (qué datos usa):  
Historial de compras de los usuarios, productos visitados, categorías de interés, tiempo de navegación y comportamiento general dentro de la tienda online.

- Salida del modelo (qué produce):  
Una lista de productos recomendados que tienen mayor probabilidad de interesar al usuario.

- Decisión que habilita (qué hace la empresa con esa salida):  
La tienda muestra recomendaciones personalizadas en la página principal para aumentar la probabilidad de que el cliente compre más productos.

## 5) Rentabilidad: KPIs antes/después (mínimo 3)

KPI 1 (ingresos/coste/eficiencia): Tasa de conversión de visitantes a compradores  
- Antes: 2% de los visitantes realizaban una compra.  
- Después: 3.5% de los visitantes realizan una compra gracias a las recomendaciones personalizadas.  
- Por qué mejora la rentabilidad: Aumenta el número de ventas sin necesidad de incrementar el gasto en publicidad.

KPI 2: Valor medio del pedido (ticket medio)  
- Antes: 35 € por pedido.  
- Después: 50 € por pedido debido a recomendaciones de productos relacionados.  
- Por qué mejora la rentabilidad: Los clientes compran más artículos en cada pedido, lo que incrementa los ingresos por cliente.

KPI 3: Tasa de abandono del carrito  
- Antes: 70% de los usuarios abandonaban el carrito sin comprar.  
- Después: 55% de abandono gracias a sugerencias relevantes y promociones personalizadas.  
- Por qué mejora la rentabilidad: Se recuperan más ventas que antes se perdían, aumentando los ingresos totales.

## 6) Diagrama del pipeline (ASCII o Mermaid)
(Pega aquí el diagrama)

## 7) Riesgos y mitigación
Riesgo 1:
- Mitigación 1:

Riesgo 2:
- Mitigación 2:

## 8) Valoración (criterio c): importancia presente y futura de la IA (10–15 líneas)
- Importancia actual (hoy):
- Importancia futura (3–5 años):
- Condiciones/limitaciones (datos, costes, regulación, ética, seguridad, empleo):
- Conclusión razonada:

## 9) Fuentes oficiales (mín. 2)
- Big Data/analítica (enlace oficial):
- IA/técnica/modelo (enlace oficial):
