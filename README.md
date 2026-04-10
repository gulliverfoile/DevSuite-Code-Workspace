# DevSuite Code Workspace 🧩

Un editor de código todo-en-uno que funciona **completamente en tu navegador**, sin necesidad de instalar nada. Ideal para desarrolladores, formadores y estudiantes que quieren gestionar proyectos de código rápidamente, extraer archivos desde texto plano, y trabajar con múltiples lenguajes.

## ✨ Funcionalidades principales

- 📝 **Editor profesional con CodeMirror 6**  
  - Resaltado de sintaxis para: Python, JavaScript, TypeScript, HTML, CSS, JSON, YAML, Markdown  
  - Autocompletado, cierre automático de corchetes, búsqueda/remplazo  
  - Tema oscuro integrado (One Dark)

- 📁 **Explorador de archivos**  
  - Vista de árbol con todos los archivos del proyecto  
  - Doble clic para abrir/cerrar archivos  
  - Pestañas (tabs) para trabajar con múltiples documentos simultáneamente

- 🧠 **Extractor UltraRobusto de código desde texto**  
  - Pega cualquier texto con bloques de código y extrae automáticamente los archivos  
  - Reconoce formatos:  
    - ```` ```python:ruta/archivo.py ````  
    - `js:src/main.js` (lenguaje:ruta)  
    - `### ruta/archivo.ext`  
    - `// Archivo: ruta/archivo.ext`  
  - Ideal para copiar proyectos desde chats, documentación o LLMs

- 💾 **Gestión de sesiones**  
  - Guarda todo tu proyecto en un archivo `.json`  
  - Carga una sesión anterior para retomar el trabajo

- 📦 **Importar/exportar**  
  - **Abrir carpeta local** (carga múltiples archivos desde tu ordenador)  
  - **Descargar todo el proyecto como ZIP** en un clic  
  - **Crear archivos nuevos** directamente desde la interfaz

- 🧩 **Cero dependencias externas de servidor**  
  - Todo corre en el cliente (JavaScript + CDNs)  
  - No necesita Python, Node, ni ningún backend

## 🚀 ¿Cómo usarlo?

1. **Online (recomendado)**  
   Visita: `https://tusuario.github.io/devsuite-code-workspace/`  
   (una vez subido a GitHub Pages)

2. **Localmente**  
   Descarga el archivo `index.html` y ábrelo con cualquier navegador moderno (Chrome, Edge, Firefox, etc.)

## 🧪 Ejemplo rápido

1. Haz clic en **"📥 Extraer código"**  
2. Pega algo como:
js:greet.js
function greet() { console.log("Hola"); }

text
3. Verás que se crea el archivo `greet.js` en el explorador  
4. Haz doble clic para editarlo, guarda la sesión o descarga el ZIP

## 🛠️ Tecnologías usadas

- [CodeMirror 6](https://codemirror.net/) - Editor de texto avanzado  
- [JSZip](https://stuk.github.io/jszip/) - Generación de archivos ZIP  
- [js-yaml](https://github.com/nodeca/js-yaml) - Soporte para YAML  
- HTML5, CSS Grid/Flex, JavaScript (ES Modules)

## 📁 Estructura del proyecto

```
index.html          # Único archivo (todo el código HTML/CSS/JS)
```

## 🧑‍💻 ¿Para quién es útil?

- Desarrolladores que quieren **extraer código limpio desde conversaciones** (ChatGPT, Claude, etc.)  
- Profesores que comparten ejemplos de código en texto plano  
- Estudiantes que practican con múltiples archivos sin instalar un IDE  
- Cualquiera que necesite un **mini workspace portable** en el navegador

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Puedes bifurcar (fork) el repositorio, mejorar el extractor o añadir más lenguajes.

## 📜 Licencia

MIT — libre para usar y modificar.

---

⭐ **Si te gusta, dale una estrella al repositorio** ⭐
```

---

## 🔧 Instrucciones para subir a GitHub

1. **Crea un repositorio nuevo** en GitHub con el nombre `devsuite-code-workspace` (o el que elijas).
2. **Sube el archivo HTML**:
- Si quieres que sea la página principal, renómbralo a `index.html`.
- También puedes subir el `README.md` (el que te acabo de dar) para que se vea bonito en la página del repo.
3. **Activa GitHub Pages**:
- Ve a Settings → Pages → Branch: `main` (o `master`) → Carpeta: `/ (root)` → Save.
4. **Espera 1-2 minutos** y tu página estará en:  
`https://TU_USUARIO.github.io/devsuite-code-workspace/`
