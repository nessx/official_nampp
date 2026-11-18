# Nampp 1.0.1

Entorno de desarrollo local para Windows: Apache, Nginx, MySQL/MariaDB, PostgreSQL, MongoDB, Redis, Memcached, Mailpit y PHP, con hosts virtuales `{nombre}.test`, HTTPS local y creación rápida de sitios.

## Novedades

- **Actualizaciones automáticas.** Nampp busca versiones nuevas en esta página de releases al abrirse y cada 6 horas. Si hay una más reciente, la descarga, comprueba su SHA-256 y la instala en silencio. Después se cierra y vuelve a abrirse ya actualizado.
- **Buscar actualizaciones a mano** desde el menú de la bandeja o desde *Preferencias → Actualizaciones*.
- **Opción para desactivarlas:** casilla *"Descargar e instalar automáticamente las nuevas versiones de Nampp"* en Preferencias.

## Instalación

1. Descarga **`Nampp-Setup-1.0.1.exe`** (más abajo, en *Assets*).
2. Ejecútalo y acepta el permiso de administrador. Nampp se instala en `C:\Program Files (x86)\Nampp`.
3. La carpeta de trabajo (`www`, `bin`, `data`…) se crea en `%USERPROFILE%\Nampp` y no se toca al actualizar ni al desinstalar.

## Actualizar desde una versión anterior

- **Desde 1.0.0 con actualizador:** no hace falta hacer nada; Nampp se actualiza solo.
- **Desde la 1.0.0 original (sin actualizador):** instala este `.exe` a mano una vez. Las siguientes versiones llegarán solas.

Al actualizar, Windows pedirá permiso de administrador. Los servicios en marcha se detienen antes de instalar.

## Verificación

SHA-256 de `Nampp-Setup-1.0.1.exe`:

`cdd820f9e0117ff019af613548e0fd3a8cb2cd888573f5b8692349307295401c`

## Requisitos

- Windows 10 u 11 de 64 bits.
- Microsoft Visual C++ Redistributable (Nampp avisa si falta).
