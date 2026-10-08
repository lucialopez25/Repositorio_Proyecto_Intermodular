# Repositorio_Proyecto_Intermodular

## 1. INTRODUCCIÓN

### 1.1. Contexto del proyecto

### **Contexto del Proyecto**

El proyecto CoSwipe se enmarca en el sector productivo de las Tecnologías de la Información y la Comunicación (TIC), concretamente en la industria del Desarrollo de Software y la Distribución Digital de Contenidos de Entretenimiento (Media & Gaming).

Para comprender el entorno donde opera el proyecto, es necesario clasificar las empresas del sector según sus características organizativas y el tipo de producto o servicio que ofrecen:

**Clasificación de Empresas del Sector**

- Plataformas de Streaming Audiovisual (SVOD - Subscription Video on Demand):

> Ejemplos: Netflix, Amazon Prime Video, Disney+, Max (HBO).
> 
> Tipo de producto/servicio: Suscripción periódica para acceso ilimitado a catálogos cerrados de películas, series y documentales bajo demanda.
> 
> Características organizativas: Grandes multinacionales tecnológicas con estructuras jerárquicas y divisionales por región geográfica. Operan con modelos intensivos en capital para producción de contenido original y mantenimiento de infraestructura en la nube (CDN).

- Plataformas de Distribución Digital de Videojuegos:

> Ejemplos: Valve (Steam), Epic Games Store, Microsoft (Xbox Game Pass), Sony (PlayStation Store).
> 
> Tipo de producto/servicio: Venta directa de licencias digitales de videojuegos, servicios de juego por suscripción y juego en la nube (Cloud Gaming).
> 
> Características organizativas: Empresas del sector tecnológico/videojuegos con estructuras matriciales altamente especializadas en desarrollo de software, gestión de comunidades y licencias con desarrolladores independientes (indies) y publishers AAA.

- Plataformas de Guía, Agregación e Intermediación de Contenidos (Discovery & Utility Apps):

> Ejemplos: JustWatch, Reelgood, TasteMates.
> 
> Tipo de producto/servicio: Aplicaciones B2C utilitarias que agregan metadatos de múltiples plataformas para ofrecer motores de búsqueda unificados, guías de disponibilidad regional y sistemas de recomendación.
> 
> Características organizativas: Startups o PyMEs tecnológicas con estructuras organizativas ágiles (Flat / Lean Organization), enfocadas en el desarrollo rápido de producto, analítica de datos (Big Data) y monetización mediante afiliación o publicidad B2B.

**Estructura Organizativa y Funciones Departamentales de una Empresa Tipo del Sector**

Una empresa representativa del sector de desarrollo de herramientas de agregación y software multimedia presenta la siguiente estructura funcional:

- Departamento de Producto (UI/UX & Product Management):

> Funciones: Definir la visión del producto, diseñar los flujos de experiencia de usuario (UX), elaborar prototipos de interfaz (UI), analizar métricas de retención de usuarios y priorizar el mapa de características (roadmap).

- Departamento de Ingeniería y Desarrollo de Software:

> Funciones: Construir la arquitectura de software (frontend móvil y backend), implementar APIs de integración con bases de datos de terceros (TMDB, IGDB), gestionar la infraestructura de servidores síncronos en la nube y asegurar la escalabilidad del sistema.

- Departamento de Marketing y Analítica de Datos (Growth & BI):

> Funciones: Diseñar estrategias de adquisición y retención de usuarios, analizar patrones de consumo mediante inteligencia de negocio (Business Intelligence) y gestionar la presencia en tiendas de aplicaciones (ASO - App Store Optimization).

- Departamento de Desarrollo de Negocio y Asuntos Legales:

> Funciones: Negociar acuerdos de afiliación con las plataformas de streaming, asegurar el cumplimiento normativo de protección de datos (RGPD) y gestionar licencias de propiedad intelectual relativas al uso de marcas y portadas.

**Análisis de Contexto Multinivel (Macro-Meso-Micro)**

Para la fundamentación teórica del proyecto, aplicamos un Análisis de Contexto Multinivel (Macro-Meso-Micro) basado en la Teoría de los Sistemas Ecológicos (Bronfenbrenner, 1979). Esta metodología nos permite encuadrar el nacimiento de CoSwipe a través de tres niveles interconectados, desde las macrotendencias globales de consumo e interfaz hasta el escenario de interacción técnica síncrona.

1. MACRO (Sistemas Globales): Transición al Streaming y UI/UX
2. MESO (Entorno Social): Nuevos Hábitos de Convivencia
3. MICRO (Interacción Técnica): Inmediadez y Sincronización
4. PUNTO DE CONVERGENCIA: Proyecto CoSwipe

**1. Nivel Macro (Macrosistema): Transformación de la Industria Digital y de las Interfaces**
En la capa más global e institucional, la última década ha estado definida por dos grandes transformaciones tecnológicas:

La consolidación de los modelos de suscripción masiva: La industria del entretenimiento ha migrado hacia catálogos unificados digitalmente. Servicios audiovisuales como Netflix, Disney+, Prime Video o HBO Max, junto con plataformas de distribución e integración de videojuegos como Steam, Xbox Game Pass y PlayStation Plus, han digitalizado el consumo de contenidos, centralizando miles de títulos en un único dispositivo.

La estandarización de las interfaces gestuales (Swipe UI): En el ámbito del diseño de interacción, la mecánica de tarjetas deslizables (swiping) pasó de ser un recurso innovador en aplicaciones de citas (Tinder, 2012) a un patrón de interacción universal consolidado por plataformas de consumo rápido como TikTok. Este paradigma ha redefinido las expectativas visuales y gestuales de los usuarios, priorizando interacciones de bajo esfuerzo cognitivo y respuesta inmediata.

**2. Nivel Meso (Mesosistema): Evolución de los Entornos de Socialización y Consumo Compartido**
Al descender al nivel de los grupos de referencia y entornos sociales comunitarios (frecuentados por usuarios de la Generación Z y Millennials), se observan dos espacios dominantes de relación:

Espacios de convivencia presencial: Reuniones en el hogar entre parejas o compañeros de piso compartido, donde la interacción con los contenidos se ejecuta de forma colectiva sobre la pantalla principal del hogar (Smart TV o consola).

Entornos de convivencia digital: Servidores y canales de voz virtuales como Discord, que operan como el punto de reunión habitual para comunidades de amigos que buscan consumir partidas de videojuegos o sesiones de cine simultáneas a distancia.

En ambos entornos, la interacción socio-técnica se caracteriza por ser multi-dispositivo y dinámica: los participantes interactúan individualmente desde sus terminales móviles mientras forman parte de la conversación grupal.

**3. Nivel Micro (Microsistema): Arquitectura de Interacción Síncrona sin Fricción**
En la escala técnica e individual, el diseño de aplicaciones móviles modernas se orienta hacia la eliminación de barreras de uso y la sincronización inmediata:

Sincronización de estado en tiempo real: El avance en las arquitecturas cliente-servidor y la gestión de eventos síncronos permite conectar múltiples dispositivos móviles dentro de una misma sesión con latencias inapreciables.

Diseño sin fricción de entrada (Zero-Friction UI): La tendencia en herramientas utilitarias efímeras prioriza la reducción de pasos previos. El acceso mediante códigos PIN, códigos QR o enlaces directos evita los flujos tradicionales de onboarding y creación de perfiles con correo electrónico, ajustándose a un uso inmediato.

**4. Punto de Convergencia: El Nacimiento de CoSwipe**
El proyecto CoSwipe se sitúa exactamente en la convergencia de estos tres niveles: adopta la madurez de los catálogos multimedia actuales (nivel Macro), aprovecha la familiaridad del patrón gestual swipe y la tecnología de sincronización en tiempo real (nivel Micro) para responder a las necesidades de interacción de los grupos sociales en entornos presenciales y virtuales (nivel Meso).


### 1.2. Problema o necesidad detectada
En los encuentros de ocio compartido, ya sea en una reunión presencial en el salón o en un canal de voz de Discord, la tarea de elegir qué contenido ver o a qué videojuego jugar suele convertirse en un proceso lento de navegación por múltiples catálogos que termina por agotar el tiempo libre del grupo.

**Definición de la parálisis por elección**

Este bloqueo responde a un fenómeno conocido en la psicología cognitiva como parálisis por elección (choice overload), el cual ocurre cuando el volumen excesivo de opciones disponibles sobrepasa la capacidad de procesamiento de la mente humana. Lejos de aumentar la satisfacción o dar libertad al usuario, la sobreoferta produce una elevada carga cognitiva y una acusada fatiga de decisión. Ante cientos de títulos al alcance de un clic, las personas entran en un estado de cuestionamiento continuo por temor a tomar una decisión mediocre, lo que posterga la elección, genera dudas en el grupo y reduce significativamente el disfrute de la experiencia final.

**Métodos de investigación del problema y resultados**

Para comprobar si esta parálisis por elección afectaba de forma real y medible a nuestros usuarios potenciales, aplicamos la metodología de investigación cualitativa conocida como The Mom Test, desarrollada por Rob Fitzpatrick. La regla fundamental de este marco radica en no mencionar jamás la idea de la aplicación ni el producto propuesto, sino enfocar las preguntas exclusivamente en comportamientos pasados, hábitos reales y dificultades sufridas por los entrevistados. De esta manera, se evitan respuestas falsas dadas por compromiso, cortesía o promesas de uso futuro que rara vez se cumplen.

Llevamos a cabo 10 entrevistas individuales a personas de entre 18 y 31 años y los resultados confirmaron una presencia masiva del problema: un 90% de los participantes (9 de cada 10) afirmó haber sufrido discusiones o bloqueos al intentar ponerse de acuerdo, calculándose una pérdida media de 32,5 minutos por cada intento de elección antes de iniciar la actividad. Esta frustración quedó reflejada en testimonios directos de los usuarios, quienes señalaban que en Discord pueden pasar 20 minutos preguntando a qué jugar hasta que la gente termina saliéndose del canal de voz, que en los pisos compartidos siempre acaba decidiendo la misma persona, o que en pareja se tarda más tiempo viendo los tráilers que la propia película.

Para profundizar en el estado emocional y conductual de los usuarios durante estos momentos de bloqueo, sintetizamos la información obtenida mediante un Mapa de Empatía (Empathy Map), una herramienta propia del Design Thinking que organiza los hallazgos en torno a lo que el usuario piensa, siente, oye, ve, dice y hace.

A través de esta perspectiva, observamos que el usuario nota constantemente que está perdiendo su tiempo de ocio y siente pereza ante la idea de iniciar otra discusión, por lo que su único deseo es empezar a jugar o ver algo de inmediato. En su entorno escucha con frecuencia comentarios como "Entrad a voz y decidimos", "A mí me
