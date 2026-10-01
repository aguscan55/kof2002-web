# KOF 2002 Web Player

Página de un solo archivo para jugar en el navegador con [EmulatorJS](https://emulatorjs.org/) e invitar a un amigo por enlace.

- **No incluye juegos ni BIOS.** Cada anfitrión carga su propio archivo desde su computadora; el archivo nunca se sube.
- El invitado no necesita la ROM: ve la partida por streaming (WebRTC) y juega como jugador 2.
- Controles iguales para los dos jugadores, con teclado o joystick.

## Uso

1. Abrir la página y cargar `kof2002.zip`.
2. Tocar **Invitar a un amigo** y mandarle el enlace.
3. Cada jugador pone su ficha con `5` y entra con `Enter`.

## Desarrollo local

```
python -m http.server 8765 --bind 127.0.0.1
```

y abrir `http://127.0.0.1:8765/index.html`.

King of Fighters es marca de SNK Corporation; este proyecto no está afiliado a SNK.
