# EcoCatálogo ALFECOPLAST

**Proyecto Académico:** Asignatura Diseño Web – UNILATINA  
**Institución:** Institución Universitaria Latina (UNILATINA)  
**Desarrollo:** Backend & Arquitectura en Laravel  

---

## 1. Contexto del Proyecto

**ALFECOPLAST** es una empresa dedicada a la distribución de productos desechables, ecológicos y personalizados. Su propósito es ofrecer alternativas que ayuden a las empresas a cumplir con las regulaciones ambientales y reducir su impacto ecológico.

La estrategia **EcoCatálogo** consiste en una aplicación web interactiva que permite a los clientes:
- Conocer el portafolio de productos ecológicos y desechables.
- Consultar características detalladas de cada ítem.
- Seleccionar productos y definir cantidades para cotización.
- Solicitar personalizaciones de productos mediante el registro de logotipos, colores corporativos y observaciones específicas.
- Enviar solicitudes de cotización formalizadas.

---

## 2. Tipos de Usuarios y Roles

1. **Administrador:**
   - Gestión integral de categorías y productos (crear, editar, activar/desactivar).
   - Consulta y seguimiento de solicitudes de cotización recibidas.
   - Administración de usuarios y control de accesos.

2. **Cliente:**
   - Registro de cuenta e inicio de sesión seguro.
   - Navegación y búsqueda en el catálogo de productos.
   - Selección de productos, cantidades y formulario de personalización.
   - Registro, almacenamiento y envío de solicitudes de cotización.

---

## 3. Arquitectura y Requerimientos Técnicos

- **Framework:** Laravel (PHP 8.2+)
- **Base de Datos:** MySQL / MariaDB (relacional)
- **Gestor de Paquetes:** Composer
- **Control de Versiones:** Git & GitHub (`main`)
- **Manejo de Estados de UI:** Idle, Loading, Success, Error
- **Seguridad:** Protección estricta de variables de entorno (`.env`), sanitización de entradas, validaciones en servidor y control de roles/permisos.

---

## 4. Estructura de Seguridad y Control de Versiones

- El archivo `.env` se encuentra excluido mediante `.gitignore` para salvaguardar claves secretas y credenciales.
- Se provee `.env.example` como plantilla pública con valores por defecto.
