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
