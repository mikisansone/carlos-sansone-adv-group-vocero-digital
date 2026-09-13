# ADV Group --- Vocero Digital con IA

**Ejercicio Práctico: Creación de Voceros Digitales Personalizados**\
Proyecto académico --- Curso Creación de contenido con AI / Coderhouse

## 1. Concepto

El proyecto traslada al lenguaje audiovisual el sistema visual
desarrollado previamente para ADV Group bajo el concepto **"Conectar los
puntos"**.

La intención fue construir una pieza en la que voz, música, personaje y
movimiento no funcionaran como recursos independientes, sino como partes
de una misma identidad: comprender información, analizar relaciones y
encontrar una dirección.

El personaje utilizado es **Martín**, definido en el Módulo 3 como
representación de un estratega contemporáneo: profesional, cercano,
observador y seguro. Se mantuvieron su apariencia, vestuario y universo
visual para asegurar continuidad entre la identidad visual y la
audiovisual.

## 2. Workflow

**Imagen del personaje → Voz IA → Música IA → Photo Avatar / Lip Sync →
Postproducción → Video final**

Herramientas utilizadas:

-   **ChatGPT**: dirección estratégica, desarrollo del guion y
    generación de la imagen maestra del avatar.
-   **ElevenLabs**: voz sintética de stock "Eduardo".
-   **Gemini**: apoyo exploratorio para evaluar alternativas de prosodia
    y configuración de voz.
-   **Suno**: generación de identidad musical.
-   **HeyGen**: Photo Avatar, animación y sincronización labial mediante
    Avatar IV.
-   **CapCut**: integración final, mezcla musical, recorte, subtítulos y
    exportación.

## 3. Identidad sonora --- ElevenLabs

### Dirección de voz

Se buscó una voz masculina adulta, cálida, segura, reflexiva y
profesional, con registro argentino/rioplatense neutro. La idea rectora
fue:

> **"Un estratega explicando una idea importante, no un locutor
> vendiendo una agencia."**

Se priorizaron ritmo controlado, pausas breves, expresividad moderada y
un cierre seguro sin tono publicitario.

### Guion

> Una estrategia no empieza con una respuesta.\
> Empieza... cuando somos capaces de mirar más allá de lo evidente.
>
> En ADV Group... creemos que pensar estratégicamente... es conectar lo
> que otros ven por separado:\
> el negocio... las personas... el contexto... los problemas... y las
> oportunidades.
>
> Primero comprendemos.\
> Después analizamos.\
> Y recién entonces... definimos una dirección.
>
> Porque comunicar no es sumar piezas.\
> Es tomar decisiones con sentido...
>
> Cuando los puntos se conectan... la complejidad se ordena... las
> oportunidades aparecen... y la creatividad encuentra un propósito.
>
> ADV Group.\
> Estrategia antes que creatividad.

**Duración del audio final:** 41,27 segundos.

### Iteración y pronunciación de marca

Durante las pruebas se detectó una pronunciación inconsistente de **ADV
Group**. Se ensayaron distintas formas de guiarla mediante separación de
letras, puntuación y escritura fonética/castellanizada ("A-De-Ve
Group"). Esto mejoró la lectura, aunque la primera mención conserva una
leve inconsistencia.

La configuración disponible en la versión utilizada no permitió alcanzar
un control fonético más preciso. Se registra como oportunidad de mejora
para futuras versiones.

La versión final fue seleccionada por transmitir mejor criterio,
experiencia, cercanía y reflexión.

## 4. Identidad musical --- Suno

La música debía traducir el concepto **"Conectar los puntos"**:
elementos inicialmente separados que progresivamente se relacionan hasta
construir una estructura y una dirección.

### Prompt final

> Minimal contemporary instrumental for a strategy and creative
> consultancy brand. Precise, intelligent and understated. Built around
> a subtle rhythmic pulse, small percussive details, restrained
> electronic textures and short repeating tonal motifs that gradually
> interlock, creating the feeling of separate elements connecting into a
> clear system. Modern editorial design aesthetic translated into sound.
> Confident, sophisticated, human and focused, with forward movement but
> no drama. Clean arrangement, controlled dynamics and generous space
> for a calm male voice-over. Around 90 BPM. Subtle evolution from
> curiosity to clarity and resolution. The final section should feel
> confident and resolved, leaving space for a spoken brand signature.
> Instrumental only. No vocals. No cinematic storytelling. No emotional
> lead melody.

**Exclusiones:** cinematic, epic, emotional soundtrack, ambient
soundscape, corporate motivational, inspirational advertising, piano
ballad, orchestral, trailer, dramatic build, sentimental, dreamy,
ethereal, synthwave, EDM, futuristic technology, heavy bass, aggressive
drums, vocals, choir.

### Exploración

Se probaron distintas alternativas:

-   **Smoke and Space**: demasiado atmosférica.
-   **Threaded Compass**: interesante, pero demasiado
    narrativa/cinematográfica.
-   **Smoke and Silence**: sofisticada, aunque todavía contemplativa.
-   **Forward Motion**: seleccionada por su precisión, progresión y
    sensación de construcción/dirección.

### Configuración documentada

-   Modelo: **v6-mini**
-   Modo: **Advanced**
-   Duration: **Auto**
-   Max Mode: **Off**
-   Weirdness: **50 %**
-   Style Influence: **50 %**
-   Variety: **High**
-   Personalize / My Taste: **Off**
-   Resultado seleccionado: **Forward Motion**
-   Instrumental, sin voces

## 5. Avatar digital --- HeyGen

Se utilizó la imagen consistente de Martín desarrollada a partir del
Manual de Identidad Visual del Módulo 3.

### Imagen maestra

-   Formato: **9:16**
-   Plano medio
-   Mirada a cámara
-   Expresión calma, segura y cercana
-   Vestuario smart-casual: camisa clara + saco grafito
-   Entorno editorial contemporáneo coherente con ADV Group
-   Iluminación natural y fondo limpio

### Integración

La imagen fue cargada como **Photo Avatar** en HeyGen. Para conservar la
identidad sonora, se subió directamente el MP3 final generado en
ElevenLabs en lugar de utilizar una voz de HeyGen.

Configuración utilizada:

-   Motion Engine: **Avatar IV**
-   Layout: **Original**
-   Zoom: **100 %**
-   Audio: archivo propio de ElevenLabs
-   Duración aproximada en HeyGen: **41,3 s**
-   Formato: **9:16**

La función **Custom Motion** aparecía disponible en la interfaz, pero no
estaba habilitada en la versión utilizada. Por ese motivo se trabajó con
el movimiento automático de Avatar IV. El resultado mantiene
sincronización labial natural, aunque la gestualidad de manos es algo
más activa que la dirección ideal definida para Martín.

La marca de agua de HeyGen corresponde al plan gratuito y es válida
según las condiciones del ejercicio.

## 6. Postproducción --- CapCut

La integración final se realizó en CapCut con tres componentes
principales:

1.  Video de Martín generado en HeyGen.
2.  Audio maestro de ElevenLabs.
3.  Música **Forward Motion** generada en Suno.

### Mezcla

-   Voz: master principal.
-   Música: **−34,1 dB**, ajustada perceptivamente para no competir con
    la locución.
-   Fade in musical: **1 s**.
-   Fade out musical: **2 s**.

El valor musical se definió por escucha y relación con la voz,
priorizando en todo momento la inteligibilidad del vocero.

### Subtítulos

Se generó una primera transcripción automática en CapCut y luego se
realizó control humano:

-   corrección de puntuación;
-   corrección de mayúsculas e inicios de oración;
-   ajuste de segmentación;
-   escritura gráfica correcta de **ADV Group**;
-   ubicación en zona segura para formato vertical;
-   estilo limpio y de alta legibilidad.

## 7. Resultado final

**Archivo:** `output/carlos-sansone-grupo-adv-vocero-digital-final.mp4`

Ficha técnica del master exportado:

-   Formato: **9:16**
-   Resolución: **1080 × 1920**
-   Frame rate: **30 fps**
-   Codec de video: **H.264**
-   Audio: **AAC estéreo, 44,1 kHz**
-   Duración final: **42,45 s**

El resultado integra voz IA, música IA, personaje consistente,
sincronización labial, identidad visual y adaptación a redes sociales.

## 8. Evaluación y aprendizajes

El workflow permitió validar que la coherencia audiovisual no depende de
una única herramienta, sino de la relación entre decisiones tomadas en
cada etapa.

**Fortalezas del resultado:**

-   continuidad visual de Martín respecto del Módulo 3;
-   voz sintética clara y con intención estratégica;
-   música subordinada a la voz y coherente con el concepto;
-   sincronización labial natural;
-   formato vertical pensado para redes;
-   revisión humana de transcripción y resultado final.

**Oportunidades de mejora:**

-   alcanzar un control fonético todavía más preciso de "ADV Group";
-   reducir la frecuencia de gestos manuales mediante controles
    personalizados de movimiento cuando estén disponibles;
-   exportar directamente desde HeyGen en una versión que permita mayor
    control del archivo fuente.

## 9. Estructura del repositorio

``` text
carlos-sansone-grupo-adv-vocero-digital/
├── README.md
├── assets/
│   ├── martin-avatar-master-9x16.png
│   ├── voz-elevenlabs-eduardo.mp3
│   └── forward-motion-suno.mp3
├── output/
│   └── carlos-sansone-grupo-adv-vocero-digital-final.mp4
└── documentation/
    ├── 01-elevenlabs-config.png
    ├── 02-heygen-avatar.png
    ├── 03-heygen-audio-avatar-iv.png
    ├── 04-capcut-three-tracks.png
    ├── 05-capcut-mix-settings.png
    └── 06-capcut-captions.png
```

## 10. Nota académica

Este repositorio corresponde a un **ejercicio académico** de Coderhouse.
Los activos generados con planes gratuitos se utilizan únicamente en
este contexto. La música generada con Suno en plan gratuito se incorpora
con finalidad académica/no comercial y con atribución a **Suno**.

------------------------------------------------------------------------

**ADV Group**\
**Estrategia antes que creatividad.**
