# 🛒 eCommerce InnovaWeb - Gestión de Usuarios

[![Estado](https://img.shields.io/badge/Estado-En%20Desarrollo-yellow)]()
[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)]()
[![MySQL](https://img.shields.io/badge/MySQL-Modelado%203FN-4479A1?logo=mysql)]()
[![Licencia](https://img.shields.io/badge/Licencia-MIT-lightgrey)]()

Sistema de consola para la gestión de usuarios en un E-commerce de tecnología, desarrollado como Evidencia de Aprendizaje N° 3. Los usuarios pueden registrarse, iniciar sesión y acceder a funcionalidades específicas según su rol (administrador o usuario estándar).

## ✨ Características Principales

### 🔐 Sistema de Autenticación
- **Registro e inicio de sesión** con validaciones seguras
- **Control de acceso mediante roles** (admin/usuario)
- **Validación con expresiones regulares** para contraseñas
- **Prevención de usuarios duplicados**

### 👥 Gestión de Usuarios
- **Menús personalizados** según tipo de usuario
- **Ver datos de usuario** (propios y de otros según permisos)
- **Cambio de roles** (solo administradores)
- **Eliminación de usuarios** (solo administradores)

### 🗃️ Base de Datos
- **Modelo relacional normalizado** (Tercera Forma Normal - 3FN)
- **Diseño entidad-relación** con integridad referencial
- **Scripts SQL incluidos** para creación y operaciones CRUD

## 🚀 Tecnologías Utilizadas

### Desarrollo Principal
![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![VS Code](https://img.shields.io/badge/Editor-VS%20Code-007ACC?logo=visual-studio-code)

### Base de Datos
![MySQL](https://img.shields.io/badge/MySQL-Modelado%203FN-4479A1?logo=mysql&logoColor=white)

### Principios Aplicados
![POO](https://img.shields.io/badge/POO-Programación%20Orientada%20a%20Objetos-green)
![Regex](https://img.shields.io/badge/Validaciones-Expresiones%20Regulares-orange)

## 📦 Instalación y Ejecución

### Prerrequisitos
- Python 3.x instalado
- Visual Studio Code (recomendado)
- Extensiones de Python para VS Code

### Pasos para ejecutar
1. **Clonar o descargar el repositorio**
   ```bash
   git clone https://github.com/tuusuario/innovaweb_ecommerce.git
   cd innovaweb_ecommerce
Abrir el proyecto en VS Code

bash
code .
Ejecutar la aplicación

bash
python src/main.py
🗄️ Estructura de la Base de Datos
Scripts SQL Incluidos
crear_bd.sql → Creación de tablas y relaciones

crud_usuarios.sql → Operaciones CRUD para la tabla usuarios

Normalización
Tercera Forma Normal (3FN) aplicada

Integridad referencial garantizada

Modelo entidad-relación optimizado

📁 Estructura del Proyecto
text
innovaweb_ecommerce/
│
├── src/                          # Código fuente principal
│    ├── main.py                  # Punto de entrada del programa  
│    ├── menu_sistema.py          # Menú por rol
│    ├── sistema_auth.py          # Funciones de registro y login
│    └── user.py                  # Clase Usuario
│
├── database/                     # Scripts de base de datos
│    ├── Creacion de tablas.txt   # Script de creación de BD
│    └── CRUD para Usuarios.txt   # Consultas CRUD
│
├── docs/                         # Diagramas y documentación
│    ├── Diagrama de Clases.png  
│    └── Diagrama de Base de datos.png
│
└── Readme.md                     # Este archivo
🛡️ Validaciones Implementadas
Contraseñas
Mínimo 6 caracteres

Letras y números obligatorios

Expresiones regulares para validación

Usuarios
Prevención de duplicados

Control de errores con mensajes claros

Acceso restringido por rol

👨‍💼 Funcionalidades por Rol
Acción	Usuario Estándar	Administrador
Ver sus datos	✅	✅
Ver todos los usuarios	❌	✅
Cambiar rol de otro usuario	❌	✅
Eliminar un usuario	❌	✅
📊 Diagramas del Proyecto
Diagrama de Clases → /docs/Diagrama de Clases.png

Diagrama de Base de datos → /docs/Diagrama de Base de datos.png

🧩 Conceptos Aplicados
Programación Orientada a Objetos (POO)

Encapsulamiento de datos

Modularidad y separación de responsabilidades

Nomenclatura estándar (snake_case)

Validación con expresiones regulares

Modelado entidad-relación

Integridad referencial en bases de datos

👥 Integrantes del Proyecto
Nombre	Rol en el Proyecto
Acosta Johana Vanessa	Base de datos
Andreoli Fernando Daniel	Base de datos
Crespin Marianela Jenifer	Python
Molina Ricardo Alberto	Python
Vaca Cristian Andres	Python
📞 Soporte
Para consultas técnicas o problemas con la ejecución, revisar la documentación en la carpeta docs/ o contactar al equipo de desarrollo.

¡Gracias por usar nuestro sistema de gestión de usuarios! 🎉
