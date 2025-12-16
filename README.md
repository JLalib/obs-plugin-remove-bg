# 🎥 Plugin OBS con IA para Fondo de Cámara

## 📌 Descripción

Este es un **plugin para OBS Studio** que permite **desenfocar o reemplazar el fondo de la cámara** en vídeo **en formato vertical (portrait)** mediante un **algoritmo de Inteligencia Artificial**.

✅ No requiere GPU  
✅ Funciona a **~25 FPS** en un ordenador estándar  
✅ Alta precisión en la detección del sujeto  
✅ Ideal para streaming, grabaciones y videollamadas  

El complemento se integra directamente en OBS Studio como un plugin nativo.

---

## 🚀 Características

- Eliminación de fondo mediante IA
- Desenfoque o sustitución del fondo
- Optimizado para vídeo vertical
- Ejecución completa en CPU
- Rendimiento fluido (~25 FPS)
- Instalación sencilla

---

## 🖥️ Requisitos

- OBS Studio instalado
- Sistema operativo Windows
- CPU estándar (no es necesaria tarjeta gráfica dedicada)

---

## 📦 Instalación

### 1️⃣ Descargar el plugin

Descarga el archivo ZIP:

```
AI_remove_bg.zip
```

---

### 2️⃣ Instalar el plugin en OBS

Descomprime el contenido **directamente en el directorio de instalación de OBS**.

**Ruta por defecto en Windows:**
```
C:\Program Files\obs-studio
```

#### Opción A: Instalación manual
1. Haz clic derecho sobre `AI_remove_bg.zip`
2. Selecciona **Extraer aquí** o **Extraer en…**
3. Elige:
   ```
   C:\Program Files\obs-studio
   ```

#### Opción B: PowerShell (recomendado)

Ejecuta PowerShell **como Administrador** y lanza el siguiente comando:

```powershell
Expand-Archive .\AI_remove_bg.zip -DestinationPath "C:\Program Files\obs-studio" -Force
```

---

### 3️⃣ Reiniciar OBS

Cierra OBS Studio completamente y vuelve a abrirlo.

El plugin estará disponible dentro de OBS.

---

## 🎛️ Uso

1. Añade una **Fuente de Captura de Vídeo** (cámara)
2. Aplica el filtro **AI Background Removal**
3. Elige entre:
   - Desenfoque de fondo
   - Reemplazo de fondo
4. Ajusta los parámetros según tus necesidades

---

## 🧠 Funcionamiento

El plugin utiliza un algoritmo de **segmentación por IA** optimizado para:
- Formato vertical
- Procesamiento en tiempo real
- Entornos sin GPU

Esto permite obtener resultados de alta calidad usando únicamente CPU.

---

## ⚠️ Notas

- El rendimiento puede variar según el procesador
- Se recomienda buena iluminación para mejores resultados
- Diseñado principalmente para cámaras en formato vertical

---

## ⭐ Soporte

Si este plugin te resulta útil, considera darle una estrella ⭐ al repositorio.
