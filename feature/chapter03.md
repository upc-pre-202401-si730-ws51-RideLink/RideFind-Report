# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

- **Primer segmento: Usuario que Alquila**

<br><img src="./img/Chapter03/Tobe1.jpg" alt="To Be Scenario Map 1" style="width: 1000px; height: auto;" ><br>

- **Segundo segmento: Propietario de Vehículos alternativos**

<br><img src="./img/Chapter03/tobe2.jpg" alt="To Be Scenario Map 2" style="width: 1000px; height: auto;" ><br>


## 3.2. User Stories.


<!-- Tabla para Epic01 -->
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Descripción del Epic</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic01</td>
      <td>Como usuario, deseo explorar las secciones principales de la Landing Page</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US01</td>
      <td>Barra de navegación en la Landing Page</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Sección de beneficios en la Landing Page</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Sección de nosotros en la Landing Page</td>
    </tr>
    <tr>
      <td>US04</td>
      <td>Sección de redes sociales/Footer</td>
    </tr>
    <tr>
      <td>US05</td>
      <td>Sección de contacto en la Landing Page</td>
    </tr>
  </tbody>
</table>

<!-- Tabla para Epic02 -->
<br>
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Descripción del Epic</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic02</td>
      <td>Como usuario, deseo poder registrarme e iniciar sesión en la aplicación fácilmente</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US06</td>
      <td>Registro de cuenta</td>
    </tr>
    <tr>
      <td>US07</td>
      <td>El usuario va a registrar y vincular su cuenta usando Google o Outlook</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Inicio de sesión</td>
    </tr>
  </tbody>
</table>

<br>
<!-- Tabla para Epic03 -->
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Descripción del Epic</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic03</td>
      <td>Como usuario, deseo poder visualizar y filtrar los vehículos disponibles en la plataforma</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US09</td>
      <td>Ver vehículos disponibles</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Filtro de búsqueda de vehículos</td>
    </tr>
  </tbody>
</table>

<br>
<!-- Tabla para Epic04 -->
<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Descripción del Epic</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Epic04</td>
      <td>Como usuario, deseo personalizar mi experiencia y tener acceso a funcionalidades adicionales</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US11</td>
      <td>Beneficios por influenciar la movilidad sostenible</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Beneficios por influenciar la movilidad eléctrica</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Sección de testimonios</td>
    </tr>
    <tr>
      <td>US14</td>
      <td>Pago de plan de suscripción</td>
    </tr>
    <tr>
      <td>US15</td>
      <td>Información de pedido</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Personalización de perfil de propietario</td>
    </tr>
    <tr>
      <td>US17</td>
      <td>Personalización de perfil del usuario que desea alquilar</td>
    </tr>
    <tr>
      <td>US18</td>
      <td>Comunicación con el propietario</td>
    </tr>
    <tr>
      <td>US19</td>
      <td>Ver recomendaciones de vehículos</td>
    </tr>
  </tbody>
</table>

---
<br><br>
<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US01</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Barra de navegación en la Landing Page</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como usuario quiero un menú para ver las secciones de la aplicación</th>
        </tr>
        <tr> 
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario 1:</span></b> El usuario necesita el menú para visualizar las secciones de la Landing page.
            <br><b><span>Dado que</b></span> el usuario se encuentra en la Landing Page.
            <br><b><span>Cuando</b></span> visualice la barra de navegación.
            <br><b><span>Entonces</b></span> podrá interactuar con las diferentes secciones y botones de la página.
            <br><b><span>Scenario 2:</span></b> El usuario necesita navegar por la Landing Page.
            <br><b><span>Dado que</b></span> el usuario se encuentra en la Landing Page.
            <br><b><span>Cuando</b></span> de clic en algún botón o sección de la barra de navegación.
            <br><b><span>Entonces</b></span> podrá ser redirigido a esa sección de la página.</td>
        </tr>
    </tbody>
</table>
<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US02</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Sección de beneficios del Landing Page</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como usuario quiero saber los servicios que ofrece la aplicación web para optar por las características que ofrece</th>
        </tr>
        <tr> 
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario 1:</span></b> El usuario quiere ver la sección de beneficios.
            <br><b><span>Dado que</b></span> el usuario se encuentra en la Landing Page.
            <br><b><span>Cuando</b></span> se encuentre en la sección de Beneficios.
            <br><b><span>Entonces</b></span> podrá visualizar sobre nuestros servicios de movilidad sostenible.</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US03</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Sección de nosotros del Landing Page</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como usuario quiero saber quiénes son y que ofrece la aplicación para optar por ellos</th>
        </tr>
        <tr> 
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario 1:</span></b> El usuario quiere ver la sección de Nosotros.
            <br><b><span>Dado que</b></span> el usuario se encuentra en la Landing Page.
            <br><b><span>Cuando</b></span> se encuentre en la sección de Nosotros.
            <br><b><span>Entonces</b></span> podrá visualizar las personas detrás de la aplicación y saber sobre nuestros servicios de movilidad sostenible.</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US04</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Sección de las redes sociales/Footer del Landing Page</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como usuario quiero visualizar en una sección las redes sociales de la aplicación</th>
        </tr>
        <tr> 
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario 1:</span></b> El usuario necesita una sección de redes sociales de Ruedarent para que pueda seguirnos.
            <br><b><span>Dado que</b></span> el usuario se encuentra en la Landing Page.
            <br><b><span>Cuando</b></span> se encuentre con el footer.
            <br><b><span>Entonces</b></span> podrá visualizar diversas redes sociales de Ruedarent.</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US05</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Sección de contactos en la Landing Page</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como usuario quiero contactar a alguna persona para resolver dudas o problemas</th>
        </tr>
        <tr> 
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario 1:</span></b> El usuario necesita una sección de contacto.
            <br><b><span>Dado que</b></span> el usuario se encuentra en la Landing Page.
            <br><b><span>Cuando</b></span> se encuentre con el contacto.
            <br><b><span>Entonces</b></span> podrá darnos sus datos y posteriormente darle solución.</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US06</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Registro de cuenta</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como usuario quiero registrarme rápidamente para empezar a usar la aplicación al instante</th>
        </tr>
        <tr> 
            <td colspan=4><b class= "red">Criterios de Aceptación:</b><br><b><span>Scenario:</span></b>El usuario se va registrar en la aplicación ingresando sus datos.<br><b><span>Dado que</b></span> el usuario se encuentra en la pantalla de Registro.<br><b><span>Y </b>coloque sus datos personales.</span><br><b><span>Cuando</b></span> presione el botón “Enviar datos”.<br><b><span>Entonces</b></span> se validarán y guardarán los datos del usuario. Posteriormente, se le mostrará la pantalla principal de la aplicación con un mensaje.</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US07</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">El usuario va a registrar y vincular su cuenta usando Google o Outlook.</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como usuario quiero registrarme y vincular mi cuenta en la aplicación Google o Outlook para empezar a usar la aplicación al instante</th>
        </tr>
        <tr>
            <td colspan=4><b class= "red">Criterios de Aceptación:</b><br>
            <b><span>Scenario:</span></b> Registro y vinculación de cuenta usando Google o Outlook.<br>
            <b><span>Dado que</span></b> el usuario se encuentra en la pantalla de Registro.<br>
            <b><span>Cuando</b></span> presione el botón "Registrarse con Google o Outlook".<br><b><span>Entonces</b></span> se le permitirá registrarse rápidamente usando su cuenta de Google o Outlook. También, se validarán y guardarán los datos del usuario. Se le mostrará un mensaje "Registrado" en la pantalla principal de la aplicación.</td>
        </tr>
    </tbody>
</table>
<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US08</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Inicio de sesión</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify"><b>Como usuario quiero poder iniciar sesión para usar la aplicación</th>
        </tr>
        <tr>
            <td colspan=4><b class= "red">Criterios de Aceptación:</b><br>
            <b><span>Scenario:</b></span> El usuario va a iniciar sesión en la aplicación con sus datos.
            <br><b><span>Dado que</b></span> el usuario se encuentra en la pantalla "Inicio de sesión".<br><b><span>Y</b></span> coloque sus credenciales.<br><b><span>Cuando</b></span> presione el botón "Iniciar sesión".<br><b><span>Entonces</b></span> se validará sus datos y se le mostrará la pantalla principal de la aplicación y se mostrará un mensaje.</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US09</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Ver vehículos disponibles</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify"><b>Como persona interesada en alquilar un vehículo quiero poder visualizar los vehículos para poder elegirlos</th>
        </tr>
        <tr>
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario:</b></span> El usuario usa la aplicación y visualiza el catálogo de vehículos.
            <br><b><span>Dado que</b></span> la persona que desea alquilar a iniciado sesión en la aplicación.
            <br><b><span>Cuando</b></span> presione el icono "Vehículos".<br><b><span>Entonces</b></span> se muestra los vehiculos registrados en el sistema y sus respectivas características.</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US10</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Filtro de búsqueda de vehículos</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify"><b>Como persona que desea alquilar quiero poder visualizar un filtro para poder encontrar el vehículo adecuado</th>
        </tr>
        <tr>
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario:</b></span> El usuario desea filtrar los vehiculos
            <br><b><span>Dado que</b></span> la persona que desea alquilar a iniciado sesión en la aplicación.
            <br><b><span>Y</b></span> este en la sección de vehículos.
            <br><b><span>Cuando</b></span>presione el filtro se desplegará los distintos filtros,  entre ellos "Tipo vehiculo", "Marca" y "Modelo".<br><b><span>Entonces</b></span> podrá ver sus vehiculos filtrados.</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US11</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Beneficios por influenciar la movilidad sostenible</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify"><b>Como la persona que desea alquilar, deseo recibir beneficios al compartir contenido de lo relacionado con Ruedarent en mis redes sociales, para sentirme motivado y valorado al contribuir a la concientización sobre la importancia de la movilidad sostenible.</th>
        </tr>
        <tr>
            <td colspan=4><b class= "red">Criterios de Aceptación:</b><br><b><span>Scenario:</span></b> El usuario usa la aplicación y comparte su salida con amigos gracias a Ruedarent.<br><b><span>Dado que</b></span> el usuario se encuentre en una sección de "Reserva de vehículo".
            <br><b><span>Cuando</b></span> presione el icono "Compartir".<br><b><span>Entonces</b></span> se le mostrará algunos beneficios por compartir su uso en la aplicación.</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US12</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Beneficios por influenciar la movilidad sostenible</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify"><b>Como la persona que desea alquilar, deseo recibir beneficios al compartir contenido de lo relacionado con Ruedarent en mis redes sociales, para sentirme motivado y valorado al contribuir a la concientización sobre la importancia de la movilidad eléctrica.</th>
        </tr>
        <tr>
            <td colspan=4><b class= "red">Criterios de Aceptación:</b><br><b><span>Scenario:</span></b> El usuario usa la aplicación y comparte su salida con amigos gracias a Ruedarent.<br><b><span>Dado que</b></span> el usuario se encuentra en la pantalla principal de la aplicación.<br><b><span>Y</b></span> presiona el botón.<br><b><span>Cuando</b></span> presione el icono "Vehículos".<br><b><span>Entonces</b></span> se le mostrará los vehículos en curso dentro de la zona.</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US13</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Sección de testimonios</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify"><b>Como la persona que desea alquilar, deseo leer testimonios de otros usuarios que han experimentado beneficios al utilizar la plataforma, como su estilo de vida, para sentirme inspirado y tomar decisiones informadas.</th>
        </tr>
        <tr>
            <td colspan=4><b class= "red">Criterios de Aceptación:</b><br><b><span>Scenario:</span></b> El usuario tendrá una sección de testimonios.<br><b><span>Dado que</b></span> el usuario se encuentra en la pantalla principal de la aplicación.<br>
            <br><b><span>Cuando</b></span> presione el botón de testimonios.<br><b><span>Entonces</b></span> se le mostrará los testimonios de las personas y podrá adjuntar el suyo.</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US14</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Pago de plan de suscripción</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como propietario quiero realizar el pago de un plan para acceder a características y beneficios adicionales</th>
        </tr>
        <tr> 
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario 1:</span></b> Pago exitoso
            <br><b><span>Dado que</b></span> el propietario desea adquirir un plan de suscripción 
            <br><b><span>Cuando</b></span> elige un plan de suscripción
            <br><b><span>Y</b></span> va a la sección de detalles del pedido
             <br><b><span>Y</b></span> selecciona el botón de pagar con PayPal
             <br><b><span>Y</b></span> confirma el pago en la plataforma de PayPal
            <br><b><span>Entonces</b></span> el sistema procesa con éxito el pago.
             <br><b><span>Y</b></span> se actualiza la cuenta del propietario
             <br><b><span>Y</b></span> el sistema concede acceso a las características y beneficios adicionales asociados al plan
               <br><b><span>Scenario 2:</span></b> Pago fallido
            <br><b><span>Dado que</b></span> el propietario desea adquirir un plan de suscripción 
            <br><b><span>Cuando</b></span> elige un plan de suscripción
            <br><b><span>Y</b></span> va a la sección de detalles del pedido
             <br><b><span>Y</b></span> selecciona el botón de pagar con PayPal
             <br><b><span>Y</b></span> intenta realizar el pago en la plataforma de PayPal
              <br><b><span>Y</b></span> el pago falla debido a problemas con PayPal
            <br><b><span>Entonces</b></span> el sistema muestra un mensaje de error
          </td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US15</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Información de pedido</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como propietario quiero visualizar la información del pedido para revisar los detalles antes de realizar el pago</th>
        </tr>
        <tr> 
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario :</span></b> Visualización de Información del Pedido
            <br><b><span>Dado que</b></span> el propietario desea adquirir un plan de suscripción 
            <br><b><span>Cuando</b></span> el propietario elige un plan de suscripción
            <br><b><span>Entonces</b></span> el propietario va a la sección de detalles del pedido
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US16</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Personalización de perfil de propietario</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como propietario de vehículos, quiero poder personalizar mi perfil para mostrar información relevante y mejorar mi visibilidad dentro de la plataforma</th>
        </tr>
        <tr> 
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario 1:</span></b> Acceso a la Sección de Mi de Perfil
            <br><b><span>Dado que</b></span> el propietario se ha registrado en la plataforma 
             <br><b><span>Y</b></span> se encuentra en la página principal de la aplicación
            <br><b><span>Cuando</b></span> desea personalizar su perfil
            <br><b><span>Entonces</b></span> el propietario puede acceder fácilmente a la sección de mi perfil desde el menú de navegación principal
               <br><b><span>Scenario 2:</span></b> Edición de Información del Perfil
            <br><b><span>Dado que</b></span> el propietario está en la sección de mi perfil
            <br><b><span>Cuando</b></span> desea actualizar su información 
            <br><b><span>Y</b></span> realiza los cambios
            <br><b><span>Entonces</b></span> los cambios se guardan automáticamente
              <br><b><span>Y</b></span> el perfil se actualiza con la nueva información proporcionada
          </td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US17</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Personalización de perfil del usuario que desea alquilar</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como usuario que desea alquilar, deseo poder personalizar mi perfil para reflejar mis preferencias y necesidades</th>
        </tr>
        <tr> 
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario 1:</span></b> Acceso a la Sección de Mi Perfil
            <br><b><span>Dado que</b></span> el usuario que desea alquilar se ha registrado en la plataforma 
             <br><b><span>Y</b></span> se encuentra en la página principal de la aplicación
            <br><b><span>Cuando</b></span> desea personalizar su perfil
            <br><b><span>Entonces</b></span> el usuario que desea alquilar puede acceder fácilmente a la sección de mi perfil desde el menú de navegación principal
               <br><b><span>Scenario 2:</span></b> Edición de Información del Perfil
            <br><b><span>Dado que</b></span> el usuario que desea alquilar está en la sección de mi perfil
            <br><b><span>Cuando</b></span> desea actualizar su información 
            <br><b><span>Y</b></span> realiza los cambios
            <br><b><span>Entonces</b></span> los cambios se guardan automáticamente
              <br><b><span>Y</b></span> el perfil se actualiza con la nueva información proporcionada
          </td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US18</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Comunicación con el propietario</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como usuario que desea alquilar quiero comunicarme con el propietario del vehículo para coordinar más detalles sobre el alquiler</th>
        </tr>
        <tr> 
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario 1:</span></b> Selección de Vehículo y Navegación a la Página de Rent Vehicle
            <br><b><span>Dado que</b></span> el usuario que desea alquilar un vehículo busca un vehículo
            <br><b><span>Cuando</b></span> selecciona un vehículo específico de la lista de vehículos disponibles
            <br><b><span>Entonces</b></span> es redirigido a una página que muestra información detallada sobre el vehículo seleccionado
               <br><b><span>Scenario 2:</span></b> Comunicación con el Propietario
            <br><b><span>Dado que</b></span> el usuario que desea alquilar está en la página de Rent Vehicle
               <br><b><span>Y</b></span> desea obtener más detalles o realizar consultas adicionales al propietario
            <br><b><span>Cuando</b></span> hace clic en el botón de contacto por WhatsApp
            <br><b><span>Entonces</b></span> se abre la aplicación de WhatsApp en su dispositivo con el número del propietario
          </td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th class= "red">Epic/Story ID</th>
            <th class= "red">US19</th>
            <th class= "red">Relacionado con (Epic ID)</th>
            <th class= "red">EP4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class= "red">Título</td>
            <th colspan=3 align= "justify">Ver recomendaciones de vehículos</th>
        </tr>
        <tr>
            <td class= "red">Descripción</td>
            <th colspan=3 align= "justify">Como usuario que desea alquilar quiero ver recomendaciones de los vehículos más usados para poder tomar decisiones fácilmente</th>
        </tr>
        <tr> 
            <td colspan=4><b class= "red">Criterios de Aceptación:</b>
            <br><b><span>Scenario 1:</span></b> Acceso a la Sección de Recomendaciones
            <br><b><span>Dado que</b></span> el usuario que desea alquilar un vehículo está navegando por la plataforma
            <br><b><span>Cuando</b></span> desea obtener recomendaciones de vehículos populares
            <br><b><span>Entonces</b></span> puede acceder fácilmente a la sección de recomendaciones desde el menú de navegación
               <br><b><span>Scenario 2:</span></b> Visualización de Vehículos Recomendados
            <br><b><span>Dado que</b></span> el usuario que desea alquilar está en la sección de recomendaciones de vehículos 
            <br><b><span>Cuando</b></span> navega por la galería de vehículos recomendados
              <br><b><span>Y</b></span> presiona el botón Ver más
            <br><b><span>Entonces</b></span> es redirigido a la página de visualización de más vehículos disponibles
          </td>
        </tr>
    </tbody>
</table>

## 3.3. Impact Mapping.

En esta sección, debemos identificar los "Business Goals" para nuestra aplicación web, la cual conecta a personas que desean alquilar un vehículo con propietarios que desean ofrecer sus vehículos. Estos usuarios nos ayudarán a cumplir estos objetivos. Hemos identificado el "Impact" o impacto que deseamos lograr, y luego estableceremos los "Deliverables" que nos permitirán como negocio digital alcanzar estos impactos. Finalmente, incluiremos las "User Stories" para obtener las características o funcionalidades que ayudarán a producir los Deliverables.


<br><img src="./img/Chapter03/Impactmap.png" alt="Impact Map" style="width: 1000px; height: auto;" ><br>

## 3.4. Product Backlog.

Con el fin de simplificar la complejidad de las tareas, hemos utilizado la escala de Fibonacci (1/2/3/5/8) para crear nuestro product backlog.
Historia de usuario base:
Tomamos como referencia US09: Como persona interesada en alquilar un vehículo quiero poder visualizar los vehículos para poder elegirlos. (Posee 3 puntos de historia).
Asimismo, utilizamos la herramienta “Planning Poker Online” para poder votar en grupo y decidir la dificultad de cada historia de usuario, tomando como punto intermedio el User Story 09

<table>
  <thead>
    <tr>
      <th># Orden</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points (1/2/3/5/8)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>US01</td>
      <td>Barra de navegación en la Landing Page</td>
      <td>Como usuario quiero un menú para ver las secciones de la aplicación</td>
      <td>3</td>
    </tr>
    <tr>
      <td>2</td>
      <td>US02</td>
      <td>Sección de beneficios del Landing Page</td>
      <td>Como usuario quiero saber los servicios que ofrece la aplicación web para optar por las características que ofrece</td>
      <td>2</td>
    </tr>
    <tr>
      <td>3</td>
      <td>US03</td>
      <td>Sección de nosotros del Landing Page</td>
      <td>Como usuario quiero saber quiénes son y qué ofrece la aplicación para optar por ellos</td>
      <td>2</td>
    </tr>
    <tr>
      <td>4</td>
      <td>US04</td>
      <td>Sección de las redes sociales/Footer del Landing Page</td>
      <td>Como usuario quiero visualizar en una sección las redes sociales de la aplicación</td>
      <td>2</td>
    </tr>
    <tr>
      <td>5</td>
      <td>US05</td>
      <td>Sección de contactos en la Landing Page</td>
      <td>Como usuario quiero contactar a alguna persona para resolver dudas o problemas</td>
      <td>2</td>
    </tr>
    <tr>
      <td>6</td>
      <td>US06</td>
      <td>Registro de cuenta</td>
      <td>Como usuario quiero registrarme rápidamente para empezar a usar la aplicación al instante</td>
      <td>3</td>
    </tr>
    <tr>
      <td>7</td>
      <td>US07</td>
      <td>Registro y vinculación de cuenta usando Google o Outlook</td>
      <td>Como usuario quiero registrarme y vincular mi cuenta en la aplicación Google o Outlook para empezar a usar la aplicación al instante</td>
      <td>3</td>
    </tr>
    <tr>
      <td>8</td>
      <td>US08</td>
      <td>Inicio de sesión</td>
      <td>Como usuario quiero poder iniciar sesión para usar la aplicación</td>
      <td>2</td>
    </tr>
    <tr>
      <td>9</td>
      <td>US09</td>
      <td>Ver vehículos disponibles</td>
      <td>Como persona interesada en alquilar un vehículo quiero poder visualizar los vehículos para poder elegirlos.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>10</td>
      <td>US10</td>
      <td>Filtro de búsqueda de vehículos</td>
      <td>Como persona que desea alquilar quiero poder visualizar un filtro para poder encontrar el vehículo adecuado</td>
      <td>5</td>
    </tr>
    <tr>
      <td>11</td>
      <td>US11</td>
      <td>Beneficios por influenciar la movilidad sostenible</td>
      <td>Como persona que desea alquilar, deseo recibir beneficios al compartir contenido relacionado con Ruedarent en mis redes sociales, para sentirme motivado y valorado al contribuir a la concientización sobre la importancia de la movilidad sostenible</td>
      <td>5</td>
    </tr>
    <tr>
      <td>12</td>
      <td>US12</td>
      <td>Beneficios por influenciar la movilidad eléctrica</td>
      <td>Como persona que desea alquilar, deseo recibir beneficios al compartir contenido relacionado con Ruedarent en mis redes sociales, para sentirme motivado y valorado al contribuir a la concientización sobre la importancia de la movilidad eléctrica</td>
      <td>5</td>
    </tr>
    <tr>
      <td>13</td>
      <td>US13</td>
      <td>Sección de testimonios</td>
      <td>Como persona que desea alquilar, deseo leer testimonios de otros usuarios que han experimentado beneficios al utilizar la plataforma para sentirme inspirado y tomar decisiones informadas.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>14</td>
      <td>US14</td>
      <td>Pago de plan de suscripción</td>
      <td>Como propietario quiero realizar el pago de un plan para acceder a características y beneficios adicionales</td>
      <td>5</td>
    </tr>
    <tr>
      <td>15</td>
      <td>US15</td>
      <td>Información de pedido</td>
      <td>Como propietario quiero visualizar la información del pedido para revisar los detalles antes de realizar el pago</td>
      <td>2</td>
    </tr>
    <tr>
      <td>16</td>
      <td>US16</td>
      <td>Personalización de perfil de propietario</td>
      <td>Como propietario de vehículos, quiero poder personalizar mi perfil para mostrar información relevante y mejorar mi visibilidad dentro de la plataforma</td>
      <td>3</td>
    </tr>
    <tr>
      <td>17</td>
      <td>US17</td>
      <td>Personalización de perfil del usuario que desea alquilar</td>
      <td>Como usuario que desea alquilar, deseo poder personalizar mi perfil para reflejar mis preferencias y necesidades.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>18</td>
      <td>US18</td>
      <td>Comunicación con el propietario</td>
      <td>Como usuario que desea alquilar quiero comunicarme con el propietario del vehículo para coordinar más detalles sobre el alquiler.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>19</td>
      <td>US19</td>
      <td>Ver recomendaciones de vehículos</td>
      <td>Como usuario que desea alquilar quiero ver recomendaciones de los vehículos más usados para poder tomar decisiones fácilmente</td>
      <td>5</td>
    </tr>
  </tbody>
</table>

---
