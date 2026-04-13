# Práctica IA (RA4 · f)

## 1) Caso de uso
- Tipo de aplicación: Recomendador de productos en e-commerce
- Problema: El usuario no encuentra fácilmente productos relevantes
- Usuario: Clientes de tienda online

## 2) Datos
- Datos: Historial de compras y clics de usuarios
- Tipo minería: Minería de patrones

## 3) Pipeline
- Recogida: Datos de navegación y compras
- Limpieza: Eliminación de datos duplicados o incompletos
- Transformación: Conversión a formato estructurado
- Entrenamiento: Modelo de recomendación
- Predicción: Productos sugeridos al usuario
- Uso: Mostrar recomendaciones en la web

## 4) Integración
- Backend: API de recomendación (Python / Flask o FastAPI)
- Frontend: Página web de productos (React o HTML)
- Flujo: Usuario navega → Backend procesa datos → IA genera recomendaciones → Frontend muestra resultados

## 5) Valor
- Mejora: Personalización de productos y mejor experiencia de usuario
- Sin IA: Recomendaciones genéricas y menos ventas
- Rentabilidad: Aumento de conversión y ventas

## 6) Diagrama

```mermaid
graph TD
A[Usuario] --> B[Frontend Web]
B --> C[Backend API]
C --> D[Modelo IA]
D --> C
C --> B
B --> A[Recomendaciones]

## 7) Riesgos
- Riesgo 1: Uso indebido de datos personales
- Mitigación 1: Anonimización y cumplimiento de RGPD

- Riesgo 2: Recomendaciones incorrectas o sesgadas
- Mitigación 2: Entrenamiento con datos variados y validación del modelo

## 8) Fuente
- Fuente: https://www.ibm.com/topics/recommendation-systems
