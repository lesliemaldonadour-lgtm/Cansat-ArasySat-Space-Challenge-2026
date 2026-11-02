Cansat ArasySat - RAS / UCAP

Misión Principal: 
1.Registrar la posición GPS (longitud, latitud y altura). (check)
2.Transmisión de datos de telemetría o datos de sensores. (check)
3.Registrar como mínimo tres variables atmosféricas, magnéticas o inerciales. (check) 
------Variables a medir: Temperatura ambiental, presión atmosférica, porcentaje de humedad, aceleración escalar, orientacion, campo magnético.

Misión Secundaria: 
-Fusión de sensores / Filtro de Kalman
-Detección de fases de vuelo (Experimentos científicos o tecnológicos propios.)


Flujo de trabajo: 

Sensores → ESP32 → Procesamiento → LoRa → Estación tierra → Análisis

TELEMETRÍA

-Tranmisión en tiempo real.
-Registro en CSV de los datos que recibe el ESP32.
# 🛰️ ArasySat – Space Challenge Py 2026

Repositorio del proyecto **ArasySat**.

## 📁 Contenido

| Carpeta | Descripción |
|---------|-------------|
| [💻 Códigos](Codigos/Codigos.md) | Códigos del transmisor, receptor y pruebas de cada sensor |
| [🔩 Componentes](Componentes/Componentes.md) | Lista de componentes utilizados |
| [📚 Documentación](Documentaci%C3%B3n/) | Datasheets, diseño de la lata y diseño del circuito |
| [🖥️ Interfaz](Interfaz/Interfaz.md) | Estación terrestre (panel de telemetría) |

### 📚 Documentación
- [Datasheets](Documentaci%C3%B3n/Datasheets/Datasheets.md)
- [Diseño de la lata](Documentaci%C3%B3n/Dise%C3%B1o%20de%20la%20lata/Dise%C3%B1o%20de%20la%20lata.md)
- [Diseño del circuito](Documentaci%C3%B3n/Dise%C3%B1o%20del%20circuito/Dise%C3%B1o%20del%20circuito.md)
