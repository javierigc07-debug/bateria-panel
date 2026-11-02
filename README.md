# bateria-panel

Panel para ver desde el móvil el estado de las baterías de casa.

La Raspberry Pi sube un resumen **cifrado** (AES-256-GCM, clave PBKDF2-SHA256) a un Gist secreto.
Esta página lo descarga y lo descifra en el propio navegador con la contraseña; en este repositorio
no hay datos, claves ni el código del Gist (va en el enlace, después de `#`).
