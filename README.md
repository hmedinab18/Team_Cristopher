🏋️‍♂️ Gym Pro - Sistema de Gestión Integral

Team Cristopher presenta una solución moderna y eficiente para la administración de gimnasios. Esta es una aplicación web progresiva (SPA) que funciona directamente en el navegador, sin necesidad de servidores complejos ni bases de datos externas.

🚀 Características Principales

🖥️ Modo Kiosco (Pantalla de Inicio)

Interfaz Inmersiva: Pantalla completa con diseño profesional.

Registro Rápido: Los alumnos ingresan su DNI para marcar asistencia al instante.

Alertas Visuales: El sistema indica si el alumno está "Al Día", tiene "Deuda" o su membresía ha "Vencido".

Acceso Administrativo Oculto: Botón discreto en la esquina superior derecha para el login del staff.

👥 Gestión de Alumnos

Registro Completo: Datos personales, foto (opcional), teléfono y dirección.

Planes Flexibles: Selección de planes predefinidos con precio editable manualmente.

Control de Pagos: Registro de método de pago (Efectivo, Yape, Plin, Transferencia).

Directorio Protegido: Base de datos completa de alumnos protegida por PIN de seguridad.

Filtros: Por año y mes de ingreso.

Acciones: Editar saldo pendiente, cambiar estado (Pagado/Debe) y eliminar.

Exportar: Descarga de la lista de alumnos en formato .txt compatible con Excel.

📦 Inventario y Ventas (POS)

Punto de Venta: Venta rápida de productos con descuento automático de stock.

Gestión de Inventario (Protegido por PIN):

Control de Costo vs. Precio de Venta.

Cálculo automático de márgenes de ganancia.

Alertas de stock bajo.

Reposición y eliminación de productos.

💰 Finanzas (Protegido por PIN)

Reportes en Tiempo Real: Ingresos por inscripciones, ventas de productos y egresos.

Gestión de Gastos: Registro de salidas de dinero (Luz, Agua, Limpieza, etc.).

Filtros Inteligentes: Visualización de movimientos por Día, Mes o Año.

Balance Neto: Cálculo automático de ganancias reales.

⚙️ Configuración y Seguridad

Roles de Usuario:

Admin: Acceso total, gestión de usuarios, planes y seguridad.

Gestor: Gestión operativa sin acceso a configuración crítica.

Vendedor: Solo ventas y registro de asistencia/alumnos.

Gestión de Planes: Crear, editar y eliminar tipos de membresías (ej: 12 Clases, Libre, Personalizado).

Seguridad: PIN numérico único para bloquear el acceso a áreas sensibles (Inventario, Finanzas, Directorio).

🔐 Credenciales por Defecto

Al iniciar el sistema por primera vez, utiliza estas credenciales. Se recomienda cambiarlas inmediatamente en la sección de Configuración.

Usuario: usuario

Contraseña: usuario

PIN de Seguridad: 1234 (Para Inventario, Directorio y Finanzas)

🛠️ Instalación y Despliegue

Opción 1: Uso Local (Sin Internet)

Descarga el archivo index.html.

Asegúrate de que la imagen del logo Logo_TEAM_ Cristopher.png esté en la misma carpeta.

Haz doble clic en index.html para abrirlo en tu navegador (Chrome, Edge, Firefox).

Opción 2: Publicar en Internet (Vercel / GitHub Pages)

Para que tú y tu equipo puedan acceder desde cualquier lugar:

Crea un repositorio en GitHub.

Sube el archivo index.html y tu imagen de logo a la raíz del repositorio.

Conecta tu repositorio a Vercel o activa GitHub Pages.

¡Listo! Tendrás un enlace (ej: gym-pro.vercel.app) para compartir.

⚠️ Notas Importantes sobre los Datos

Este sistema utiliza LocalStorage para guardar toda la información (alumnos, ventas, configuraciones) directamente en el navegador de tu computadora.

No borres el caché: Si borras el historial/caché del navegador, perderás los datos.

Haz copias de seguridad: Usa la función de "Descargar Backup" (si se implementa a futuro) o exporta tus reportes regularmente.

Dispositivo Único: Los datos no se sincronizan entre computadoras diferentes a menos que uses una base de datos en la nube (versión futura).

Desarrollado para Team Cristopher.
