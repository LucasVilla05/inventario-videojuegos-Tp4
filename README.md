# inventario-videojuegos-Tp4
# 🎮 Sistema de Seguimiento de Inventario de Videojuegos

Este proyecto fue desarrollado por **Lucas Matías Villavicencio** como parte del **Trabajo Práctico N.º 4** de la materia **Seminario de Práctica en Informática** de la Universidad Siglo 21.

El sistema permite gestionar un inventario personal de videojuegos, evitando duplicados y recomendando nuevos títulos, utilizando **Java** y **MySQL**. Se aplican principios de **programación orientada a objetos**, conexión a base de datos con **JDBC**, manejo de **excepciones**, uso de **interfaces** y estructuras como **ArrayList**.

---

## 📌 Funcionalidades principales

- Registro de usuarios.
- Agregado de videojuegos con validación de duplicados.
- Almacenamiento persistente en base de datos MySQL.
- Visualización y búsqueda de videojuegos.
- Generación de recomendaciones (estructura preparada).
- Uso de clases abstractas, herencia, interfaces y excepciones.
- Menú por consola para pruebas interactivas.

---

## 🧱 Tecnologías utilizadas

- 🧩 Java SE 17
- 💾 MySQL
- 🛠️ JDBC
- 💻 IDE: IntelliJ IDEA / NetBeans
- 🔐 Manejo de excepciones
- 📦 Arquitectura modular con patrón DAO

---

## 📂 Estructura del proyecto

inventario-videojuegos-Tp3/
├── modelo/
│ ├── Usuario.java
│ ├── Videojuego.java
│ ├── VideojuegoFisico.java
│ ├── Inventario.java
│ └── InterfazRecomendador.java
│
├── dao/
│ ├── ConexionBD.java
│ ├── UsuarioDAO.java
│ └── VideojuegoDAO.java
│
├── Main.java
└── esquema_bd.sql

yaml
Copiar código

---

## ⚙️ Requisitos

- Java JDK 17+
- MySQL Server
- IDE de Java (IntelliJ IDEA, NetBeans, Eclipse)
- Conector JDBC para MySQL

---

## 🚀 Cómo ejecutar

1. **Clonar el repositorio:**

```bash
git clone https://github.com/LucasVilla05/inventario-videojuegos-Tp3.git
Importar en tu IDE preferido.

Ejecutar el script SQL:

Abrí MySQL y ejecutá el archivo esquema_bd.sql para crear la base de datos y las tablas necesarias:

sql
Copiar código
SOURCE ruta/al/archivo/esquema_bd.sql;
Verificar configuración JDBC:

En ConexionBD.java, asegurate de que los datos coincidan con tu entorno:

java
Copiar código
private static final String URL = "jdbc:mysql://localhost:3306/inventario_juegos";
private static final String USUARIO = "root";
private static final String CONTRASEÑA = "";
Ejecutar Main.java para probar funcionalidades.

🧪 Pruebas realizadas
Inserción de usuario y videojuego.

Prevención de duplicados.

Listado y búsqueda.

Conexión con MySQL vía JDBC.

Validación de menú sin errores.

🔐 Notas de seguridad
Se recomienda cifrar las contraseñas en versiones futuras.

Alineado a la Ley 25.326 de Protección de Datos Personales (Argentina).

📬 Contacto
Lucas Matías Villavicencio
📧 villavicenciolucas271@gmail.com
