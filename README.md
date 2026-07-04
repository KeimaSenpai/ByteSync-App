# ByteSync

<p align="center">
  <img src="assets/logo.png" alt="ByteSync Logo" width="150">
</p>

<h3 align="center">
Protege tus archivos con copias de seguridad automáticas y en tiempo real.
</h3>

<p align="center">
Olvídate de copiar archivos manualmente. ByteSync mantiene tus carpetas sincronizadas automáticamente mientras trabajas.
</p>

---

## 🚀 ¿Qué es ByteSync?

**ByteSync** es una aplicación de escritorio desarrollada con **Python, Flask y PyWebView** que crea copias de seguridad automáticas de tus carpetas en tiempo real.

Cada vez que creas, modificas, eliminas o mueves un archivo en la carpeta protegida, el cambio se replica instantáneamente en el destino elegido, sin necesidad de pulsar botones de sincronización ni ejecutar copias manuales.

Es una solución sencilla, rápida y completamente local para mantener tus archivos siempre respaldados.

---

# ✨ Características

## ⚡ Sincronización en tiempo real

ByteSync supervisa continuamente tus carpetas utilizando el sistema de archivos de Windows.

Cualquier cambio realizado en la carpeta de origen se replica automáticamente en el destino:

- 📄 Archivos nuevos
- ✏️ Modificaciones
- 🗑 Eliminaciones
- 📂 Movimientos y cambios de nombre

Todo ocurre de forma automática y transparente.

---

## 💾 Copias de seguridad automáticas

Antes de comenzar la sincronización en tiempo real, ByteSync crea una copia completa de la carpeta seleccionada para asegurar que ambos directorios sean idénticos.

Después de esa copia inicial, solo se sincronizan los cambios necesarios.

---

## 🔌 Compatible con discos y memorias USB

Puedes sincronizar tus archivos hacia:

- 💽 Discos duros internos
- 💿 Discos externos
- 🔌 Memorias USB
- 📁 Cualquier carpeta del equipo
- 🌐 Unidades compartidas de red

---

## 🔄 Reconexión inteligente

Si desconectas un disco externo o una memoria USB durante la sincronización, ByteSync detecta el cambio automáticamente.

Cuando el dispositivo vuelva a estar disponible podrás reanudar la copia sin necesidad de crear una nueva sincronización.

---

## 📁 Administra múltiples copias

Puedes crear tantas sincronizaciones como necesites.

Cada copia conserva:

- Carpeta de origen
- Carpeta destino
- Estado actual
- Disponibilidad del dispositivo
- Actividad en tiempo real

Todo desde una única interfaz.

---

## 📊 Actividad en vivo

Observa todo lo que sucede mientras ByteSync trabaja.

La aplicación muestra en tiempo real:

- Archivos copiados
- Archivos modificados
- Eliminaciones
- Carpetas creadas
- Cambios detectados

Sin necesidad de actualizar la ventana.

---

## ⚙️ Gestión sencilla

Desde el panel de configuración puedes:

- Crear nuevas copias de seguridad
- Administrar sincronizaciones existentes
- Reanudar copias pausadas
- Cambiar carpetas de destino
- Supervisar el estado de cada respaldo

---

## 🔄 Actualizaciones automáticas

ByteSync puede comprobar automáticamente si existe una nueva versión publicada en GitHub.

Incluye:

- Comprobación automática en segundo plano
- Búsqueda manual desde Ajustes
- Información de la versión instalada
- Acceso directo al último lanzamiento
- Notificación cuando hay una nueva actualización disponible

---

## 🎨 Interfaz moderna

Diseñada para ser simple y agradable de utilizar.

Características:

- 🌑 Tema oscuro
- ✨ Glassmorphism
- 📱 Diseño adaptable
- ⚡ Animaciones suaves
- 📂 Navegación intuitiva

---

## 🔒 Protección inteligente

Para evitar sincronizaciones innecesarias, ByteSync ignora automáticamente archivos temporales y carpetas del sistema como:

- `__pycache__`
- `.git`
- `node_modules`
- `Thumbs.db`
- `desktop.ini`
- `.tmp`
- `.lock`
- `.crdownload`

---

## ⚡ Alto rendimiento

La aplicación utiliza eventos del sistema de archivos para detectar cambios instantáneamente.

Esto significa:

- Sin escaneos constantes
- Sin consumo excesivo de CPU
- Sin esperas entre cambios

Solo sincroniza cuando realmente ocurre una modificación.

---

## 💻 Funciona completamente sin conexión

ByteSync no depende de servicios en la nube.

Tus archivos permanecen siempre bajo tu control.

No requiere:

- Cuentas
- Servidores externos
- Internet

---

# 🖥 Tecnologías

- Python
- Flask
- PyWebView
- Watchdog
- HTML5
- CSS3
- JavaScript
- Server-Sent Events (SSE)

---

# 💼 Ideal para

- Usuarios que desean proteger sus documentos
- Copias de seguridad personales
- Empresas
- Oficinas
- Diseñadores
- Programadores
- Fotógrafos
- Creadores de contenido
- Cualquier persona que quiera evitar perder información importante

---

# ❤️ ¿Por qué ByteSync?

✅ Copias de seguridad totalmente automáticas

✅ Sincronización instantánea en tiempo real

✅ Compatible con discos y memorias USB

✅ Administración de múltiples respaldos

✅ Bajo consumo de recursos

✅ Interfaz moderna y sencilla

✅ Funciona completamente sin conexión

✅ Mantén tus archivos siempre protegidos

---

# 📄 Licencia

Este proyecto se distribuye bajo la licencia MIT.

---

<p align="center">
Desarrollado con ❤️ en Python.
</p>
