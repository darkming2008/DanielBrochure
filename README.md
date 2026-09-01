# Landing Page & Formulario de Contacto — Daniel Castañeda

Landing page bilingüe (Español / Inglés) orientada a la conversión para **Daniel Castañeda | Fractional PMO & Delivery Excellence Director**. Incluye una presentación ejecutiva de servicios, métricas clave, sección acerca de mí con enlace a LinkedIn y un formulario de contacto funcional integrado con envío directo por correo electrónico.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5 & CSS3:** Estructura semántica, diseño responsive y estilos ejecutivos sin dependencias externas de CSS.
* **JavaScript (Vanilla):** Lógica simple para la conmutación de idioma en tiempo real (ES / EN).
* **Formspree:** Servicio de backend para la recepción y procesamiento de mensajes del formulario de contacto.

---

## 📂 Archivos Requeridos en el Directorio

Para que el proyecto cargue correctamente, asegúrate de colocar los siguientes recursos multimedia en la misma carpeta raíz que el archivo `index.html`:

| Archivo | Descripción | Formato Sugerido |
| :--- | :--- | :--- |
| `index.html` | Código principal de la landing page y el formulario. | Archivo HTML |
| `banner.png` | Imagen del banner superior en la sección Hero. | PNG / WEBP (~1200x500px) |
| `profile.jpg` | Fotografía de perfil para la sección "Acerca de Mí". | JPG / WEBP (~400x400px) |

---

## 📩 Configuración del Formulario de Contacto

El formulario de contacto está preconfigurado para enviar la información directamente al correo: **`ingdaniel.castaneda@gmail.com`**.

> **Nota sobre seguridad:** El formulario incluye un campo oculta antispam (*honeypot*) con el atributo `name="_gotcha"` para prevenir envíos automatizados por bots.

---

## 🌐 Configuración de Enlaces e Idioma

* **LinkedIn:** La sección "Acerca de Mí" incluye un botón directo al perfil profesional: `https://www.linkedin.com/in/danielcastanedapmp/`.
* **Switch de Idioma:** El botón selector `ES | EN` en la barra de navegación permite alternar entre español e inglés de forma instantánea mediante la clase CSS activa en el cuerpo del documento (`body.lang-es` / `body.lang-en`).
