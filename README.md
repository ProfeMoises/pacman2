# 🟡 Pac-Man – Juego Clásico en Canvas (Versión Responsiva)

¡Revive la experiencia del arcade original con este Pac-Man programado en HTML, CSS y JavaScript usando Canvas! Un homenaje al clásico de 1980 con laberinto, fantasmas, power pellets y todo el sabor retro, **ahora jugable también en móviles y tablets**.

---

## 🎮 Cómo jugar

El objetivo es simple: **come todos los puntos del laberinto** evitando a los fantasmas. Si te tocan, pierdes una vida. Usa los **power pellets** para volverte invencible temporalmente y poder comer a los fantasmas.

### Controles

#### En ordenador (escritorio)
| Tecla | Acción |
|-------|--------|
| `↑` / `W` | Mover arriba |
| `↓` / `S` | Mover abajo |
| `←` / `A` | Mover izquierda |
| `→` / `D` | Mover derecha |
| `P` | Pausar / Reanudar |
| Botón **"Nuevo"** | Reiniciar partida |

#### En móvil o tablet
- Los **botones táctiles** (▲, ▼, ◀, ▶) aparecen automáticamente si se detecta una pantalla táctil pequeña.
- También puedes **alternar manualmente** entre modo táctil y escritorio con el botón 📱/🌐.
- El botón ⏯️ pausa el juego.

> 💡 **Consejo:** Pac‑Man se mueve automáticamente en la dirección que elijas. Si choca contra una pared, se detendrá hasta que pueda girar. Puedes cambiar de dirección en cualquier momento y él la "recordará" para la próxima intersección.

### Puntuación y vidas

| Elemento | Puntos |
|----------|--------|
| Pellet (bolita pequeña) | 10 |
| Power Pellet (bolita grande parpadeante) | 50 |
| Fantasma asustado (azul) | 200 |
| Completar nivel | – |

- Comienzas con **3 vidas**.
- Al perder todas, el juego termina (**Game Over**).
- Al comer todos los pellets del laberinto, **avanzas de nivel** y la dificultad aumenta (los fantasmas se vuelven más rápidos).

---

## 👻 Los fantasmas y sus personalidades

Cada uno de los cuatro enemigos tiene un color y un comportamiento único (aunque simplificado en esta versión):

- **Blinky (rojo)** – El fantasma sombra, te persigue directamente.
- **Pinky (rosa)** – La emboscadora, intenta ponerse delante de ti.
- **Inky (celeste)** – El impredecible, su movimiento es errático.
- **Clyde (naranja)** – El distraído, a veces te ignora y se va a su esquina.

Cuando comes un **Power Pellet**, todos los fantasmas se vuelven azules y huyen de ti durante unos segundos. Aprovecha para comerlos y sumar puntos extra.

### Modos de los fantasmas
- **Scatter** – Se dirigen a una esquina del mapa.
- **Chase** – Te persiguen activamente.
- **Frightened** – Modo asustado (tras un Power Pellet).

---

## 🌀 Características de esta versión

- ✅ **Laberinto casi idéntico al clásico** de 28×31 baldosas.
- ✅ **Física mejorada**: Pac‑Man se desliza por el centro de los pasillos y solo gira en intersecciones. ¡Adiós a los atascos en las paredes!
- ✅ **Túnel** que teletransporta de un lado al otro.
- ✅ **Inteligencia artificial** de los fantasmas (persecución, dispersión, huida al comer power pellet).
- ✅ **Sistema de niveles progresivos** (aumenta la velocidad de los fantasmas).
- ✅ **Efectos visuales**: animación de la boca de Pac‑Man, ondulaciones en los fantasmas, power pellets pulsantes.
- ✅ **Mensajes en pantalla** para Game Over, pausa y victoria.
- ✅ **Totalmente responsivo**: se adapta a móviles y tablets.
- ✅ **Controles táctiles** que aparecen automáticamente (o se activan con un botón).
- ✅ **Detección automática de dispositivo**, con opción de forzar el modo deseado.

---

## 📜 Historia de Pac-Man

Pac-Man (originalmente **Puck Man** en Japón) fue creado por **Toru Iwatani** y lanzado por **Namco** en mayo de 1980. Se convirtió en un fenómeno mundial y es considerado uno de los videojuegos más influyentes de todos los tiempos.

- **Inspiración:** Iwatani quería hacer un juego que atrajera a todo tipo de público, no solo a los jugadores habituales de *shooters*. La forma de Pac-Man surgió al ver una pizza a la que le faltaba una porción.
- **Arcadia:** Rápidamente superó a *Space Invaders* en popularidad y generó más de 1000 millones de dólares en monedas durante su primer año.
- **Nombre:** El nombre japonés "Puck Man" derivaba de "paku paku", onomatopeya de abrir y cerrar la boca. Se cambió a "Pac-Man" para evitar vandalismo en las máquinas estadounidenses (cambiar la P por una F).
- **Fantasmas:** Originalmente se llamaban *Shadow*, *Speedy*, *Bashful* y *Pokey*, pero luego adoptaron los nombres que conocemos: Blinky, Pinky, Inky y Clyde.
- **Récords:** La puntuación perfecta en Pac-Man es de **3.333.360 puntos**, lograda por primera vez por Billy Mitchell en 1999.

---

## 🧠 Datos curiosos

- Pac-Man fue el primer videojuego en tener **personajes con personalidad**, lo que inspiró la creación de futuros juegos narrativos.
- El fantasma rojo (Blinky) es ligeramente más rápido que los demás, y es el único que acelera cuando quedan pocos pellets.
- El juego original no tiene un final real; después del nivel 256 ocurre un famoso **"split-screen bug"** (error de pantalla dividida) que impide seguir jugando.
- Existe una canción de **"Pac-Man Fever"** que llegó al top 10 de Billboard en 1982.
- Se estima que Pac-Man ha sido jugado **más de 10 mil millones de veces** en todo el mundo.

---

## 🛠️ Detalles técnicos

El juego está construido con tecnologías web estándar:
- **HTML5 Canvas** para todo el renderizado.
- **JavaScript** puro para la lógica de juego, sin dependencias externas.
- **CSS** para la interfaz, animaciones y diseño responsivo.
- La resolución de la pantalla de juego es de 560×620 píxeles (28×31 celdas de 20 px).

### Cómo ejecutarlo
1. Copia el código completo en un archivo con extensión `.html`.
2. Ábrelo en cualquier navegador moderno (Chrome, Firefox, Edge, Safari…).
3. En móvil o tablet, los controles táctiles aparecerán automáticamente. Si no, pulsa el botón 📱.
4. ¡A jugar!

Puedes modificar parámetros como la velocidad de Pac‑Man o la duración del Power Pellet editando las variables al inicio del bloque `<script>`.

---

## 🏆 ¿Crees que puedes lograr la puntuación perfecta?

¡Demuéstralo! Controla a Pac-Man, devora todos los pellets y conviértete en una leyenda del laberinto… ahora también desde tu móvil.

**Creado con ❤️ y nostalgia por los videojuegos clásicos.**
