# landing-baltodano

Landing de demostración para el **Bufete del Lic. Oscar Felipe Baltodano Valverde**, abogado en San José, Costa Rica.

Sitio estático de una sola página (`index.html`, CSS y JS inline), mobile first, con estética sobria: azul marino, gris y acento dorado sobre blanco, tipografía serif clásica.

## Contenido

- **Presentación del despacho** y del licenciado Baltodano Valverde, con trato directo y consulta presencial o virtual.
- **Agenda de consulta en línea** interactiva: modalidad (presencial / virtual) → día hábil → horario de 45 minutos → datos de contacto → confirmación con resumen de la cita.
  - Botón que abre **WhatsApp con el mensaje ya redactado** (modalidad, día, hora, nombre, teléfono y tema).
  - Botón **«Agregar al calendario»** que genera un archivo `.ics` en el navegador.
- **Recordatorios automáticos por WhatsApp**: al reservar, 24 horas antes, el mismo día y después de la consulta.
- **De la consulta a la cita**: recorrido en cuatro pasos del mensaje inicial a la cita confirmada.
- **Valoración real**: 5.0 ★ con 10 reseñas en Google, con enlace al perfil público.
- **Ubicación** en San José con mapa y WhatsApp **+506 8631 0255** (`wa.me/50686310255`).

## Notas de la demostración

- No se listan especialidades concretas: el sitio indica que el despacho trabaja en distintas áreas del derecho y que cada caso se evalúa en la consulta inicial.
- Los horarios de la agenda son ilustrativos. La reserva no se almacena en ningún servidor: se envía al despacho por WhatsApp desde el teléfono del usuario y queda sujeta a confirmación.
- La dirección exacta del despacho se comparte al confirmar la cita.
- No hay promesas de resultados ni cifras que no provengan de la ficha pública de Google.

## Despliegue

Se construye con un `Dockerfile` de dos líneas (`nginx:alpine` + copia de los archivos) y se publica en EasyPanel desde este repositorio (rama `main`).

Sitio de referencia hecho por Nocodeveloper.