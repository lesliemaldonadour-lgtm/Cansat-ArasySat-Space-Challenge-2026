
# 🛰️ Cansat ArasySat - RAS / UCAP - Space Challenge 2026

## Misión Principal: 
1.Registrar la posición GPS (longitud, latitud y altura). (check)
2.Transmisión de datos de telemetría o datos de sensores. (check)
3.Registrar como mínimo tres variables atmosféricas, magnéticas o inerciales. (check) 
------Variables a medir: Temperatura ambiental, presión atmosférica, porcentaje de humedad, aceleración escalar, orientacion, campo magnético.

## Misión Secundaria: 
-Fusión de sensores / Filtro de Kalman
-Detección de fases de vuelo (Experimentos científicos o tecnológicos propios.)


## Flujo de trabajo: 

Sensores → ESP32 → Procesamiento → LoRa → Estación tierra → Análisis


Repositorio del proyecto **ArasySat**.

## 📁 Contenido

| Carpeta | Descripción |
|---------|-------------|
| [💻 Códigos](Codigos/Codigos.md) | Códigos del transmisor, receptor y pruebas de cada sensor |
| [🔩 Componentes](Componentes/Componentes.md) | Lista de componentes utilizados |
| [📚 Documentación](Documentaci%C3%B3n/) | Datasheets, diseño de la lata y diseño del circuito |
| [🖥️ Interfaz](Interfaz/Interfaz.md) | Estación terrestre (panel de telemetría) |
