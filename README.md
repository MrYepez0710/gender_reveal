# La Gran Carrera Revelación v2 🏁💙💗

Carrera de karts en 3D (estilo arcade, vista desde atrás) con personajes personalizables. El ganador se elige en secreto y la carrera siempre termina con ese resultado.

> La versión 1 (honguitos, vista lateral) está en la rama `claude/gender-reveal-mario-kart-1fb405`.

## Cómo usarla
1. Abre `index.html` en Chrome o Edge (no requiere instalación).
2. Toca **⚙ Corredores** (o tecla `S`):
   - Agrega de 2 a 8 corredores: nombre, hombre/mujer/niño/niña, peinado, tono de piel, color de cabello, lentes y barba.
   - Elige **quién gana** (queda oculto tras “Ganador ya configurado”), las vueltas y un mensaje final opcional.
3. Pulsa **¡ARRANCAR!**: se sortea la parrilla de salida corredor por corredor, sigue una toma aérea de la parrilla, el 3-2-1 y la carrera.
4. Al final aparece el ganador con su nombre en grande, en azul (hombre/niño) o rosa (mujer/niña), con confeti y podio.

Botón ⛶ (arriba a la derecha) o tecla `F`: pantalla completa. `M` silencia. En la portada, las teclas `1`–`8` eligen al ganador de forma discreta.

La pista tiene curvas, subidas, bajadas y dos rampas de salto. Hay objetos: biberón turbo, pañal, patito de hule, rayo y estrella.

Prueba interna: en la consola, `__simTest(300)` simula 300 carreras con 2 a 8 corredores y confirma que siempre gana el elegido.
