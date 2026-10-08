# Plan de identificación y preservación — Almadraba Diseño

**Lunes 20 de marzo, 10:45.** Explicación a Elena Ruiz (gerente) antes de tocar nada. Las referencias **L1…L23** remiten a mi [lista de comprobación](lista-comprobacion.md).

**Hechos que orientan la búsqueda (L6):** el render se presentó en exclusiva hace dos semanas (hacia el 6 de marzo). Marta pidió la excedencia hace diez días. Según Javier, el «jueves 14» se quedó hasta tarde y esa semana le pidió un pendrive. **Ojo con la fecha:** si el 20 es lunes, el 14 fue martes y el jueves fue el 16. Hay que confirmarlo con Javier, porque cambia cuánto margen queda en los registros que rotan (L2, L19).

**Ventana de interés:** del 6 de marzo a hoy.

---

## 1. Las fuentes de evidencia

### En la mesa de Marta

| # | Fuente | Qué puede contener |
|---|---|---|
| F1 | **Portátil Dell** encendido, bloqueado, con BitLocker y conectado al dock | Memoria (procesos, VPN, sesión de OneDrive), disco cifrado, historial de USB conectados, navegación, correo |
| F2 | **Disco externo negro de 2 TB** en el dock | Copias del render u otros proyectos. **Propietario desconocido** |
| F3 | **iPhone de empresa** | WhatsApp con clientes (y quizá con Lucía), fotos, correo |
| F4 | **Móvil personal** en el bolso | Comunicaciones con Lucía. **No es de la empresa** |
| F5 | **Dock USB-C** | No guarda datos, pero alimenta el portátil: si se desconecta, el portátil puede apagarse o suspenderse |

### En la oficina, fuera de la mesa

| # | Fuente | Qué puede contener |
|---|---|---|
| F6 | **Pendrive de Javier** (en su cajón) | Ficheros copiados por Marta, aunque se hayan borrado |
| F7 | **El pendrive de Marta «que no funcionaba»** — no localizado | Posible soporte de la copia. Puede no haber estado nunca estropeado |
| F8 | **Sobremesa compartido de la entrada** (sesión de Outlook de otra compañera) | Escaneos e impresiones, posibles envíos de correo desde un equipo que no es el suyo |
| F9 | **Impresora multifunción** | Historial de trabajos; los escaneos van al correo de quien la usa |
| F10 | **Servidor de ficheros** del cuarto de informática | El render original, sus metadatos y, si hay auditoría, quién lo abrió o copió |
| F11 | **NAS de copias** (14 copias nocturnas) | El estado del servidor día a día: qué existía y cuándo |
| F12 | **Cortafuegos** | Conexiones salientes y de la VPN: subidas, horarios y accesos desde casa |

### En la nube y en manos de terceros

| # | Fuente | Titular | Qué puede contener |
|---|---|---|---|
| F13 | **Microsoft 365** de `mgarcia`: OneDrive, Outlook, registros de auditoría y de inicio de sesión | Almadraba (administra Bahía) | Ficheros compartidos o descargados, correos enviados, accesos desde dispositivos no corporativos |
| F14 | **Claves de recuperación de BitLocker** en el portal de Microsoft | Almadraba (administra Bahía) | Lo necesario para leer el disco de F1 si se apaga |
| F15 | **Bahía Sistemas**: configuración de la VPN y registros de su acceso remoto | Bahía | Conexiones de Marta en teletrabajo; también lo que haya hecho la propia Bahía en los equipos |
| F16 | **Cámara domo** del pasillo y su grabador en conserjería | Comunidad de propietarios | Entradas y salidas del día de la tarde larga |
| F17 | **La propuesta del estudio de Sevilla** tal como la recibió el cliente | El cliente hotelero | El render filtrado, con sus metadatos, para compararlo con el original |
| F18 | **Equipos de casa de Marta** (los viernes teletrabaja) | Marta | Fuera de alcance; ver límites |

### Personas (L4)

**Javier** (el día de la tarde larga y el pendrive), **Elena**, el **técnico de Bahía**, la **compañera** cuya sesión está abierta en el sobremesa y el **conserje** (grabador de la cámara). También **Marta**: hay que anotar literalmente lo que ha dicho del móvil personal y cómo ha reaccionado.

---

## 2. La prioridad

La ordeno por **cuándo se pierde** cada fuente, cruzado con su valor probable y el esfuerzo de obtenerla (L18, L19). La RAM es la primera, pero no la única que caduca.

| Orden | Fuente | Cuándo se pierde | Por qué va aquí |
|---|---|---|---|
| 1 | **F1 Portátil (memoria y estado)** | En minutos: si se apaga, se suspende, se desconecta el dock o Marta se lo lleva | La memoria es lo más volátil (RFC 3227 §2.1). Con BitLocker, apagarlo deja el disco cifrado y pierde la sesión y la VPN (L13) |
| 2 | **F3 iPhone de empresa** | En minutos: borrado remoto o que se lo lleve | Dispositivo inalámbrico que se puede borrar a distancia (L15) |
| 3 | **F2 Disco externo** y **F6 pendrive de Javier** | Hoy: se pueden llevar o reutilizar, y lo borrado se sobrescribe | Fácil de perder y muy alto valor probable (L18) |
| 4 | **F12 Log del cortafuegos** | **Hoy o mañana.** Guarda una semana: si los hechos fueron el 14, ese día está a punto de pisarse | Volatilidad que no es RAM: un registro que se sobrescribe (L19) |
| 5 | **F11 Copias del NAS** | **Esta noche** se borra la copia más antigua, que es de la época de la presentación del render | Copias que rotan; cada noche se pierde un día de la ventana (L19) |
| 6 | **F9 Historial de la impresora** | Con cada trabajo nuevo; capacidad desconocida | Registro que se sobrescribe con el uso diario de la oficina (L19) |
| 7 | **F8 Sobremesa compartido** | Hoy: lo usa todo el equipo y la sesión abierta se puede cerrar en cualquier momento | Cada uso altera la evidencia (L16) |
| 8 | **F16 Grabación de la cámara** | Como máximo un mes (art. 22.3 LOPDGDD, comprobar versión vigente); en la práctica, a menudo antes, según la capacidad del grabador | Grabación que caduca; depende de un tercero, así que hay que pedirla ya (L20) |
| 9 | **F13 Registros de Microsoft 365** | Según la licencia (días o meses) | Registros con retención limitada, además de que Marta puede borrar ficheros de OneDrive desde cualquier dispositivo (L19) |
| 10 | **F15 Registros de Bahía**, **F10 servidor** y **F14 claves** | Estables a corto plazo, salvo que Bahía haga mantenimiento | Bajo riesgo inmediato, pero hay que congelar cambios (L16) |
| 11 | **F17 Propuesta de Sevilla** | Estable | Bajo riesgo; basta con pedirla esta semana |
| — | **Testimonios** | La memoria de los testigos se degrada en días | Recoger hoy por escrito (L4) |
| — | **F4, F7, F18** | Fuera de mi alcance | Ver límites |

---

## 3. Las medidas inmediatas

| Fuente | Qué hago ahora | Lista |
|---|---|---|
| **F1 Portátil** | Que Marta no lo toque. Fotografiar la pantalla de bloqueo, el dock y las conexiones. **No apagar, no desconectar el dock** y comprobar que está enchufado. Pedir a Bahía la clave de recuperación de BitLocker antes de nada. Para capturar la memoria hace falta una sesión: decidirlo con Elena y Bahía, con herramientas desde un soporte propio, y documentar el cambio que introduce. Después, aislar de la red. | L3, L5, L7, L12, L13, L16, L21 |
| **F2 Disco externo** | Fotografiarlo conectado. Preguntar a Elena de quién es. Si es de la empresa: desconectarlo de forma segura del dock, embolsar, etiquetar y custodiar. No conectarlo a ningún equipo. | L5, L11, L14, L23 |
| **F3 iPhone de empresa** | Fotografiar sin desbloquear. Bolsa Faraday con el cargador, para que no se borre a distancia ni se quede sin batería. Etiquetar y custodiar. | L15, L23 |
| **F6 Pendrive de Javier** | Pedirle que lo entregue ahora y que confirme por escrito que no lo ha usado desde que se lo devolvió. Embolsar, etiquetar y abrir la cadena de custodia. | L9, L22, L23 |
| **F8 Sobremesa compartido** | Fotografiar la pantalla tal cual. No navegar por el correo de la compañera. Dejarlo fuera de uso hoy (avisar al equipo). | L7, L14, L16 |
| **F9 Impresora** | Pedir a Bahía que exporte hoy el historial de trabajos. Hasta entonces, no usarla. | L19, L20 |
| **F10 Servidor** | No tocarlo. Pedir a Bahía que no haga cambios, que exporte los registros de acceso si existen y que **no active la auditoría ahora** sin valorarlo antes: hacerlo después de los hechos puede alterar la evidencia y alertar (NIST §3.1.1). Calcular el hash del render original. | L16, L20, L22 |
| **F11 NAS** | Pedir a Bahía que **suspenda la rotación** antes de la copia de esta noche, o que copie aparte las más antiguas, documentándolo. | L19, L20 |
| **F12 Cortafuegos** | Pedir a Bahía que exporte hoy el log completo, con su hash, y que amplíe la retención. | L19, L20 |
| **F13 Microsoft 365** | Pedir a Bahía que exporte la auditoría, los inicios de sesión y la actividad de OneDrive de `mgarcia`, y que active la retención sobre su buzón y OneDrive. Que no se borre ni se deshabilite nada sin acordarlo. | L10, L11, L20 |
| **F15 Bahía** | Que todo acceso remoto a los equipos se haga coordinado conmigo y quede documentado. | L16, L22 |
| **F16 Cámara** | Elena pide **hoy por escrito** a la administración de la comunidad que conserve las grabaciones del 6 al 20 de marzo, sobre todo las tardes del 14 y del 16. | L10, L11, L20 |
| **F17 Propuesta de Sevilla** | Elena pide al cliente el documento tal como lo recibió (el fichero o el correo original, no una captura). | L10, L11 |
| **Personas** | Declaración escrita y firmada de Javier hoy. Anotar lo dicho por Marta y por el técnico de Bahía. | L4 |
| **Todo** | Notas con hora y desfase de reloj; croquis de la oficina; una etiqueta por pieza; cadena de custodia. | L2, L5, L22, L23 |

**Resumen de lo que hay que pedir a otros:** a **Bahía**, la clave de BitLocker y que exporte y conserve los logs del cortafuegos, la impresora, el NAS y Microsoft 365, sin tocar nada más. A la **comunidad**, que conserve las grabaciones. Al **cliente**, la propuesta original. A **Javier**, el pendrive y su declaración.

---

## 4. Los límites

| Lo que no puedo tocar | Por qué | Qué hago en su lugar |
|---|---|---|
| **El móvil personal de Marta (F4)** | No es de la empresa y protege su intimidad; la autorización de Elena no lo cubre | No tocarlo. Solo con su consentimiento libre, informado y por escrito, o con autorización judicial. Mientras tanto, fuentes alternativas: el iPhone de empresa y los inicios de sesión de Microsoft 365, que muestran desde qué dispositivos accedió (L11, L14) |
| **El bolso y el pendrive que falta (F7)** | No puedo registrar sus pertenencias | Preguntarle si quiere entregarlo voluntariamente. Si no, el análisis del portátil puede revelar el número de serie de los USB conectados (L9, L11) |
| **Retener a Marta** | No soy autoridad. Puede irse | Que se vaya es decisión de Elena con asesoría laboral. Si se va, **sin** el portátil, el iPhone ni el disco si son de la empresa. El acceso a dispositivos corporativos tiene límites (art. 87 LOPDGDD, comprobar versión vigente y si hay política de uso comunicada) (L1, L14) |
| **La contraseña del portátil** | Marta no está obligada a dármela | Acceso con una cuenta de administración a través de Bahía, como tercero de confianza (ENFSI §9.2), documentando la alteración. Si no es viable, mantenerlo encendido y aislado hasta decidirlo (L13) |
| **El correo de la compañera en el sobremesa (F8)** | Datos de otra persona sin relación con los hechos | Fotografiar la pantalla y preservar el equipo. Su buzón solo si aparecen indicios que lo justifiquen (L14) |
| **La grabación de la cámara (F16)** | No es de Almadraba: la gestiona la comunidad | Petición de conservación por escrito; si no colaboran, a través de denuncia y juzgado (L11, L20) |
| **El estudio de Sevilla y Lucía** | Fuera de la organización | Solo por vía judicial. Mientras, el documento que tiene el cliente (L11) |
| **Los equipos de casa de Marta (F18)** | Fuera del control de la organización | Alternativa: logs de la VPN y de Microsoft 365, que registran esos accesos (L10, L11) |
| **El disco externo (F2), si es personal** | Mismo caso que el móvil | Consentimiento o autorización judicial; mientras, que no salga de la oficina si Elena puede pedirlo legítimamente (L14) |
| **Analizar ahora** | Analizar en el original altera fechas de acceso | Recoger primero, analizar después y siempre sobre una copia (L22) |

---

## 5. De dónde sale cada decisión

| Decisión | Lista | Norma |
|---|---|---|
| Confirmar la fecha del 14 con Javier y anotar horas y desfase | L2, L4 | RFC 3227 §2, §3.2 |
| Apartar a Marta del portátil y el móvil | L3 | NIST §3.1.3 · ENFSI §8.2 |
| Recoger la declaración de Javier y anotar lo que dijo Marta | L4 | RFC 3227 §3.2 |
| Fotografiar y hacer un croquis de la mesa, el sobremesa y el cuarto de informática | L5, L7 | ENFSI §8.2 · NIST §3.1.2 |
| Buscar más allá de la mesa: pendrives, impresora, servidor, NAS, cortafuegos | L6, L8, L9 | ENFSI §8.2 · NIST §3.1.1 · RFC 3227 §3.2 |
| Incluir la nube, Bahía, la cámara y el cliente | L10 | NIST §3.1.1 |
| Anotar el titular de cada fuente y buscar alternativas a lo inaccesible | L11 | NIST §3.1.1 |
| No apagar el portátil y conseguir la clave de BitLocker | L12, L13 | ENFSI §9.1, §9.2 · RFC 3227 §2.2 |
| No tocar el móvil personal ni el correo de la compañera | L14 | NIST §3.1.1 · RFC 3227 §2.3 |
| iPhone en bolsa Faraday con alimentación | L15 | ENFSI §8.2 |
| Aislar el portátil solo después de capturar la memoria; congelar cambios de Bahía | L16 | RFC 3227 §2.2 · NIST §3.1.3 |
| Incluir fuentes de valor dudoso (dock, sobremesa compartido) en vez de descartarlas | L17 | RFC 3227 §3.2 |
| Priorizar el cortafuegos, el NAS y la impresora por encima del disco | L18, L19 | NIST §3.1.2 |
| Pedir hoy la conservación a Bahía, la comunidad y el cliente | L20 | NIST §3.1.1, §3.1.2 |
| Memoria antes que disco en el portátil | L21 | RFC 3227 §2.1 |
| Cadena de custodia y no analizar sobre el original | L22 | RFC 3227 §2, §2.4 · NIST §3.1.2 |
| Etiquetar cada pieza | L23 | ENFSI §8.2 |
