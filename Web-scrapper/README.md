# 🕸️ Simple Web Scraper GUI

Pequeña aplicación en **Python + Tkinter** que descarga el texto visible de cualquier página web y lo guarda en un archivo `.txt` con un solo clic.  
Su objetivo es **educativo**: aprender los fundamentos de requests, parsing con Beautiful Soup y una interfaz gráfica mínima.

---

## ✨ Características

|                         | Descripción |
|-------------------------|-------------|
| **GUI cross-platform**  | Ventana Tkinter de ~500 px, sin dependencias de escritorio externas. |
| **Barra de progreso**   | Muestra el avance mientras descarga el HTML en streaming. |
| **Texto limpio**        | Elimina `<script>`, `<style>`, navegaciones, SVG & footers para quedarte con el contenido legible. |
| **Salida organizada**   | Guarda `scrape_YYYYMMDD_HHMMSS.txt` en la carpeta que elijas. |
| **User-Agent propio**   | Incluye un UA descriptivo; modifícalo si vas a distribuir la app. |

---

## 📦 Instalación

```bash
# Requiere Python 3.9 o superior
py -m pip install requests beautifulsoup4
