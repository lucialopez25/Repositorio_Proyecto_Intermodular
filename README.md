# Repositorio_Proyecto_Intermodular

## 1. INTRODUCCIÓN

### 1.1. Contexto del proyecto
Para la fundamentación teórica del proyecto, aplicamos un Análisis de Contexto Multinivel (Macro-Meso-Micro) basado en la Teoría de los Sistemas Ecológicos (Bronfenbrenner, 1979) y en los modelos de análisis sistémico sociotécnico. Esta metodología nos permite encuadrar el nacimiento de CoSwipe a través de tres niveles interconectados, desde las macrotendencias globales de consumo e interfaz hasta el escenario de interacción técnica síncrona.

1.MACRO (Sistemas Globales): Transición al Streaming y UI/UX

2.MESO (Entorno Social): Nuevos Hábitos de Convivencia

3.MICRO (Interacción Técnica): Inmediadez y Sincronización

4.PUNTO DE CONVERGENCIA: Proyecto CoSwipe



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
El problema principal que aborda este proyecto es la parálisis por elección o choice overload que ocurre en reuniones sociales presenciales, ya sean parejas, grupos de amigos o familiares al intentar seleccionar una película, serie o videojuego para disfrutar en conjunto.

La parálisis por elección (o choice overload) es la incapacidad para tomar una decisión cuando se presenta un exceso de opciones o información, provocando un bloqueo a las personas que lo sufren

Esta problemática se manifiesta a través de los siguientes factores:

* **Pérdida de tiempo:** Inversión de períodos prolongados (a menudo superiores a 30 minutos) navegando por los catálogos de distintas plataformas sin llegar a un acuerdo.
* **Fricción e indecisión grupal:** Conflictos o discusiones derivadas de opiniones encontradas, donde el debate abierto perjudica la experiencia de ocio.
* **Sesgo de visibilidad:** Tendencia a elegir siempre los mismos títulos o recomendaciones principales de las plataformas por fatiga de búsqueda, ignorando opciones del catálogo que complacerían a todos.
* **Ausencia de herramientas:** Inexistencia de una solución unificada que aplique esta dinámica tanto al sector cinematográfico como al de los videojuegos multijugador o cooperativos locales.
### 1.3. Propuesta de solución
La solución propuesta consiste en el diseño y desarrollo de una aplicación móvil multiplataforma que automatiza el proceso de toma de decisiones en grupo.  

El funcionamiento del sistema se basa en la creación de salas locales sincronizadas en tiempo real. El anfitrión crea una sala mediante un código único o código QR y configura unos filtros previos como el tipo de contenido y las plataformas activas. Los participantes se unen a la sala desde sus propios dispositivos móviles y comienzan a deslizar una lista limitada de opciones (Like hacia un lado, Pass hacia el otro).  

Mediante un algoritmo de coincidencia (match), en el momento en que se detecta unanimidad (o la mayor puntuación ponderada), la aplicación detiene el proceso y muestra de forma destacada la opción elegida, indicando además la plataforma o medio en el que está disponible para su consumo inmediato.  

### 1.4. Objetivos del proyecto

#### 1.4.1. Objetivo general

Diseñar, desarrollar e implementar una aplicación móvil multiplataforma que permita al grupo decidir rápidamente que películas, series ver o que videojuegos jugar. El método de decisión será una pantalla con tarjetas que se deslizan (swipe) y que se sincroniza en tiempo real entre varios dispositivos conectados a una sala virtual.

El objetivo es evitar la paralisis por elección grupal y que haya desacuerdos. Con esto se quiere reducir el tiempo que el grupo necesita para elegir. La aplicación dará un resultado en base a la tarjeta más elegida.

La app detectará cuando varias tarjetas obtengan el mismo número de me gusta y propondrá más tarjetas para desempatar al grupo. También mostrará en qué plataforma está disponible, para que el grupo pueda jugar o ver de inmediato.

#### 1.4.2. Objetivos específicos

Para determinar los objetivos específicos usamos  la metodología de desarrollo más usada de la industria , la metodología SCRUM que nosotros hemos adaptado a nuestro proyecto de la siguiente manera:

1. **Análisis y Diseño :** Diseñar un prototipo visual de todas las pantallas de la aplicación, incluido el login, apoyándose en un estudio comparativo (benchmarking) de aplicaciones similares y en un análisis de la curva de aprendizaje del usuario. Para esto apoyarnos en aplicaciones como Figma.
2. **Tecnología :** Seleccionar el lenguaje de desarrollo más adecuado para nosotros (Dart o Kotlin) y aplicar una arquitectura MVC
3. **Implementación :** de la interfaz: Implementar el algoritmo de coincidencia (match) y la funcionalidad de elección (swipe) sobre datos simulados.
4. **Datos:** Diseñar la base de datos y analizar qué tipo de SGBD se adapta mejor al proyecto (por ejemplo, MongoDB frente a una base de datos relacional).
5. **Servidor:** Analizar y seleccionar la capa de servidor más adecuada, teniendo en cuenta el acceso a datos, la sincronización de resultados en tiempo real entre usuarios y la protección de datos, especialmente en el login.
6. **Integración:** Implementar la gestión de salas sincronizadas conectando la aplicación con la base de datos y el servidor.
7. **Pruebas:** Pruebas, corrección de errores y versión final.
   
### 1.5. Alcance del proyecto

Para realizar el alcance del proyecto se utilizo la metodología de Análisis de Requisitos, la cual nos permitió identificar, clasificar y delimitar las áreas y técnicas que el sistema cubrirá, abarcando las siguientes áreas:

Módulo de Gestión de Salas: Creación, configuración, cierre y unión a salas mediante código numérico único de 4 a 6 dígitos o escaneo de código QR.  

Módulo de Filtros Previos: Definición de parámetros de búsqueda (modo película/juego, plataformas de streaming/consola disponibles, número de jugadores y géneros.  

Módulo de Interacción (Swipe): Interfaz gráfica interactiva para el deslizamiento de tarjetas con gestos táctiles, limitando el mazo a una cantidad optimizada de cartas por ronda.  

Sincronización en Tiempo Real: Comunicación bi-direccional entre el servidor y los móviles de la sala para detectar coincidencias al instante.  

Módulo de Resultados e Información: Pantalla de victoria (Match) que muestra las plataformas donde consumir el contenido.  

Compatibilidad Multiplataforma: Despliegue funcional en dispositivos móviles Android e iOS.  

### 1.6. Limitaciones y exclusiones

Limitaciones Dependencia de APIs de terceros: La disponibilidad, precisión y actualización del catálogo de películas y videojuegos dependerá directamente de los tiempos de respuesta y límites de consulta (rate limits) de las APIs externas (TMDB e IGDB).   

Conectividad a Internet: Aunque la sala se denomine "local" por la proximidad física de los usuarios, la sincronización requiere una conexión activa a Internet para la comunicación con la base de datos en la nube.    

Exclusiones Reproducción de contenido directo: La aplicación no actuará como plataforma de reproductor de vídeo ni ejecutor de juegos (cloud gaming), su alcance se limita estrictamente a la facilitación de la decisión.   

Derechos de propiedad intelectual: Las imágenes, portadas, logotipos y demás elementos identificativos de películas, series y videojuegos estarán sujetos a los derechos de sus respectivos propietarios y a las condiciones de uso establecidas por las fuentes utilizadas.  

Cambios en la disponibilidad del contenido: La disponibilidad de películas, series y videojuegos en las diferentes plataformas podrá variar con el tiempo debido a cambios en los catálogos, acuerdos de distribución o condiciones de servicio de dichas plataformas.  

Gestión de compras o suscripciones integradas: No se procesarán pagos dentro de la app ni se gestionarán las suscripciones de los usuarios a las plataformas de streaming.  

Derechos de propiedad intelectual: Las imágenes, portadas, logotipos y demás elementos identificativos de películas, series y videojuegos estarán sujetos a los derechos de sus respectivos propietarios y a las condiciones de uso establecidas por las fuentes utilizadas.  

Red social persistente: En esta versión del proyecto no se incluirá un sistema de mensajería interna, chat global ni listas de amigos permanentes entre salas.  


### 1.7. Estructura de la memoria



## 2. ANÁLISIS DEL CONTEXTO Y VIABILIDAD

### 2.1. Sector profesional y perfil de usuarios

El proyecto se encuadra en el sector del desarrollo de software móvil y soluciones digitales para el ocio y entretenimiento. Se sitúa en la intersección entre las aplicaciones de recomendación de contenido y las herramientas de toma de decisiones grupales. El público objetivo se divide en dos perfiles principales:

Usuario Principal (Gen Z y Millennials, 18-35 años): Nativos o adoptantes digitales avanzados, consumidores habituales de plataformas de streaming (Netflix, HBO Max, Disney+, Prime Video) y servicios de videojuegos (Xbox Game Pass, PlayStation Plus, Steam). Acostumbrados a la navegación por gestos en redes sociales y aplicaciones de citas y que valoran la inmediatez, la simplicidad visual y la ausencia de fricciones (como formularios de registro largos).

Usuario Secundario (Grupos familiares, amigos y parejas): Usuarios de diversa edad que buscan una herramienta funcional para resolver rápidamente la elección de ocio en el hogar durante los fines de semana o momentos de reunión.

### 2.2. Análisis de la necesidad El crecimiento de los catálogos ha generado la paradoja de la elección: a mayor cantidad de opciones, mayor es la fatiga cognitiva y el tiempo requerido para tomar una decisión.

El análisis de esta necesidad revela tres puntos de dolor fundamentales:

* **Sesgo de grupo y dominante:** En las discusiones abiertas, la decisión suele inclinarse hacia la persona más firme del grupo, dejando insatisfechos a otros integrantes.
* **Tiempo de búsqueda desproporcionado:** El tiempo invertido en seleccionar qué ver o a qué jugar llega a consumir una fracción significativa del tiempo libre total disponible.
* **Falta de una solución transversal:** Las soluciones actuales suelen limitarse exclusivamente al cine o carecen de capacidades sincrónicas locales y transversales que incluyan videojuegos cooperativos/multijugador.

### 2.4
Costes de la mano de obra para el proyecto
Estimando 3 meses de trabajo en jornadas de 8 horas diarias (480 h), sumándole un 30 % de coste de contratación de la Seguridad Social:

Analista / Diseñador UI-UX. 210 horas a 15 €/hora * 1,3 de coste SS = 4.095 €
Programador Multiplataforma (Fullstack). 225 horas a 17 €/hora * 1,3 de coste SS = 4.972,50 €
QA / Tester de Software. 45 horas a 15 €/hora * 1,3 de coste SS = 877,50 €
Subtotal Personal = 9.945 €

**Costes técnicos asociados a herramientas y despliegue comercial:**
**Licencias**
Apple Developer Program |~99 € / año |Pago Anual |Requisito indispensable para publicar en la App Store en IOS
Google Play Console |~$25 USD (~23 €) |Pago único |Para publicar en Google Play Store

Infraestructura Cloud
Firebase / Supabase: Cuentan con capas gratuitas amplias (Free Tier / Plan Spark). Para un MVP con tráfico inicial, el gasto mensual ronda entre 0 € y 30 €/mes.Cero coste de mantenimiento de servidores.

**Costes operativos**
Electricidad : paquete Gana Energia 24h -> 0,119€/KWh sin permanencia
Fibra : paquete Orange Conecta Empresas: 50,90 €/mes, 1 Gb simétrico, IP estática, router de alto rendimiento, VPN entre sedes y backup 4G.


