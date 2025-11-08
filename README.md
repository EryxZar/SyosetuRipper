### 📘 SyosetuRipper

**SyosetuRipper** es un *userscript* para **Tampermonkey** que facilita la descarga y archivado de novelas web desde [Syosetu.com](https://ncode.syosetu.com/).
Agrega automáticamente botones de **descarga individual en formato EPUB** junto a cada capítulo y un botón flotante **“📚 Descargar todos”** que recorre todas las páginas del índice.

Cada capítulo se guarda como un archivo **EPUB**, listo para abrir en lectores como **Calibre** o **Kindle**, y la opción “Descargar todos” crea un **archivo ZIP** con todos los capítulos ordenados y numerados.
Además, muestra una **barra de progreso de texto** que indica el avance de la descarga y el empaquetado.

---

### ✨ Características

* 📕 Botón de **descarga individual** para cada capítulo.
  
* 📚 Botón **“Descargar todos”** que:
  * Reúne todos los capítulos automáticamente.
  * Convierte cada uno en un EPUB independiente.
  * Los empaqueta en un solo archivo ZIP.
    
* ⏳ **Indicador de progreso** en pantalla.
  
* 🔢 Los archivos se **numeran automáticamente** (por ejemplo: `001- Capítulo 1.epub`, `010- Epílogo.epub`).
  
* 💾 Todo se ejecuta **localmente en el navegador**, sin servidores externos.

---

### ⚙️ Instalación

1. Instala **[Tampermonkey](https://www.tampermonkey.net/)** en tu navegador.
2. Crea un nuevo *userscript* y pega el código de `SyosetuRipper.user.js`.
3. Visita una novela en Syosetu, por ejemplo:
   👉 `https://ncode.syosetu.com/n3709ho/`
4. Aparecerán los nuevos botones **“Descargar”** y **“📚 Descargar todos”** en la página.

---

### 🧠 Notas

* Los EPUB siguen el estándar **EPUB 2.0**.
* Probado en **Chrome** y **Firefox**.
* No requiere iniciar sesión ni depende de servidores externos.
