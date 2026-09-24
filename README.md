# 🌾 Cuaderno Digital de Danzas Folclóricas Tradicionales

> **Herramienta web ágil, ligera y 100% offline para bailarines, profesores y ballets de folclore tradicional argentino.**  
> Permite consultar, registrar y estudiar coreografías oficiales, compases exactos, figuras, elementos y notas de ensayo directamente desde la computadora o el celular, con sincronización por archivo de respaldo.

---

## 💡 ¿Por qué nació este proyecto? (Problema y Solución)

* **El Problema:** En los ensayos de ballet, talleres o peñas folclóricas, es muy frecuente dudar sobre la estructura exacta de una danza: *¿cuántos compases tiene la introducción?*, *¿quién se esconde primero en la segunda del Escondido?*, *¿cuántos compases dura el arresto en la Zamba?* o *¿en qué esquina empieza el Triunfo?*. Escribir o buscar en cuadernos de papel es engorroso y buscar en internet consume tiempo y datos móviles en salas de ensayo donde suele haber poca señal.
* **La Solución:** Una aplicación web ultraligera, sin servidores ni registros, que vive en el celular del bailarín y funciona al instante sin conexión a internet, mostrando cada danza como una **ficha técnica interactiva** y permitiendo pasar los datos desde la PC al celular con un solo clic.

---

## 📖 Manual de Uso Paso a Paso

### 1. ¿Cómo consultar una danza?
1. Abre la aplicación en tu celular o PC.
2. En la barra lateral verás la lista de danzas disponibles.
3. Puedes usar el **buscador `🔍`** para escribir cualquier término (por ejemplo: *"Gato"*, *"Zamba"*, *"pañuelo"*, *"castañetas"*).
4. Toca sobre la danza que quieras y se abrirá su ficha completa en pantalla.

### 2. ¿Cómo leer la Ficha Coreográfica?
Cada danza está organizada en tres bloques claros y visuales:
* **📍 Elementos y Ubicación:** Indica la posición inicial de partida (extremos de la mediana, esquinas opuestas), los elementos necesarios (castañetas, pañuelo blanco, paso básico) y cuántos compases dura la introducción musical hasta el grito de *¡Adentro!*.
* **💃 Coreografía (Primera y Segunda):** Muestra cada figura en una fila destacada con su insignia de compases en color poncho criollo (ej: `💃 Vuelta entera` ➔ `[ 8 compases ]`).
* **📝 Notas del Ensayo / Ballet:** Espacio dedicado a correcciones del profesor, miradas de complicidad, movimientos de brazos, vestuario o variaciones coreográficas de tu ballet.

### 3. ¿Cómo agregar una danza nueva?
1. Toca o haz clic en el botón **"➕ Nueva Danza"** (abajo en el menú lateral).
2. Completa los casilleros del formulario:
   * **Nombre de la danza:** (Ej: *El Triunfo*).
   * **Clasificación:** (Ej: *Pareja suelta e independiente • Picaresca de esquinas*).
   * **Ubicación inicial:** (Ej: *Enfrentados en esquinas opuestas*).
   * **Elementos:** (Ej: *Castañetas y paso básico*).
   * **Introducción:** (Ej: *6 compases con aviso de ¡Aura!*).
   * **Figuras:** Escribe una figura por línea con el formato `Figura - X compases`.  
     *Ejemplo:*
     ```text
     Esquina de balanceo - 4 compases
     Giro - 4 compases
     Esquina de balanceo - 4 compases
     Giro - 4 compases
     Media vuelta - 4 compases
     Zapateo y zarandeo - 8 compases
     Media vuelta - 4 compases
     Giro final y coronación - 4 compases
     ```
   * **Notas personales:** Consejos de estilo, correcciones o variantes de la Segunda.
3. Haz clic en **"Guardar"**. La danza se incorporará de inmediato a tu cuaderno.

### 4. ¿Cómo editar o eliminar una danza?
* **Para editar:** Abre la danza y toca el botón **"✏️ Editar"** en la barra superior (o en la barra inferior del celular). Modifica los datos que necesites y dale a **Guardar**.
* **Para eliminar:** Dentro de la ventana de edición, toca el botón rojo **"Eliminar"** abajo a la izquierda.

### 5. ¿Cómo armar tu lista de ensayo del día (⭐ Favoritas)?
Toca la estrella **★** al lado de las danzas que vayas a practicar hoy. Luego selecciona la pestaña **"⭐ Ensayando"** en el buscador: la lista se filtrará mostrando únicamente esas danzas para no perder tiempo buscando entre todo el repertorio durante la clase.

### 6. 🔄 ¿Cómo pasar las coreografías de la PC al Celular (Respaldo)?
Cargar coreografías largas y detalladas es mucho más cómodo desde el teclado de la computadora. Puedes pasarlas a tu celular en 3 sencillos pasos:

#### Paso A: En tu Computadora
1. Carga o edita tus danzas cómodamente en la PC.
2. Haz clic en el botón **"💾 Respaldo"** abajo en el menú lateral.
3. Haz clic en **"📥 Descargar Archivo JSON"**. Se descargará el archivo `danzas_folclore_respaldo.json`.
4. Envíate ese archivito por WhatsApp Web a tu propio chat.

#### Paso B: En tu Celular
1. En WhatsApp de tu celular, guarda el archivo recibido en la carpeta *Descargas* de tu teléfono.
2. Abre el Cuaderno Folclórico en tu celular.
3. Toca **"💾 Respaldo"**.
4. En *"Cargar archivo de respaldo"*, toca **"Seleccionar archivo"** y elige `danzas_folclore_respaldo.json`.
5. ¡Listo! Todas las coreografías cargadas en la PC aparecerán al instante en tu celular.

---

## 🌾 Danzas Tradicionales Precargadas en el Cuaderno

El cuaderno incluye inicialmente 4 danzas fundamentales del folclore argentino:

1. **Gato:** 36 compases oficiales por parte. Pareja suelta e independiente, picaresca. Castañetas, paso básico, zapateo y zarandeo, y coronación en el centro.
2. **Chacarera Simple:** 56 compases por parte. Avance y retroceso, giros, vueltas enteras, zapateos y media vuelta.
3. **Zamba Tradicional:** Pareja suelta, amoresca y señorial. Vuelta entera de 16c con pañuelo blanco, arrestos simples, dobles y cortejo de miradas.
4. **Escondido:** Picaresca de esquinas. 4 esquinas de balanceo (16c), vueltas y el tradicional juego donde la dama se esconde en la Primera y el varón se esconde en la Segunda.

---

## 📱 Cómo tenerlo en el Celular (Acceso directo como App)

1. Abre el enlace de tu repositorio en **GitHub Pages** desde el navegador de tu celular:  
   `https://tu-usuario.github.io/cuaderno-folclore/`
2. **En Android (Google Chrome):** Toca los **3 puntos** arriba a la derecha y selecciona **"Agregar a la pantalla principal"** (o *"Instalar aplicación"*).
3. **En iPhone (Safari):** Toca el botón **Compartir** (cuadrado con flecha hacia arriba) y selecciona **"Agregar al inicio"**.
4. ¡Listo! Se creará el ícono con la espiga de trigo en tu pantalla de inicio y se abrirá a pantalla completa sin barras de navegador, listo para consultar en el ensayo.

---

## 🧠 Arquitectura Técnica y Aprendizaje

El proyecto fue construido siguiendo la metodología **KISS (Keep It Simple, Stupid)**: todo el sistema vive en un único archivo autónomo (`index.html`):

### 1. El Parseador de Figuras (JavaScript Inteligente)
Para que el usuario no tenga que armar tablas complejas, el código interpreta líneas simples con guión:
```javascript
const parts = line.split('-');
const nombreFigura = parts[0].trim(); // "Vuelta entera"
const compases = parts[1].trim();     // "8 compases"