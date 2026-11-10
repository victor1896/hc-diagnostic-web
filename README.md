# HC Diagnostic E.I.R.L. — sitio web inicial

## Contenido
- `index.html`: página institucional adaptable a computadora, tablet y celular.
- Incluye áreas de servicio, contacto por WhatsApp y una pantalla demostrativa de verificación.

## Publicar con GitHub Pages
1. Crear un repositorio **público** llamado `hc-diagnostic-web` (GitHub Free requiere repositorio público para GitHub Pages).
2. Subir `index.html` a la raíz del repositorio.
3. Abrir **Settings → Pages**.
4. En **Build and deployment**, elegir **Deploy from a branch**.
5. Seleccionar la rama `main` y la carpeta `/ (root)`, guardar.
6. Esperar a que GitHub Pages publique el sitio.

## Importante antes de usar con pacientes
La verificación de resultados de este prototipo es solo visual y siempre devuelve `NO ENCONTRADO`. No contiene base de datos ni valida resultados reales. Para operar con pacientes se necesita un backend con autenticación, control de acceso, almacenamiento seguro, auditoría y protección de datos personales. No subir informes, nombres, DNI ni resultados clínicos a este repositorio público.

## Personalización pendiente
- Reemplazar el monograma provisional `HC` por el logo original proporcionado por el propietario, sin modificarlo.
- Confirmar dirección, horarios y canales oficiales antes de publicarlos.
- Implementar el sistema seguro de verificación y QR antes de anunciarlo como funcional.
