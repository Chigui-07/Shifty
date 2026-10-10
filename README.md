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

### 2026-10-09 — SHIFTY 0.9: inventario visual del laboratorio
- Se añadió un indicador de inventario de Poción Mini y estado actual (normal/mini) al HUD del Laboratorio.
- Recoger la poción la almacena sin activarla; usarla con Q o el botón consume una unidad.
- Sin pociones, la acción muestra un aviso; volver al tamaño normal sigue siendo una función de pruebas sin devolución de la poción.
- Se agregaron partículas al recoger pociones y etiquetas dinámicas en el botón.
- Nivel 1 permanece congelado, sin cambios en sus plataformas, obstáculos ni mecánicas.
- Pendiente: comprobar la actualización en navegador y evolucionar el inventario para múltiples tipos de pociones.

### 2026-10-09 — SHIFTY 0.10: gravedad experimental
- Laboratorio: segunda poción morada coleccionable de gravedad en x=550, con contador separado del inventario Mini.
- F o botón Gravedad consume la poción al invertir la gravedad; volver a la normalidad no devuelve la unidad (mecánica provisional).
- Dany se orienta visualmente según la gravedad, salta en la dirección correspondiente y puede apoyarse en la cara inferior de plataformas y en un techo exclusivo del Laboratorio.
- Las pociones Mini y Gravedad pueden coexistir; el Nivel 1 oficial no recibió cambios de geometría ni mecánicas.
- Pendiente: prueba manual en navegador, especialmente colisiones invertidas, saltos y acceso a la meta.

### 2026-10-09 — SHIFTY 0.11: gravedad amarilla
- Decisión definitiva de color: la **Poción de Gravedad es amarilla**, mientras la Poción Mini continúa verde. Se actualizaron frasco, iconos y etiquetas de gravedad.
- Laboratorio: indicador visible de gravedad normal/invertida en HUD y aviso amarillo en pantalla mientras la gravedad está invertida.
- Nivel 1 sigue congelado: sin modificaciones de recorrido ni obstáculos.
- Pendiente: probar visualmente en navegador y validar física invertida antes de sumar más mecánicas.

### 2026-10-09 — Fix: transformación Mini + gravedad invertida
- Corregido el anclaje vertical de Dany al cambiar de tamaño: con gravedad normal conserva la posición de los pies; con gravedad invertida conserva la parte superior apoyada en el techo.
- Al crecer se comprueba espacio contra plataformas, túneles, techo y límites horizontales. Si no cabe, se cancela el crecimiento sin mover al personaje.
- El Nivel 1 sigue sin cambios. Pendiente: comprobar en navegador las combinaciones de ambas pociones.

### 2026-10-09 — Fix adicional: techo sólido durante cambios de tamaño invertidos
- Reporte: Dany todavía escapaba por arriba al alternar tamaño pequeño/normal con gravedad invertida.
- Se agregó límite físico continuo y exclusivo del Laboratorio en la cara inferior del techo (y=16) al estar invertido, más estabilización de posición y velocidad al transformarse allí.
- Pendiente: prueba manual del usuario en GitHub Pages; no se considera validado hasta reproducir la secuencia sin fallos.

### 2026-10-09 — SHIFTY 0.12: efectos de transformación
- Laboratorio: al usar Poción Mini o restaurar tamaño, Dany muestra pulso y partículas verdes.
- Al activar o restaurar gravedad, se muestra pulso y partículas amarillas.
- La animación visual dura aproximadamente 0,42 segundos; no modifica el tamaño físico, las colisiones ni la física existente.
- Se limpia el efecto al reiniciar el intento. Nivel 1 permanece congelado.
- Pendiente: comprobar los efectos en navegador, incluyendo transformaciones con gravedad invertida sobre el techo.

### 2026-10-09 — SHIFTY 0.13: animaciones ambientales
- Pociones Mini (verde) y Gravedad (amarilla) flotan suavemente arriba/abajo y muestran un halo pulsante. El movimiento es visual: sus coordenadas de recogida no cambian.
- Dany respira suavemente cuando está quieto y apoyado, tanto en gravedad normal como invertida. El efecto modifica únicamente la representación gráfica, no las colisiones.
- Nivel 1 conserva recorrido y jugabilidad. Próxima propuesta: inventario escalable para futuras pociones.
- Pendiente: comprobación visual en navegador.

### 2026-10-09 — SHIFTY 0.14: cuatro mejoras del Laboratorio
- Inventario visual: ranuras de Poción Mini y Gravedad con cantidades, teclas Q/F y resaltado de habilidades activas; tercera ranura reservada para una futura habilidad. Solo se muestra en Laboratorio.
- Movimiento: se corrigió la animación de respiración para que siga avanzando cuando Dany permanece quieto.
- Zonas de pruebas: señalización visible para Mini, Gravedad, túnel y combinación de poderes; no se modifica la geometría de Nivel 1 ni se añaden riesgos al recorrido.
- Audio sintetizado con Web Audio: saltar, recoger monedas/pociones, transformar, fallar y completar; botón para activar o silenciar sonido. El audio comienza tras una interacción permitida por el navegador.
- Pendiente: probar manualmente interfaz, audio y jugabilidad en navegador; no se considera validado aún.

### 2026-10-09 — SHIFTY 0.15: Poción Nave (sin alas)
- Nueva poción celeste en Laboratorio, ubicada cerca de x=760; se recoge en inventario y se activa con G o botón táctil.
- Al activarla Dany saca una nave desde atrás, entra en la cabina y puede pilotarla. G permite guardarla sin recuperar la poción consumida.
- Dentro de la nave, mantener Saltar/espacio activa propulsores en vez de un salto; al soltar se aplica gravedad. Con gravedad invertida, gravedad y propulsión se invierten y también se invierte el movimiento horizontal de la nave.
- Combinaciones simultáneas: tamaño Mini + gravedad invertida + nave; con Mini, la nave es más pequeña y se desplaza más rápido.
- Inventario, señales y controles actualizados. Nivel 1 sin cambios de geometría o contenido.
- Pendiente: probar visualmente la animación y la física de vuelo/colisiones en navegador, en especial las combinaciones triples.

### 2026-10-09 — SHIFTY 0.16: Nave rosa permanente y Normal gris
- La Poción Nave cambia de celeste a rosa. Activarla con G transforma permanentemente a Dany en piloto hasta consumir una Poción Normal. No se puede guardar ni desactivar la nave pulsando G otra vez.
- Nueva Poción Normal gris, con ejemplares en Laboratorio (x=895 y x=1810), recogida en inventario y activación con H o botón táctil. Restablece nave desactivada, tamaño normal y gravedad normal simultáneamente.
- Antes de crecer, comprueba el espacio disponible para evitar atravesar plataformas o techo. El reinicio también restaura todas las transformaciones.
- Inventario y señales actualizados. La nave mantiene propulsores con Saltar, velocidad superior en Mini y controles horizontales invertidos bajo gravedad invertida.
- Nivel 1 sigue congelado. Pendiente: pruebas manuales en navegador de las combinaciones y retorno a Normal, especialmente desde el techo.

### 2026-10-09 — SHIFTY 0.17: corrección de nave invertida
- Corregida la colisión vertical: la nave debe detenerse en la cara superior o inferior de plataformas según su dirección vertical, incluso cuando los propulsores se oponen a la gravedad invertida.
- El techo sólido del Laboratorio limita el movimiento hacia arriba independientemente de la orientación de gravedad.
- Los controles horizontales conservan su sentido natural en nave invertida: izquierda va a la izquierda y derecha a la derecha. La sensación diferente proviene de la orientación visual y de la dinámica vertical.
- Se conserva Nivel 1 y la combinación de Mini + Nave + Gravedad invertida.
- Pendiente: validar en navegador la colisión a velocidad máxima y el aterrizaje desde ambos lados.

### 2026-10-09 — SHIFTY 0.18: nave con inercia y peso
- La nave acelera, frena y cambia de dirección progresivamente, sin invertir controles horizontales.
- Con gravedad invertida, la respuesta horizontal y el encendido de propulsores son más lentos; se incrementa ligeramente la fuerza de gravedad para una sensación más pesada.
- La nave Mini conserva mayor agilidad que la grande.
- Inclinación visual sutil según velocidad y llama de propulsión proporcional al empuje real.
- Nivel 1 no se altera. Pendiente: probar en navegador el equilibrio de la física, las colisiones y la combinación triple.

### 2026-10-09 — SHIFTY 0.19: pociones de contacto
- Eliminado el uso del inventario y de las teclas Q/F/G/H para activar pociones. Los efectos se aplican directamente al tocar las botellas.
- Verde: tamaño Mini; amarilla: gravedad invertida; rosa: nave pilotable; gris: restaura simultáneamente tamaño normal, gravedad normal y ausencia de nave.
- Las transformaciones pueden combinarse y permanecen activas hasta tocar una botella gris. Las botellas ya usadas desaparecen durante ese intento.
- Si no hay espacio para crecer al tocar la gris, no se consume y se muestra un aviso.
- Los botones de pociones y la barra de inventario se ocultan; las señales y las instrucciones ahora explican el contacto. Los controles de movimiento, salto/propulsores y el Nivel 1 permanecen.
- Pendiente: pruebas manuales de contacto, colisiones y retorno a Normal en navegador.

### 2026-10-09 — SHIFTY 0.20: arreglo de nave invertida inmóvil
- La colisión horizontal solo bloquea al cruzar realmente un lateral del obstáculo desde fuera; se evita inmovilizar la nave cuando se desplaza junto a superficies tras invertir gravedad.
- La nave invertida responde algo más rápido horizontalmente sin perder la inercia; propulsores invertidos ligeramente más fuertes para contrarrestar su peso.
- Izquierda y derecha mantienen su sentido normal. Nivel 1 sin cambios.
- Pendiente: verificar en navegador, en particular nave + gravedad invertida y triple combinación con Mini.

### 2026-10-09 — SHIFTY 0.21: seis pociones y tres estados independientes
- Morada: Dany pequeño. Verde: Dany grande (comprueba espacio antes de crecer).
- Amarilla: gravedad invertida. Celeste: gravedad normal.
- Rosa: activa la nave. Gris: retira exclusivamente el vehículo, sin modificar tamaño ni gravedad.
- Todas se activan al contacto; no hay inventario ni teclas para transformarse. Las transformaciones se combinan libremente.
- Añadidas botellas verde y celeste al Laboratorio y actualizados colores, letreros e instrucciones. Nivel 1 permanece intacto.
- Pendiente: validar en navegador combinaciones, retorno a tamaño grande y posiciones de botellas.

### 2026-10-09 — SHIFTY 0.22: pociones en el techo
- Añadidas siete pociones a lo largo del techo del Laboratorio (altura y=62), incluyendo varias celestes para restaurar la gravedad normal, rosa para nave, gris para salir de ella, verde para crecer y morada para encogerse.
- Señal de orientación en la parte superior. Permite salir del techo sin reiniciar después de invertir gravedad.
- Nivel 1 permanece intacto. Pendiente: validar accesibilidad de todas las botellas en navegador.

### 2026-10-10 — SHIFTY 0.23: propulsores y sierras móviles
- Dos propulsores azules en el suelo del Laboratorio lanzan a Dany con velocidad vertical hacia arriba, permitiendo saltos altos sin pulsar otra tecla.
- Dos propulsores naranjas suspendidos en el aire aceleran la caída de Dany hacia abajo.
- Los propulsores funcionan con Dany normal, Mini y en nave, independientemente del estado de gravedad; tienen un breve enfriamiento para evitar activaciones repetidas instantáneas.
- Dos sierras móviles oscilan horizontalmente y hacen perder el intento al tocarlas. Se añadieron efectos gráficos y carteles explicativos.
- Nivel 1 permanece intacto. Pendiente: comprobar equilibrio, accesibilidad y colisiones en navegador.

### 2026-10-10 — SHIFTY 0.24: plataformas móviles e intermitentes
- Tres plataformas móviles oscilan horizontal o verticalmente en el Laboratorio.
- Tres plataformas intermitentes aparecen durante aproximadamente el 62 % de cada ciclo y luego desaparecen; se dibuja su contorno cuando están ausentes.
- Las plataformas activas participan en las colisiones del jugador y combinan con propulsores y sierras.
- Señales de orientación y texto del Laboratorio actualizados. Nivel 1 intacto.
- Pendiente: pruebas en navegador, especialmente cuando una plataforma desaparece bajo Dany o se mueve mientras está encima.

### 2026-10-10 — SHIFTY 0.25: plataformas móviles transportan a Dany
- Corrección: si Dany está apoyado sobre una plataforma móvil, hereda el desplazamiento horizontal y vertical de esa plataforma.
- Se contempla el apoyo en la cara inferior al jugar con gravedad invertida.
- Las plataformas intermitentes no se modifican: siguen desapareciendo y dejan caer a Dany.
- Nivel 1 permanece intacto. Pendiente: validar en navegador el transporte sobre plataformas verticales y con gravedad invertida.

### 2026-10-10 — SHIFTY 0.26: alcance de beta, lienzo y controles móviles
- Decisión de diseño: primera beta de estilo geométrico digital, sin temática de aire libre.
- Cada nivel nuevo del futuro editor partirá de un lienzo vacío con suelo continuo; el creador colocará las demás piezas. El nivel beta provisional se simplificó a suelo continuo, sin obstáculos precolocados, con fondo violeta/azul y suelo geométrico.
- Piezas previstas para la beta: bloques sólidos de apoyo, pinchos oscuros, nave, pociones de gravedad normal/invertida y de activación/retirada de vehículo. Sin techo por defecto.
- Reservado para actualizaciones futuras: rueda, pociones de tamaño pequeño/grande, sierras, plataformas móviles, propulsores y otras mecánicas avanzadas.
- El Laboratorio conserva todas las mecánicas ya implementadas para pruebas, pero no representa el catálogo inicial de la beta.
- En dispositivos táctiles, controles izquierda/derecha/salto fijados a la parte inferior de la pantalla y disposición de juego ajustada a la altura del dispositivo, evitando desplazamiento de la página. La cámara horizontal del mundo continúa siguiendo a Dany.
- Pendiente: implementar editor, catálogo restringido de beta, niveles guardables y probar controles en teléfono real.

### 2026-10-10 — SHIFTY 0.27: PWA y juego horizontal
- Se agregó `manifest.webmanifest` para instalar SHIFTY como aplicación web independiente desde navegadores compatibles; modo fullscreen y orientación landscape solicitada.
- Se creó `icon.svg` como ícono inicial y `sw.js` con caché de recursos y preferencia por la red para recibir actualizaciones desde GitHub Pages.
- Interfaz móvil en horizontal: canvas ocupa el área disponible, HUD compacto y controles táctiles fijos sobre la pantalla. En vertical aparece una sugerencia para girar el dispositivo.
- La orientación no se puede forzar universalmente desde el navegador: depende del dispositivo, permisos y soporte de instalación. El teléfono puede requerir rotación automática activada.
- GitHub Pages continúa como distribución oficial; cada commit desplegado actualiza la PWA en línea, aunque el navegador puede tardar en refrescar recursos almacenados.
- Pendiente: probar instalación y controles en Android real; posiblemente añadir íconos PNG para compatibilidad amplia.
