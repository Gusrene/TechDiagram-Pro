# TechDiagram Pro ⚡🎥🔌

**TechDiagram Pro** es una plataforma web interactiva y gratuita diseñada para la ingeniería, diagramación y cuantificación de sistemas especiales de seguridad electrónica, redes de datos, infraestructura IoT, instalaciones fotovoltaicas y almacenamiento de energía en baterías (BESS).

---

## 🚀 Características Principales

### 1. Librerías de Componentes Especializados
* **CCTV & Seguridad Física:** Cámaras IP (Domo, Bullet 4K, PTZ), NVRs/VMS, controladores de acceso IP, lectoras biométricas, cerraduras magnéticas y botones REX.
* **Energía Solar Fotovoltaica & BESS:** Paneles solares TOPCon/Bifaciales (580W), inversores de string y microinversores, bancos de baterías de litio LiFePO4, cajas combinadoras DC y protecciones DPS.
* **Redes & Telecomunicaciones:** Switches PoE/PoE+, routers de borde, Access Points Wi-Fi 6 y gabinetes en rack.
* **IoT & Automatización:** Gateways LoRaWAN, sensores ambientales, PLCs industriales y medidores Modbus.

### 2. Trazado de Canalizaciones y Mapeo Normativo
* **Cálculo según TIA-569 / NEC:** Medición automática de metros lineales para Tubería EMT (3/4" y 1"), PVC, Conduit y Escalerillas / Bandejas tipo Malla.
* **Cómputo de Accesorios:** Conteo automático de cajas de paso 4"x4", chalupas, coples de unión y abrazaderas de soporte espaciadas normativamente.
* **Alertas Normativas:** Notificación en tiempo real si un tramo excede los 30 metros sin caja de halado o si supera dos curvas de 90°.

### 3. Calibración sobre Planos Arquitectónicos
* Carga de planos en formato **PNG, JPG o SVG**.
* Herramienta de **Calibración de Escala Real (📏)** indicando la distancia exacta de un muro o cota.
* Control de **opacidad** y visibilidad del plano de fondo.

### 4. Asistente de Cálculo Fotovoltaico (NEC 690 & IEC 62548)
* Cálculo de tensión máxima de circuito abierto corregida por temperatura mínima ($V_{oc\_max}$).
* Verificación de rangos de seguimiento MPPT e índice de sobredimensionamiento DC/AC.
* Estimación de generación diaria en $kWh/\text{día}$ según Horas Sol Pico (HSP).

### 5. Exportación y Lista de Materiales (BOM)
* Generación de cómputo métrico e inventario de equipos.
* Exportación de la **Lista de Materiales (BOM)** a formato **CSV / Excel** con mermas de seguridad aplicadas (+10% en cableado, +5% en canalización).
* Guardado del diagrama en **JSON** y exportación de plano gráfico en **SVG**.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5 Canvas / SVG:** Renderizado vectorial interactivo de alta velocidad.
* **JavaScript (ES6+):** Motor de cálculo técnico y manipulador de eventos.
* **CSS3 (Flexbox/Grid):** Interfaz limpia, responsiva y temática en modo oscuro técnico.

---

## ⚙️️ Despliegue Local o en Vercel

### Para desarrollo local:
Basta con clonar el repositorio y abrir el archivo `index.html` en cualquier navegador web moderno:

```bash
git clone [https://github.com/Gusrene/TechDiagram-Pro.git](https://github.com/Gusrene/TechDiagram-Pro.git)
cd TechDiagram-Pro
# Abre index.html directamente en tu navegador