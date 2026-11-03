# Istalador Auraled

Auraled **5.2.4** para Windows x64. Una sola aplicación con su motor de iluminación incluido.

[Descargar la última versión de Auraled](https://auraled-flow.marketing-lemos-agencia.workers.dev/descargar/auraled)

1. Cierra Auraled desde «Salir» junto al reloj antes de actualizar.
2. Ejecuta el instalador y sigue sus pasos. La versión anterior y sus ajustes se conservan.
3. Abre **Aruraled** desde Inicio y continúa con la guía de Laura.

En **Preferencias → Iniciar Auraled con Windows** puedes activar o desactivar el arranque automático. El cambio se guarda al instante, sin pulsar Aplicar. También puedes elegirlo durante la instalación. Al iniciar sesión, Auraled queda en el área del reloj y recupera tu configuración, incluido el estado de luces apagadas si así lo dejaste.

Esta versión también corrige la acumulación de iconos junto al reloj: reutiliza una identidad estable al reabrirse, retira su icono al salir y evita que las vistas de prueba creen iconos. Se conservan la reapertura de la ventana, el montaje interactivo y los paneles persistentes de V5.2.3.

El enlace de descarga es permanente: selecciona la publicación más reciente con el archivo `Istalador.Auraled.exe`. Las nuevas versiones pueden tardar hasta cinco minutos en aparecer. Los borradores de GitHub no se ofrecen.

Aplicación e instalador: **5.2.4.0**. Motor WASAPI: **5.2.2.0**, sin cambios. El instalador incluye componentes, fuentes correspondientes, licencias, accesos directos y desinstalador. No necesitas instalar Prismatik aparte.

Windows 10 o posterior x64, .NET Framework 4.7.2 o posterior y Windows PowerShell 5.1. Si falta WebView2 Runtime, el instalador lo prepara desde Microsoft y requiere Internet.

[Publicación 5.2.4 y notas](https://github.com/Conde-de-Lemos/auraled/releases/tag/v5.2.4)

Instalador: **159.378.879 bytes**. SHA-256: `6459ad8422ed87933800657e2e81cb3f9bec5470be4d30e9e71846f7fabe8170`.

Se comprobaron el inicio oculto, la reapertura, la limpieza del icono tras un cierre forzado, el registro aislado, las funciones del instalador con carga mínima, el motor Virtual, los ajustes, la importación, el audio real de Windows y la interfaz. En esta revisión no se reinició el equipo, no se instaló el paquete completo sobre la instalación habitual ni se hizo una nueva prueba física USB. El producto no tiene firma Authenticode.

Las versiones anteriores, incluidos [V5.2.3](https://github.com/Conde-de-Lemos/auraled/releases/tag/v5.2.3-beta.4) y [V5.2.2](https://github.com/Conde-de-Lemos/auraled/releases/tag/v5.2.2-beta.3), permanecen disponibles. Los archivos automáticos «Source code» de GitHub contienen este repositorio de distribución; las fuentes de la aplicación y del motor acompañan al instalador.

Para mantenimiento: conservar el nombre del activo `Istalador.Auraled.exe` en cada nueva publicación; no es necesario editar el botón de la web. Cada cambio posterior lleva una nueva versión numérica y conserva las entregas anteriores.

[Guía de instalación y soporte](https://auraled-flow.marketing-lemos-agencia.workers.dev/instalacion#descargas)
