# Brainstormings · Estudio Ideamia

Votación de ideas y pizarrón de la reunión de brainstorming.

- **La página** (`index.html` + `config.js`) vive en GitHub Pages.
- **Los datos** viven en Google: un Apps Script ("Servidor brainstormings Ideamia", cuenta ideamia.contacto)
  que guarda todo en la planilla "Brainstormings Ideamia · datos". Su dirección (`/exec`) va en `config.js`.
- Las contraseñas del DC y del SMM están en el Apps Script: Configuración del proyecto → Propiedades del script
  (`DC_PASSWORD`, `SMM_PASSWORD`). No van en este repositorio.

## Actualizar
- Cambios en la página: subir el `index.html` nuevo acá (Add file → Upload files).
- Cambios en el servidor: pegar `apps-script/Code.js` + `apps-script/Backend.js` en el Apps Script y
  hacer Implementar → Gestionar implementaciones → editar → Nueva versión (así la dirección no cambia).

## La reunión en la web
0. SMM: crea la campaña y escribe el brief (fecha y hora de reunión). Aparece en "Próximos brainstormings".
1. DC: abre la campaña y arranca el reloj. Fase 1: cada uno anota solo, en papel.
2. DC: "Siguiente fase". Cada uno lee sus cinco y el DC las carga en el Pizarrón (una columna y un color por persona).
   Ronda 2: se mueven, se agrandan y se cruzan las notas como en Miro (el equipo también, si está habilitado).
   Ronda 3: "Hacer final" con las cuatro preguntas.
3. DC: "Pasar finales a votación" → "Activar votación" → manda el enlace por WhatsApp.
4. DC: da vuelta los papeles y elige una o varias. Las otras van al cementerio y se pueden usar en otra campaña.
