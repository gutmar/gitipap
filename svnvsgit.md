# Principales diferencias entre Subversion (SVN) y Git

1. Modelo de control de versiones

Subversion (SVN): Usa un modelo centralizado, donde todo el historial y la gestión del código residen en un servidor central. Los usuarios deben estar conectados para la mayoría de las operaciones.

Git: Utiliza un modelo distribuido, donde cada clon del repositorio contiene todo el historial del proyecto. Permite trabajar sin conexión y sincronizar cambios más adelante.

2. Flujo de trabajo

SVN: Promueve un flujo lineal y centralizado, basado en ramas limitadas (como trunk/branches/tags) y commits directamente al servidor.

Git: Favorece un flujo más flexible con ramas locales, lo que permite trabajar en paralelo sin afectar la rama principal hasta que se desee integrar.

3. Manejo de ramas

SVN: Las ramas son copias del código en diferentes carpetas del repositorio y suelen ser más pesadas.

Git: Las ramas son livianas, rápidas de crear y cambiar, facilitando el trabajo colaborativo y experimental.

4. Velocidad

SVN: Más lento en operaciones que requieren acceso al historial, ya que depende del servidor.

Git: Muy rápido en casi todas las operaciones (commit, diff, log) al trabajar localmente.

5. Manejo de cambios

SVN: Realiza seguimiento por archivos individuales.

Git: Realiza seguimiento por conjuntos de cambios (snapshots), lo que facilita el manejo de fusiones (merge) y revertir versiones.

6. Repositorio

SVN: Un solo repositorio central para todos los usuarios.

Git: Cada usuario tiene una copia completa del repositorio (incluyendo historial).

7. Trabajo colaborativo

SVN: Más dependiente de la conexión al servidor. Las integraciones múltiples simultáneas pueden generar conflictos.

Git: Favorece un trabajo asincrónico y descentralizado, permitiendo múltiples flujos de trabajo (feature branches, pull requests, etc.).

