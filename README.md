# ProyectoIonicAngularOmarMorales
Aplicación Ionic + Angular 
# Proyecto Ionic + Angular - App Móvil

Este proyecto es una aplicación web y móvil desarrollada con la plataforma **Ionic Framework** y **Angular**, estructurada para ofrecer una interfaz moderna y fluida con navegación basada en componentes Standalone.

## Objetivo del proyecto
El propósito principal de esta aplicación es servir como un prototipo funcional de gestión y navegación multi-vista, permitiendo a los usuarios interactuar con interfaces personalizadas, autenticación local y configuraciones clave en un entorno híbrido.

---

## Características principales
La aplicación está organizada en tres vistas (pestañas / tabs) principales:

* **Home (`tab1`):** Vista principal con pantalla de inicio de sesión (Login) integrada con backend, validación de credenciales y navegación hacia el registro de usuarios.
* **About (`tab2`):** Vista orientada al registro de nuevos usuarios y detalle de información institucional o contextual sobre la plataforma.
* **Settings (`tab3`):** Vista de administración e información de perfil, que cuenta con navegación de retorno rápido a la vista principal mediante botones flotantes (`ion-fab`).

---

## Modelo inicial de datos

### Credenciales de Prueba (Demo):
* **Correo:** `admin@prueba.com`
* **Contraseña:** `123456`

### Estructura JSON del Usuario:
El flujo de autenticación y manejo de sesión utiliza la siguiente estructura básica para el objeto **Usuario**:

```json
{
  "id": 1,
  "username": "admin@prueba.com",
  "correo": "admin@prueba.com",
  "password": "123456",
  "fecha_registro": "2026-09-11"
}
