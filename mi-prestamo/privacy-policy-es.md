# Política de privacidad de Mi Préstamo

Fecha de vigencia: 9 de septiembre de 2026.

Mi Préstamo es una aplicación de BonMenDev para calcular y gestionar préstamos
personales. No proporciona asesoramiento financiero.

## Datos y almacenamiento local

Los montos, tasas, plazos, nombres de préstamos, pagos, notas, comisiones,
recordatorios y preferencias que registra el usuario se procesan y almacenan
localmente en su dispositivo mediante SQLite. No se crea una cuenta y BonMenDev
no opera un servidor que reciba esta información.

Eliminar la aplicación o sus datos puede eliminar esa información. El usuario
puede crear un respaldo local `.miprestamo`; este archivo puede contener los
datos financieros registrados y no está cifrado.

## Reportes, respaldos y aplicaciones externas

Mi Préstamo puede generar reportes PDF y respaldos localmente. Solo salen del
dispositivo cuando el usuario decide guardarlos, imprimirlos o compartirlos
mediante el selector o la hoja de compartir de Android. La aplicación o servicio
de destino procesa el archivo bajo sus propias políticas. Mi Préstamo no realiza
sincronización ni backup automático en la nube.

## Recordatorios y permisos

Los recordatorios se programan localmente. En Android 13 o posterior, la app
solicita `POST_NOTIFICATIONS` únicamente cuando el usuario intenta activar esta
función. Declara `RECEIVE_BOOT_COMPLETED` para restablecer recordatorios después
de reiniciar o actualizar el dispositivo; el plugin también declara `VIBRATE`
para el comportamiento de notificaciones. No solicita alarmas exactas.

No utiliza cámara, micrófono, ubicación, contactos, SMS, llamadas ni permisos
generales de almacenamiento.

## Terceros y seguimiento

Mi Préstamo Pro se ofrece como una compra única procesada por Google Play. Google
puede procesar la información necesaria para completar, restaurar y administrar
la transacción conforme a sus propias políticas. Mi Préstamo consulta a Google
Play el producto, el precio localizado y el estado de compra; BonMenDev no recibe
ni almacena números completos de tarjeta u otras credenciales de pago.

No se integran publicidad, analítica, telemetría, seguimiento, autenticación ni
servicios cloud propios. Las librerías de PDF, compartir, archivos,
notificaciones y compras se revisan contra el artefacto final antes de publicar.

## Menores y cambios

La aplicación no está dirigida específicamente a menores y no recopila
deliberadamente información personal de menores. Esta política se actualizará si
cambian las prácticas, permisos o integraciones.

## Contacto

Desarrollador/marca: **BonMenDev**.

Contacto: **bonmendev.apps@gmail.com**.

URL pública para Google Play:
**https://cristhianbonillamendez-pixel.github.io/bonmendev/mi-prestamo/privacy-policy/**.
