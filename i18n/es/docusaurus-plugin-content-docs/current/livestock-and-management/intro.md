---
sidebar_label: "Introduccion"
sidebar_position: 1
---

# 🐄 Gestión Ganadera

## 🎯 Objetivo

Permitir al productor o encargado llevar un **registro digital básico de los animales**, su ubicación, estado sanitario y movimientos clave, para mejorar el control operativo y la eficiencia.

---

## 🔑 Funcionalidades del MVP

### 1. Registro de Rodeo

- Alta de animales:
  - Individual o por lote/categoría
  - Datos clave: número de caravana, sexo, raza, fecha de nacimiento o edad estimada
- Clasificación:
  - Por categoría: terneros, vaquillonas, vacas, toros
  - Por finalidad: recría, engorde, vientres, etc.
- Asociación con campo/potrero/lote

---

### 2. Movimientos

- Cambio de potrero o campo
- Ingresos y egresos (ventas, muertes, compras)
- Fecha y motivo

---

### 3. Sanidad

- Registro de vacunaciones y tratamientos:
  - Fecha
  - Tipo (vacuna, antiparasitario, etc.)
  - Producto aplicado
- Alertas para refuerzos o próximos tratamientos

---

### 4. Reproducción (Opcional MVP++)

- Servicios: toro natural o inseminación artificial
- Diagnóstico de preñez
- Pariciones esperadas y reales

---

### 5. Dashboard Básico

- Total de animales por categoría
- Últimos movimientos
- Alertas sanitarias próximas
- Tasa de mortandad o egresos

---

## 📲 Flujo Mínimo de Uso

1. El usuario crea su campo.
2. Carga sus animales (manualmente, vía Excel o con lector de caravanas más adelante).
3. Registra eventos (movimientos, sanidad).
4. Visualiza el resumen y las alertas en el panel.

---

## 🧠 ¿Y a Futuro?

- Trazabilidad completa con SENASA (API SIGSA, caravanas electrónicas)
- Integración con balanzas o lectores RFID
- Control de alimentación y consumos
- Gestión económica por animal o lote
