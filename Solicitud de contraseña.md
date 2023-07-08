# Habilitar la solicitud de contraseña para acciones administrativas en Windows

1. Abrir `Editor del Registro`
2. Navegar a:

    ```path
    Equipo\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System
    ```

3. Abrir `ConsentPromptBehaviorAdmin` y cambiar "Información del valor" (_de `5`_) a `1` y dar clic en Aceptar.
4. _Desde ahora la computadora pedirá `contraseña`/`PIN` para cualquier acción de administrador en lugar de solo `Yes`/`No`_.
