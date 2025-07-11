# Asistente Interactivo de Cotización y Selección de Planes Contables para Antox.cl 🚀

Bienvenido al repositorio del proyecto para el desarrollo de un asistente interactivo, diseñado para simplificar la selección de servicios contables y de asesoría en [Antox.cl](https://www.antox.cl/planescontables). Este asistente busca mejorar la experiencia del usuario y guiarlo eficientemente a través de la compleja oferta de servicios de Antox.cl, incluyendo sus asociaciones estratégicas.

## 🎯 Descripción del Producto Digital (El Asistente)

Este "Asistente de Cotización/Selección de Plan" es una herramienta basada en web que interactúa con el usuario a través de una serie de preguntas clave. Su objetivo principal es:

1.  **Clarificar la Oferta:** Ayudar a los usuarios a comprender qué plan contable de Antox.cl se adapta mejor a sus necesidades.
2.  **Personalizar la Recomendación:** Ofrecer una recomendación personalizada basada en sus respuestas.
3.  **Optimizar el Contacto:** Dirigir al usuario hacia la opción más adecuada: un plan contable específico, una asesoría personalizada, o los servicios de nuestros socios especializados ([misauditores.cl](https://www.misauditores.cl/) para auditorías y [peritolaboral.cl](https://www.peritolaboral.cl/) para temas laborales).
4.  **Destacar Valor Agregado:** Comunicar el beneficio del hosting gratuito ofrecido a través de [hostinghat.cl](https://www.hostinghat.cl/) como parte de la solución integral de Antox.cl.

El asistente es una aplicación de frontend puro (HTML, CSS, JavaScript) que puede ser fácilmente integrada en la página existente de Antox.cl o funcionar como una subpágina dedicada.

## 💡 Problemática Abordada y Solución Implementada

### Problemática: La Complejidad en la Selección de Servicios Contables

En el sector de servicios profesionales como la contabilidad y auditoría, los usuarios a menudo enfrentan una alta **complejidad en la toma de decisiones**. Para [Antox.cl](https://www.antox.cl/), la variedad de "planes contables" directos, la posibilidad de asesorías personalizadas, y la existencia de alianzas con especialistas como [misauditores.cl](https://www.misauditores.cl/) y [peritolaboral.cl](https://www.peritolaboral.cl/), aunque es una fortaleza, puede generar **confusión y fricción** en la experiencia del usuario.

Los usuarios pueden:
* Sentirse abrumados por la cantidad de opciones en `www.antox.cl/planescontables`.
* No saber qué plan es el "correcto" para su situación específica (ej. tipo de empresa, volumen de operaciones).
* Desconocer cuándo su necesidad va más allá de un plan predefinido y requiere una asesoría o un servicio especializado de un socio.
* Perder el valor añadido del hosting gratuito de [hostinghat.cl](https://www.hostinghat.cl/) al no entender cómo se integra en la oferta.

Esto puede llevar a la **indecisión, abandono del sitio o a un contacto inicial menos eficiente** para Antox.cl. Aplicando principios de **Diseño Centrado en el Usuario** y **UX (Experiencia de Usuario)**, identificamos la necesidad de simplificar este "viaje del cliente".

### Solución Implementada: El Asistente Interactivo

Para abordar esta problemática, he desarrollado un "Asistente de Cotización/Selección de Plan" interactivo. Este asistente opera como un embudo de información guiado, siguiendo el enfoque de *Design Thinking* para pasar de la **empatía** con el usuario a la **definición** de su necesidad, y luego a la **ideación** y **prototipado** de la solución.

**Características Clave del Asistente:**

* **Preguntas Guiadas:** Formula preguntas progresivas sobre las características del usuario/empresa (ej., tipo de contribuyente, tamaño, servicios requeridos).
* **Lógica de Ramificación:** Las preguntas y recomendaciones se adaptan dinámicamente según las respuestas anteriores del usuario.
* **Recomendaciones Personalizadas:** Al final del flujo, el asistente presentará:
    * Uno o más **planes contables de Antox.cl** que mejor se ajusten.
    * La opción de **contactar para una asesoría personalizada** si la necesidad es muy específica.
    * Una **derivación clara a `misauditores.cl` o `peritolaboral.cl`** si la consulta es de su especialidad (ej., "Necesitas una auditoría específica de XX, te recomendamos a nuestros socios de MisAuditores.cl").
    * Menciona y contextualiza el **beneficio del hosting gratuito de hostinghat.cl** cuando sea relevante para el tipo de servicio recomendado.
* **Diseño Intuitivo:** La interfaz es limpia y fácil de usar, minimizando la carga cognitiva del usuario.

## 🛠️ Tecnologías Utilizadas y Motivación del Proyecto

Este proyecto está construido con tecnologías web estándar para asegurar compatibilidad y facilidad de implementación:

* **HTML5:** Estructura semántica del asistente.
* **CSS3:** Estilos y diseño responsivo para una experiencia consistente en diferentes dispositivos.
* **JavaScript (Vanilla JS):** Lógica interactiva para las preguntas, la ramificación y la generación de recomendaciones.

**Motivación del Proyecto:**
La motivación detrás de este asistente es doble:

1.  **Para Antox.cl:** Optimizar el proceso de adquisición de clientes, reducir las consultas iniciales que no están pre-calificadas, y asegurar que los clientes encuentren la solución correcta, aumentando potencialmente la conversión y la satisfacción del cliente.
2.  **Para los Usuarios:** Simplificar una decisión compleja, ahorrándoles tiempo y esfuerzo en la búsqueda del servicio adecuado, y garantizándoles que están tomando una decisión informada. Esto alinea la solución con los principios de *Service Design*, enfocándose en mejorar el "viaje" completo del cliente.

## 🚀 Guía de Instalación y Uso

Para ejecutar y probar este asistente localmente, sigue estos sencillos pasos:

1.  **Clonar el Repositorio:**
    ```bash
    git clone [URL_DE_TU_REPOSITORIO_GITHUB]
    cd [nombre-de-tu-repositorio]
    ```
2.  **Abrir en el Navegador:**
    * Simplemente abre el archivo `index.html` en tu navegador web preferido.
    * Puedes hacerlo arrastrando el archivo `index.html` a la ventana de tu navegador o haciendo doble clic sobre él.

### Uso del Asistente:
Una vez abierto, el asistente te guiará automáticamente:
1.  Responde a cada pregunta seleccionando la opción que mejor se adapte a tu situación.
2.  Haz clic en "Siguiente" o el botón correspondiente para avanzar.
3.  Al final, se te presentará una recomendación personalizada.

## 🌐 Producto Digital Desplegado

Puedes acceder y probar el asistente en vivo a través del siguiente enlace:

👉 **[ENLACE_A_TU_ASISTENTE_DESPLEGADO_EN_GITHUB_PAGES_O_OTRO_HOSTING]**

## 📺 Video Técnico del Proyecto

He preparado un video explicativo en YouTube que detalla la problemática, la solución implementada (con una demostración en vivo del asistente), y cómo funciona.

🎥 **[ENLACE_A_TU_VIDEO_DE_YOUTUBE]**

## 🤝 Contribuciones y Feedback

¡Tu feedback es valioso! Si tienes sugerencias o encuentras algún problema, por favor, abre un "Issue" en este repositorio.

Este proyecto fue desarrollado como parte de la Evaluación Final del módulo "Desarrollo de Portafolio para Especialidades".

---
