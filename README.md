# 🥁 Visor Rítmico MIDI - El Cóndor Pasa

[![Estado](https://img.shields.io/badge/Estado-Finalizado-success)](https://github.com/tu-usuario/nombre-del-repo)
[![Tecnología](https://img.shields.io/badge/Tecnología-Tone.js%20%7C%20MIDI-blue)](https://tonejs.github.io/)

Este proyecto es una aplicación web interactiva que utiliza la librería **Tone.js** para cargar y reproducir archivos MIDI, enfocándose en la visualización sincronizada de las partes de percusión. Permite a los usuarios seleccionar un instrumento de percusión para aumentar su volumen y enfocar su patrón rítmico.

## 🔗 Demo en Vivo (GitHub Pages)

[Haz clic aquí para ver el Visor Rítmico funcionando](https://[TU_USUARIO].github.io/[NOMBRE_DEL_REPOSITORIO]/)

*(Recuerda reemplazar `[TU_USUARIO]` y `[NOMBRE_DEL_REPOSITORIO]` con tus datos una vez que lo subas).*

---

## ✨ Características

* **Reproducción Sincronizada:** Carga y reproduce el archivo `condor_pasa.mid` usando la precisión del `Tone.Transport`.
* **Visualización Rítmica:** Las notas de percusión se muestran en un *timeline* que se mueve en tiempo real.
* **Acento de Percusión:** Al hacer clic en un instrumento (Bombo, Tarola, etc.), su volumen se acentúa (simulando velocidad MIDI 127) y el visor se enfoca solo en ese instrumento.
* **Control de Tempo (BPM):** Slider interactivo para cambiar el tempo de la canción al instante.
* **Controles de Mezcla:** Sliders independientes para controlar el volumen general de **Percusión** y **Melodía** (otros canales MIDI).
* **Metrónomo Visual:** Indicadores de compás y pulso sincronizados con el `Tone.Transport`.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5 / CSS3:** Estructura y estilos de la interfaz de usuario.
* **JavaScript (ES6+):** Lógica de la aplicación.
* **Tone.js:** Framework de audio para la reproducción de música en el navegador, control de tiempo, y síntesis de sonido.
* **@tonejs/midi:** Librería para parsear y extraer datos de los archivos `.mid`.

---

## 📂 Estructura del Proyecto (Crucial)

Para que el proyecto funcione correctamente (tanto localmente en XAMPP como en GitHub Pages), la estructura de archivos debe ser la siguiente, ya que el código JavaScript depende de estas rutas: