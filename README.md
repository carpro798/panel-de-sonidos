# ⚡ CARPRO ENTERPRISE SOLUTIONS | v4.5 "AETHELGARD"

![Status](https://img.shields.io/badge/Status-Stable-23A559?style=for-the-badge)
![Version](https://img.shields.io/badge/Build-4.5.0.3-5865F2?style=for-the-badge)
![License](https://img.shields.io/badge/Security-Enterprise_Grade-black?style=for-the-badge)

**Carpro Enterprise** es un motor de gestión multimedia de ultra-bajo nivel diseñado para entornos de alto rendimiento. No es solo una soundboard; es una arquitectura modular de procesamiento de señales con una interfaz lineal de grado industrial.

---

## 🛠 SYSTEM ARCHITECTURE (CAPAS DEL SISTEMA)

El software opera bajo un modelo de **Micro-Servicios Internos** para garantizar estabilidad absoluta:

| Capa | Componente | Función Técnica |
| :--- | :--- | :--- |
| **EGUI** | Enterprise Graphical Interface | Renderizado de alta densidad basado en CustomTkinter. |
| **HAL** | Hardware Abstraction Layer | Comunicación directa con drivers de audio vía SDL2. |
| **DAL** | Data Abstraction Layer | Persistencia de estados mediante serialización JSON asíncrona. |
| **SMP** | Signal Media Processor | Pipeline de conversión automática MP4/MP3 -> PCM Wave. |

---

## 🚀 CARACTERÍSTICAS PRINCIPALES

### 🔹 Interfaz de Grado Industrial
Diseño lineal optimizado para la eficiencia operativa. Sin distracciones visuales, enfocado en la precisión de los parámetros.

### 🔹 Motor de Audio de Latencia Cero
Utiliza buffers de pre-carga dinámicos para asegurar que el trigger del teclado y la salida de audio tengan un desfase menor a **15ms**.

### 🔹 Gestión de Recursos Inteligente
- **Auto-Cache**: Limpieza automática de archivos temporales.
- **Multi-Binding**: Soporte para asignación de teclas complejas.
- **Enterprise Settings**: Panel de ajustes rectos con sliders de precisión y switches de estado binario.

---
