# 🎶 Festival Música

**Festival Música** es una página web ficticia dedicada a la promoción y difusión de un festival musical. El sitio presenta información clave sobre el evento, incluyendo detalles de los conciertos, artistas participantes y contenido multimedia como videos promocionales.

---

## 📄 Descripción

Este sitio web está diseñado para ofrecer una **experiencia visual moderna y atractiva**, enfocada en la presentación de contenido multimedia y la **facilidad de navegación** para los usuarios interesados en el festival.

---

## 🛠️ Tecnologías y Herramientas Utilizadas

- **HTML5**: Estructura principal del sitio.
- **SASS (SCSS)**: Preprocesador CSS utilizado para escribir estilos de manera más eficiente y modular.
- **Gulp**: Automatización de tareas como compilación, minificación y optimización de recursos.
- **CSSNano**: Plugin utilizado con Gulp para minificar y optimizar el CSS generado.
- **Terser**: Herramienta utilizada para minificar y optimizar el archivo JavaScript `galeria.js`.

---

## ⚙️ Proceso de Desarrollo y Minificación

- Se desarrolló utilizando **SASS** para organizar y reutilizar estilos de manera eficiente.
- **Gulp** fue la herramienta encargada de compilar los archivos `.scss` a `.css`, y luego minificarlos usando **CSSNano**, mejorando el rendimiento de carga.
- El archivo JavaScript principal (`galeria.js`) fue minificado con **Terser** para entregar un script más ligero al usuario.

> ⚠️ **Nota**: La carpeta con los archivos fuente (como los originales `.scss` y JS sin minificar) **no está incluida** en este repositorio.  
> Los archivos presentes (`index.html`, `galeria.js`, y los videos en la carpeta `video/`) ya están minificados y listos para producción.

---

## 📂 Estructura del Proyecto

```bash
Festival Música/
├── index.html
├── build/
│   ├── css/
│   │   ├── app.css
│   │   └── app.css.map
│   ├── js/
│   │   ├── galeria.js
│   │   └── galeria.js.map
│   └── img/
│       ├── imagen_vocalista.avif
│       ├── imagen_rock.avif
│       ├── imagen_vocalista.webp
│       ├── imagen_rock.webp
│       ├── icono_rock.webp
│       ├── icono_rock.avif
│       ├── icono_edm.webp
│       ├── icono_edm.avif
│       ├── imagen_vocalista.jpg
│       ├── imagen_rock.jpg
│       ├── icono_rock.png
│       ├── icono_edm.png
│       ├── thumb/
│       │   ├── 1.avif
│       │   ├── 1.jpg
│       │   ├── 1.webp
│       │   ├── 2.avif
│       │   ├── 2.jpg
│       │   ├── 2.webp
│       │   ├── 3.avif
│       │   ├── 3.jpg
│       │   ├── 3.webp
│       │   ├── 4.avif
│       │   ├── 4.jpg
│       │   ├── 4.webp
│       │   ├── 5.avif
│       │   ├── 5.jpg
│       │   ├── 5.webp
│       │   ├── 6.avif
│       │   ├── 6.jpg
│       │   ├── 6.webp
│       │   ├── 7.avif
│       │   ├── 7.jpg
│       │   ├── 7.webp
│       │   ├── 8.avif
│       │   ├── 8.jpg
│       │   ├── 8.webp
│       │   ├── 9.avif
│       │   ├── 9.jpg
│       │   ├── 9.webp
│       │   ├── 10.avif
│       │   ├── 10.jpg
│       │   ├── 10.webp
│       │   ├── 11.avif
│       │   ├── 11.jpg
│       │   ├── 11.webp
│       │   ├── 12.avif
│       │   ├── 12.jpg
│       │   └── 12.webp
│       └── grande/
│           ├── 1.avif
│           ├── 1.jpg
│           ├── 1.webp
│           ├── 2.avif
│           ├── 2.jpg
│           ├── 2.webp
│           ├── 3.avif
│           ├── 3.jpg
│           ├── 3.webp
│           ├── 4.avif
│           ├── 4.jpg
│           ├── 4.webp
│           ├── 5.avif
│           ├── 5.jpg
│           ├── 5.webp
│           ├── 6.avif
│           ├── 6.jpg
│           ├── 6.webp
│           ├── 7.avif
│           ├── 7.jpg
│           ├── 7.webp
│           ├── 8.avif
│           ├── 8.jpg
│           ├── 8.webp
│           ├── 9.avif
│           ├── 9.jpg
│           ├── 9.webp
│           ├── 10.avif
│           ├── 10.jpg
│           ├── 10.webp
│           ├── 11.avif
│           ├── 11.jpg
│           ├── 11.webp
│           ├── 12.avif
│           ├── 12.jpg
│           └── 12.webp
├── video/
│   ├── concierto.mp4
│   ├── concierto.ogg
│   ├── concierto.webm
│   ├── ._concierto.mp4
│   ├── ._concierto.ogg
│   └── ._concierto.webm


