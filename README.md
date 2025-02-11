# PPSActividad4Unidad1Ignacio

## 🔍 Buscar alternativas para probar la aplicación en una Sandbox
Existen varias formas de crear un entorno controlado para probar tu aplicación:

- **Máquina Virtual**: Puedes usar VirtualBox o VMware para crear un entorno aislado.
- **Docker**: Si tu aplicación es compatible con contenedores, puedes crear una imagen y ejecutarla en un contenedor Docker.
- **Emuladores**: Si tu aplicación es móvil, puedes usar Android Studio (para Android) o Xcode (para iOS).
- **Sandbox online**: Puedes usar servicios como [JSFiddle](https://jsfiddle.net/) (para JavaScript), [Replit](https://replit.com/) o [CodeSandbox](https://codesandbox.io/) dependiendo del lenguaje de programación de tu calculadora.
- **Entorno Virtual Python**: Si tu aplicación está en Python, puedes usar `venv` para aislar dependencias.

## 🛠 Pasos para la prueba en Windows Sandbox

### 1️⃣ Activar Windows Sandbox (si no está habilitado)
1. Abrir **"Activar o desactivar características de Windows"**.

![](/Imagenes/1.png)


2. Buscar **Windows Sandbox** y marcar la casilla.

![](/Imagenes/2.png)

3. Hacer clic en **Aceptar** y reiniciar el sistema si es necesario.

### 2️⃣ Ejecutar Windows Sandbox
1. Abrir **Windows Sandbox** desde el menú de inicio.

![](/Imagenes/3.png)

2. Se iniciará un entorno limpio y temporal de Windows.

### 3️⃣ Copiar los archivos de la calculadora
1. Desde el sistema anfitrión, copiar los archivos de la aplicación.
2. Pegarlos dentro de la ventana de Windows Sandbox.

### 4️⃣ Instalar dependencias y ejecutar la aplicación
- Si la aplicación requiere instalación de dependencias, usar los siguientes comandos según el entorno. En este caso instalamos python.

### 5️⃣ Realizar pruebas funcionales
- Probar las operaciones básicas: suma, resta, multiplicación y división.

![](/Imagenes/4.png)

![](/Imagenes/5.png)

### 6️⃣ Cerrar Windows Sandbox
- Una vez terminadas las pruebas, cerrar Windows Sandbox.
- Todos los archivos y cambios realizados dentro del entorno desaparecerán automáticamente.
