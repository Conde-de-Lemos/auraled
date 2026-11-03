# Istalador Auraled

Auraled **5.2.5** para Windows x64. Una sola aplicación con su motor de iluminación incluido.

[Descargar la última versión de Auraled](https://auraled-flow.marketing-lemos-agencia.workers.dev/descargar/auraled)

1. Cierra Auraled desde **Salir** junto al reloj antes de actualizar.
2. Instala la nueva versión. Se conservan las versiones anteriores y se copian tus ajustes sin modificar el origen.
3. Abre **Aruraled** desde Inicio.
4. Activa **Preferencias → Iniciar Auraled con Windows**, o marca esa opción durante la instalación. Se guarda al instante, sin pulsar Aplicar.

**5.2.5 corrige el error de acceso denegado al Registro de 5.2.4.** El inicio automático utiliza un acceso directo en la carpeta de Inicio de tu usuario. No pide permisos de administrador ni cambia los permisos de Windows. Preferencias y el instalador utilizan el mismo servicio.

Al iniciar sesión, Auraled queda en el área del reloj y recupera el modo y el estado de luces guardados, incluido apagado. Sin configuración aplicada muestra la instalación. Se conserva la corrección del icono duplicado, la instancia única y la reapertura de la ventana.

El enlace de descarga es permanente. Las nuevas versiones pueden tardar hasta cinco minutos en aparecer; los borradores de GitHub no se ofrecen.

Aplicación e instalador: **5.2.5.0**. Motor WASAPI: **5.2.2.0**, sin cambios. El instalador incluye fuentes correspondientes, componentes, licencias, accesos directos y desinstalador. No necesitas instalar Prismatik aparte.

Windows 10 o posterior x64, .NET Framework 4.7.2 o posterior y PowerShell 5.1. Si falta WebView2 Runtime, el instalador lo prepara desde Microsoft y requiere Internet.

[Publicación 5.2.5 y notas](https://github.com/Conde-de-Lemos/auraled/releases/tag/v5.2.5)

Instalador: **161.550.473 bytes**. SHA-256: `c834783506bab94037d4a9feeb74d596a03bab4c3a52f5bf89721530862b42c0`.

Comprobado con la carpeta real de Inicio y la clave Run bloqueada: quince controles del acceso directo, siete del servicio del ejecutable completo y seis de las funciones del instalador con carga mínima y ejecutable real. Pasan también motor Virtual, Unicode, modos, audio real de Windows, arranque apagado, reapertura, icono e interfaz. No se reinició Windows ni se hizo una nueva prueba física USB en esta revisión. No se sustituyó la instalación habitual durante las pruebas.

Las versiones anteriores, incluidos [5.2.4](https://github.com/Conde-de-Lemos/auraled/releases/tag/v5.2.4) y [5.2.3](https://github.com/Conde-de-Lemos/auraled/releases/tag/v5.2.3-beta.4), permanecen disponibles como historial. Los archivos automáticos «Source code» de GitHub contienen este repositorio de distribución; las fuentes de la aplicación y del motor acompañan al instalador.

Para mantenimiento: conservar `Istalador.Auraled.exe` en cada nueva publicación; no hace falta editar el botón de la web. Cada cambio lleva una nueva versión numérica y conserva las entregas anteriores.

[Guía de instalación y soporte](https://auraled-flow.marketing-lemos-agencia.workers.dev/instalacion#descargas)
