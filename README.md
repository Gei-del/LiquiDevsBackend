<div align="center">

# 🍦 Byte Cream

### Plataforma de comercio electrónico Full Stack

**Proyecto colaborativo desarrollado por el equipo LiquidDevs**

Java · Spring Boot · MySQL · JPA · API REST · JavaScript · HTML · CSS · Git/GitHub

</div>

---

## 💡 ¿Qué es Byte Cream?

**Byte Cream** es una plataforma de comercio electrónico desarrollada de manera colaborativa por el equipo **LiquidDevs**.

El proyecto fue construido con un enfoque **Full Stack**, separando la interfaz web y los servicios backend en repositorios independientes.

La solución integra tecnologías de desarrollo frontend con un backend desarrollado en **Java y Spring Boot**, persistencia de información mediante **Spring Data JPA** y soporte para **MySQL**.

Byte Cream permitió al equipo aplicar conocimientos de desarrollo de software en un proyecto colaborativo, trabajando con control de versiones, integración de componentes, lógica de negocio y gestión de datos.

---

## 🎯 Objetivo

El objetivo de Byte Cream fue desarrollar una aplicación de comercio electrónico que permitiera aplicar conocimientos de desarrollo Full Stack en un escenario práctico.

Durante su construcción se trabajaron diferentes áreas:

- 🎨 Desarrollo frontend
- ⚙️ Desarrollo backend
- 🔗 Servicios web
- 🗄️ Persistencia de datos
- 👤 Gestión de usuarios
- 📦 Gestión de productos
- 🛒 Procesos asociados a compras y pedidos
- 🔐 Conceptos de seguridad
- 🌿 Control de versiones
- 🤝 Desarrollo colaborativo

---

## ✨ Funcionalidades

Byte Cream trabaja diferentes funcionalidades propias de una plataforma de comercio electrónico:

- 👤 Gestión de usuarios
- 🔐 Autenticación y acceso a funcionalidades
- 🛍️ Visualización de productos
- 📦 Gestión de productos
- 🛒 Experiencia de compra
- 📋 Gestión de pedidos
- 🧭 Navegación entre diferentes secciones
- 🎨 Interfaces y componentes visuales
- ⚙️ Lógica de negocio
- 🗄️ Persistencia de información
- 🔗 Comunicación entre los diferentes componentes de la aplicación

---

# 🛠️ Tecnologías

## 🎨 Frontend

La interfaz web fue desarrollada utilizando tecnologías fundamentales del desarrollo web.

- HTML5
- CSS3
- JavaScript
- Manipulación del DOM
- Gestión de eventos
- Diseño de interfaces
- Componentes web

---

## ⚙️ Backend

El backend de Byte Cream se encuentra en un repositorio independiente y fue desarrollado utilizando el ecosistema Java.

Tecnologías utilizadas:

- Java 17
- Spring Boot
- Spring Web MVC
- Spring Data JPA
- Spring Security
- Bean Validation
- Maven

El backend concentra la lógica relacionada con la gestión de información y los servicios necesarios para la aplicación.

---

## 🗄️ Base de datos y persistencia

El proyecto utiliza tecnologías de persistencia del ecosistema Spring.

- MySQL
- H2
- Spring Data JPA
- MySQL Connector/J

**MySQL** permite trabajar con una base de datos relacional para almacenar la información de la aplicación.

**Spring Data JPA** facilita la interacción entre las entidades Java y la capa de persistencia.

**H2** también está incluido en el backend como motor de base de datos disponible para el proyecto.

---

## 🔐 Seguridad

El backend incluye **Spring Security** dentro de sus dependencias.

Esta tecnología proporciona la base para implementar mecanismos relacionados con:

- Autenticación
- Autorización
- Protección de recursos
- Control de acceso

---

# 🏗️ Arquitectura general

Byte Cream separa la aplicación web y el backend en repositorios diferentes.

```text
                         🍦 BYTE CREAM
                              │
               ┌──────────────┴──────────────┐
               │                             │
               ▼                             ▼
        🎨 FRONTEND                     ⚙️ BACKEND
      HTML · CSS · JS              Java · Spring Boot
               │                             │
               │                             ├── Spring Web MVC
               │                             ├── Spring Data JPA
               │                             └── Spring Security
               │                             │
               └──────────────┬──────────────┘
                              │
                              ▼
                       🔗 Servicios Web
                              │
                              ▼
                      🗄️ Persistencia
                         MySQL · H2
```

Esta separación facilita la organización de responsabilidades entre la interfaz, la lógica de aplicación y la persistencia de datos.

---

# 📁 Estructura del proyecto

## 🎨 Frontend

```text
Proyecto-LiqueDevs/
│
├── Activos/
├── CSS/
├── Componentes/
├── Base de datos/
├── HTML/
├── JS/
│
├── acercaDeNosotros.html
├── paginaPrincipal.html
├── package.json
├── package-lock.json
└── README.md
```

---

## ⚙️ Backend

El backend se encuentra en un repositorio independiente:

```text
LiquiDevsBackend/
│
├── .mvn/
│   └── wrapper/
│
├── src/
│
├── .gitattributes
├── .gitignore
├── mvnw
├── mvnw.cmd
└── pom.xml
```

El archivo `pom.xml` administra las dependencias y configuración Maven utilizadas por el backend.

---

# 🔗 Repositorios

## 🎨 Frontend / aplicación principal

https://github.com/Gei-del/Proyecto-LiqueDevs

## ⚙️ Backend

https://github.com/Gei-del/LiquiDevsBackend

---

# 👥 Equipo LiquidDevs

Byte Cream fue desarrollado mediante trabajo colaborativo.

## 👩‍💻 Lorena Pontón

Participación en el desarrollo e implementación de funcionalidades, integración de componentes y diferentes etapas de construcción del proyecto.

## 👨‍💻 Luis Villada

Desarrollo y acompañamiento técnico del equipo, aportando experiencia en implementación y resolución de diferentes retos técnicos.

## 👨‍💻 Sebastián Leiva

Desarrollo e implementación de funcionalidades y participación en diferentes etapas de evolución del proyecto.

## 👩‍💻 Samary Cardoza

Desarrollo frontend, con especial participación en diseño visual, estilos, colores y construcción de landing pages.

---

## 🤝 Trabajo colaborativo

Una parte fundamental de Byte Cream fue desarrollar una solución tecnológica sobre una misma base de trabajo junto con otros desarrolladores.

El proceso incluyó:

```text
💡 Idea
   ↓
📋 Planeación y distribución de tareas
   ↓
🎨 Frontend + ⚙️ Backend
   ↓
🌿 Ramas de Git
   ↓
💻 Desarrollo
   ↓
📦 Commits
   ↓
🔀 Integración de cambios
   ↓
🔎 Revisión
   ↓
🛠️ Correcciones
   ↓
🍦 Byte Cream
```

Aunque cada integrante tuvo áreas de mayor afinidad, el proyecto fue construido mediante la participación y colaboración del equipo.

---

# 🌱 Aprendizajes

Byte Cream permitió fortalecer diferentes conocimientos técnicos y habilidades profesionales.

### 💻 Desarrollo Full Stack

- HTML
- CSS
- JavaScript
- Java
- Spring Boot
- Spring Web MVC
- Spring Data JPA
- Maven
- MySQL

### 🗄️ Datos

- Bases de datos relacionales
- Persistencia de información
- Entidades
- JPA
- Integración entre backend y base de datos

### 🔐 Backend

- Organización de aplicaciones Java
- Lógica de negocio
- Servicios web
- Persistencia
- Validación
- Conceptos de seguridad con Spring Security

### 🌿 Ingeniería de software

- Git
- GitHub
- Manejo de ramas
- Commits
- Integración de código
- Organización de repositorios
- Resolución de conflictos
- Desarrollo sobre una base de código compartida

### 🤝 Trabajo en equipo

- Distribución de responsabilidades
- Comunicación técnica
- Revisión conjunta
- Integración de funcionalidades
- Resolución colaborativa de problemas

---

# 🚀 Ejecutar el Frontend

## 1. Clonar el repositorio

```bash
git clone https://github.com/Gei-del/Proyecto-LiqueDevs.git
```

## 2. Entrar al proyecto

```bash
cd Proyecto-LiqueDevs
```

## 3. Instalar dependencias

```bash
npm install
```

Posteriormente puede ejecutarse la interfaz web desde el entorno local correspondiente.

---

# ⚙️ Ejecutar el Backend

## 1. Clonar el backend

```bash
git clone https://github.com/Gei-del/LiquiDevsBackend.git
```

## 2. Entrar al proyecto

```bash
cd LiquiDevsBackend
```

## 3. Ejecutar utilizando Maven Wrapper

### Windows

```bash
mvnw.cmd spring-boot:run
```

### Linux / macOS

```bash
./mvnw spring-boot:run
```

> Para utilizar MySQL es necesario configurar correctamente la conexión de base de datos correspondiente al entorno de ejecución.

---

# 📚 Contexto del proyecto

Byte Cream representa una experiencia práctica de construcción de software **Full Stack en equipo**.

El proyecto permitió trabajar no solamente en la creación de interfaces, sino también en conceptos relacionados con backend, persistencia de datos, seguridad, integración de componentes y control de versiones.

Además, trabajar con diferentes desarrolladores permitió experimentar con un flujo colaborativo de desarrollo utilizando Git y GitHub.

---

# 🚀 Posibles mejoras

Como evolución del proyecto se pueden explorar:

- Mejorar la experiencia responsive
- Fortalecer pruebas del backend
- Documentar los endpoints
- Incorporar documentación con OpenAPI / Swagger
- Mejorar validaciones
- Fortalecer autenticación y autorización
- Crear pruebas automatizadas
- Implementar CI/CD
- Desplegar frontend y backend
- Mejorar observabilidad y manejo de errores

---

<div align="center">

# 🍦 Byte Cream

### Una experiencia Full Stack construida en equipo.

**Java · Spring Boot · MySQL · JPA · JavaScript · HTML · CSS · Git · GitHub**

Desarrollado colaborativamente por **LiquidDevs** 🚀

</div>
