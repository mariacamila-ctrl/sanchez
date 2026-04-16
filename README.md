# Beauty-Studio

# PROYECTO GRUPAL:

Nombre Equipo: los galacticos

Enlace repositorio: https://github.com/mariacamila-ctrl/Beauty-Studio.git

Nombre de Integrantes:

carlos santiago achipiz

victor alejandro pantoja

maria camila sanchez

IDENTIFICACIÓN DE LA ORGANIZACIÓN Y EL PROBLEMA

Nombre de la empresa: Beauty Studio
Sector económico: Sector terciario (comercio y servicios de belleza)

Descripción del problema

Beauty Studio no cuenta actualmente con un sistema de información automatizado para la gestión del inventario

y el registro de ventas. Estas actividades se realizan de forma manual, lo que genera:

Falta de control en las existencias

Riesgo de desabastecimiento

Pérdidas económicas por errores humanos

Dificultad para generar reportes

Procesos administrativos ineficientes

La ausencia de un sistema limita la toma de decisiones basadas en datos confiables y actualizados.

SOLUCIÓN PROPUESTA

Se propone el diseño e implementación de un sistema de información que permita:

Registrar productos (nombre, código, precio, cantidad)

Actualizar automáticamente el inventario

Generar reportes de ventas (diarios, semanales, mensuales)

Controlar niveles mínimos de stock

Reducir errores humanos

Resultado esperado: Mejorar la gestión interna, aumentar la productividad y optimizar el servicio al cliente.

ARQUITECTURA DEL SISTEMA

📥 ENTRADAS (Inputs)

Datos de productos:

Código

Nombre

Categoría

Precio

Cantidad disponible

Datos de ventas:

Fecha y hora

Productos vendidos

Cantidad

Total

Método de pago

Datos de proveedores:

Nombre

Contacto

Productos suministrados

Precio de compra

Datos de usuarios:

Nombre

Usuario y contraseña

Rol

Responsables:

Vendedores: registran ventas

Administrador: gestiona productos y usuarios

Tipos de datos:

Numéricos: precios, cantidades

Texto: nombres, códigos, categorías

🔨 PROCESOS (Throughput)

Almacenamiento:

Base de datos estructurada (productos, ventas, usuarios)

Procesamiento:

Cálculo automático de ventas

Actualización del inventario

Generación de ingresos

Validaciones:

Campos obligatorios

Tipos de datos correctos

Formatos válidos

Cálculos:

Total = precio × cantidad

Stock = stock actual − ventas

📤 SALIDAS (Outputs)

Información generada:

Estado del inventario en tiempo real

Registro actualizado de ventas

Reportes:

Ventas (diarias, semanales, mensuales)

Productos más vendidos

Productos con bajo stock

Ingresos totales

Otros:

Facturas o comprobantes digitales

👥 USUARIOS Y ROLES

Administrador:

Control total

Gestión de productos, usuarios y reportes

Vendedor/Cajero:

Registro de ventas

Consulta de productos

Control de acceso:

Basado en roles

Permisos diferenciados

📌 INFORMACIÓN CRÍTICA

Datos críticos:

Inventario (cantidades, códigos)

Ventas (historial, totales)

Precios

Datos que no se pueden perder:

Historial de ventas

Información de productos

Inventario

Usuarios y accesos

🎯 IMPACTO DEL SISTEMA

Problemas que soluciona:

Desorganización operativa

Falta de control administrativo

Información poco confiable

Ineficiencia en procesos

Niveles de decisión:

Operativo: control diario

Táctico: gestión de inventario

Estratégico: crecimiento del negocio

DECISIONES QUE PERMITE TOMAR

Reposición de productos

Identificación de productos más vendidos

Aplicación de promociones

Control de ingresos

Planeación del crecimiento
