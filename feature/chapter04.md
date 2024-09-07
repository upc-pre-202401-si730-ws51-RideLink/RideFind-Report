## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

User Bounded Context

<img src="img/Chapter04/UserBoundedContext.jpg" alt="User Bounded Context Class Diagram">

Content Bounded Context

<img src="img/Chapter04/ContentBoundedContext.jpg" alt="Content Bounded Context Class Diagram">

Collaboration Bounded Context

<img src="img/Chapter04/CollaborationBoundedContext.jpg" alt="Collaboration Bounded Context Class Diagram">

Monetization Bounded Context

<img src="img/Chapter04/MonetizationBoundedContext.jpg" alt="Monetization Bounded Context Class Diagram">

### 4.7.2. Class Dictionary
<hr>

<table border="1" width="30%">
  <tr>
    <td colspan="1" valign="top">User</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase User representa a los usuarios de la aplicación</td>
  </tr>
<table>

<table border="1" width="30%">
  <tr>
    <td colspan="1" valign="top">Writer</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Writer representa a los escritores de la aplicación</td>
  </tr>
<table>

<table border="1" width="30%">
  <tr>
    <td colspan="1" valign="top">Illustrator</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Illustrator representa a los ilustradores de la aplicación</td>
  </tr>
<table>

<table border="1" width="30%">
  <tr>
    <td colspan="1" valign="top">Reader</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Reader representa a los lectores de la aplicación</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">UserFactory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase UserFactory es una clase hija de UserManager y se encarga de la creación de los usuarios del sistema.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createUser()</td>
    <td colspan="2" valign="top">Método que crea nuevos objetos de tipo User.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">WriterFactory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase WriterFactory es una clase hija de UserFactory. Se encarga de la creación de los usuarios escritores en la aplicación.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createUser()</td>
    <td colspan="2" valign="top">Método que crea nuevos objetos de tipo Writer.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">IllustratorFactory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase IllustratorFactory es una clase hija de UserFactory. Se encarga de la creación de los usuarios ilustradores en la aplicación.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createUser()</td>
    <td colspan="2" valign="top">Método que crea nuevos objetos de tipo Illustrator.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">ReaderFactory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase ReaderFactory es una clase hija de UserFactory. Se encarga de la creación de los usuarios lectores en la aplicación.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createUser()</td>
    <td colspan="2" valign="top">Método que crea nuevos objetos de tipo Reader.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">UserManager</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase UserManager se encarga de la gestión de los usuarios en el sistema.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createUser()</td>
    <td colspan="2" valign="top">Método que crea nuevos objetos de tipo User.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">getUser()</td>
    <td colspan="2" valign="top">Método que obtiene el identificador de un usuario.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">updateUser()</td>
    <td colspan="2" valign="top">Método que actualiza los atributos de un usuario.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">deleteUser()</td>
    <td colspan="2" valign="top">Método que elimina a un usuario del sistema.</td>
  </tr>
<table>

<table border="1" width="30%">
  <tr>
    <td colspan="1" valign="top">Account</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Account representa la cuenta de los usuarios de la aplicación.</td>
  </tr>
<table>

<table border="1" width="30%">
  <tr>
    <td colspan="1" valign="top">Subscription</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Subscription representa la suscripción a un plan de la aplicaicón.</td>
  </tr>
<table>

<table border="1" width="30%">
  <tr>
    <td colspan="1" valign="top">Plan</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Plan representa a los planes de suscripción de la aplicación.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">Observer</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Observer es una clase se encarga de notificar acerca de cambios realizadosa otro objeto </td>
  </tr>
  <tr>
    <td colspan="1" valign="top">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">update()</td>
    <td colspan="2" valign="top">Método que informa al resto de los observadores acerca de n cambio de estado.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">SuscriptionObserver</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase SuscriptionObserver es una clase hija de Observer. Se encarga de gestionar el estado de las suscripciones del sistema.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">update()</td>
    <td colspan="2" valign="top">Método que actualiza el estado de la suscripción de un usuario.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">UserObserver</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase UserObserver es una clase hija de Observer. Se encarga de gestionar los estados de los usuarios en el sistema.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">update()</td>
    <td colspan="2" valign="top">Método que actualiza el estado de usuario.</td>
  </tr>
<table>


## 4.8. Database Design

### 4.8.1. Database Diagram
<div style="display:flex; justify-content:center; flex-direction:column; text-align:center">
   <p>Se presenta a continuación el modelo físico elaborado para esta entrega, tomando en cuenta los requisitos necesarios para el negocio.</p>
   <img src="img/Chapter04/DataBaseDiagram Ride.jpg" alt="ArtCollab Database Model"> 
</div>
