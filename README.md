# La Gran Carrera Revelación v3 🏁🌀💙💗

Carrera de karts en **3D real** (Three.js) con loop, obstáculos, flechas turbo y rampas de salto. Personajes personalizables, sorteo de parrilla y ganador elegido en secreto (la carrera siempre termina con ese resultado).

> Versiones anteriores: v1 (honguitos) en `claude/gender-reveal-mario-kart-1fb405`, v2 (pseudo-3D) en `claude/gender-reveal-v2-personajes`.

## Cómo usarla
1. Abre `index.html` en Chrome o Edge. **Deja `three.min.js` en la misma carpeta**: es el motor 3D y viene incluido, así que no se necesita internet.
2. **⚙ Corredores** (o tecla `S`): de 2 a 8 corredores, quién gana, vueltas y mensaje final. (Usa la misma configuración que la v2 en ese navegador.)
3. **¡ARRANCAR!**: sorteo de parrilla → toma aérea → 3-2-1 → carrera → revelación con el nombre del ganador en azul o rosa.

Botón ⛶ / tecla `F`: pantalla completa · `M`: sonido · teclas `1`–`8` en la portada: elegir ganador discretamente.

## Lo nuevo en la v3
- Loop vertical con cámara de transmisión lateral cada vez que el líder lo cruza.
- Obstáculos: sonajas gigantes giratorias, pelotas de playa rebotando, cubos ABC que suben y bajan.
- Flechas turbo antes del loop y en la recta trasera; dos rampas de salto con trucos en el aire.
- Director de cámaras tipo TV: cambia de toma cada 4–6 s (persecución, frontal para ver las caras, lateral, dron, pelotón, cámara fija junto a la pista y helicóptero), además de las tomas especiales del loop y de la meta.
- Personajes 3D con cara dibujada según su configuración: ojos, pestañas, cejas y fleco del color de su cabello, lentes, barba, peinado y tono de piel.

Prueba interna: en la consola, `__simTest(300)` simula 300 carreras y confirma que siempre gana el elegido.
