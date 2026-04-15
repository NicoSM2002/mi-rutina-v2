# Mi Rutina App — Documento Fundacional

> "Tu entrenador en el bolsillo."

---

## 1. Verdad de Marca (Brand Truth)

### Historia de Origen

Mi Rutina nace de una experiencia real. Su creador lleva dos anos entrenando con un entrenador personal — mayormente presencial, pero con periodos de entrenamiento virtual durante viajes. Cuando un amigo cercano empezo a entrenar virtualmente con el mismo entrenador (porque vive lejos), las limitaciones del sistema tradicional se hicieron evidentes:

- Esperando en el gimnasio a que el entrenador conteste, pero el entrenador esta con otros clientes presenciales y no puede dedicarte tiempo
- Rutinas enviadas por WhatsApp que se pierden entre mensajes personales
- Preguntas sobre tecnica que un simple mensaje no resuelve
- Comidas que se intentaron registrar en Fitia (app externa con version paga), donde habia que subir todo manual — al final el entrenador la abandono y volvio a pedir fotos por WhatsApp, donde tambien se perdian
- Cero visibilidad de si el entrenador realmente esta analizando tu progreso, tus comidas, tu entrenamiento

De ahi nace la pregunta: **¿Por que no existe una sola aplicacion que centralice todo esto?** Una herramienta dedicada exclusivamente para que el entrenador profesionalice su servicio virtual y el atleta tenga todo en un solo lugar.

### El Problema

El entrenamiento virtual vive en el caos. Los entrenadores mandan rutinas por WhatsApp, los pesos por un lado, las notas por otro, las fotos de comidas se pierden entre mensajes personales, y al final nadie sabe si el cliente realmente esta entrenando. El mayor reto es la desconexion: el entrenador pierde tiempo, pierde control, y el cliente pierde motivacion.

### La Solucion

**Mi Rutina App** es un anadido profesional al servicio del entrenador. No reemplaza al entrenador — lo potencia. El atleta siempre sabe que hay un profesional real detras de su plan. La app simplemente centraliza todo el ecosistema entrenador-atleta en un solo lugar: rutinas interactivas, seguimiento nutricional con IA, control de pagos, comunicacion directa y metricas de progreso.

### Declaracion de Marca

Mi Rutina no es una app de rutinas genericas. Es una herramienta construida para **entrenadores** que quieren entregar un servicio profesional, diferenciado y escalable a cada uno de sus afiliados. La app existe para cerrar la brecha entre el entrenador y el atleta, eliminando la friccion y convirtiendo el entrenamiento virtual en una experiencia superior a la presencial.

### Creencias Fundamentales

- Todo entrenador merece herramientas profesionales para escalar su negocio
- La tecnologia debe eliminar friccion, no agregarla
- La Inteligencia Artificial es un aliado que potencia al entrenador, no lo reemplaza
- Un cliente que ve su progreso real es un cliente que renueva mes a mes
- La centralizacion de informacion es la base de un servicio de calidad
- **Siempre hay un profesional detras** — la app es el vehiculo, no el destino

### Principios de Producto

Reglas de decision que guian cada feature y cada cambio en la plataforma:

1. **Simplicidad sobre cantidad** — Si hay duda entre agregar complejidad o mantener la app simple, siempre elegimos simple. No queremos abrumar al usuario con mil herramientas como hacen otras apps de fitness.
2. **El entrenador es el centro** — Cada feature debe hacer que el entrenador se vea mas profesional ante su atleta. La app es un anadido a su servicio, no un reemplazo.
3. **Informacion donde se necesita** — Nada de "ir a otra app para ver esto". Todo en un mismo lugar.
4. **Visual y rapido** — GIFs antes que textos largos. Tarjetas antes que tablas. Minimalista antes que recargado.
5. **Cero friccion de entrada** — Un link y listo. Sin descargas, sin registros complicados, sin versiones pagas con features basicos bloqueados.

---

## 2. Arquitectura de Audiencia

### Persona 1: El Entrenador Virtual

**Arquetipo:** El Profesional que Quiere Escalar

- **Motivacion:** Pasar de manejar 5-10 clientes de forma desordenada a gestionar 20, 30 o mas con la misma calidad de servicio
- **Creencia actual:** "WhatsApp y Excel me funcionan, pero siento que pierdo clientes porque no puedo darles seguimiento real"
- **Punto de tension:** Dedica mas tiempo organizando informacion que entrenando. Cada cliente nuevo es mas carga administrativa. Cuando esta con un cliente presencial, los virtuales quedan esperando respuestas.
- **Objeccion principal:** "Mis clientes no van a usar otra app" / "Ya tengo mi sistema armado con WhatsApp"
- **Estado de exito:** Tiene un panel centralizado donde ve el progreso de todos sus clientes, recibe notificaciones automaticas cuando completan rutinas o envian comidas, y puede editar rutinas en minutos. Sus clientes lo perciben como un profesional de otro nivel

### Persona 2: El Atleta Comprometido

**Arquetipo:** El Cliente que Quiere Resultados Reales

- **Motivacion:** Tener claridad total sobre que hacer cada dia, como hacerlo, y ver que su esfuerzo se traduce en resultados medibles
- **Creencia actual:** "Mi entrenador me manda PDFs y mensajes, pero a veces me pierdo o no se si estoy haciendo bien los ejercicios"
- **Punto de tension:** No tiene un lugar centralizado para ver su rutina, registrar sus comidas, y comunicarse con su entrenador. Llega al gimnasio y tiene que esperar a que el entrenador conteste para saber que hacer.
- **Objecion principal:** "¿De verdad mi entrenador esta revisando mis cosas o esto es automatico?" / "¿Voy a tener que aprender a usar otra app mas?"
- **Estado de exito:** Abre una sola app, ve exactamente su sesion del dia con GIFs de tecnica, registra sus comidas con foto y recibe analisis nutricional instantaneo, y sabe que su entrenador esta al tanto de todo sin tener que escribirle

### Persona 3: El Atleta Nuevo o Casual

**Arquetipo:** El que Llega sin Experiencia

- **Motivacion:** Empezar a entrenar con guia profesional pero sin el costo del presencial. Muchas veces entrena virtual porque es significativamente mas economico (presencial ~$700,000 COP/mes vs virtual ~$250,000-$300,000 COP/mes)
- **Creencia actual:** "Quiero entrenar pero no se nada, necesito que alguien me diga exactamente que hacer"
- **Punto de tension:** No conoce los ejercicios, no sabe tecnica, no sabe cuanto peso usar. Un mensaje de texto con "press inclinado 3x12" no le dice nada.
- **Objecion principal:** "¿Voy a poder entrenar bien sin tener al entrenador al lado?"
- **Estado de exito:** Abre la app, ve el GIF de cada ejercicio, entiende la tecnica, puede preguntarle al asistente de IA si tiene dolor o duda, y siente que tiene un acompanamiento real aunque sea virtual

### Quien NO es el Target

- Usuarios casuales que buscan rutinas genericas o planes de entrenamiento gratuitos
- Gimnasios o cadenas que necesitan gestion de membresias masivas
- Personas que quieren entrenar sin la guia de un entrenador profesional
- Atletas que buscan una app que les genere rutinas automaticas — **aqui siempre hay un entrenador real detras**

---

## 3. Contexto Cultural y Posicionamiento

### El Momento

El entrenamiento virtual exploto post-pandemia y se quedo. Millones de personas entrenan con coaches a distancia, pero las herramientas no han evolucionado: siguen usando WhatsApp, PDFs estaticos y hojas de calculo. Hay una brecha enorme entre lo que el entrenador quiere entregar y lo que sus herramientas le permiten.

### La Tension Cultural

Existe una tension real: la gente quiere entrenamiento personalizado con un profesional, pero el presencial es caro. El virtual es significativamente mas economico (menos de la mitad del precio), pero la experiencia es inferior porque las herramientas no estan a la altura. **Mi Rutina resuelve esa tension** — hace que el entrenamiento virtual se sienta tan profesional y acompanado como el presencial, a una fraccion del costo.

### Panorama Competitivo

| Categoria | Ejemplos | Limitacion |
|-----------|----------|------------|
| Apps de rutinas genericas | Strong, Hevy, FitNotes | Son para usuarios individuales, no para la relacion entrenador-atleta |
| Plataformas de coaching | TrueCoach, TrainHeroic | Costosas, complejas, no incluyen IA, enfocadas en mercado anglosajon |
| WhatsApp + Excel | El metodo tradicional | Caos total, cero profesionalismo, no escala |
| Google Sheets / Notion | Entrenadores organizados | Resuelve rutinas pero no comidas, pagos, ni tecnica visual. Sigue fragmentado |
| Apps con bots de mensajeria | Bots de Telegram/WhatsApp | Limitados, sin interfaz visual, sin GIFs, sin analisis nutricional |
| Apps de nutricion (Fitia, MyFitnessPal) | Registro de comidas dedicado | Versiones pagas para features basicos, registro manual tedioso, desconectadas del entrenamiento |

### El Patron de Fragmentacion

El entrenador virtual tipico hoy usa 3-5 herramientas distintas: WhatsApp para comunicarse, Excel/Sheets para rutinas, alguna app para comidas, transferencia bancaria para pagos, y videollamada para corregir tecnica. **Cada herramienta adicional es un punto de fuga donde se pierde informacion y se pierde el cliente.**

### Espacio en Blanco (White Space)

No existe una plataforma que sea un **ecosistema cerrado entrenador-atleta** con:
- Inteligencia Artificial integrada (chat + analisis nutricional)
- GIFs de tecnica por ejercicio
- Cero friccion (PWA, sin descarga de tiendas, sin versiones pagas bloqueando features basicos)
- Enfoque en el mercado latinoamericano
- Precio accesible para entrenadores independientes

### Declaracion de Posicionamiento

Mi Rutina App es la primera plataforma de entrenamiento virtual en Latinoamerica que convierte al entrenador independiente en un profesional con herramientas de nivel empresa, usando Inteligencia Artificial para automatizar lo repetitivo y permitirle enfocarse en lo que importa: entrenar.

---

## 4. Marco de Mensajeria

### Mensaje Central

**"Tu entrenador en el bolsillo."**
Una sola frase que captura la promesa: acceso inmediato, permanente y profesional al servicio de tu entrenador, desde cualquier lugar.

### Elevator Pitch (30 segundos)

> Mi Rutina es una app para entrenadores virtuales que centraliza todo en un solo lugar — rutinas con GIFs de tecnica, seguimiento de comidas con analisis de IA, pagos y comunicacion directa. El entrenador edita las rutinas desde su portal, el atleta las ve en la app con todo el detalle que necesita. En vez de usar WhatsApp, Excel y tres apps diferentes, todo esta en un link. Es un anadido profesional al servicio del entrenador que hace que sus clientes lo vean como un profesional de otro nivel.

### Pilares de Mensaje

1. **Cero Friccion** — Aplicacion Web Progresiva (PWA). Funciona como app nativa, sin descargas molestas en tiendas. Un link y listo.

2. **Ecosistema Cerrado** — Tu y tus clientes conectados en una sola plataforma dedicada. Nada de informacion dispersa entre apps.

3. **Control Total** — Adios a la fragmentacion de herramientas. Rutinas, comidas, pagos, comunicacion y progreso en un solo lugar.

### Mensajes por Audiencia

**Para entrenadores:**
- "Deja de perseguir clientes por WhatsApp. Ten todo en un solo lugar."
- "Tus clientes te van a ver como un profesional de otro nivel."
- "La misma calidad de servicio con 5 o con 50 clientes."
- "Cada ejercicio ya tiene su GIF y su tecnica cargada. Arma rutinas en minutos."

**Para atletas:**
- "Tu rutina completa con tecnica visual, siempre disponible."
- "No mas esperar a que tu entrenador conteste para saber que hacer."
- "Sube una foto de tu comida y recibe analisis nutricional al instante."
- "Tu entrenador, pero con superpoderes."

### Manejo de Objeciones

| Objecion | Respuesta |
|----------|-----------|
| "Mis clientes no van a usar otra app" | No es otra app — es un link que abre directo sin descargar nada. Y lo que ven es TU servicio con tu nombre, no una app generica. |
| "Ya tengo mi sistema con WhatsApp" | WhatsApp funciona para comunicarte, pero ¿tus clientes pueden ver su rutina con GIFs, registrar comidas con IA, y ver sus pagos en un solo lugar? Con Mi Rutina sumas eso a lo que ya haces. |
| "¿De verdad funciona sin estar presencial?" | Cada ejercicio tiene un GIF mostrando la tecnica exacta. Si aun asi hay dudas, el asistente de IA conoce tu rutina y te guia. Es como tener a tu entrenador al lado, pero en el bolsillo. |
| "¿No es muy caro?" | El entrenamiento virtual ya cuesta menos de la mitad que el presencial. La app es un costo minimo para el entrenador ($24,900/atleta/mes) que se traduce en un servicio premium que retiene clientes. |
| "¿Voy a poder entrenar bien sin experiencia?" | La app te muestra paso a paso cada ejercicio con video, tiene IA que responde tus dudas en tiempo real, y tu entrenador recibe notificacion de todo lo que haces. Estas mas acompanado que en muchos gimnasios presenciales. |

### Mensajes de Soporte

- "No solo cambias de app. Cambias de nivel."
- "Centraliza. Automatiza. Escala."
- "Se acabo el 'como se hace esto?' — GIFs integrados en cada ejercicio"
- "IA que trabaja para ti — analisis nutricional desde una simple foto"
- "Profesionaliza tu servicio hoy"

### Atributos de Tono

| Atributo | Definicion | Ejemplo |
|----------|-----------|---------|
| Directo | Sin rodeos, va al grano | "Todo tu ecosistema en un solo lugar" |
| Profesional | Transmite confianza y competencia | Datos precisos, metricas claras |
| Motivacional | Impulsa la accion sin ser agresivo | "Entra al futuro del entrenamiento online" |
| Cercano | Habla de tu a tu, sin ser informal | "Tu cliente ve su progreso real" |

### Lenguaje a Evitar

- No usar "la mejor app" o superlativos vacios
- No usar jerga tecnica con entrenadores (evitar "PWA", "KV", "API")
- No prometer resultados fisicos directos (la app es la herramienta, no el entrenador)
- No posicionarse en contra de WhatsApp de forma agresiva — posicionarse como la evolucion natural
- No decir "reemplaza a tu entrenador" — siempre posicionar como un anadido al servicio profesional

---

## 5. Identidad Visual y Principios de Diseno

### Filosofia Visual

Mi Rutina sigue un enfoque **moderno, minimalista y no abrumador**. A diferencia de muchas apps de fitness que saturan la pantalla con mil opciones, metricas y botones, Mi Rutina prioriza la claridad: que el atleta abra la app y sepa exactamente que tiene que hacer hoy sin pensar.

### Principios de Diseno

1. **Menos es mas** — Cada pantalla tiene un proposito claro. Si algo no es necesario en ese momento, no se muestra.
2. **Visual antes que textual** — GIFs de tecnica en vez de descripciones largas. Tarjetas de color en vez de tablas. Iconos claros en vez de menus profundos.
3. **Rapido de leer** — Tipografia grande y legible. Jerarquia visual clara. El atleta en el gimnasio necesita ver rapido, no leer parrafos.
4. **No abruma** — El error de muchas apps de fitness es mostrar todo a la vez. Mi Rutina muestra solo lo relevante para el momento.
5. **Profesional y limpio** — La app representa al entrenador. Tiene que verse premium sin ser recargada.

### Paleta de Color

- **Fondos oscuros** (#1a1a2e, #16213e) — Elegancia, modernidad, reduccion de fatiga visual
- **Acentos verdes** (#00d4aa, #10b981) — Exito, progreso, salud
- **Acentos azules/violeta** (#6366f1, #818cf8) — Confianza, tecnologia, IA
- **Indicadores de estado** — Verde (completado/al dia), Amarillo (pendiente), Rojo (vencido)
- **Texto claro sobre oscuro** — Alto contraste para legibilidad en el gimnasio

### Estilo de Interfaz

- Tarjetas con bordes redondeados y sombras sutiles
- Gradientes suaves en botones y headers
- Animaciones minimas pero fluidas (transiciones entre pantallas, timer circular)
- Iconos emoji nativos para familiaridad inmediata (💪🍽️💳✏️)
- Sin sobrecarga de informacion — navegacion por tabs con maximo 4-5 opciones

---

## 6. Plataforma y Herramientas

### Portal del Atleta

#### Perfil y Metricas
- Visualizacion de composicion corporal: peso, porcentaje de grasa, masa muscular, IMC, BMR
- Tarjetas de progreso con comparativas temporales (ej: Julio a Enero)
- Medidas corporales detalladas: brazo, pecho/espalda, muslo, edad metabolica

#### Rutina Interactiva
- **5 sesiones semanales** con asignacion personalizada por dia
- **Planificacion semanal unica** — el entrenador maneja una sola semana activa y la ajusta cada semana segun el progreso del atleta (ej: cada sabado/domingo actualiza pesos y ejercicios para la siguiente semana)
- **Estructura por sesion:**
  - Calentamiento dinamico con ejercicios vinculados a GIFs
  - 3 circuitos con series configurables y tiempos de descanso
  - Cardio final opcional
- **Tarjetas de ejercicio** con:
  - Nombre del ejercicio y grupo muscular
  - Peso objetivo y repeticiones por serie
  - Boton de tecnica con notas del entrenador
  - GIF demostrativo de cada ejercicio (base de datos de 120+ ejercicios)
- **Tipos de series avanzados:**
  - Normal (peso x reps estandar)
  - Drop Set (reduccion progresiva de peso en escalones configurables)
  - Piramidal (progresion ascendente/descendente por escalon)
- **Timer de descanso inteligente** con animacion circular, boton +30s, y alerta sonora
- **Flujo de completar sesion:** overlay de confirmacion con notas opcionales para el entrenador, envio automatico por email
- **Auto-avance de sesiones:** al completar una, se carga la siguiente automaticamente

#### Registro Nutricional
- **5 slots de comida diarios:** Desayuno, Medias Nueves, Almuerzo, Onces, Cena
- **Subida de fotos** de cada comida con almacenamiento en la nube (Cloudflare R2)
- **Analisis nutricional por IA (Claude):** la foto se analiza automaticamente y devuelve:
  - Calorias estimadas (kcal)
  - Proteina (g)
  - Carbohidratos (g)
  - Grasas (g)
  - Evaluacion detallada de la comida segun el objetivo del atleta
- **Reporte diario consolidado** — todas las comidas del dia se envian al entrenador en un solo email a las 10 PM (Colombia), en vez de un email por cada comida. Incluye fotos, descripciones, analisis de IA y totales de macros del dia
- **Historial de comidas** con fotos y analisis guardados por fecha
- **Estado de envio** por slot: el atleta sabe que comidas ya registro ese dia

#### Pagos
- Estado de pago mensual: "Al dia" o "Pendiente"
- Monto, fecha limite, y link de pago configurado por el entrenador
- Boton "Pagar ahora" que redirige al medio de pago

#### Asistente de IA
- Chat con Claude integrado en la pantalla de rutina
- Contexto completo: conoce la rutina del dia, el perfil del atleta, y su historial de comidas
- Responde preguntas sobre tecnica, pesos, descansos, nutricion
- Puede ayudar con dolores o molestias (ej: "me duele la muneca, ¿que ejercicio puedo sustituir?")
- Disponible 24/7 sin costo adicional para el entrenador

#### Resumen Semanal
- Vista consolidada de la semana (lunes a sabado) con navegacion entre semanas
- **Totales de macros semanales:** calorias, proteina, carbohidratos, grasas acumulados
- **Sesiones completadas** de la semana con notas del atleta
- **Comidas por dia** con tarjetas colapsables, fotos y analisis nutricional
- **Email semanal automatico** — cada sabado a las 10 AM (Colombia) se envia al entrenador un resumen completo de la semana de cada atleta con sesiones, comidas y macros

#### Navegacion
- Barra inferior con 5 tabs: Perfil, Rutina, Comidas, Resumen, Pagos
- Transiciones suaves entre pantallas
- Indicador visual de tab activo

---

### Portal del Entrenador

#### Gestion de Clientes
- Lista de clientes con nombre y plan asignado
- Acceso individual al dashboard de cada cliente
- Datos completamente aislados entre clientes

#### Editor de Rutinas
- **Selector de dia** para editar cada sesion por separado
- **Constructor de circuitos** visual con:
  - Ejercicios arrastrables con nombre, musculo, peso, reps
  - Selector de tipo de serie (Normal / Drop Set / Piramidal)
  - Configuracion de escalones para drop sets y piramidales
- **Selector de ejercicios** con base de datos de 120+ ejercicios:
  - Busqueda por nombre o grupo muscular
  - Preview del GIF de cada ejercicio
  - 12 grupos musculares: Pecho, Espalda, Biceps, Triceps, Hombros, Cuadriceps, Isquiotibiales, Gluteo, Pantorrilla, Trapecio, Abdomen
- **Notas tecnicas** personalizadas por ejercicio
- **Guardar y publicar** rutina en un click — se sincroniza instantaneamente con el atleta

#### Seguimiento de Comidas
- Vista por dia de todas las comidas registradas del atleta
- Fotos, descripciones y analisis nutricional de IA
- Historial completo organizado cronologicamente
- Recibe reporte diario consolidado a las 10 PM con todas las comidas del dia

#### Resumen Semanal (Entrenador)
- Misma vista de resumen semanal que el atleta, accesible desde el tab "Resumen" en el panel de cada cliente
- Navegacion entre semanas para revisar historico
- Totales de macros, sesiones completadas y comidas por dia
- Email semanal automatico cada sabado 10 AM con el resumen de cada atleta

#### Control de Pagos
- Configuracion del monto mensual, fecha limite y link de pago por cliente
- Toggle para marcar como pagado o pendiente
- Estado visible en tiempo real

#### Seccion de Pago de Plataforma
- Monto mensual de la plataforma por atleta
- Fecha limite de pago
- Boton para realizar pago

#### Chat de Soporte
- Boton de soporte en el header de cada cliente
- Chat directo con el administrador de la plataforma
- Contexto automatico: cada mensaje incluye el nombre del atleta que se esta gestionando
- Historial persistente de conversaciones

#### Navegacion del Entrenador
- Barra inferior con 6 tabs: Clientes, Rutinas, Comidas, Resumen, Pagos, Editar
- Header con nombre del cliente seleccionado

---

### Panel de Administracion

- Acceso oculto desde la pantalla de seleccion de rol (protegido con contrasena)
- Lista de todas las conversaciones de soporte activas
- Vista previa del ultimo mensaje y conteo de mensajes
- Chat de respuesta directa a cada entrenador
- Notificacion por email cuando un entrenador escribe

---

### Integraciones de IA

| Integracion | Modelo | Funcion |
|-------------|--------|---------|
| Chat del Atleta | Claude Haiku 4.5 | Asistente de entrenamiento contextualizado con rutina y perfil del atleta |
| Analisis Nutricional | Claude Haiku 4.5 (Vision) | Analiza fotos de comidas y devuelve macronutrientes estimados |

---

### Arquitectura Tecnica

| Componente | Tecnologia | Funcion |
|------------|-----------|---------|
| Frontend | HTML/CSS/JS (single-file PWA) | Toda la interfaz en un solo archivo, funciona offline |
| Backend | Cloudflare Worker | API serverless que maneja todas las acciones |
| Base de Datos | Cloudflare KV | Almacenamiento key-value para rutinas, comidas, pagos, completaciones, chats |
| Almacenamiento de Fotos | Cloudflare R2 | CDN para fotos de comidas con URLs publicas |
| Notificaciones | Resend (Email API) | Emails automaticos: reporte diario de comidas (10 PM), resumen semanal (sabados 10 AM), notificacion de sesion completada |
| Cron Triggers | Cloudflare Workers Cron | Dos triggers programados: diario (comidas) y semanal (resumen) |
| IA | Claude API (Anthropic) | Chat contextualizado + analisis de imagenes de comida |
| Hosting | GitHub Pages | Hosting gratuito del frontend con deploy automatico |
| Service Worker | Cache-first + Network-first | Soporte offline, actualizaciones instantaneas |

---

## 7. Estrategia de Canales

### Canales Prioritarios

| Canal | Rol | Por que |
|-------|-----|---------|
| **TikTok** | Adquisicion de entrenadores | El publico #1. Cantidad enorme de entrenadores haciendo contenido: rutinas, lives, llamadas a entrenar. Es donde estan los entrenadores virtuales. |
| **Instagram** | Marca + comunidad | Contenido visual de la app, testimonios, reels cortos. Complementa TikTok con audiencia ligeramente mas profesional. |
| **Referidos (boca a boca)** | Crecimiento organico | Un entrenador que usa la app y se ve profesional genera curiosidad en otros entrenadores. |

### Canales Depriorizados

- **LinkedIn** — No es donde estan los entrenadores personales. No es el target.
- **Facebook Ads** — Posible en el futuro pero no es prioridad inicial.
- **Google Ads** — No hay busqueda activa del problema todavia ("app para entrenadores virtuales" no tiene volumen).

### Estrategia de Lanzamiento

1. **Proyecto piloto** — Primer entrenador real (el entrenador personal del creador) usa la app con sus clientes virtuales para validar, iterar y alimentar mejoras con feedback real.
2. **Contenido organico** — Documentar el proceso en TikTok/Instagram: "Construi una app para mi entrenador" como narrativa autentica.
3. **Expansion por red** — Desde el entrenador piloto, llegar a su red de entrenadores. El producto se vende solo cuando lo ven funcionando.

### Funnel de Conversion

```
Entrenador ve contenido en TikTok/Instagram
    ↓
Visita el perfil / link en bio
    ↓
Ve demo de la app (video o link directo)
    ↓
Contacto directo (DM o WhatsApp)
    ↓
Onboarding personalizado (se carga su primer cliente)
    ↓
Entrenador usa la app con sus atletas
    ↓
Atletas ven la app → preguntan → referidos
```

---

## 8. Propuesta de Valor y Diferenciadores

### Modelo de Negocio

- **El atleta no paga por la app.** No sabe cuanto vale ni que existe un costo de plataforma. La app es parte del servicio de su entrenador.
- **El entrenador paga $24,900 COP/atleta/mes.** Es el costo de profesionalizar su servicio. Con 10 clientes virtuales que le pagan ~$250,000-$300,000/mes cada uno, el costo de la plataforma es minimo frente a sus ingresos.
- **No hay version gratuita limitada ni features bloqueados.** Cada atleta activo tiene acceso a todo. La barrera es el entrenador, no el atleta.

### Comparativa: Metodo Tradicional vs Mi Rutina App

| Aspecto | Metodo Tradicional | Mi Rutina App |
|---------|-------------------|---------------|
| Entrega de rutinas | PDFs estaticos y confusos | App interactiva paso a paso |
| Correccion de tecnica | Textos largos e ignorados | GIFs integrados en cada ejercicio |
| Registro nutricional | Fotos sueltas por chat o apps pagas con registro manual | Analisis automatico por IA desde una foto |
| Comunicacion | Mezclada con vida personal en WhatsApp | Notas estructuradas por sesion |
| Control de pagos | "Ya me pagaste?" por mensaje | Panel con estados y links de pago |
| Seguimiento de progreso | Hojas de calculo manuales | Metricas visuales automaticas |
| Soporte al entrenador | Inexistente | Chat integrado con admin |
| Escalabilidad | Cada cliente es mas carga | Misma calidad con 5 o 50 clientes |
| Preguntas de tecnica | Esperar a que el entrenador conteste | IA + GIF disponibles al instante |

### 10 Diferenciadores Clave

1. **Base de datos de 120+ ejercicios con GIFs** — Demostraciones visuales de tecnica directamente en la rutina del atleta
2. **Analisis nutricional por IA** — El atleta sube una foto de su comida y recibe estimacion de macros al instante (sin registro manual, sin version paga)
3. **Tipos de series avanzados** — Drop Sets y Piramidales configurables, no solo series normales
4. **Planificacion semanal flexible** — Una semana activa que el entrenador ajusta semanalmente segun el progreso del atleta, garantizando sobrecarga progresiva real y personalizada
5. **Reportes automaticos inteligentes** — Reporte diario consolidado de comidas (10 PM) y resumen semanal completo cada sabado (10 AM) con sesiones, comidas y macros acumulados
6. **PWA sin descarga** — Funciona como app nativa desde un link. Sin App Store, sin Google Play, cero friccion
7. **Asistente de IA 24/7** — Chat integrado que conoce la rutina del atleta y responde preguntas de tecnica, pesos, nutricion, e incluso dolores o molestias
8. **Timer de descanso inteligente** — Temporizador integrado con tiempos por circuito y opcion de extender
9. **Chat de soporte integrado** — Comunicacion directa entrenador-admin con contexto del atleta
10. **Datos centralizados y persistentes** — Todo en la nube: rutinas, comidas, pagos, completaciones, fotos. Sin perder informacion

---

## 9. Vision y Metricas de Exito

### Vision

Convertirse en la plataforma estandar para entrenadores virtuales en Latinoamerica. Que cada entrenador independiente tenga acceso a herramientas de nivel empresa para entregar un servicio que sus clientes amen y renueven mes a mes.

### Etapa Actual: Proyecto Piloto

- **Fase:** Validacion con primer entrenador real
- **Objetivo:** Que un entrenador use la app con sus clientes virtuales durante al menos 3 meses, iterar con feedback real, y demostrar retencion de atletas.
- **Exito del piloto:** El entrenador no quiere volver a WhatsApp.

### Metrica Norte (North Star)

**Retencion mensual de afiliados del entrenador.** Si los clientes del entrenador se quedan mes a mes, significa que la plataforma esta entregando valor real.

### KPIs de Soporte

| KPI | Descripcion | Cadencia |
|-----|------------|----------|
| Rutinas completadas / semana | Mide engagement del atleta | Semanal |
| Comidas registradas / dia | Mide adopcion del registro nutricional | Diaria |
| Tiempo de respuesta admin (soporte) | Mide calidad del soporte | Por ticket |
| Entrenadores activos | Mide crecimiento de la base | Mensual |
| Atletas por entrenador (promedio) | Mide escalabilidad real | Mensual |

### Leading Indicators (Senales Tempranas)

- Entrenador que edita rutinas en la primera semana → alta probabilidad de quedarse
- Atleta que completa 3+ sesiones en la primera semana → alta retencion
- Atleta que usa el registro de comidas → engagement profundo
- Entrenador que agrega un segundo cliente → validacion del producto

### Lo que NO Medimos (para mantener foco)

- Metricas de vanidad (descargas, visitas)
- Tiempo en la app (no buscamos adiccion, buscamos eficiencia)
- Comparativas entre atletas (cada proceso es individual)

---

## Resumen Ejecutivo

**Mi Rutina App** es un anadido profesional al servicio del entrenador virtual, impulsado por IA. No reemplaza al entrenador — lo potencia. El atleta siempre sabe que hay un profesional real detras.

Nace de una experiencia real: la frustracion de entrenar virtualmente con herramientas que no estan disenadas para eso. La informacion se pierde entre WhatsApp, PDFs, apps de comida pagas, y hojas de calculo. Mi Rutina centraliza todo en un solo lugar.

Su diferenciador principal es que **no es una app para el usuario final** — es una herramienta para **entrenadores** que transforma la experiencia de sus afiliados, les permite escalar sin perder calidad, y les da el control total de su negocio.

**Modelo:** El atleta no paga por la app. El entrenador paga $24,900 COP por atleta al mes.

**Pilares:** Cero Friccion. Ecosistema Cerrado. Control Total.

**Etapa:** Proyecto piloto con primer entrenador real. Canales: TikTok e Instagram.

---

*Documento vivo — se actualiza conforme evoluciona la plataforma.*
*Ultima actualizacion: Abril 2026*
