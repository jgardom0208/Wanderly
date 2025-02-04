### Anteproyecto: Wanderly – Explora y Conecta con el Mundo

#### b.2. Título del proyecto
**Wanderly: Explora y Conecta con el Mundo**

#### b.3. Nombre del autor del proyecto
**Juan Antonio García Domínguez**

#### b.4. Descripción
Wanderly es una red social diseñada para viajeros y aventureros que desean compartir sus experiencias, inspirarse en otros y planificar nuevas exploraciones. La plataforma permite a los usuarios:

- Crear perfiles de viaje con mapas interactivos donde marquen los destinos visitados y los que desean explorar.
- Publicar fotos, blogs de viaje y recomendaciones personalizadas sobre alojamientos, restaurantes, actividades y transporte.
- Conectar con otros viajeros con intereses y planes similares, creando una comunidad global.
- Participar en grupos de destinos específicos, como "Europa en Mochila", "Amantes del Trekking", o "Viajeros Gastronómicos".
- Acceder a herramientas útiles para planificar viajes, como listas de pendientes, presupuestos y guías colaborativas.
- Unirse a retos y dinámicas de la comunidad, como “50 países antes de los 30” o “Explora 5 playas paradisíacas”.

Wanderly no solo es un espacio para compartir aventuras, sino también para encontrar compañeros de viaje, aprender de la experiencia de otros y mantener viva la pasión por explorar.

#### b.5. Objetivos del proyecto
- Crear un espacio único que conecte a viajeros de todo el mundo y fomente la interacción social basada en el amor por explorar.
- Proveer herramientas prácticas que ayuden a los usuarios a planificar y registrar sus viajes de manera eficiente.
- Inspirar a las personas a descubrir nuevos destinos a través de contenido generado por la comunidad.
- Generar una red inclusiva donde viajeros de todos los niveles puedan compartir conocimientos y experiencias.
- Facilitar la búsqueda de compañeros de viaje con intereses similares mediante filtros y algoritmos de recomendación.

#### b.6. Tecnologías utilizadas
##### **Frontend:**
- **Next.js:** Para construir una aplicación web rápida y optimizada.
- **Tailwind CSS:** Para un diseño moderno, limpio y personalizable.
- **Mapbox o Leaflet.js:** Para la creación de mapas interactivos que permitan a los usuarios marcar sus viajes y explorar destinos.

##### **Backend:**
- **Node.js con Express.js:** Para manejar la lógica del servidor y las API REST.
- **PostgreSQL o MySQL:** Base de datos relacional para almacenar información de usuarios, publicaciones, mapas y conexiones entre viajeros.
- **Firebase:** Para autenticación segura y almacenamiento en tiempo real.

##### **Otros:**
- **OpenWeather API:** Para mostrar el clima actual en los destinos de interés.
- **Cloudinary:** Para subir y optimizar fotos de viajes.
- **JWT (JSON Web Tokens):** Para la autenticación y seguridad de las cuentas de usuario.
- **GitHub:** Para el control de versiones y colaboración en el desarrollo del proyecto.

#### b.7. Modelo de Base de Datos Relacional
Para mejorar la integridad y eficiencia de los datos, Wanderly usará una base de datos relacional con PostgreSQL o MySQL. El esquema incluirá las siguientes tablas:

- **Usuarios:** ID, nombre, email, contraseña, foto de perfil, bio, fecha de registro.
- **Destinos:** ID, nombre, país, coordenadas, descripción, imagen.
- **Publicaciones:** ID, usuario_id, destino_id, título, contenido, fecha_publicación, imagen.
- **Comentarios:** ID, publicacion_id, usuario_id, contenido, fecha_comentario.
- **Amigos/Conexiones:** ID, usuario_id_1, usuario_id_2, estado.
- **Intereses de Viaje:** ID, usuario_id, categoría.
- **Retos:** ID, nombre, descripción, recompensa.
- **Usuarios_Retos:** ID, usuario_id, reto_id, estado.

Este modelo permitirá realizar consultas optimizadas y mantener la consistencia de los datos.

#### b.8. Recomendaciones adicionales para el proyecto
- **Wireframes iniciales:** Diseñar una interfaz atractiva con foco en los mapas interactivos y las publicaciones de los usuarios.
- **Sistema de gamificación:** Incluir logros como "Viajero Global" o "Explorador de Naturaleza" para premiar la actividad y el alcance del usuario.
- **Búsqueda avanzada:** Ofrecer filtros por intereses, destinos, presupuesto y estilos de viaje (aventura, relax, lujo, etc.).
- **Modo oscuro:** Agregar un diseño visual alternativo que mejore la experiencia del usuario durante el uso nocturno.

#### b.9. Posibles funcionalidades futuras
- **Integración con plataformas de alojamiento y vuelos** para facilitar la búsqueda de reservas.
- **Recomendaciones personalizadas** basadas en las publicaciones, destinos visitados o guardados por el usuario.
- **Explorador social:** Un algoritmo que sugiera compañeros de viaje o grupos basados en intereses comunes.
- **Plataforma de contenido premium:** Guías de viaje descargables o itinerarios exclusivos creados por viajeros expertos.
