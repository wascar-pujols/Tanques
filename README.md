# Tanques

Juego de tanques para 2 jugadores hecho en **Unity 6** para la materia *Programación de Video Juegos*.
Basado en el paquete "Tanks! Tutorial" (Tanks Complete), con modificaciones propias.

**Autor:** Wascar Pujols (matrícula 1-22-0075)

## Cómo se juega

Dos jugadores en el mismo teclado. Gana la partida el primero en llegar a 5 rondas ganadas.

| Acción | Jugador 1 | Jugador 2 |
|---|---|---|
| Mover | W / A / S / D | Flechas |
| Disparar (mantener y soltar) | Espacio | Enter |

> Ajusta los controles si en tu Input Actions están configurados distinto.

## Características

- Rondas de 2 jugadores, el ganador se decide a 5 victorias.
- Temporizador máximo de 4 minutos: si se acaba el tiempo, ambos jugadores pierden.
- Enemigos que persiguen a los tanques y les estorban durante la pelea (se destruyen con disparos).
- Pantalla final con el ganador, su puntaje y el tiempo que tardó en ganar.

## Cómo ejecutarlo

**Opción A: Jugar directamente en WEB**
1. A traves del link: `https://wascar-pujols.github.io/Tanques/`

**Opción B: versión compilada**
1. Ve a la sección **Releases** del repositorio y descarga `Tanques-Windows.zip`.
2. Descomprime y ejecuta el `.exe`.

**Opción C: desde Unity**
1. Clona el repositorio: `git clone https://github.com/wascar-pujols/Tanques.git`
2. Ábrelo con Unity Hub usando **Unity 6**.
3. Abre la escena principal y pulsa Play.

## Scripts principales

- `GameManager.cs`: ciclo del juego, rondas, temporizador, enemigos y pantalla final.
- `TankManager.cs`: configuración de cada tanque (color, punto de aparición).
- `EnemyBlocker.cs`: comportamiento de los enemigos.

## Créditos

Assets y scripts base: *Tanks! Tutorial*, Unity Technologies.
