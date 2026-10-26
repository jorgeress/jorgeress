<a href="https://jorgeress.github.io">
  <img src="assets/header.svg" width="100%" alt="Jorge García: malware, Linux y ciberseguridad. A veces se me ocurren cosas.">
</a>

<p align="center">
  <a href="https://jorgeress.github.io"><img src="https://img.shields.io/badge/web-jorgeress.github.io-c792ea?style=flat-square&labelColor=0b0d12" alt="Web"></a>
  <a href="mailto:jgarciamartinezdev@proton.me"><img src="https://img.shields.io/badge/correo-proton.me-3ddc97?style=flat-square&labelColor=0b0d12" alt="Correo"></a>
  <a href="https://www.linkedin.com/in/jorgegarciamartinezdev"><img src="https://img.shields.io/badge/LinkedIn-Jorge_García-0a66c2?style=flat-square&labelColor=0b0d12" alt="LinkedIn"></a>
</p>

Ciberseguridad, Linux y ML.


### Con lo que trabajo

<p align="left">
  <img src="https://skillicons.dev/icons?i=arch,linux,bash,c,cpp,docker,python,nodejs,java,postgres,mongodb,js,ts,react,nextjs,pytorch,aws,git&perline=11" alt="Arch, Linux, Bash, C, C++, Docker, Python, Node.js, Java, PostgreSQL, MongoDB, JavaScript, TypeScript, React, Next.js, PyTorch, AWS, Git">
</p>


### Proyectos

<p align="center">
  <a href="https://github.com/jorgeress/crisol"><img src="assets/proyectos/crisol.webp" width="48%" alt="Crisol"></a>
  <a href="https://github.com/jorgeress/cromatoforo"><img src="assets/proyectos/cromatoforo.webp" width="48%" alt="Cromatóforo"></a>
  <a href="https://github.com/jorgeress/cibo"><img src="assets/proyectos/cibo.webp" width="48%" alt="CIBO"></a>
  <a href="https://github.com/jorgeress/pinchadiscos"><img src="assets/proyectos/pinchadiscos.webp" width="48%" alt="Pinchadiscos"></a>
  <a href="https://github.com/jorgeress/garabato"><img src="assets/proyectos/garabato.webp" width="48%" alt="Garabato"></a>
  <a href="https://github.com/jorgeress/vitrina"><img src="assets/proyectos/vitrina.webp" width="48%" alt="Vitrina"></a>
</p>

<details>
<summary><b>Crisol</b>: motor de triaje estático de malware y banco de pruebas para reglas YARA</summary>
<br>

Cualquiera puede lanzar `yara reglas.yar muestra.exe`. Lo que distingue a un analista es saber cuánto vale esa regla: cuántos falsos positivos suelta contra software legítimo y qué detecta de verdad. Aquí eso es un número reproducible. El harness midió un 12,18 % de falsos positivos sobre 52 binarios firmados y legítimos, y guió el rediseño regla a regla hasta dejarlo en 0 % sin perder detección. Cada cambio está justificado con datos, no con intuición.
</details>

<details>
<summary><b>Cromatóforo</b>: un escritorio de Arch donde todo el color sale del wallpaper</summary>
<br>

Cambias el fondo y la barra, el lanzador, el terminal, el prompt, las notificaciones, el editor, el navegador, Steam, Spotify y las aplicaciones GTK y Qt adoptan la paleta en la misma pasada. Diecinueve consumidores colgando de un único origen de verdad, cada uno con su plantilla: para cambiar cómo se mapea un color se toca la plantilla, nunca el config del programa final.

Lo interesante no es que quede bonito, es lo que no encaja en el modelo. `qt6ct` vigila su fichero de configuración y no el esquema al que ese fichero apunta, así que regenerar la paleta no repinta nada y hay que hacerle `touch` para despertarlo. Steam solo lee su CSS al arrancar, y el script no lo reinicia a propósito: te cerraría el juego en mitad de una partida. Todo eso está documentado, trampas incluidas.
</details>

<details>
<summary><b>CIBO</b>: asistente de IA que corre entero en local sobre Ollama</summary>
<br>

Sabe cuándo tirar de una calculadora real en vez de inventarse los números, ejecuta código Python en un subproceso aislado y lleva una capa que impide que los datos sensibles salgan del equipo. Lo empecé para entender cómo funciona un LLM por dentro en lugar de quedarme en usarlo.
</details>

<details>
<summary><b>Pinchadiscos</b>: generador de playlists de Spotify en Next.js</summary>
<br>

Filtras por artista, género, década y popularidad, revisas el resultado en el navegador y lo guardas en tu cuenta real. OAuth 2.0 con refresco automático de token y el intercambio pasando por rutas de servidor, para que el client secret no acabe nunca en el navegador.
</details>

<details>
<summary><b>Garabato</b>: de un guion en texto plano a un vídeo montado</summary>
<br>

Voz, imágenes, subtítulos y ensamblado final. Lo monté porque grabar la narración y buscar una imagen por frase es lo que convierte un vídeo de ocho minutos en un día entero de trabajo. Los guiones siguen unas reglas y criterios fijados de antemano, y el pipeline hace el resto del vídeo sin que yo toque nada. Cada paso es idempotente: puedes cortar por la mitad y retomar.
</details>

<details>
<summary><b>Vitrina</b>: mi colección de juegos, películas, libros y discos, de Obsidian a la web</summary>
<br>

Cada obra es una ficha en Markdown dentro de Obsidian, y se publica como web estática en [jorgeress.github.io/vitrina](https://jorgeress.github.io/vitrina/). Está explicado cómo montarte la tuya.
</details>

También **[PokeGAN](https://github.com/jorgeress/pokegan)**, una DCGAN entrenada desde cero durante 10.000 épocas para generar sprites de Pokémon.

Ahora mismo estoy con una app que todavía es secreto.

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jorgeress/jorgeress/output/serpiente-oscura.svg">
  <img src="https://raw.githubusercontent.com/jorgeress/jorgeress/output/serpiente.svg" width="100%" alt="Una serpiente recorriendo mi gráfico de contribuciones">
</picture>
