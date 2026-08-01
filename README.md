[README_vector_cargo.md](https://github.com/user-attachments/files/30621879/README_vector_cargo.md)
# ✈️ Vector Cargo — Dashboard de Operaciones

Dashboard operativo tipo "centro de control" para una aerolínea de carga, con KPIs en tiempo real, gráficos interactivos y panel de alertas. Construido con HTML, CSS y Chart.js — un solo archivo, sin backend.

**🔗 Demo en vivo:** https://kleiberb.github.io/vector-cargo-dashboard/

## ✨ Características

- **KPIs operativos**: puntualidad, utilización de flota, volumen de carga y costo de combustible, con indicadores de variación
- **Gráfico de tendencia** de 12 meses con doble eje (puntualidad % vs. volumen de carga)
- **Gráfico de rutas** con el volumen top por destino
- **Medidor circular (SVG)** de utilización de flota
- **Tabla de vuelos** con estados en vivo (a tiempo / retraso / embarcando)
- **Panel de alertas operativas** con niveles de severidad
- **Ticker inferior** tipo tablero de aeropuerto, con animación de scroll infinito
- Reloj y fecha en tiempo real
- Diseño responsivo con estética de centro de control (oscuro, ámbar/teal)

## 🛠️ Tecnologías

- **Chart.js** — gráficos de línea y barras interactivos
- **SVG** — medidor circular de utilización
- **CSS Grid** y animaciones puras (ticker, indicador de estado en vivo)
- **JavaScript vanilla** — reloj en tiempo real, generación dinámica de tablas y alertas
- Tipografía: Oswald (títulos), Inter (texto), JetBrains Mono (datos)

## 📊 Sobre los datos

Este demo usa datos ficticios para mostrar el diseño y la funcionalidad. En un proyecto real, el dashboard se conecta a la fuente de datos del cliente (Excel, base de datos o API) para actualizarse automáticamente.

## 🚀 Cómo usarlo

Abre `index.html` en cualquier navegador moderno, o visita el [demo en vivo](https://kleiberb.github.io/vector-cargo-dashboard/). No requiere instalación.

## 👤 Autor

**Kleiber Benavides** — KB Afterburner Data
Desarrollo de dashboards, automatización y visualización de datos.
📩 Disponible para proyectos freelance en Workana.
