# ProyectoAlmacenamiento

Sistema de gestión de almacenamiento desarrollado en C# Windows Forms, orientado al control de productos, clientes, proveedores, rutas, transporte y entregas dentro de una base de datos.

---

## Descripción

Este proyecto permite administrar un sistema completo de almacenamiento y logística, incluyendo:

- Registro de productos
- Gestión de clientes y domicilios
- Control de proveedores
- Administración de transportistas y transporte
- Rutas de entrega
- Control de entregas y detalles
- Manejo de anaqueles (almacenamiento físico)

---

##  Estructura del proyecto

### Núcleo del sistema
- `Programa.cs` → Punto de entrada de la aplicación
- `Controlador de base de datos` → Manejo de conexión y consultas
- `ProyectoAlmacenamiento.csproj` → Configuración del proyecto

---

### Módulos principales

####  Productos
- `Producto.cs`
- `Producto.Designer.cs`
- `Producto.resx`

####  Clientes
- `Cliente.cs`
- `Cliente.Diseñador.cs`
- `Cliente.resx`
- `DomicilioCliente.cs`
- `DomicilioCliente.Diseñador.cs`

####  Proveedores
- `Proveedor.cs`
- `Proveedor.Diseñador.cs`
- `Proveedor.resx`

####  Almacenamiento
- `AlmacenamientoProducto.cs`
- `AlmacenamientoProducto.Designer.cs`
- `AlmacenamientoProducto.resx`
- `Anaquel.cs`
- `Anaquel.Diseñadora.cs`
- `Anaquel.resx`

####  Logística
- `Transporte.cs`
- `Transporte.Diseñador.cs`
- `Transportista.cs`
- `Transportista.Diseñador.cs`
- `Ruta.cs`
- `Ruta.Diseñador.cs`

####  Entregas
- `Entrega.cs`
- `Entrega.Designer.cs`
- `DetalleEntrega.cs`
- `DetalleEntrega.Designer.cs`

####  Interfaz principal
- `Menú del Proyecto almacenamiento.cs`
- `Menú del Proyecto almacenamiento.Designer.cs`
- `Menú del Proyecto almacenamiento.resx`

---

##  Tecnologías utilizadas

- C# (.NET Framework)
- Windows Forms (WinForms)
- SQL Server (conexión a base de datos)
- ADO.NET
- Configuración mediante `App.config`
- Paquetes NuGet (`packages.config`)

---



---
