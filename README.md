# ForgeAPK — descargas oficiales

 Este repositorio contiene **únicamente los binarios** de ForgeAPK para Windows.
 El código fuente vive en un repositorio privado.

Web oficial: **https://forgeapk.vercel.app**

## ¿Qué descargo?

| Archivo | Para quién |
| --- | --- |
| `ForgeAPK-Setup-<version>.exe` | Instalador para Windows 10/11 (64 bits). Incluye el runtime de Visual C++, no necesitas nada más. |
| `ForgeAPK-<version>-portable.zip` | Versión portable: descomprime y ejecuta, sin instalación. |

## Requisitos

* Windows 10 (1809) o Windows 11, 64 bits.
* 8 GB de RAM (16 GB recomendados para proyectos grandes).
* 10 GB libres (35 GB si dejas que la app descargue el toolchain completo).
* Internet solo para la primera descarga del toolchain; después puede trabajar **offline**.

## Novedades de la 0.2.0

* Centro de descargas con modo **local** (solo lo que falta) y modo **completo**.
* Asistente que localiza las versiones oficiales de Flutter, JDK 17 y Android SDK.
* Descargas con reanudación, reintentos y espejos alternativos.
* Detección automática de **proxy** y configuración manual con usuario y contraseña.
* Corregido el error `MSVCP140.dll` que impedía arrancar la aplicación.

## Aviso de SmartScreen

El instalador no está firmado con un certificado de pago, así que Windows puede
mostrar un aviso la primera vez. Pulsa «Más información» → «Ejecutar de todas formas».
