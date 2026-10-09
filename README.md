# SHIFTY 🎮

Videojuego de plataformas 2D en fase de diseño. Este README funciona como **documento vivo y bitácora oficial**: las decisiones confirmadas se distinguen de las ideas pendientes.

## Visión
- Protagonista inicial: **Dany**, un personaje pequeño y personalizable. Podrían existir más personajes, con diferencias o progresión por definir.
- Los niveles principales introducirán pociones, vehículos y nuevas funciones; tendrán variedad de desafíos dentro de una estética compartida aún sin definir.
- Mecánicas basadas en **pociones** recogidas en los niveles, no poderes exclusivos de Dany.
- Las pociones pueden acumularse en inventario; consumir varias seguidas no acumula usos activos. Tras abandonar un estado se requiere otra poción para recuperarlo.
- **Varios estados pueden coexistir** y combinarse con vehículos. **Solo un vehículo a la vez.** La nave tendrá reglas especiales por diseñar.
- Estados previstos: tamaño pequeño, gravedad invertida y retorno al estado normal. Vehículos/mecánicas previstos: rueda y nave; vuelo y demás detalles pendientes.

## Dificultades y recompensas
Las variantes de una dificultad normal conservan la **misma cara**. Colores: Fácil azul, Normal verde, Difícil amarillo, Muy difícil naranja, Extremo morado; las cinco Pesadillas usan rojos progresivamente más oscuros. Las caras finales serán diseños propios.

| Dificultad | Estrellas | Diamantes base/propuestos |
|---|---:|---:|
| Fácil | 2 | 50 |
| Normal | 3 | 75 |
| Difícil | 4 | 150 |
| Difícil | 5 | 175 |
| Muy difícil | 6 | 200 |
| Muy difícil | 7 | 225 |
| Extremo | 8 | 350 |
| Extremo | 9 | 375 |
| Pesadilla fácil | 10 | 500 |
| Pesadilla normal | 11 | 550* |
| Pesadilla difícil | 12 | 600* |
| Pesadilla extrema | 13 | 650* |
| Pesadilla infernal | 15 | 750* |

\* **Pendiente confirmar** la distribución escalonada de diamantes de Pesadilla. El salto de 13 a **15 estrellas** en Infernal es intencional. Los aumentos de 25 diamantes para las variantes normales son la interpretación actual.

- Las estrellas se conceden por la **primera finalización**, no al repetir.
- Los diamantes también tienen recompensa única por nivel. Idea a concretar: parte por progreso/fallos, resto al completar. En Pesadilla, se plantearon 100 garantizados y 400 proporcionales al avance para la recompensa base de 500; faltan detalles y adaptación a variantes.
- El porcentaje de progreso del nivel **no** es la moneda de clasificación: esta se llama **Estrellas**.

## Calidad de niveles y martillos
Solo el administrador del juego concede calificaciones oficiales a niveles comunitarios. **La dificultad y la calidad son independientes**.

| Calidad | Martillos para el creador | Efecto SOLO en la cara de dificultad |
|---|---:|---|
| Calificado | 1 | Sin efecto adicional |
| Especial | 2 | Contorno de fuego |
| Épico | 3 | Llama animada alrededor |
| Legendario | 4 | Llamas rosadas **en movimiento**, cuya energía parece absorber la superficie de la cara |
| Mítico | 5 | Energía celeste animada, cara transformada, ojos brillantes, sonrisa brillante si existe y chispas intensas |

Los efectos visuales de calidad **solo afectan a la cara**, no a la pantalla de victoria ni al resto de la interfaz. Conviene ofrecer una opción para reducir destellos/animaciones (propuesta).

## Coleccionables y personalización
- Hasta **tres monedas opcionales por nivel**; sus espacios solo aparecen si el nivel contiene monedas.
- **Oro**: niveles principales; ocultas, con rutas alternativas, llaves u otros retos de exploración. No son necesarias para completar el nivel.
- **Bronce**: monedas de niveles comunitarios mientras no tengan aprobación oficial. Deben verificarse al publicar el nivel.
- **Plata**: monedas comunitarias aprobadas por el administrador. Un nivel puede estar calificado y conservar monedas de bronce si estas no merecen aprobación.
- **Diamantes**: moneda para tiendas. **Estrellas**: clasificación/progreso.
- **Taller/galería**: personajes, vehículos, atuendos, colores y decoraciones, con visualización de coleccionables.
- **Tienda**: algunas personalizaciones comprables; otras se obtendrán mediante logros. **Los logros los definirá el creador del proyecto**, no el asistente.

## Estadísticas
Totales de monedas de oro/plata, estrellas, diamantes obtenidos, niveles completados, niveles Pesadilla completados, fallos/intentos, clics/toques dentro de niveles, **tiempo jugado** y **martillos** de creador cuando corresponda. Se proponen récords y tiempo por nivel; detalle pendiente.

## Zona online
- Editor y creación de niveles; búsqueda; niveles guardados y favoritos; rankings mundiales de estrellas y creadores; tienda.
- Para publicar, el nivel debe **verificarse completándolo** por el creador u otra persona.
- Tras publicarse, entra en la **cola de revisión** del administrador para una posible calificación oficial.
- Se aceptan como conceptos el **modo práctica**, **favoritos** e **historial de récords**; reglas concretas pendientes.
- Propuesta técnica: cambios jugables tras verificar requerirían nueva verificación.

## Pendientes de diseño
Motor, plataforma, controles, estética, interfaz, diseño de Dany y personajes adicionales, habilidades/progresión de personajes, reglas de la nave, vehículos y pociones, duración/activación de estados, recompensas exactas por fallo, diamantes de Pesadilla, editor, verificación y moderación, economía, servidores, reglas de monedas y récords. No dar por confirmadas las propuestas.

## Bitácora
### 2026-10-09 — Docs: inicio de la bitácora
- Se recopilaron las decisiones de diseño conversadas hasta ahora.
- Se definieron colores de dificultad, estrellas (incluida Pesadilla infernal de **15**), calidades, martillos y efectos visuales exclusivos de las caras.
- Se añadieron **animaciones de llamas** para Legendario y Mítico.
- Próximo paso: diseñar identidad visual, Dany y la primera experiencia jugable antes de implementar los sistemas online.

### 2026-10-09 — Diseño provisional de Dany y expresiones
- **Dany (boceto 02, no definitivo):** cuerpo cuadrado redondeado y equilibrado, color #E8E8E8, ojos ovalados más juntos, solo piernas largas, contorno oscuro marcado y sonrisa suave.
- Otras formas geométricas quedan reservadas como posibilidades para **futuros personajes**, no como transformaciones cosméticas de Dany.
- La tienda podrá vender **algunas expresiones y algunos colores**; no todos estarán a la venta.
- **Expresiones activables:** mediante una tecla se abre un menú pequeño con las expresiones que el jugador posee; elige una y el personaje la muestra. Se contempla su uso comunicativo en un **futuro multijugador**. Tecla, duración, interrupciones y catálogo exacto aún pendientes.

### 2026-10-09 — Duración de las expresiones
- **Confirmado:** las expresiones seleccionadas desde el menú se muestran durante unos segundos y luego el personaje recupera automáticamente su expresión normal.
- **Pendiente:** duración exacta; 3 segundos es una propuesta de prueba, no una decisión definitiva.

### 2026-10-09 — Feat: prototipo jugable 0.1
- Se eligió **HTML5 + JavaScript Canvas** para la primera versión jugable.
- Se creó `index.html` sin dependencias externas: nivel horizontal con cámara, plataformas, saltos, obstáculos, meta, intentos y cronómetro.
- Dany usa el boceto provisional: cuadrado redondeado gris claro, ojos ovalados próximos, sonrisa suave y piernas animadas.
- Animaciones iniciales mediante código: reposo, desplazamiento, salto, caída y aterrizaje (provisionales).
- Menú de expresiones con **E** o botón, tres expresiones de prueba y duración de **3 segundos provisional**.
- Controles: A/D o flechas, Espacio/W/flecha arriba, E para expresiones y R para reiniciar; botones táctiles.
- **Pendiente:** probar en navegador real, ajustar físicas y arte, definir diseño final de Dany y construir siguientes mecánicas.

## Ejecutar prototipo
Abrir [index.html](./index.html) en un navegador moderno. No requiere instalar nada. Para publicarlo en GitHub Pages: Settings → Pages → Deploy from a branch → main / root. La publicación aún debe configurarse y verificarse.

### 2026-10-09 — Prototipo de laboratorio: poción pequeña
- Se añadió al `index.html` una poción coleccionable para probar el inventario y la transformación de tamaño.
- **Q** o el botón táctil permite usar una poción recogida y alternar entre tamaño pequeño y normal; la transformación de regreso se bloquea si falta espacio.
- Se añadió un pasadizo bajo para probar el cambio de tamaño. Los gráficos y geometría son provisionales.
- Este nivel es un **laboratorio de pruebas**, no un nivel oficial.
- Pendiente: probar la colisión, ajustar posición del pasadizo, mejorar decoraciones y definir cómo se obtiene la poción para recuperar el tamaño normal en el diseño definitivo. La alternancia actual es una facilidad temporal de prueba.

### 2026-10-09 — Ajustes de laboratorio (0.3)
- La poción se llama **Poción Mini** y es **verde claro**.
- Al estar pequeño, Dany **corre más rápido** (345 frente a 260 unidades/s) y **salta menos alto** (impulso -460 frente a -660); valores provisionales para probar.
- Se revisaron las colisiones horizontales y verticales de las plataformas, que deben ser sólidas; los obstáculos peligrosos y caídas eliminan a Dany.
- Se añadió porcentaje de avance por posición horizontal (0–99 %, 100 % al llegar a la meta).
- Se añadió animación provisional de derrota con partículas y breve espera antes de reaparecer.
- Recuperar tamaño normal con Q sigue siendo exclusivamente una ayuda temporal del laboratorio, no la mecánica definitiva.
- **Pendiente:** verificar en navegador la física, los saltos y el pasadizo; no confundir plataformas sólidas con obstáculos letales.

### 2026-10-09 — Prototipo 0.4: animaciones
- Dany ahora tiene parpadeo periódico, balanceo suave en reposo, zancadas más marcadas, partículas al correr, impulso visual al saltar, estiramiento durante la caída y compresión al aterrizar.
- Todas las animaciones son procedurales y provisionales; pendiente probarlas y ajustar sus tiempos y amplitudes en navegador.

### 2026-10-09 — SHIFTY 0.5: navegación
- Se añadió un **menú principal** con título SHIFTY, representación animada provisional de Dany y botón Jugar.
- **Jugar** abre el selector de niveles; por ahora solo contiene el **Laboratorio de pruebas**.
- Se añadió menú de **pausa** con Continuar, Reiniciar y Menú principal, activable con Escape o botón.
- El nivel no avanza mientras el usuario está en los menús.
- Pendiente: verificar la navegación en navegador, mejorar arte y definir las secciones definitivas del menú.

### 2026-10-09 — SHIFTY 0.6: progreso y final de nivel
- Barra visual de avance sincronizada con el porcentaje, desde 0 % en la posición inicial.
- Pantalla de victoria con tiempo e intentos, opciones de repetir, volver al selector de niveles o al menú principal.
- El laboratorio sigue siendo el único nivel jugable; el primer nivel oficial se desarrollará aparte.
- Pendiente: comprobar las pantallas en navegador y diseñar el primer nivel oficial.

### 2026-10-09 — SHIFTY 0.7: primer nivel oficial
- Se añadió **Nivel 1: Primeros pasos**, seleccionable desde el menú junto al Laboratorio.
- Nivel 1 introduce desplazamiento, saltos, plataformas, peligros y bandera; no tiene pociones.
- El Laboratorio conserva su Poción Mini, obstáculos y recorrido original.
- Ambos niveles comparten por ahora el motor, HUD y arte provisional; sus geometrías y peligros se cargan por separado.
- Pendiente: pruebas reales de jugabilidad, ajustar dificultad, comprobar GitHub Pages y definir decoraciones.

### 2026-10-09 — SHIFTY 0.8: monedas en el laboratorio
- Se agregaron **3 monedas doradas opcionales** exclusivamente al Laboratorio; el Nivel 1 permanece congelado y sin modificaciones.
- Las monedas tienen animación de giro/flotación, partículas al recogerlas y contador en el HUD.
- El resultado del laboratorio incluye la cantidad de monedas obtenidas; se reinician al reintentar. Aún no existe guardado permanente.
- Pendiente: probar su accesibilidad y colisiones en navegador; ajustar ubicación si alguna resulta difícil de recoger.
