% Finca Monterruiz
% Ana Rodríguez Pérez
% Curso 2023/24

# Descripción general del proyecto

Finca Monterruiz es un sitio web diseñado para ofrecer diversas experiencias en torno al viñedo. Esto incluye visitas guiadas, catas, talleres, conferencias, exposiciones y más. Todo ello con el objetivo de compartir con los visitantes las diferentes actividades que se llevan a cabo en el viñedo a lo largo del año.

## Funcionalidad principal de la aplicación

Permitir a los usuarios explorar el catalogo de actividades que se ofrecen con la posibilidad de reservar aquellas que deseen realizar indicando la fecha, hora y número de personas.

Una vez realizada la actividad los usuarios podrán dejar un comentario y una valoración positiva o negativa sobre su experiencia.

El administrador se encargará de crear, modificar, borrar y bloquear temporalmente las actividades. También gestionará los usuario y las reservas que se realicen.

Los usuarios para poder reservar una actividad deberán registrarse previamente 

## Objetivos generales

A diferencia de los casos de uso, los objetivos no tienen principio ni fin.

Por ejemplo:

* Objetivo: Explorar, reservar y evaluar las diferentes actividades y experiencias que se ofrecen relacionadas con el enoturismo.

* Casos de uso: 
    * Invitado (usuario no logueado):
        - Registrarse.
        - Ver catálogo de actividades.
        - Ver vista "contáctanos".
        - Ver vista "Nuestra Historia".
        - Ver comentarios de las actividades.
    * Usuario logueado:
        - Iniciar sesión.
        - Reservar actividad.
        - Cancelar actividad.
        - Dejar un comentario.
        - Valorar actividad.
        - Administrar perfil.
    * Administrador:
        - Validad/bloquear usuario.
        - Crear actividad.
        - Modificar actividad.
        - Borrar actividad.
        - Gestionar reservas.
        - Gestionar usuarios.
             

# Elemento de innovación

- Uso del framework Laravel.
- Implementación del sistema de newsletter. (opcional)
- Uso de la API de autenticación de Google para habilitar el inicio de sesión con cuentas de Gmail. (opcional)
