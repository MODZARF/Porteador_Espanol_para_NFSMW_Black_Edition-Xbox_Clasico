# Porteador Español para NFSMW Black Edition - Xbox Clásico

Herramienta hecha en Python para portear el audio de **PS2** y los vídeos de **PC** a la versión de **Xbox Clásico** de **Need For Speed Most Wanted Black Edition**, dejándolo 100% en español.

> ⚠️ **AVISO LEGAL IMPORTANTE**
**ESTE PROYECTO NO CONTIENE NINGÚN ARCHIVO DEL JUEGO NI MATERIAL CON COPYRIGHT.**
Necesitas aportar tus propias copias legales. El sistema verifica por CRC que los archivos sean 100% originales.

---

### ✨ Características

- 💬 Juego completamente en español: textos, audio, vídeos y texturas.
- 🎬 Vídeos porteados desde PC con mayor resolución = un poco más de calidad que el original de Xbox.
- 📺 Mod Widescreen del portal PS2Wide incluido, para ver los vídeos en pantalla completa sin barras negras.
- 🧩 Sistema 100% limpio, modular y seguro.

---

### 📋 Dependencias

Necesitas tener esto a mano, no está incluido en el repo:

1.  **Python 3.8 o superior**
2.  **Pack de herramientas VP6 de bluesky-dev12:**
    👉 https://github.com/bluesky-dev12/MAD-x-VP6-x-MPC-x-MPV-x-WMV-Compiler/releases/tag/4.0
3.  **NFS.BIN.TOOL de Ekey (las 2 herramientas):**
    👉 https://github.com/Ekey/NFS.BIN.Tool/releases/tag/0.4
4.  💿 **ISO legal y original** de NFSMW de PS2 versión **PAL**
5.  🎮 **Juego original** NFSMW Black Edition de Xbox Clásico versión **NTSC-U** extraído en carpeta
6.  💻 **Juego original** NFSMW versión PC en español

---

### 🚀 Cómo usar

1.  Descarga el zip `Port_Esp_NFSMW_By_ZARF.zip` de la pestaña **Releases** y extráelo.
2.  Descarga las 2 herramientas de **NFS.BIN.TOOL de Ekey** y ponlas en la misma carpeta extraída.
3.  Descarga el pack de **bluesky**, instala todo el contenido de la carpeta **INSTALL FIRST** que trae, luego extrae la carpeta `COMPILER` dentro de la misma carpeta extraída de mi zip.
4.  Pon los archivos de audio de PS2 en la carpeta `PS2_AUDIO`. Para obtenerlos usa el script `extraer_audio_ps2.py` que incluye mi zip, solo ejecútalo al lado de la ISO PAL.
5.  Copia los vídeos .vp6 en español de la versión de PC en la carpeta `PC_VIDEOS`.
6.  Pon el juego completo de Xbox NTSC extraído en carpeta dentro de `JUEGO_XBOX`.
7.  Ejecuta el script `iniciar.py`.

El proceso se inicia automáticamente, pero en un punto el programa de conversión de vp6 te pedirá configuración manual. Cuando aparezca, pon:

> **Bitrate:** `1800`
> **Mode:** `one pass - Best Quality`
> **Max Frames:** `30`

Dale OK en cada vídeo. Cuando termine la conversión espera a que se empaquete todo.

✅ Cuando acabe el proceso aparecerá el mensaje: **"Parche aplicado con éxito"**. El juego quedará listo y parcheado en la carpeta `JUEGO_XBOX`.

---

### 🙏 Créditos y Agradecimientos

- **ZARF:** Diseño del sistema de parcheo y testeo.
- **bluesky-dev12:** Por el pack de herramientas para videos de NFS.
- **Ekey:** Por NFS.BIN.TOOL.
- **PS2Wide:** Por los bytes del mod widescreen para los videos.
- **Dichicitow810:** Por inspirar este proyecto.
