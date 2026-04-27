# ⚽ TECHCUP FÚTBOL

Bienvenido/a a la organización **techcup-futbol-dosw**.  
Este espacio contiene los repositorios y servicios del proyecto **TechCup Fútbol**, basado en una arquitectura de microservicios (backend) + frontend.

---

## 🧠 Descripción

TECHCUP FÚTBOL es un sistema para la gestión de torneos deportivos que permite administrar usuarios, jugadores, equipos, torneos e invitaciones, aplicando buenas prácticas de arquitectura distribuida.

---

## 🧩 Arquitectura

El sistema está compuesto por múltiples componentes:

### 🖥️ Frontend
- `techcup-front`

### 🌐 API Gateway / Orquestación
- `techcup-apigateway`

### 🔧 Microservicios Backend

- 🔐 **Identidad / autenticación** → `techcup-identity`  
- 👤 **Usuarios y jugadores** → `techchup-users`  
- ⚽ **Equipos** → `techcup-teams`  
- 🏆 **Torneos** → `techcup-tournaments`  
- 📊 **Competencias** → `techcup-competitions`  

---

## 📦 Repositorios principales

| Repositorio | Descripción | Visibilidad |
|------------|------------|------------|
| `.github` | Configuración y documentación de la organización | Public |
| `techchup-users` | Servicio de Usuarios y Jugadores | Private |
| `techcup-apigateway` | API Gateway / Orquestador | Private |
| `techcup-competitions` | Servicio de Competencias | Private |
| `techcup-front` | Frontend del sistema | Private |
| `techcup-identity` | Servicio de identidad | Private |
| `techcup-teams` | Gestión de equipos | Private |
| `techcup-tournaments` | Servicio de torneos | Private |

---

## ⚙️ Tecnologías utilizadas

| Tecnología | Descripción |
| ---------- | ----------- |
| **Java 17+** | Lenguaje principal utilizado para el desarrollo |
| **Spring Boot** | Framework backend para APIs REST |
| **Maven** | Gestión de dependencias y build |
| **PostgreSQL** | Base de datos principal |
| **Spring Security** | Autenticación y autorización |
| **JWT** | Manejo de autenticación mediante tokens |
| **Docker (opcional)** | Contenerización |
| **GitHub Actions** | Integración y despliegue continuo (CI/CD) |
| **Azure App Service** | Plataforma de despliegue en la nube |

---

## 🚀 CI/CD

Cada microservicio implementa su propio pipeline independiente con:

- Build  
- Test  
- Deploy  

Esto permite que cada servicio sea desplegado y evolucionado de forma autónoma.

---

## 🌐 Despliegue

Cada servicio se encuentra desplegado en Azure:

| Servicio | URL |
|---------|-----|
| Usuarios | (agregar) |
| Identidad | (agregar) |
| Equipos | (agregar) |
| Torneos | (agregar) |

---

## 📋 Convenciones de desarrollo

Se recomienda que cada repositorio incluya:

- README con:
  - Descripción del servicio  
  - Requisitos (runtime, base de datos, variables de entorno)  
  - Instrucciones de ejecución  
  - Endpoints (si aplica)  
- Archivo `.env.example`  
- Documentación de cambios (`CHANGELOG.md` si aplica)

---

## 🔧 Flujo de trabajo (Git)

- Crear ramas desde `main`:
  - `feature/<nombre>`
  - `fix/<nombre>`

- Crear Pull Request con:
  - Qué cambia  
  - Cómo probarlo  
  - Notas o riesgos  

---

## 👥 Equipo

Proyecto desarrollado en el curso de Desarrollo de Software.

---

## 📌 Notas

- Arquitectura desacoplada  
- Base de datos por microservicio  
- Integración mediante APIs REST  
- Separación clara de responsabilidades entre servicios  

---

## 🔗 Organización

https://github.com/techcup-futbol-dosw
