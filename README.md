# Ganaplay

### 🌐 Redirecciones y Correos por País

Este módulo gestiona las redirecciones automáticas y correos transaccionales enviados por la plataforma, asegurando que todos los flujos respeten el país al que pertenece la cuenta del usuario: **Guatemala** o **El Salvador**.

***

1\. Acceso al Módulo

**Ruta de Acceso:** \
**URL:**&#x20;

***

#### 2. Funcionalidades

🔄 **2.1 Redirecciones Automáticas por País**\
El sistema envía correos dependiendo del país asociado a la cuenta del usuario.\
Todos los correos enviados al usuario deben cumplir con reglas específicas según su país:

* El **remitente del correo** debe corresponder al país del usuario.
  * El Salvador(🇸🇻 ): `no-reply@sv.ganaplay.com`
  * Guatemala(🇬🇹): `no-reply@gt.ganaplay.com`
* Los **enlaces incluidos en los correos** (por ejemplo, para recuperación de contraseña) deben redirigir a la URL correcta según el país.

#### 🔎 3. Casos Específicos y Reglas

📥 **3.1 Recuperación de Contraseña**

* El enlace enviado en el correo debe llevar a la plataforma del país del usuario:
  * Usuario de 🇸🇻 El Salvador → redirige a: `https://sv.ganaplay.com/reset-password`
  * Usuario de 🇬🇹 Guatemala → redirige a: `https://gt.ganaplay.com/reset-password`

✉️ **3.2 Remitente del Correo según País**

* **El Salvador**: Correos deben enviarse desde dominios terminados en `@sv.ganaplay.com`.
* **Guatemala**: Correos deben enviarse desde dominios terminados en `@gt.ganaplay.com`.

#### 🖼️ 5. Visualización

Aunque este módulo no presenta una visual directa para el usuario final, se espera:

* Redirecciones transparentes, sin notificaciones de cambio de país.
* Correos recibidos con branding visual coherente con cada país.

#### 🕒 6. Control de Versiones

| Versión | Fecha       | Cambios Realizados                        | Responsable        |
| ------- | ----------- | ----------------------------------------- | ------------------ |
| 1.0     | 2025-07-07  | Versión inicial del manual                | Equipo de Producto |
| 1.1     | _Pendiente_ | Validación del flujo de correos y enlaces | QA / Desarrollo    |

***

¿Deseas que te lo entregue en Word o PDF? ¿O necesitas que lo incluya dentro de un manual mayor?
