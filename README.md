<div align="center">

# CLANNAD HD en español
### Parche comunitario para la edición de Steam

![Idioma](https://img.shields.io/badge/Espa%C3%B1ol-Latinoamericano-cc3434?style=for-the-badge)
![Plataforma](https://img.shields.io/badge/Steam-Windows-1b2838?style=for-the-badge&logo=steam)
![Desarrollo](https://img.shields.io/badge/Desarrollado_con-Codex-237a57?style=for-the-badge)

**Una localización al español latinoamericano de la historia de CLANNAD, sus rutas, After Story y la Dangopedia.**

[**Descargar parche**](https://github.com/ignanava/Parche-de-traduccion-para-CLANNAD-HD-SPANISH-PATCH-/archive/refs/heads/main.zip) · [**Ver tutorial**](https://www.youtube.com/watch?v=ZIwjfCTz5pY) · [**Guía en Steam**](https://steamcommunity.com/sharedfiles/filedetails/?id=3832556009)

</div>

---

## Sobre el proyecto

Este proyecto, impulsado por **Igna**, acerca CLANNAD HD de Steam al público de habla hispana mediante una traducción integrada directamente en el juego.

**Codex, de OpenAI, fue una herramienta central en su desarrollo.** Se utilizó para investigar los archivos del juego, programar herramientas, trabajar la localización por lotes, mantener un glosario y comprobar la integridad de los archivos reconstruidos. También ayudó a resolver los problemas de codificación y fuentes para mostrar los caracteres españoles.

El trabajo de localización busca conservar la personalidad de cada personaje, su género, el tono emocional de las escenas, el humor y la continuidad de las conversaciones. Se emplea español latinoamericano neutro, manteniendo la ambientación japonesa y los nombres de los personajes.

## ¿Qué incluye?

- Historia principal, rutas y finales.
- After Story.
- Diálogos, narraciones, pensamientos y opciones de respuesta.
- Dangopedia.
- Textos auxiliares identificados durante el desarrollo.
- Fuente adaptada para acentos, ñ y signos de interrogación y exclamación españoles.

Las voces japonesas originales se conservan. El texto se lee dentro de CLANNAD; no hace falta utilizar un traductor en pantalla.

## Descargar

### [Descargar el parche en ZIP](https://github.com/ignanava/Parche-de-traduccion-para-CLANNAD-HD-SPANISH-PATCH-/archive/refs/heads/main.zip)

Este enlace descarga el contenido actual del repositorio. Al descomprimirlo encontrarás una carpeta con los archivos necesarios:

    Seen.txt
    dat/
    └── migmix-1m-regular.ttf

También puedes consultar la [sección de descargas del repositorio](https://github.com/ignanava/Parche-de-traduccion-para-CLANNAD-HD-SPANISH-PATCH-/releases).

**Necesitas tu propia copia de CLANNAD HD de Steam.** El parche está preparado para la edición inglesa de Windows, App ID **324160**.

## Instalación: copiar y pegar

1. **Cierra CLANNAD.**
2. Descarga el ZIP y **extrae su contenido**.
3. Localiza la carpeta del juego: en Steam, haz clic derecho sobre **CLANNAD → Administrar → Explorar archivos locales**.
4. Antes de reemplazar nada, guarda en otra ubicación una copia de estos dos archivos del juego: <code>Seen.txt</code> y <code>dat/migmix-1m-regular.ttf</code>.
5. Dentro de la carpeta extraída del parche, selecciona **Seen.txt y la carpeta dat**.
6. Cópialos a la **carpeta raíz de CLANNAD**, donde se encuentra <code>SiglusEngine_Steam.exe</code>.
7. Acepta **combinar las carpetas** y **reemplazar los dos archivos**. Conserva el resto del contenido de <code>dat</code>.
8. Abre CLANNAD normalmente desde Steam y selecciona **MigMix 1M** en la configuración de texto.

**Copia el contenido del parche, no la carpeta exterior que lo contiene.** No necesitas ejecutar comandos ni instalar fuentes en Windows.

Para comprobar el inicio de la traducción, selecciona **NEW GAME** y comienza a leer el prólogo.

## Tutorial en video

[![Ver tutorial de instalación del parche de CLANNAD HD al español](https://img.youtube.com/vi/ZIwjfCTz5pY/hqdefault.jpg)](https://www.youtube.com/watch?v=ZIwjfCTz5pY)

### [Ver el tutorial en YouTube](https://www.youtube.com/watch?v=ZIwjfCTz5pY)

## ¿Cómo se hizo con Codex?

El proyecto combinó localización de textos y desarrollo de herramientas específicas para CLANNAD:

1. **Investigación del formato.** Se inspeccionaron los scripts y los recursos del motor para identificar los textos editables.
2. **Herramientas conservadoras.** Se desarrolló un procedimiento para modificar los textos seleccionados y ajustar sus referencias, conservando las instrucciones y recursos ajenos a la traducción.
3. **Localización por lotes.** Se trabajó con contexto narrativo, un glosario persistente y traducciones guardadas para mantener continuidad y evitar repetir trabajo.
4. **Corrección de caracteres.** Se adaptaron la codificación de los textos y la fuente incluida con el juego para los caracteres españoles.
5. **Comprobaciones técnicas.** Se compararon hashes y estructuras binarias y se verificaron los textos insertados, las referencias y la conservación de los recursos no editados.
6. **Preparación del parche.** El resultado se redujo a dos archivos para facilitar una instalación manual.

**La participación de Codex abarcó programación, investigación, traducción, localización y comprobaciones automatizadas.** Las pruebas técnicas no equivalen a una revisión visual y editorial exhaustiva de toda la novela; los reportes de la comunidad ayudarán a corregir los problemas que se detecten.

## Preguntas frecuentes

### ¿Necesito instalar algo adicional?

No. Descarga, extrae y copia los archivos. La fuente adaptada viene en la carpeta <code>dat</code>; selecciónala como **MigMix 1M** dentro de CLANNAD.

### ¿Tengo que aplicar otros parches primero?

No. Los archivos de este repositorio contienen el parche que se distribuye aquí. No necesitas instalar entregas anteriores.

### ¿Se modifican las voces o el ejecutable?

No. Se reemplazan únicamente <code>Seen.txt</code> y <code>dat/migmix-1m-regular.ttf</code>.

### ¿Se modifican mis partidas guardadas?

La copia manual de esos dos archivos no modifica los archivos de guardado. No se ha comprobado la compatibilidad de todos los guardados históricos.

### ¿Puedo borrar la descarga después de instalar?

Sí. El juego conserva los archivos que copiaste en su carpeta. Guarda por separado las copias originales si quieres poder desinstalar el parche.

### ¿Cómo lo desinstalo?

Cierra el juego y devuelve a sus ubicaciones las copias de <code>Seen.txt</code> y <code>dat/migmix-1m-regular.ttf</code> que guardaste antes de instalar.

### ¿Por qué se ven mal los acentos?

Comprueba que hayas copiado también la fuente de <code>dat</code> y que **MigMix 1M** esté seleccionada en el juego.

### ¿Qué pasa si Steam restaura los archivos originales?

Puede ser necesario volver a copiar los archivos del parche. Conserva siempre tu respaldo de los originales.

## Reportar un problema

Puedes abrir un reporte en [Issues](https://github.com/ignanava/Parche-de-traduccion-para-CLANNAD-HD-SPANISH-PATCH-/issues).

Para que sea más fácil localizarlo, incluye:

- La escena o fecha dentro del juego.
- El personaje y la frase afectada.
- Una captura, si es posible.
- Las decisiones necesarias para llegar a ese punto, cuando sean relevantes.
- Si se trata de un fallo de instalación, explica qué ocurre y qué archivos copiaste.

Marca los spoilers y evita publicar datos personales o partidas que no quieras compartir.

## Apoya el proyecto

Si el parche te sirve, puedes apoyar su difusión:

- **[Visita la guía en Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=3832556009)** y deja tu valoración o comentario.
- **[Comparte el tutorial en YouTube](https://www.youtube.com/watch?v=ZIwjfCTz5pY)** con quienes necesiten ayuda para instalarlo.
- Añade una estrella al repositorio.
- Comparte errores y sugerencias para mejorar la traducción.

Gracias a quienes prueben el parche y ayuden a que más personas puedan disfrutar de CLANNAD en español.

---

**Proyecto comunitario no oficial, impulsado por Igna con la ayuda de Codex.** Sin afiliación ni respaldo de los responsables de CLANNAD. Los derechos de la obra y de sus recursos pertenecen a sus respectivos titulares.
