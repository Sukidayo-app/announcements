---
layout: default
title: Preguntas frecuentes
lang: es
---
<style>
  .page-title { font-size: 24px; font-weight: 700; margin-bottom: 20px; }
  .toc { background: #fafafa; border: 1px solid #e8e8e8; border-radius: 10px; padding: 20px 24px; margin-bottom: 32px; }
  .toc-title { font-size: 14px; font-weight: 700; margin-bottom: 10px; color: #666; }
  .toc ul { list-style: none; padding-left: 0; margin: 0; }
  .toc li { font-size: 14px; margin-bottom: 4px; }
  .toc a { color: #EE8514; text-decoration: none; }
  .toc a:hover { text-decoration: underline; }
  .toc > ul > li { margin-bottom: 2px; }
  .toc details > summary {
    font-size: 14px; font-weight: 600; color: #EE8514; cursor: pointer;
    list-style: none; padding: 5px 0; display: flex; align-items: flex-start; gap: 7px;
  }
  .toc details > summary::-webkit-details-marker { display: none; }
  .toc details > summary::before {
    content: "\25B6"; font-size: 9px; line-height: 2.1; color: #EE8514;
    flex: 0 0 auto; transition: transform .15s ease;
  }
  .toc details[open] > summary::before { transform: rotate(90deg); }
  .toc details > summary:hover { text-decoration: underline; }
  .toc details > ul { padding-left: 20px; margin: 2px 0 10px; }
  .toc details > ul > li { font-size: 13.5px; margin-bottom: 7px; line-height: 1.55; }
  .toc details a { color: #555; }
  .toc details a:hover { color: #EE8514; }
  .faq-body h2, .faq-body h3 { scroll-margin-top: 16px; }
  .faq-body h2 { font-size: 18px; font-weight: 700; margin: 32px 0 12px; padding-bottom: 8px; border-bottom: 2px solid #f0f0f0; }
  .faq-body h3 { font-size: 16px; font-weight: 700; margin: 20px 0 6px; color: #EE8514; }
  .faq-body h3::before { content: "Q. "; }
  .faq-body h3 + p::before { content: "A. "; font-weight: bold; }
  .faq-body p { font-size: 15px; margin-bottom: 12px; }
  .faq-body ul, .faq-body ol { padding-left: 24px; margin-bottom: 12px; font-size: 15px; }
  .faq-body li { margin-bottom: 4px; }
  .faq-body a { color: #EE8514; }
  .faq-body blockquote { background: #f5f5f5; border-left: 4px solid #EE8514; padding: 12px 16px; border-radius: 4px; margin-bottom: 12px; font-size: 14px; }
  .faq-body table { border-collapse: collapse; width: 100%; margin-bottom: 16px; font-size: 14px; }
  .faq-body th, .faq-body td { border: 1px solid #eee; padding: 8px 12px; }
  .faq-body th { background: #f9f9f9; }
  @media (max-width: 600px) {
    .page-title { font-size: 20px; }
    .toc { padding: 16px 18px; }
    .toc details > summary { font-size: 13.5px; }
    .toc details > ul > li { font-size: 13px; }
    .faq-body h2 { font-size: 16px; }
    .faq-body h3 { font-size: 15px; }
    .faq-body p, .faq-body ul, .faq-body ol { font-size: 14px; }
    .faq-body table { display: block; overflow-x: auto; -webkit-overflow-scrolling: touch; }
  }
</style>

<div class="page-title">Preguntas frecuentes</div>
{% include lang-tabs.html section="faq" lang="es" %}

<div class="toc">
  <div class="toc-title">📖 Índice</div>
  <ul>
    <li>
      <details>
        <summary>🐾 Primeros pasos</summary>
        <ul>
          <li><a href="#q-how-to-start">¿Cómo empiezo?</a></li>
          <li><a href="#q-change-profile">¿Puedo cambiar mi nombre, género o el nombre del animal más adelante?</a></li>
          <li><a href="#q-no-notifications">No recibo notificaciones. ¿Qué hago?</a></li>
          <li><a href="#q-no-questions">No recibo preguntas. ¿Qué hago?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>📝 Q&amp;A, Quiz de pareja y respuestas</summary>
        <ul>
          <li><a href="#q-see-results">¿Cómo veo los resultados?</a></li>
          <li><a href="#q-edit-answer">Respondí por error. ¿Puedo volver a hacerlo?</a></li>
          <li><a href="#q-comment-notification">¿Mi pareja recibirá una notificación cuando comente una respuesta?</a></li>
          <li><a href="#q-partner-only-question">Mi pareja recibió la última pregunta pero yo no.</a></li>
          <li><a href="#q-past-answers-missing">Mis respuestas y resultados anteriores han desaparecido.</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>📷 Nuestros recuerdos</summary>
        <ul>
          <li><a href="#q-memory-when">¿Cuándo puedo empezar a añadir el recuerdo de este mes?</a></li>
          <li><a href="#q-memory-edit">¿Puedo editar un recuerdo que ya añadí?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>🛠 Ajustes y funciones</summary>
        <ul>
          <li><a href="#q-delivery-time">¿Puedo cambiar la hora de entrega de las preguntas?</a></li>
          <li><a href="#q-logout">¿Cómo cierro sesión?</a></li>
          <li><a href="#q-transfer-data">¿Cómo transfiero mis datos a un nuevo dispositivo?</a></li>
          <li><a href="#q-fresh-start-screen">Inicié sesión tras cambiar de dispositivo pero empieza desde cero.</a></li>
          <li><a href="#q-cohabitation">¿Puedo cambiar mi situación de convivencia?</a></li>
          <li><a href="#q-future-anniversary">¿Puedo establecer una fecha futura para un aniversario?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>📅 Aniversarios</summary>
        <ul>
          <li><a href="#q-fixed-anniversary">Hay aniversarios que no puedo eliminar ni cambiar de nombre. ¿Por qué?</a></li>
          <li><a href="#q-anniversary-order">Quiero cambiar el orden de mis aniversarios.</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>💌 Tarjetas de mensaje</summary>
        <ul>
          <li><a href="#q-card-edit">¿Puedo editar o eliminar una tarjeta de mensaje que ya se envió?</a></li>
          <li><a href="#q-card-timezone">Mi pareja y yo vivimos lejos. ¿Qué zona horaria se usa para la hora de entrega de las tarjetas?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>🚪 Eliminar cuenta y desvincular pareja</summary>
        <ul>
          <li><a href="#q-delete-account">¿Cómo elimino mi cuenta?</a></li>
          <li><a href="#q-unpair">¿Cómo me desvinculo de mi pareja?</a></li>
          <li><a href="#q-partner-deleted">¿Qué pasa si mi pareja elimina su cuenta?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>💳 Suscripción</summary>
        <ul>
          <li><a href="#q-sub-features">¿Qué funciones incluye la suscripción?</a></li>
          <li><a href="#q-sub-both">¿Necesitamos los dos una suscripción?</a></li>
          <li><a href="#q-sub-cancel">¿Cómo cancelo mi suscripción?</a></li>
          <li><a href="#q-sub-cancel-timing">¿Las funciones premium se desactivan inmediatamente al cancelar?</a></li>
          <li><a href="#q-sub-after-cancel">¿Perderé el acceso a las funciones de pago que estaba utilizando (como las respuestas a preguntas de pago o las categorías añadidas a «Cosas que quiero hacer») después de cancelar?</a></li>
          <li><a href="#q-sub-device-change">Si cambio de dispositivo durante el periodo de suscripción, ¿se transferirá la suscripción?</a></li>
          <li><a href="#q-sub-not-working">Tengo suscripción pero las funciones premium no funcionan.</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>🎁 Decoraciones y sorpresas</summary>
        <ul>
          <li><a href="#q-furniture-unlock">¿Cómo desbloqueo más muebles y objetos?</a></li>
          <li><a href="#q-furniture-countdown">La cuenta regresiva de muebles ha desaparecido. ¿Por qué?</a></li>
        </ul>
      </details>
    </li>
    <li>
      <details>
        <summary>❓ Otros</summary>
        <ul>
          <li><a href="#q-skip-question">¿Qué hago si una pregunta me parece difícil o no tengo ganas?</a></li>
          <li><a href="#q-ads">He visto un anuncio desagradable. ¿Podéis hacer algo al respecto?</a></li>
        </ul>
      </details>
    </li>
  </ul>
</div>

<div class="faq-body" markdown="1">

## 🐾 Primeros pasos {#primeros-pasos}

### ¿Cómo empiezo? {#q-how-to-start}

Así es como puedes empezar:

**La persona que envía la invitación:**
1. Inicia sesión y pulsa «Empezar de cero»
2. Introduce tu perfil y elige tu animal
3. Responde la primera pregunta
4. Invita a tu pareja
5. Tras el tutorial, recibiréis preguntas a una hora fija 💌

**La persona que recibe la invitación:**
1. Pulsa «Empezar con código de invitación» e introduce el código
2. Introduce tu perfil y elige tu animal
3. Responde la primera pregunta
4. Tras el tutorial, recibiréis preguntas a una hora fija 💌

### ¿Puedo cambiar mi nombre, género o el nombre del animal más adelante? {#q-change-profile}

Sí — desde Mi página (icono del menú arriba a la derecha) → Ajustes → Ajustes básicos. El tipo y color del animal no pueden cambiarse.

### No recibo notificaciones. ¿Qué hago? {#q-no-notifications}

Ve a los ajustes de tu dispositivo y activa las notificaciones de Riamo.

### No recibo preguntas. ¿Qué hago? {#q-no-questions}

Es posible que tu pareja aún no haya respondido. La siguiente pregunta se envía a la hora de entrega programada, una vez que ambos habéis respondido.

---

## 📝 Q&A, Quiz de pareja y respuestas {#preguntas}

### ¿Cómo veo los resultados? {#q-see-results}

Los resultados se muestran cuando ambos habéis respondido. Si respondes primero, la respuesta de tu pareja estará oculta hasta que ella responda.

### Respondí por error. ¿Puedo volver a hacerlo? {#q-edit-answer}

Solo las respuestas de Q&A pueden editarse. Las del Quiz de pareja no pueden cambiarse.

### ¿Mi pareja recibirá una notificación cuando comente una respuesta? {#q-comment-notification}

Sí, recibirá una notificación push y una insignia roja dentro de la app.

### Mi pareja recibió la última pregunta pero yo no. {#q-partner-only-question}

Puede ser un error — contáctanos desde Menú → Contáctanos.

### Mis respuestas y resultados anteriores han desaparecido. {#q-past-answers-missing}

Puede ocurrir temporalmente por congestión de red. Vuelve a abrir la app. Si persiste un día después, contáctanos.

---

## 📷 Nuestros recuerdos {#recuerdos}

### ¿Cuándo puedo empezar a añadir el recuerdo de este mes? {#q-memory-when}

Puedes subir los recuerdos del mes actual desde el día 1 de cada mes. Usa el botón + en Nuestros registros → pestaña Recuerdos para añadirlos. Además, del 25 a las 12:00 hasta el 3 del mes siguiente a las 23:59, también aparece un banner en la pantalla de inicio.

### ¿Puedo editar un recuerdo que ya añadí? {#q-memory-edit}

Puedes editar las fotos y la «nota del recuerdo». Selecciona el recuerdo y pulsa el icono de edición (lápiz). Los comentarios no pueden editarse.

---

## 🛠 Ajustes y funciones {#ajustes}

### ¿Puedo cambiar la hora de entrega de las preguntas? {#q-delivery-time}

Solo la persona que envió la invitación puede cambiarlo. Se ajusta en incrementos de 1 hora. Mi página (icono del menú arriba a la derecha) → Ajustes → Ajustes básicos → Hora de entrega.

### ¿Cómo cierro sesión? {#q-logout}

Mi página (icono del menú arriba a la derecha) → Otros → Cerrar sesión. Una vez mostrada la pantalla de confirmación, volverás a la pantalla de inicio de la aplicación.

### ¿Cómo transfiero mis datos a un nuevo dispositivo? {#q-transfer-data}

Puedes transferir tus datos iniciando sesión con la misma cuenta que utilizaste en tu dispositivo anterior. Si inicias sesión con una cuenta diferente, se tratará como una cuenta nueva y tus datos anteriores no se trasladarán.

- Si usaste Google para iniciar sesión, inicia sesión con la misma cuenta de Google en ambos dispositivos
- Si usaste Apple para iniciar sesión, inicia sesión con el mismo Apple ID en ambos dispositivos

### Inicié sesión tras cambiar de dispositivo pero empieza desde cero. {#q-fresh-start-screen}

Si inicias sesión con una cuenta diferente a la que usabas antes, el tutorial comenzará como si fueras un usuario nuevo.

Si inicias sesión con la misma cuenta que usabas anteriormente, la pantalla de inicio de Riamo debería aparecer inmediatamente. Si no aparece, es posible que hayas iniciado sesión con una cuenta diferente. Prueba a iniciar sesión con otra cuenta.

Si accidentalmente empezaste con una cuenta nueva, cierra sesión o elimina la cuenta desde el menú de tres puntos (…) en la esquina superior derecha de la pantalla del tutorial, confirma qué cuenta debes usar y vuelve a iniciar sesión.

### ¿Puedo cambiar mi situación de convivencia? {#q-cohabitation}

Sí, puedes cambiarlo siguiendo los pasos a continuación.

Mi página (icono de engranaje en la esquina superior derecha) → Menú → Configuración básica → Información de pareja → Situación de convivencia

A partir del siguiente horario de entrega tras el cambio, recibirás preguntas adaptadas a tu nueva situación de convivencia.

### ¿Puedo establecer una fecha futura para un aniversario? {#q-future-anniversary}

Lo sentimos, las fechas futuras no están disponibles en este momento.

---

## 📅 Aniversarios {#aniversarios}

### Hay aniversarios que no puedo eliminar ni cambiar de nombre. ¿Por qué? {#q-fixed-anniversary}

Los siguientes cuatro aniversarios se crean automáticamente como predeterminados y no pueden eliminarse ni renombrarse: Aniversario de pareja, Tu cumpleaños, Cumpleaños de tu pareja y el Día que empezaste a usar Riamo.

### Quiero cambiar el orden de mis aniversarios. {#q-anniversary-order}

Los aniversarios se ordenan automáticamente por la fecha más próxima y no pueden reordenarse manualmente.

---

## 💌 Tarjetas de mensaje {#tarjeta-mensaje}

### ¿Puedo editar o eliminar una tarjeta de mensaje que ya se envió? {#q-card-edit}

Las tarjetas de mensaje enviadas no pueden editarse ni eliminarse. Las tarjetas programadas pueden editarse o eliminarse antes de su entrega.

### Mi pareja y yo vivimos lejos. ¿Qué zona horaria se usa para la hora de entrega de las tarjetas? {#q-card-timezone}

La hora de entrega programada se basa en la zona horaria del destinatario. Por ejemplo, si configuras la entrega a las 8:00, la tarjeta llegará a las 8:00 en la hora local de tu pareja.

---

## 🚪 Eliminar cuenta y desvincular pareja {#cuenta}

### ¿Cómo elimino mi cuenta? {#q-delete-account}

En Riamo no utilizamos un sistema de "darse de baja". En su lugar, puedes eliminar tu cuenta directamente desde la aplicación:

Mi página (icono del menú arriba a la derecha) → Ajustes → Gestión de cuenta → Eliminar cuenta

Ten en cuenta que, al eliminar tu cuenta, todos tus datos de respuestas serán borrados y no será posible recuperarlos posteriormente. Además, las suscripciones no se cancelan automáticamente. Debes completar el proceso de cancelación por separado.

[Relacionado: ¿Cómo puedo cancelar mi suscripción?](#suscripcion)

### ¿Cómo me desvinculo de mi pareja? {#q-unpair}

Riamo está diseñado para usarse en pareja, por lo que no ofrecemos una opción para "desvincular" cuentas. En su lugar, guiamos a los usuarios al proceso de baja, incluida la eliminación de la cuenta.

Artículos relacionados:
- [¿Qué ocurre si mi pareja elimina su cuenta?](#cuenta)
- [¿Cómo puedo darme de baja o eliminar mi cuenta?](#cuenta)

### ¿Qué pasa si mi pareja elimina su cuenta? {#q-partner-deleted}

Riamo está diseñado para utilizarse por parejas. Una vez disuelta la pareja (tras la eliminación de la cuenta de tu pareja), no podrás utilizar el servicio de forma independiente.

Cuando tu pareja elimina su cuenta, aparecerá una notificación en tu pantalla informándote de la eliminación y solicitándote la aprobación para la eliminación de tu cuenta.

Por ejemplo, en el caso de una pareja A y B:
- La persona A elimina su cuenta
- Aparecerá una notificación en la pantalla de Riamo de B informándole de la eliminación de la cuenta de A y solicitando el consentimiento de B para eliminar su propia cuenta, ya que no será posible seguir utilizándola en el futuro

---

## 💳 Suscripción {#suscripcion}

### ¿Qué funciones incluye la suscripción? {#q-sub-features}

Las funciones incluidas son las siguientes:

- Experiencia sin anuncios
- Más temas del Quiz de pareja disponibles
- Personalización de la Lista de deseos
- Más fotos disponibles en «Nuestros recuerdos» mensuales
- Más recuerdos que puedes registrar al cumplir deseos de tu lista

### ¿Necesitamos los dos una suscripción? {#q-sub-both}

No — si cualquiera de los dos se suscribe, ambos disfrutáis de las funciones premium.

### ¿Cómo cancelo mi suscripción? {#q-sub-cancel}

Esto debe hacerse a través de Google Play o la App Store, no dentro de la aplicación Riamo. Para obtener más información, consulta las páginas siguientes.

- [Cancelar, pausar o cambiar una suscripción de Google Play (Centro de ayuda de Google Play)](https://support.google.com/googleplay/answer/7018481)
- [Cómo cancelar una suscripción en Apple (Soporte técnico de Apple)](https://support.apple.com/es-es/118428)

### ¿Las funciones premium se desactivan inmediatamente al cancelar? {#q-sub-cancel-timing}

Aunque canceles a mitad de periodo, podrás seguir utilizando las funciones de pago hasta la siguiente fecha de renovación. Ejemplo: para una suscripción válida hasta el 31 de julio, si cancelas el 29 de julio, podrás seguir utilizándola hasta el día 31.

### ¿Perderé el acceso a las funciones de pago que estaba utilizando (como las respuestas a preguntas de pago o las categorías añadidas a «Cosas que quiero hacer») después de cancelar? {#q-sub-after-cancel}

Los resultados de diagnósticos de pareja de pago que ya hayas recibido seguirán estando accesibles después de la cancelación. Sin embargo, las categorías añadidas a tu lista «Cosas que quiero hacer» durante el periodo de suscripción ya no se podrán ver tras la cancelación. Tras la cancelación, los elementos de la lista de deseos contenidos en las categorías añadidas quedarán ocultos.

### Si cambio de dispositivo durante el periodo de suscripción, ¿se transferirá la suscripción? {#q-sub-device-change}

La información del contrato de suscripción está vinculada a la cuenta de App Store/Google Play utilizada en el momento de la compra, no a tu cuenta de inicio de sesión de Riamo. Después de cambiar de dispositivo, inicia sesión en App Store/Google Play con la misma cuenta utilizada para la compra y, a continuación, selecciona [Restaurar compra] en la pantalla de compra de la suscripción.

※ Las suscripciones no se pueden transferir entre diferentes sistemas operativos (Android → iOS / iOS → Android). En tales casos, cancela la suscripción en la tienda donde se compró originalmente y vuelve a comprarla en la tienda de tu nuevo sistema operativo.

- [Cancelar, pausar o cambiar una suscripción de Google Play (Centro de ayuda de Google Play)](https://support.google.com/googleplay/answer/7018481)
- [Cómo cancelar una suscripción en Apple (Soporte técnico de Apple)](https://support.apple.com/es-es/118428)

### Tengo suscripción pero las funciones premium no funcionan. {#q-sub-not-working}

La información del contrato de suscripción está vinculada a la cuenta de App Store/Google Play utilizada en el momento de la compra, no a tu cuenta de inicio de sesión de Riamo. Comprueba que la cuenta de la tienda es la que está suscrita al servicio. Si estás utilizando la cuenta correcta y sigues sin poder acceder a las funciones de pago, ponte en contacto con el servicio de asistencia a través de Mi página (icono del menú arriba a la derecha) → [Contactar con nosotros].

---

## 🎁 Decoraciones y sorpresas {#sorpresas}

### ¿Cómo desbloqueo más muebles y objetos? {#q-furniture-unlock}

Se añaden nuevos muebles a medida que respondéis las preguntas juntos. Podéis comprobar cuántas preguntas faltan para el siguiente mueble en el contador "○ preguntas para el siguiente mueble" que aparece en la pantalla de inicio.

### La cuenta regresiva de muebles ha desaparecido. ¿Por qué? {#q-furniture-countdown}

Actualmente, la obtención de muebles finaliza cuando habéis respondido un número determinado de preguntas. Una vez que habéis conseguido todos los muebles disponibles, la cuenta regresiva deja de aparecer.

Ten en cuenta que está previsto un rediseño en el futuro, que incluirá cambios en la colocación de muebles y objetos, así como en la forma de obtenerlos.

---

## ❓ Otros {#otros}

### ¿Qué hago si una pregunta me parece difícil o no tengo ganas? {#q-skip-question}

No hay presión. Un simple «lo intentamos mañana» está bien. Id a vuestro propio ritmo.

### He visto un anuncio desagradable. ¿Podéis hacer algo al respecto? {#q-ads}

Lamentamos mucho las molestias. Tenemos configuraciones de bloqueo para evitar anuncios de categorías inapropiadas. Sin embargo, cuando la propia aplicación anunciada se distribuye como herramienta de seguridad o de IA, por ejemplo, no siempre es posible detectar de antemano si el contenido del anuncio utiliza un lenguaje alarmista o engañoso. Si ves un anuncio malintencionado, haz una captura de pantalla y contacta con nosotros a través del formulario de consulta.

Ten en cuenta que los anuncios y las funciones de pago nos ayudan a mantener un funcionamiento estable y a seguir desarrollando nuevas funciones. Agradecemos tu comprensión.

---

## 📮 ¿Sigues necesitando ayuda?

Contáctanos desde Menú → Contáctanos.

</div>
