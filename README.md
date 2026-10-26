# Quick Search Tools — Privacy Policy

Last updated: 26 October 2026. Applies to Quick Search Tools version 1.13.0, Chrome Web Store item `mfkjnapnipdafokbhnionjnhmpajdkdk`.

Publisher and responsible contact: **Ekain Herce Villacorta**.  
Support and privacy enquiries: **quicksearchtoolsprivacy@gmail.com**.

## What the extension does

Quick Search Tools organises saved websites in a local library and a temporary For Later inbox. It also provides configurable ad/tracker blocking, supported cookie-banner rejection, per-site preferences, optional current-site data clearing and Maps/ChatGPT links on supported Google search pages.

## Information used and stored locally

In this policy, collecting and handling data includes accessing or processing information on your device, even if it is never sent to the publisher. The extension accesses information through Chrome extension APIs, user input and relevant elements of supported HTTP/HTTPS pages, including frames.

- **Saved websites:** URLs, titles, folders, favourites, temporary-link timestamps and favicon references or images. A URL can include query strings supplied by the user. Saving links is initiated by the user, including manual entry, current-tab capture, bulk capture, importing a backup or dropping links. 
- **Preferences:** language, theme, feature defaults, website-specific settings and positions/visibility of floating controls. A per-site preference can store the relevant website hostname. 
- **Block statistics:** numeric totals, the local-day count, the feature start date, sampling timestamps and rule/timestamp counts needed to avoid counting the same match twice. This feature does not persist request URLs or a log of visited sites. 
- **Transient browser/page information:** current tab URL, title and available favicon; current search query; and relevant page elements used to show controls, identify supported consent buttons or hide supported advertising elements. These are used for the visible features. The extension does not keep a full browsing history, page snapshots, typed form contents, passwords or message archives. 

The library, preferences and persisted statistics use `chrome.storage.local` in your Chrome profile. This version does not use `chrome.storage.sync` or sync them with Chrome bookmarks or a developer-operated server. Free-plan usage is calculated from the local library; there is no separate usage-analytics service. Current tab identifiers and per-page counters are also processed in memory to update the interface and per-site blocking rules.

## How information is used

URLs, titles and icons let you save, display, search, edit, import, export and reopen links. Folder names, favourites and timestamps organise your library and For Later inbox. Hostnames and preferences apply your chosen settings on each site. Page elements are inspected automatically while the relevant feature is enabled to display browsing controls, hide supported advertisements and operate recognised cookie-rejection controls. Search queries construct the Maps/ChatGPT links. Chrome's local rule-match information supplies visible aggregate block counters. Data is used for these functions, not to build advertising profiles.

## Network requests and third-party services

When saved links are displayed, icon images may load automatically from the saved website's `/favicon.ico`, an icon URL saved from a tab or imported backup, or Chrome's favicon endpoint/cache as a fallback. A saved icon URL can belong to a third-party image host. Recipients are the operator of that image URL and its hosting/network providers; Chrome's own icon retrieval is handled by Google Chrome. They may receive the requested resource, your IP address and normal browser request metadata, including cookies where the browser permits them. Direct icon images use a no-referrer policy. No library database or block-statistics database is uploaded with these requests. Opening a saved link navigates to the website you choose, whose operator receives normal navigation data.

On supported Google search pages, Maps and ChatGPT controls construct links from the current search query. When you choose such a link, the selected service receives the query and normal navigation metadata: Google operates Maps and OpenAI operates ChatGPT. The extension does not automatically upload search queries to a developer service. The privacy policies of [Google](https://policies.google.com/privacy) and [OpenAI](https://openai.com/policies/privacy-policy/) apply to those services.

All extension code and blocking lists are bundled in the package. No remote executable code, analytics SDK or tracking pixel is loaded by the extension. The extension's own block-count sampling uses Chrome's local API, not a remote server.

## Cookie handling and site-data deletion

When enabled, the extension inspects relevant page elements and attempts to choose recognised rejection options in supported cookie-consent banners. It does not promise to handle every banner or record universal consent. It does not read the contents of Chrome's cookie database.

You can explicitly request deletion of the current site's cookies or supported site data/cache from the popup. The origin of the selected tab is rechecked before deletion. Clearing cookies can sign you out. This feature does not clear browser history or saved passwords.

## Developer access, sharing and sale

Version 1.13.0 has no developer-operated account, cloud sync, analytics, payment or licensing service. The publisher does not receive the saved library, browsing controls' page content or block-statistics database through the extension. The publisher does not sell user data, use it for advertising or credit/lending decisions, or transfer it for unrelated purposes. The network activity described above is limited to user-facing website/icon features and user-selected navigation.

Information you voluntarily send to the support contact is used to answer and resolve your request. Do not include passwords or sensitive page contents in a support message. Email delivery is handled by the chosen mail providers.

If you email support, the publisher receives your email address, the name shown by your email account, your message and any attachments you choose to send. The support mailbox is hosted by Google Gmail; your own email provider also handles delivery. Support correspondence is retained for handling and following up the request and deleted when no longer needed for that purpose, unless retention is necessary to meet a legal obligation or resolve a dispute. You can request its deletion using the contact below. This is separate from extension data, which the publisher cannot retrieve or erase remotely.

## Storage and security

Local data relies on the security of your device, Chrome profile and Chrome's extension-storage isolation. The extension does not add its own encryption to local storage or exported JSON backups. Anyone with access to your device, profile or backup files may be able to read them. Keep your device and Chrome updated, protect your profile and store backups securely. URLs and titles may themselves contain sensitive information; check them before saving, exporting or sharing.

Maps and ChatGPT links use HTTPS. Saved website and icon addresses may use HTTP or HTTPS as provided by the user, page or imported file; HTTP traffic is not encrypted. The no-referrer policy on direct icon images prevents sending the referring page URL but does not conceal your IP address from the image host. The extension does not operate a data-upload endpoint or promise additional encryption for third-party navigation.

## Retention, export and deletion

Saved links do not expire automatically. Local settings and aggregates remain until removed or the extension's storage is cleared. You can delete individual saved links or folders, clear the For Later inbox and export/import your library using the manager. Deleting a folder preserves its contents in its parent, as shown in the UI. Existing data above the new free limits is retained.

Removing the extension clears its local extension storage according to Chrome's behaviour. Exported JSON files are separate files under your control and are not deleted when the extension is removed; delete those files yourself if no longer wanted. Third-party websites and Chrome may retain their own caches or records under their own policies.

You can view and edit saved links in the library manager, delete links individually and clear For Later. Removing a folder alone does not remove its links. You can change global and per-site settings in the popup, disable individual features or disable the extension. There is no separate reset button for all statistics or preferences in this version: to remove all extension-local data, uninstall it through Chrome's Manage extensions page. Per-page counters in worker memory are invalidated when a tab navigates or closes; they are not a persistent browsing log. Today's aggregate rolls over on the next sample after the local date changes; the overall count remains until local extension data is removed.

## Payments and future changes

The current free plan permits 3 folders total (including subfolders) and 5 For Later links. A Pro price is shown as a preview, but purchasing and activation are unavailable in version 1.13.0. No payment details or licence identifiers are collected by this version. If payment, licensing, accounts or sync are added, the policy and store disclosures will be updated before those services are offered.

## Limited use and contact

The use of information received from Google APIs adheres to the Chrome Web Store User Data Policy, including its Limited Use requirements. Information is used only for the described user-facing functionality and permitted support, not for sale, unrelated advertising, unrelated human review or creditworthiness decisions.

For questions about this policy or local-data controls, contact **quicksearchtoolsprivacy@gmail.com**.

You may also use this address to request access to, correction of or deletion of support correspondence. Requests concerning local library data must be carried out on your device using the controls above, because the publisher has no remote access to it. Policy changes will be published on this page with an updated date; changes to data practices will also be reflected in the store disclosures before the corresponding functionality is offered.

---

# Quick Search Tools — Política de privacidad

Última actualización: 26 de octubre de 2026. Aplicable a Quick Search Tools 1.13.0, elemento de Chrome Web Store `mfkjnapnipdafokbhnionjnhmpajdkdk`.

Responsable: **Ekain Herce Villacorta**.  
Contacto de privacidad y asistencia: **quicksearchtoolsprivacy@gmail.com**.

## 1. Qué hace la extensión

Organiza webs en una biblioteca local y en Para luego. Ofrece bloqueo configurable de anuncios y rastreadores, rechazo de avisos de cookies compatibles, ajustes por sitio, eliminación de datos del sitio actual a petición del usuario y accesos a Maps y ChatGPT en búsquedas de Google compatibles.

## 2. Qué datos se recogen y cómo

El tratamiento incluye acceder a datos o procesarlos localmente aunque no se transmitan al responsable. La extensión utiliza las API de Chrome, los datos que introduces y elementos relevantes de las páginas HTTP/HTTPS compatibles, incluidos sus marcos.

- **Biblioteca:** direcciones URL, títulos, nombres y estructura de carpetas, favoritos, identificadores locales, marcas de tiempo de Para luego y referencias o imágenes de iconos. Se incorporan cuando guardas una pestaña, capturas varias, introduces o arrastras un enlace o importas una copia. Las URL pueden contener parámetros con datos personales. 
- **Preferencias:** idioma, tema, modo de bloqueo, ajustes generales y por sitio, nombres de dominio y posición y visibilidad de los controles flotantes. 
- **Estadísticas:** recuentos agregados de peticiones bloqueadas, fecha de inicio, día local, marcas de muestreo e identificadores de reglas con sus recuentos para evitar duplicados. Las estadísticas persistentes no guardan URL de peticiones ni un historial de sitios visitados. 
- **Datos transitorios:** URL, título, identificador e icono disponible de las pestañas, consulta actual de búsqueda y elementos relevantes de la página para mostrar controles, ocultar anuncios compatibles e identificar opciones de rechazo de cookies. No se conserva un historial completo de navegación, capturas de páginas, contraseñas, contenido de formularios ni archivos de mensajes. 

## 3. Para qué se utilizan

Los enlaces, títulos e iconos permiten guardar, mostrar, buscar, editar, importar, exportar y volver a abrir webs. Las carpetas, favoritos y fechas organizan la biblioteca y Para luego. Los dominios y preferencias aplican tus ajustes por sitio. Mientras una función está habilitada, se inspeccionan automáticamente los elementos pertinentes para mostrar sus controles, ocultar anuncios y accionar opciones reconocidas de rechazo de cookies. Las consultas construyen los accesos a Maps/ChatGPT. Las coincidencias de reglas proporcionadas por Chrome permiten mostrar contadores de bloqueo. El uso del plan gratuito se calcula a partir de la biblioteca local. Estos datos no se utilizan para crear perfiles publicitarios.

## 4. Dónde y cómo se almacenan

La biblioteca, preferencias y estadísticas persistentes se guardan en `chrome.storage.local`, dentro de tu perfil de Chrome. No se usa `chrome.storage.sync`, no se sincroniza la biblioteca con marcadores de Chrome y no existe un servidor del desarrollador para cuentas, sincronización, analítica, pagos o licencias en esta versión. Los identificadores de pestañas y contadores por página también se procesan temporalmente en memoria para actualizar los controles y las excepciones de bloqueo.

## 5. Con quién se comparten datos y qué sale del dispositivo

El responsable no recibe la biblioteca, el contenido de las páginas ni la base de estadísticas a través de la extensión. No vende datos, no los usa para publicidad ni decisiones crediticias o de préstamo y no los transfiere para fines ajenos a las funciones descritas.

- **Iconos:** al mostrar enlaces pueden cargarse automáticamente imágenes desde `/favicon.ico` de la web guardada, desde una URL de icono guardada de una pestaña o importada, o mediante el servicio/caché de iconos de Chrome como alternativa. Una URL de icono puede pertenecer a un alojamiento externo. El operador de la imagen y sus proveedores de alojamiento/red reciben la dirección del recurso, la IP y metadatos normales de la petición, incluidas cookies cuando el navegador lo permita. Google Chrome gestiona su propia obtención de iconos. Las imágenes directas usan una política sin referente. No se sube la base de la biblioteca ni de estadísticas. 
- **Maps y ChatGPT:** al elegir esos accesos se envía la consulta actual al servicio elegido: Google para Maps y OpenAI para ChatGPT, junto con los datos normales de navegación. No se suben automáticamente consultas a un servidor del desarrollador. Se aplican las políticas de [Google](https://policies.google.com/privacy) y [OpenAI](https://openai.com/policies/privacy-policy/). 
- **Webs abiertas:** al abrir un enlace, el sitio elegido y sus proveedores reciben los datos normales de esa navegación y aplican sus propias políticas. 
- **Asistencia:** si escribes al correo de contacto, el responsable recibe tu dirección, el nombre mostrado por tu cuenta, el mensaje y los adjuntos que decidas enviar para atender tu consulta. Google Gmail aloja el buzón de soporte y tu proveedor de correo también interviene en la entrega. No envíes contraseñas ni contenido sensible innecesario. 

El código y las listas de bloqueo están incluidos en el paquete. No se carga código ejecutable remoto, un SDK de analítica ni un píxel de seguimiento. El muestreo de bloqueos usa la API local de Chrome.

## 6. Cookies y eliminación de datos de sitios

Cuando está habilitada, la función de cookies inspecciona elementos relevantes de la página e intenta accionar opciones reconocidas de rechazo. No garantiza cubrir todos los avisos ni registra un consentimiento universal. No lee el contenido de la base de cookies de Chrome.

Desde el popup puedes solicitar expresamente borrar cookies o los datos y caché compatibles del sitio actual. Se vuelve a comprobar el origen de la pestaña antes de borrar. Chrome realiza la eliminación; la extensión no copia ni envía el contenido eliminado. Puede cerrarse tu sesión. La función no elimina el historial del navegador ni las contraseñas guardadas.

## 7. Seguridad

El almacenamiento local depende de la seguridad de tu dispositivo, tu perfil y el aislamiento del almacenamiento de extensiones de Chrome. No se añade cifrado propio al almacén local ni a las copias JSON. Quien tenga acceso al perfil o a esas copias podría leerlas. Protege tu dispositivo, mantén Chrome actualizado y revisa los enlaces antes de exportarlos o compartirlos.

Los accesos a Maps y ChatGPT usan HTTPS. Las direcciones de webs e iconos pueden usar HTTP o HTTPS según el enlace introducido, la página o el archivo importado; HTTP no cifra el tráfico. La política sin referente de los iconos directos evita enviar la URL de la página de origen, pero no oculta tu IP al servidor de la imagen. No existe un punto de subida de datos del desarrollador ni se promete cifrado adicional para la navegación a terceros.

## 8. Conservación, acceso, exportación y eliminación

Los enlaces, incluidos los de Para luego, no caducan automáticamente. Los ajustes y contadores agregados permanecen hasta que los elimines o se borren los datos locales de la extensión. Los elementos existentes por encima de los límites gratuitos se conservan. Puedes consultar y editar enlaces en el gestor, borrar enlaces individuales, vaciar Para luego y exportar o importar la biblioteca en JSON. Borrar una carpeta conserva sus enlaces en la carpeta superior, como indica la interfaz.

Los contadores por página en memoria se invalidan cuando una pestaña navega o se cierra. El agregado de hoy cambia al siguiente muestreo tras el cambio de fecha local; el total permanece hasta borrar los datos locales. Esta versión no tiene un botón independiente para reiniciar todos los ajustes y estadísticas. Para eliminar todos los datos locales, desinstala la extensión desde Gestionar extensiones de Chrome, que elimina su almacenamiento según su funcionamiento.

Las copias JSON exportadas son archivos independientes que debes eliminar tú; no desaparecen al desinstalar. Chrome y los sitios externos pueden conservar sus cachés o registros según sus propias políticas. Los correos de soporte se conservan para atender la consulta y su seguimiento y se eliminan cuando dejan de ser necesarios para ello, salvo obligaciones legales o resolución de disputas. Puedes solicitar su eliminación al correo de contacto.

## 9. Opciones y contacto

Puedes cambiar ajustes generales o por sitio, desactivar funciones individuales o deshabilitar la extensión. Para preguntas sobre privacidad o solicitudes de acceso, rectificación o eliminación de correspondencia de soporte, escribe a **quicksearchtoolsprivacy@gmail.com**. La biblioteca local debes gestionarla en tu dispositivo: el responsable no puede recuperarla ni borrarla a distancia.

## 10. Pagos, uso limitado y cambios

El plan gratuito incluye 3 carpetas, contando subcarpetas, y 5 enlaces en Para luego. Se muestra un precio Pro previsto, pero la compra y activación no están disponibles en 1.13.0. No se recogen datos de pago ni identificadores de licencia.

El uso de información recibida de las API de Google respeta la política de datos de usuario de Chrome Web Store, incluidos sus requisitos de uso limitado. Se utiliza para las funciones visibles y la asistencia permitida, no para venta, publicidad ajena, revisión humana no relacionada ni decisiones crediticias.

Los cambios de esta política se publicarán con una nueva fecha. Si se incorporan pagos, licencias, cuentas, sincronización u otros tratamientos, la política y las declaraciones de la tienda se actualizarán antes de ofrecerlos.
