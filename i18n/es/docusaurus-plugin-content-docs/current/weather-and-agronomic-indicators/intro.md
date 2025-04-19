---
sidebar_label: "Introduction"
sidebar_position: 1
---

## 🌤️ Clima e Indicadores Agronómicos (Integrado con Campos y Lotes)

### 🎯 Objetivo

Proveer datos meteorológicos y agronómicos clave para **anticipar eventos climáticos**, **planificar labores**, y **reducir riesgos** productivos, integrados a cada campo o lote cargado en la app.

---

### 🔗 Integración con Campos

Cada campo registrado tendrá:

- Coordenadas geográficas (lat/lon)
- Asociación automática con una fuente climática (API externa o estación propia)
- Visualización de clima actual, pronóstico y datos históricos específicos para ese campo

---

### 🔑 Funcionalidades Clave

#### 1. Clima Actual por Campo

- 🌡️ Temperatura actual
- 💧 Humedad relativa
- 🌬️ Viento (velocidad y dirección)
- 🌧️ Precipitaciones últimas 24h
- ☀️ Radiación solar (opcional)

> **Fuente sugerida:** OpenWeather, Climatic, INTA, o estaciones propias.

---

#### 2. Pronóstico del Tiempo (5-7 días)

- Temperaturas máximas y mínimas
- Probabilidad de lluvia
- Alertas meteorológicas (heladas, tormentas, olas de calor)
- Visualización en calendario o timeline de labores

---

#### 3. Alertas Inteligentes

- ⚠️ Fumigación: advertir si se espera lluvia o viento fuerte
- ❄️ Heladas: alerta para cultivos sensibles o épocas críticas
- 🔥 Ola de calor: recomendaciones para manejo de ganado o riego

> Las alertas se generan automáticamente según el pronóstico asociado al campo.

---

#### 4. Histórico Climático por Campo o Lote

- Precipitaciones acumuladas (día, semana, mes, campaña)
- Número de heladas
- Comparativas entre campañas anteriores
- Visualización en gráficos simples

---

#### 5. Índices Agronómicos (Versión Expandida)

- 🌿 **NDVI** (Índice de vegetación): vía imágenes satelitales
- 📈 **Grado-día**: seguimiento del desarrollo de cultivos
- 💦 **Índice hídrico**: cálculo simple combinando clima + suelo

---

### 🧪 MVP Sugerido para esta Funcionalidad

1. Geolocalización de cada campo.
2. Clima actual y pronóstico de 7 días visible desde el perfil del campo.
3. Timeline de eventos climáticos importantes.
4. Alertas básicas por clima (ej: lluvia próxima).
5. Visualización de lluvias acumuladas de los últimos 7 días.

---

### 📲 Visualización Sugerida

- Módulo de clima dentro del detalle de cada campo.
- Dashboard resumen con clima actual de todos los campos.
- Notificaciones push o email ante alertas relevantes.
