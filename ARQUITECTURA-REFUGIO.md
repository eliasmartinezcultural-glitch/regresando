# Refugio de Elías — Documento de arquitectura base
Estado: IDEA Y ESTRUCTURA BASE BLOQUEADAS
Versión: 1.0
Repositorio: `eliasmartinezcultural-glitch/regresando`
Página: https://eliasmartinezcultural-glitch.github.io/regresando/

Este documento conserva las decisiones fundacionales. Las futuras ampliaciones deben respetarlas. Se puede enriquecer el mundo, pero no convertirlo de nuevo en una web convencional con menú de tarjetas.

## 1. Idea central inalterable

El Refugio es un pequeño mundo personal, apacible y de inspiración rural patagónica. La persona entra a un lugar y permanece en él: no visita una colección de páginas. La casa es el ambiente principal, los objetos son las entradas naturales a las experiencias y las habitaciones/patio/senderos amplían ese mismo mundo.

Debe sentirse acogedor, artesanal, matero, humano y vivo incluso cuando Elías no está presente. No tiene obligaciones, rachas, presión, publicidad ni necesidad de una presencia constante del autor.

## 2. Reglas estructurales bloqueadas

1. **Un solo mundo continuo:** casa, habitaciones, patio y recorrido pertenecen al mismo lugar imaginario.
2. **El objeto ES la puerta:** la guitarra abre música y práctica musical; el mate abre el rincón matero; la TV abre el cine; los libros abren lecturas; la estufa/fogón abre el rincón de pausa; la ventana conduce al patio, paisaje o sendero.
3. **No volver a una cuadrícula de tarjetas:** la navegación principal se integra en la escena. Al interactuar con un objeto, el ambiente sigue presente; el contenido puede aparecer en un cuaderno, papel, pantalla de TV, estante u otra pieza coherente con el mundo.
4. **Exploración libre:** no hay recorrido obligatorio, objetivos diarios ni castigo por irse.
5. **Primero estabilidad:** cada ampliación se incorpora sin romper lo que ya funciona. Mantener una copia/commit estable antes de cambios grandes y revisar el archivo antes de editar.
6. **Multidispositivo realista:** diseño adaptable a celular, tablet, computadora y netbook antigua. Evitar motores 3D pesados, dependencias innecesarias y descargas obligatorias. Priorizar ilustración 2D rica en capas, profundidad, luz, sombras y movimientos sutiles.
7. **Accesibilidad:** controles táctiles amplios, teclado, foco visible, contraste alternativo, texto legible y respeto por la preferencia de movimiento reducido.
8. **Sin cuenta ni contraseña:** el acceso a la experiencia no requiere registro.
9. **Privacidad honesta:** las notas personales se guardan localmente en ese navegador/dispositivo. No prometer sincronización entre dispositivos hasta implementar y probar una solución real. No incrustar secretos ni información privada en el repositorio público.
10. **Sin dependencia de la presencia de Elías:** el contenido básico debe estar preparado, ser comprensible y útil por sí mismo.
11. **Internet con límites claros:** la escena y sus funciones locales deben funcionar sin servicios externos siempre que sea posible. Música, vídeos o enlaces externos pueden necesitar conexión y deben indicarlo.
12. **Nada de presión comercial:** no anuncios, ventanas insistentes, notificaciones ni mecánicas adictivas. Cualquier colaboración voluntaria futura será discreta y nunca condición de acceso.
13. **Primero calma:** la llegada debe permitir mirar el ambiente y respirar; el silencio y no hacer nada son usos legítimos.
14. **El mundo debe tener sentido:** no añadir objetos solo como decoración. Cada objeto interactivo debe conducir a una experiencia o contenido definido.

## 3. Mapa inicial del mundo

### Casa principal
- **Mesa matera / mate:** pausa, notas libres, ritual cotidiano y compañía tranquila.
- **Guitarra:** repertorio, acordes, ejercicios breves, ideas musicales y práctica sin exigencia.
- **Televisor:** cine y animación, cine argentino y patagónico, lista personal y enlaces legales disponibles.
- **Estante de libros:** lecturas, cuentos, curiosidades, historias locales y preguntas para investigar.
- **Fogón o estufa:** contemplación, relatos cortos, frases, calor visual y descanso.
- **Sillón:** descanso libre, sin tareas.
- **Ventana:** clima visual, patio, paisaje y transición natural al exterior.
- **Rincón de voz:** canto, calentamiento suave, afinación y confianza vocal; puede estar junto a la guitarra o abrirse desde un objeto coherente, no como menú genérico.
- **Cuaderno personal:** objetivos pequeños, ideas, lecturas y registro voluntario de aprendizajes.
- **Rincón de foco:** temporizador opcional, una intención pequeña y pausas sin culpa.

### Patio
- Plantas, leña, herramientas, tierra, sombra, banco, sendero y pequeños detalles rurales.
- Actividades contemplativas y descubrimientos opcionales; no una lista de tareas domésticas.
- Puede alojar relatos breves, observación de naturaleza y referencias patagónicas cuidadas.

### Recorrido exterior
- Sendero y puntos de interés conectados visualmente con la casa.
- Se explora a voluntad; debe existir siempre una forma evidente de volver a la casa.
- Los espacios futuros pueden incluir galpón/taller, jardín, mirador u otros rincones si aportan una experiencia clara.

## 4. Lenguaje visual y sensorial

- Inspiración: casa rural patagónica, artesanía, acuarela/textura pintada y materiales naturales.
- Paleta: madera, tierra, crema, verde apagado, cobre y luz cálida.
- Riqueza de detalles organizada: objetos reconocibles, capas de profundidad y rincones con identidad.
- Animación mínima y lenta: vapor de la pava, llama del fogón, cortina o hojas que se mueven suavemente, cambio de luz.
- Sonido apagado por defecto; nunca reproducir audio automáticamente.
- Evitar estética corporativa, paneles de dashboard, menús flotantes dominantes o exceso de botones sobre la escena.

## 5. Arquitectura técnica de trabajo

- Sitio estático HTML/CSS/JavaScript en GitHub Pages.
- Sin backend ni base de datos por defecto.
- JavaScript claro, modular y fácil de inspeccionar.
- Mantener cada experiencia separada de la presentación cuando sea viable; evitar duplicar lógica.
- El contenido externo se abre de forma explícita y no debe confundirse con contenido alojado por el Refugio.
- Probar después de cada cambio: escritorio, ancho de celular, teclado, cierre de paneles, almacenamiento local y consola/sintaxis cuando haya herramientas disponibles.
- No afirmar que está publicado o probado visualmente hasta comprobarlo.

## 6. Método para construir en profundidad

Para cada nuevo rincón, trabajar en este orden:
1. Propósito emocional y utilidad concreta.
2. Objeto físico que sirve de entrada.
3. Qué ve y oye la persona (sin audio automático).
4. Interacciones posibles y cómo volver.
5. Contenido real que encontrará, con suficiente profundidad.
6. Diseño adaptable y accesible.
7. Guardado y privacidad, si corresponde.
8. Implementación pequeña, prueba y confirmación antes del siguiente bloque.

## 7. Lista de control antes de aceptar una ampliación

- ¿Sigue pareciendo un lugar y no un sitio web tradicional?
- ¿Se entra a través del objeto correcto?
- ¿El ambiente principal sigue presente?
- ¿La experiencia es libre de presión?
- ¿Se entiende sin que Elías esté presente?
- ¿Funciona con teclado y pantalla táctil?
- ¿Es razonablemente liviana para una netbook antigua?
- ¿Se explica honestamente qué funciona sin internet y dónde se guardan los datos?
- ¿Se puede volver a la casa fácilmente?
- ¿La ampliación preserva lo ya estable?

## 8. Primera prioridad de desarrollo

La siguiente fase no es sumar botones al azar. Es enriquecer el escenario y convertir cada objeto en un rincón completo:
1. Consolidar visualmente la habitación principal y ubicar de forma clara los objetos reales: guitarra, mate, TV, libros, fogón, sillón y ventana.
2. Diseñar la televisión como entrada a Mi cine.
3. Diseñar la mesa matera como espacio central de pausa y cuaderno.
4. Diseñar la guitarra y el rincón de voz como experiencias musicales conectadas.
5. Crear transición natural desde la ventana hacia el patio.
6. Ampliar el patio y luego los senderos, manteniendo siempre continuidad espacial.

**Regla final:** el mundo puede crecer todo lo que haga falta; su esencia no cambia. Es un refugio para entrar, habitar y regresar a uno mismo, no una plataforma que exige atención.
