# ☕ Sistema de Gestión para Cafetería - Proyecto Final (Bases de Datos)

Este repositorio contiene el desarrollo del **sistema de gestión para una cafetería** como trabajo final de la materia **Bases de Datos**. La aplicación está construida con **AngularJS** como frontend, conectada a una base de datos **SQL** mediante una API backend.

## 📋 Descripción del Proyecto

El sistema permite gestionar las operaciones básicas de una cafetería, incluyendo la administración de productos, empleados, pedidos y clientes. Implementa operaciones **CRUD** (Crear, Leer, Actualizar y Eliminar) sobre las entidades principales.

## 🛠️ Tecnologías Utilizadas

- **Frontend:** AngularJS
- **Backend:** Node.js (Express)
- **Base de Datos:** MySQL *(o PostgreSQL, SQL Server, etc.)*
- **Lenguaje:** JavaScript
- **ORM (opcional):** Sequelize / Knex / otro --EDITAR --

## 📁 Estructura del Proyecto
-- EDITAR --
/cafeteria-system/
│
├── frontend/ # Aplicación AngularJS
│ ├── index.html
│ ├── app/
│ │ ├── controllers/
│ │ ├── services/
│ │ └── views/
│ └── ...
│
├── backend/ # API REST (Node.js/Express)
│ ├── routes/
│ ├── models/
│ ├── controllers/
│ └── server.js
│
├── database/ # Scripts de creación y datos
│ ├── schema.sql
│ └── seed.sql
│
├── README.md
└── ...


## 🔑 Funcionalidades Principales

- Gestión de **productos** (cafés, alimentos, bebidas)
- Gestión de **categorías**
- Administración de **empleados**
- Registro de **clientes**
- Registro y control de **pedidos**
- Operaciones CRUD completas para cada entidad
- Conexión persistente con base de datos SQL
- Validaciones básicas en formularios

## 🗄️ Modelo Entidad-Relación

El modelo de base de datos está normalizado e incluye relaciones entre:

- Productos y Categorías (1:N)
- Pedidos y Clientes (N:1)
- Pedidos y Productos (N:M mediante tabla intermedia)
- Pedidos y Empleados (N:1)

*El diagrama E-R se encuentra en el archivo `/database/diagrama-er.png`.* --- EDITAR --

## 🚀 Instrucciones de Instalación

### Requisitos previos

- Node.js y npm
- MySQL (o tu motor de base de datos SQL)
- Git

### Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/cafeteria-system.git
cd cafeteria-system


