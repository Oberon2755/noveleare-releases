# 🔒 Política de Privacidad de Noveleare

**Última actualización:** 20 de octubre de 2026 · Versión 1.2.0  
**Responsable del tratamiento:** Noveleare (Oberon2755)  
**Contacto Oficial de Privacidad:** noveleare@gmail.com  
**Sitio Web Oficial:** https://noveleare.vercel.app  
**Portal de Privacidad:** https://noveleare.vercel.app/privacy  
**Términos del Servicio:** https://noveleare.vercel.app/terms  

---

## Resumen Ejecutivo de Privacidad

1. **Aislamiento Local (Local-First):** Tus proyectos literarios `.novel`, borradores, capítulos y fichas de lore residen exclusivamente en el disco duro de tu computadora personal. Noveleare no dispone de servidores centrales para alojar tus obras.
2. **Cero Entrenamiento de IA:** Noveleare **nunca** recopila, vende, lee ni utiliza el contenido de tus novelas para entrenar, afinar o alimentar modelos de Inteligencia Artificial propios ni de terceros.
3. **Cumplimiento Google API Services:** Cumplimiento riguroso con la *Google API Services User Data Policy*, incluidos todos los requisitos de **Uso Limitado** (*Limited Use*). Tus datos de Google OAuth se usan exclusivamente para autenticación y verificación de licencia (hasta 5 equipos por cuenta), sin rastreo ni publicidad.
4. **Claves Cifradas (BYOK):** Tus credenciales de API personales se almacenan localmente en tu sistema operativo mediante `safeStorage` (DPAPI en Windows) y se comunican directamente con los endpoints oficiales de cada proveedor de IA sin intermediación de Noveleare.

---

## 1. Responsable del Tratamiento y Compromiso Fundamental

El responsable del tratamiento de los datos personales asociados a la aplicación de escritorio **Noveleare** y al sitio web oficial (`https://noveleare.vercel.app`) es el titular y desarrollador del software (en adelante, **«Noveleare»** o **«Nosotros»**), con canal de contacto oficial y directo en el correo electrónico `noveleare@gmail.com`.

En Noveleare reconocemos que la labor literaria requiere el máximo grado de confidencialidad, intimidad y seguridad. Por esta razón, el software ha sido concebido y desarrollado bajo el estándar de **Privacidad por Diseño** (*Privacy by Design*) y una estricta arquitectura **Local-First** (primero en tu equipo local).

> **Principio Rector de Intangibilidad Literaria:** Noveleare no dispone ni mantiene servidores propios para el almacenamiento, alojamiento o procesamiento en la nube del contenido de sus obras, novelas, escenas, poemas, guiones o notas creativas. Su material narrativo reside física y exclusivamente en el almacenamiento local de su dispositivo.

---

## 2. Categorías de Datos y Ubicación de Almacenamiento

### A. Contenido Creativo y Proyectos Literarios (.novel) — 100% Local
- **Manuscritos y Capítulos:** Todos los textos, fragmentos narrativos, revisiones paralelas (versiones R1/R2), anotaciones en los márgenes, escaletas y sinopsis.
- **Biblias de Creación de Mundo:** Fichas descriptivas de personajes, razas y especies, árboles genealógicos, mapas interactivos, líneas temporales y glosarios de terminología ficticia.
- **Telemetría Editorial Client-Side:** El cálculo de la curva de tensión narrativa, el conteo de palabras, la detección de muletillas y la verificación ortotipográfica conforme a la RAE se ejecutan enteramente en la memoria RAM y CPU de su propia computadora. Ningún fragmento se envía a servidores externos para su análisis estadístico.
- **Ubicación física:** Únicamente en su disco duro local dentro de la carpeta o unidad que usted elija al guardar su proyecto en formato `.novel`.

### B. Claves API de Inteligencia Artificial (BYOK) — 100% Local Cifrado
- Si el Usuario opta por utilizar las funciones de asistencia creativa de IA, suministra sus propias claves API personales (Google Gemini, OpenAI, Anthropic Claude o xAI Grok).
- **Cifrado nativo del Sistema Operativo:** Estas claves se almacenan localmente cifradas a través de la API `safeStorage` de Electron, la cual hace uso de la interfaz DPAPI (*Data Protection API*) en Windows.
- Las claves API **jamás se transmiten ni se sincronizan con servidores de Noveleare**.

### C. Datos de Autenticación y Gestión de Licencias — Nube Segura
Únicamente cuando el Usuario decide voluntariamente iniciar sesión con su cuenta de Google para activar o sincronizar su licencia **Noveleare Pro**:
- **Dirección de correo electrónico:** utilizada como identificador único de cuenta para vincular el estado de la licencia adquirida.
- **Nombre público de perfil y URL de avatar:** mostrados en la interfaz gráfica del estudio para personalizar su entorno de trabajo.
- **Identificador de Usuario (UID):** código alfanumérico provisto por el proveedor de autenticación.
- **Identificador Anónimo de Dispositivo:** un hash criptográfico no reversible derivado de parámetros de hardware del equipo para verificar el cumplimiento del límite de hasta **cinco (5) computadoras personales** autorizadas por licencia Pro.

### D. Datos de Transacción y Facturación — Gestionados por Merchant of Record
Las transacciones económicas para la compra de licencias Pro son gestionadas directamente por **Lemon Squeezy LLC**, que actúa como comerciante registrado oficial (*Merchant of Record*). Noveleare **no almacena, no procesa ni tiene acceso a números de tarjetas de crédito o débito**, cuentas bancarias ni datos financieros sensibles.

---

## 3. Finalidades Específicas del Tratamiento y Base Jurídica

De conformidad con las normativas internacionales de protección de datos (incluyendo el RGPD europeo y normativas iberoamericanas concordantes), el tratamiento de los datos mínimos de cuenta se realiza bajo las siguientes bases jurídicas:
- **Ejecución del Contrato de Licencia (Art. 6.1.b RGPD):** Validar la compra de la licencia Noveleare Pro, habilitar las funciones avanzadas en los equipos autorizados y gestionar la activación en hasta 5 dispositivos.
- **Consentimiento Expreso del Usuario (Art. 6.1.a RGPD):** Proporcionado voluntariamente al iniciar sesión con Google OAuth o al aceptar los términos y políticas en el modal de primer arranque de la aplicación.
- **Interés Legítimo en la Prevención de Fraude (Art. 6.1.f RGPD):** Controlar el uso lícito de licencias comerciales y evitar la distribución o duplicación ilegítima de claves en redes públicas.

Noveleare **no comercializa, no alquila, no vende ni transfiere** sus datos personales a terceros con fines de publicidad, perfilado de comportamiento ni prospección comercial.

---

## 4. Flujo de Datos en la Asistencia de Inteligencia Artificial (BYOK)

Noveleare incorpora herramientas de asistencia creativa que operan bajo el esquema **Bring Your Own Key** (*trae tu propia clave*):
- **Transmisión Directa Cliente-Servidor:** Cuando el Autor pulsa un botón de embellecimiento, sugerencia de continuidad o consulta en el chat creativo, la porción de texto expresamente seleccionada es enviada de forma directa y cifrada mediante HTTPS/TLS desde el proceso local de Noveleare hacia los servidores oficiales de la API del proveedor configurado (Google LLC, Anthropic PBC, OpenAI LLC o xAI Corp).
- **Ausencia de Servidores Puente:** La comunicación no es intermediada, reenviada ni registrada en ningún servidor de Noveleare.
- **Condiciones del Proveedor de IA:** El procesamiento de los fragmentos textuales por parte del proveedor seleccionado se rige exclusivamente por sus correspondientes términos y políticas de privacidad para clientes de API comerciales.

> **Garantía de Cero Entrenamiento:** Noveleare no utiliza, no analiza ni suministra los textos de los usuarios para el entrenamiento, ajuste fino (*fine-tuning*) o mejora de ningún modelo de inteligencia artificial propio ni de terceros.

---

## 5. Cumplimiento con la Política de Datos de Usuario de Google (Google API Services User Data Policy)

El uso y la transferencia que hace Noveleare a cualquier otra aplicación de la información recibida a través de las APIs de Google cumplen rigurosamente con la [Política de Datos de Usuario de los Servicios de API de Google](https://developers.google.com/terms/api-services-user-data-policy) (*Google API Services User Data Policy*), incluyendo en su totalidad los requisitos de **Uso Limitado** (*Limited Use requirements*):
- **Finalidad Estricta:** La información recibida de Google (dirección de correo electrónico, nombre, foto de perfil y UID) se emplea únicamente para autenticar la identidad del usuario y sincronizar el estado de su licencia Noveleare Pro en sus dispositivos personales autorizados.
- **Prohibición de Transferencia Injustificada:** No transferimos datos de usuario de Google a terceros, salvo que sea indispensable para el funcionamiento de los servicios de autenticación segura (proveedor de backend Supabase), para cumplir con la legislación aplicable o en el marco de una reestructuración corporativa legal formal.
- **Prohibición de Uso Publicitario:** Los datos de usuario obtenidos a través de las APIs de Google jamás se utilizan para servir anuncios publicitarios, ni se comercializan con redes de publicidad dirigida o intermediarios de datos (*data brokers*).
- **Prohibición de Lectura Humana No Autorizada:** Ningún miembro del equipo humano de Noveleare lee ni examina los datos de usuario de Google, salvo que contemos con su consentimiento previo y expreso para la resolución de un problema técnico de soporte, sea estrictamente necesario por razones de seguridad informática o sea exigido por un mandamiento legal fundado.
- **Prohibición de Entrenamiento de IA:** Los datos de usuario de Google nunca se emplean para entrenar, reentrenar ni afinar modelos de aprendizaje automático o inteligencia artificial.

---

## 6. Destinatarios y Encargados del Tratamiento (Terceros Subprocesadores)

Para hacer posible la autenticación y distribución del Software, colaboramos con las siguientes entidades especializadas que cumplen con estándares rigurosos de protección de datos:
- **Google LLC (EE. UU.):** Proveedor de inicio de sesión seguro (Google OAuth).
- **Supabase Inc. (EE. UU.):** Infraestructura de base de datos segura y gestión de identidades, con cifrado en tránsito (TLS 1.3) y en reposo (AES-256).
- **Lemon Squeezy LLC (EE. UU.):** Plataforma de comercio electrónico y Merchant of Record para el cobro de licencias Pro, gestión fiscal y cumplimiento tributario internacional. Certificación de seguridad PCI-DSS Nivel 1.
- **GitHub Inc. (Microsoft Corporation):** Distribución de versiones ejecutables y consulta estática del manifiesto de actualización `latest.yml` sin recopilación de telemetría de identidad.

---

## 7. Medidas Técnicas y Organizativas de Seguridad

Noveleare aplica salvaguardas técnicas avanzadas para proteger la confidencialidad e integridad de la información:
- **Cifrado Criptográfico de Credenciales:** Las claves API se almacenan con algoritmos de cifrado simétrico robustos gestionados directamente por el sistema operativo del usuario a través de Electron `safeStorage` (DPAPI).
- **Protocolos de Comunicación Segura:** Todas las conexiones externas para autenticación, verificación de licencias y llamadas a modelos de IA se ejecutan exclusivamente sobre canales HTTPS forzados con certificados TLS 1.2 o 1.3.
- **Principio de Mínimo Privilegio:** La aplicación de escritorio no requiere permisos de administrador del sistema operativo para su funcionamiento regular y no tiene capacidad técnica para explorar carpetas del sistema fuera de las explícitamente designadas por el usuario para abrir o guardar sus proyectos `.novel`.

---

## 8. Conservación y Supresión de Datos

El ciclo de vida de los datos se rige por el principio de minimización:
- **Datos Locales del Usuario:** Los archivos de proyecto `.novel`, configuraciones y copias de seguridad locales residen indefinidamente en su equipo bajo su propio control y pueden ser eliminados en cualquier momento por usted simplemente borrando los archivos o desinstalando la aplicación.
- **Datos de Cuenta y Licencia:** La información de su perfil y estado de licencia se conserva mientras mantenga activa su cuenta de usuario. Si solicita la cancelación o eliminación de su cuenta, sus registros en la base de datos de autenticación serán suprimidos de manera definitiva en un plazo máximo de treinta (30) días hábiles.

---

## 9. Derechos del Usuario (Acceso, Rectificación y Supresión)

Usted goza de los siguientes derechos reconocidos internacionalmente en materia de protección de datos personales:
- **Derecho de Acceso:** Conocer con precisión qué datos de cuenta se encuentran asociados a su usuario.
- **Derecho de Rectificación:** Modificar o actualizar cualquier dato de perfil inexacto.
- **Derecho de Supresión («Derecho al Olvido»):** Solicitar el borrado definitivo de su cuenta y metadatos de activación de nuestros servidores.
- **Derecho de Desvinculación de Dispositivos:** Gestionar y desautorizar de forma autónoma cualquiera de sus 5 equipos activos desde el panel de ajustes de la aplicación.

Para ejercer cualquiera de estos derechos, basta con enviar un correo electrónico con su solicitud a `noveleare@gmail.com` desde la dirección de correo electrónico asociada a su cuenta de Noveleare.

---

## 10. Privacidad de Menores

Noveleare no está dirigido a menores de trece (13) años (o la edad mínima legal aplicable en su país, como dieciséis (16) años en determinados estados miembros de la Unión Europea). No recopilamos conscientemente datos personales de menores de edad. Si un padre, madre o tutor legal toma conocimiento de que un menor a su cargo ha facilitado datos de cuenta a Noveleare, puede contactarnos en `noveleare@gmail.com` para proceder a su eliminación inmediata.

---

## 11. Política de Cookies y Tecnologías de Rastreo

El software de escritorio de Noveleare **no utiliza cookies publicitarias, píxeles de seguimiento ni kits de desarrollo de software (SDK) de perfilado comercial**.

En el sitio web oficial (`https://noveleare.vercel.app`), únicamente se sirven archivos estáticos indispensables para la visualización de la documentación, las descargas y el contenido legal, sin implementar mecanismos de rastreo de navegación cruzada entre sitios web ajenos.

---

## 12. Actualizaciones de esta Política y Canal de Contacto Oficial

Noveleare podrá actualizar periódicamente esta Política de Privacidad para adaptarla a modificaciones normativas o mejoras técnicas en la arquitectura del Software. La versión en vigor siempre se encontrará disponible públicamente en esta dirección con la indicación expresa de su fecha de revisión.

### Canal de Contacto Oficial de Privacidad
- 📧 **Correo electrónico:** `noveleare@gmail.com`  
- 🌐 **Portal de Privacidad:** `https://noveleare.vercel.app/privacy`  
- 📄 **Términos del Servicio:** `https://noveleare.vercel.app/terms`
