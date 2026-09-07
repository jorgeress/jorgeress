# > Jorge <

Estudio Ingeniería de Software en U-tad, con la especialización en Ciberseguridad.

Me muevo en dos terrenos que acaban tocándose: construir cosas y entender cómo se rompen. Lo primero suele empezar porque necesito una herramienta que no existe, y termina en Python o con una interfaz en React. Lo segundo pasa en Linux, y baja a C cuando hace falta ver qué ocurre de verdad por debajo.

Nada de lo que hay aquí abajo es un tutorial seguido hasta el final. Todos salieron de un problema mío concreto, y en los README está también lo que no llegó a funcionar.

### Con lo que trabajo

**Sistemas y bajo nivel** · Linux · C · C++ · Bash
**Backend** · Python · Java
**Frontend** · JavaScript (ES6+) · React · Next.js · Tailwind
**Otros** · YARA · TensorFlow · ffmpeg · Wayland / Hyprland · pywal

### Lo que he construido

**[Crisol](https://github.com/jorgeress/yardstick)** : motor de triaje estático de malware y banco de pruebas para reglas YARA.
Cualquiera puede lanzar `yara reglas.yar muestra.exe`. Lo que distingue a un analista es saber cuánto vale esa regla: cuántos falsos positivos suelta contra software legítimo y qué detecta de verdad. Aquí eso es un número reproducible. El harness midió un 12,18 % de falsos positivos sobre 52 binarios firmados y legítimos, y guió el rediseño regla a regla hasta dejarlo en 0 % sin perder detección. Cada cambio está justificado con datos, no con intuición.

**[CIBO](https://github.com/jorgeress/cibo-project)** : asistente de IA que corre entero en local sobre Ollama.
Sabe cuándo tirar de una calculadora real en vez de inventarse los números, ejecuta código Python en un subproceso aislado y lleva una capa que impide que los datos sensibles salgan del equipo. Lo empecé para entender cómo funciona un LLM por dentro en lugar de quedarme en usarlo. Está en pausa, y en el README explico por qué.

**[Pinchadiscos](https://github.com/jorgeress/spotify-playlist-builder)** : generador de playlists en Next.js.
Filtras por artista, género, década y popularidad, revisas el resultado en el navegador y lo guardas en tu cuenta real. OAuth 2.0 con refresco automático de token y el intercambio pasando por rutas de servidor, para que el client secret no acabe nunca en el navegador.

**[Garabato](https://github.com/jorgeress/botYoutube)** : de un guion en texto plano a un vídeo montado.
Voz, imágenes, subtítulos y ensamblado final. Lo monté porque grabar la narración y buscar una imagen por frase es lo que convierte un vídeo de ocho minutos en un día entero de trabajo. El guion y el criterio siguen siendo míos, que es donde está el valor. Cada paso es idempotente: puedes cortar por la mitad y retomar.


**[Cromatóforo](https://github.com/jorgeress/dotfiles)** : un escritorio de Arch donde todo el color sale del wallpaper.
Cambias el fondo y la barra, el lanzador, el terminal, el prompt, las notificaciones, el editor, el navegador, Steam, Spotify y las aplicaciones GTK y Qt adoptan la paleta en la misma pasada. Diecinueve consumidores colgando de un único origen de verdad, cada uno con su plantilla: para cambiar cómo se mapea un color se toca la plantilla, nunca el config del programa final. Lo interesante no es que quede bonito, es lo que no encaja en el modelo. `qt6ct` vigila su fichero de configuración y no el esquema al que ese fichero apunta, así que regenerar la paleta no repinta nada y hay que hacerle `touch` para despertarlo. Steam solo lee su CSS al arrancar, y el script no lo reinicia a propósito: te cerraría el juego en mitad de una partida. Todo eso está documentado, trampas incluidas.

También hay por aquí una **[DCGAN entrenada desde cero](https://github.com/jorgeress/generador-pokemons-gan)** durante 10.000 épocas para generar sprites de Pokémon, que acabó siendo sobre todo un ejercicio de pelearse con el mode collapse, y una **[mediateca en Obsidian](https://github.com/jorgeress/mediateca)** publicada como web estática con los juegos, películas, libros y discos que me han gustado.

---

### 🔗 Conecta conmigo

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jgarciamartinezdev@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jorge-garc%C3%ADa-mart%C3%ADnez-1a2574292)
