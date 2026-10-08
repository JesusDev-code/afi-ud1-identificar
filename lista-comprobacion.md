# Lista de comprobación: identificar antes de tocar

Normas: **RFC 3227**, **NIST SP 800-86** y **ENFSI BPM-FIT-01**. Cada punto se cita en el plan como **L1…L23**.

## Al llegar

- [ ] **L1.** Confirmar la autorización firmada y su alcance; avisar a quien proceda (dirección, fuerzas de seguridad). — *RFC 3227 §2 · ENFSI §8.2*
- [ ] **L2.** Abrir notas con fecha y hora; anotar el desfase del reloj respecto a UTC. — *RFC 3227 §2*
- [ ] **L3.** Asegurar la escena y apartar al sospechoso y a los testigos de los dispositivos y de lo que pueda comunicarse con ellos. — *NIST §3.1.3 · ENFSI §8.2*
- [ ] **L4.** Anotar quién está presente, qué hacía, qué vio y cómo reaccionó. — *RFC 3227 §3.2*
- [ ] **L5.** Fotografiar y hacer un croquis con la ubicación y el estado de cada elemento. — *ENFSI §8.2 · NIST §3.1.2*
- [ ] **L6.** Recorrer la escena de forma sistemática, empezando por las zonas más probables según los hechos. — *ENFSI §8.2*

## Antes de tocar nada

- [ ] **L7.** Fotografiar lo que muestra cada pantalla, incluida la de bloqueo. — *NIST §3.1.2*
- [ ] **L8.** Inventariar las fuentes físicas: equipos, portátiles, almacenamiento en red, extraíbles, móviles, cámaras. — *NIST §3.1.1*
- [ ] **L9.** Preguntar por los soportes que no están a la vista: prestados, perdidos, «estropeados», usados fuera. — *RFC 3227 §3.2*
- [ ] **L10.** Identificar las fuentes fuera de la escena: servidores, nube, logs de red, copias de seguridad, ISP, teletrabajo. — *NIST §3.1.1*
- [ ] **L11.** Anotar el propietario de cada fuente, qué hace falta para obtenerla y una alternativa si no es accesible. — *NIST §3.1.1*
- [ ] **L12.** Anotar el estado de cada dispositivo: encendido, alimentación, red, wifi, VPN, periféricos. — *ENFSI §9.2 · NIST §3.1.3*
- [ ] **L13.** Ante cifrado activo o borrado remoto: no apagar y localizar quién custodia las claves. — *ENFSI §9.1, §9.2 · RFC 3227 §2.2*
- [ ] **L14.** Equipos personales, de terceros o datos de otras personas: comprobar la base legal antes de tocarlos. — *NIST §3.1.1 · RFC 3227 §2.3*
- [ ] **L15.** Móviles e inalámbricos: bolsa Faraday o apagado según procedimiento, vigilando la batería. — *ENFSI §8.2*
- [ ] **L16.** Decidir con la organización cómo cortar las vías externas de cambio, valorando *deadman switches* e impacto en el trabajo. — *RFC 3227 §2.2 · NIST §3.1.3*

## Al decidir qué se adquiere y en qué orden

- [ ] **L17.** Listar los sistemas implicados y qué es relevante y admisible; en caso de duda, recoger de más. — *RFC 3227 §3.2*
- [ ] **L18.** Priorizar cada fuente por valor probable, volatilidad y esfuerzo. — *NIST §3.1.2*
- [ ] **L19.** Estimar cuándo se pierde cada fuente no volátil: logs que se sobrescriben, copias que rotan, grabaciones que se borran. — *NIST §3.1.2*
- [ ] **L20.** Pedir hoy a los terceros que conserven lo que rota; lo que exija orden judicial, a través de las fuerzas de seguridad. — *NIST §3.1.1, §3.1.2*
- [ ] **L21.** En cada equipo, seguir el orden de volatilidad: memoria → temporales → disco → logs remotos → configuración → archivo. — *RFC 3227 §2.1*
- [ ] **L22.** Recoger primero y analizar después; preservar como si fuera a juicio, con custodio y cadena de custodia. — *RFC 3227 §2, §2.4 · NIST §3.1.2*
- [ ] **L23.** Etiquetar cada pieza: referencia única, descripción, lugar, responsable, fecha y hora. — *ENFSI §8.2*
