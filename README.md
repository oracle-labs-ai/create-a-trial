# Crear un ambiente trial en Oracle Cloud

Esta guía documenta el flujo para crear una cuenta de **Oracle Cloud Free Tier** y habilitar un ambiente trial de OCI siguiendo las capturas incluidas en la carpeta `images`.

> Usa tus propios datos personales, correo y método de pago. Las capturas solo muestran el orden del proceso y los campos que aparecen durante el registro.

## 1. Abrir Oracle Cloud Free Tier

1. Entra a la página de **Oracle Cloud Free Tier**.
2. Haz clic en **Start for free** para iniciar el registro.

![Oracle Cloud Free Tier](<images/Imagen 1.png>)

## 2. Completar la información inicial de la cuenta

En la sección **Account Information**, completa los campos requeridos:

1. Selecciona el **Billing Country/Territory**.
2. Ingresa **First Name** y **Last Name**.
3. Ingresa tu **Email**.
4. Marca el hCaptcha **I am human**.
5. Haz clic en **Verify my email**.

![Formulario de información de cuenta](<images/Imagen 2.png>)

## 3. Esperar el enlace de verificación

Oracle mostrará el mensaje **Email verification link sent**. El enlace de verificación se envía al correo indicado y tiene una validez limitada.

![Enlace de verificación enviado](<images/Imagen 3.png>)

## 4. Abrir el correo de verificación

Busca en tu bandeja de entrada el correo de **Oracle Cloud** con el asunto **Verify your email to create your Oracle Cloud account**.

![Correo de verificación recibido](<images/Imagen 4.png>)

## 5. Verificar el correo

Abre el correo y haz clic en **Verify email** para confirmar tu dirección de correo y volver al flujo de creación de cuenta.

![Botón Verify email](<images/Imagen 5.png>)

## 6. Crear la contraseña de la cuenta

Después de verificar el correo, continúa en **Account Information** y crea una contraseña segura.

La contraseña debe cumplir estas reglas:

- Mínimo 8 caracteres.
- Al menos 1 minúscula.
- Al menos 1 mayúscula.
- Al menos 1 número.
- Al menos 1 carácter especial.
- Máximo 40 caracteres.
- No debe contener tu nombre, apellido, correo, espacios ni los caracteres restringidos que muestra el formulario.

Confirma la contraseña en **Confirm Password** y verifica que aparezca **Passwords Matched**.

![Configuración de contraseña](<images/Imagen 6.png>)

## 7. Seleccionar la región principal

En **Home Region**, busca y selecciona la región donde se creará la cuenta. En la captura se busca `chic` y se selecciona **US Midwest (Chicago)**.

> La región principal no se puede cambiar fácilmente después. Selecciona la región más adecuada para tu laboratorio o la que el ejercicio requiera.

![Selección de Home Region](<images/Imagen 7.png>)

## 8. Revisar la información de dirección y verificación de identidad

Completa o revisa la sección **Address Information**. Luego, en **Payment/Identity Verification**, lee las condiciones de verificación:

- Oracle indica que no se cobra por usar OCI Free Tier.
- Puede aparecer un cargo temporal pequeño como validación del método de pago.
- Oracle no acepta tarjetas virtuales, prepagadas o de un solo uso.

Haz clic en **Add payment verification method**.

![Verificación de pago e identidad](<images/Imagen 8.png>)

## 9. Agregar el método de pago

En el modal **Add Payment Method**, completa la sección **Billing Information** con los datos requeridos de facturación.

![Información de facturación](<images/Imagen 9.png>)

## 10. Completar los detalles de la tarjeta

En **Payment Details**, selecciona el tipo de tarjeta y completa:

1. **Card Number**.
2. **Expiration Month**.
3. **Expiration Year**.
4. **CVN**.

Cuando todo esté completo, haz clic en **Finish**.

![Detalles de tarjeta](<images/Imagen 10.png>)

## 11. Cerrar la confirmación de pago

Si la validación es exitosa, aparecerá el modal **Oracle Cloud Free Tier** con el mensaje **Thank you!**. Haz clic en **Close** para volver al formulario.

![Confirmación de pago](<images/Imagen 11.png>)

## 12. Aceptar el acuerdo e iniciar el trial

En la sección **Agreement**:

1. Marca el checkbox para aceptar el acuerdo de Oracle Cloud.
2. Haz clic en **Start my free trial**.

![Inicio del trial](<images/Imagen 12.png>)

## Resultado esperado

Al finalizar el flujo, la cuenta de Oracle Cloud Free Tier queda registrada y el ambiente trial queda en proceso de creación o disponible para iniciar sesión en OCI.
