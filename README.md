# Math-IA's 🧮 

<div align="center">

<img src="https://nestjs.com/img/logo-small.svg" width="25" alt="Nest Logo">
<img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" width="25" alt="Next Logo">
<img src="https://www.vectorlogo.zone/logos/mongodb/mongodb-icon.svg" width="25" alt="Mongo Logo">
<img src="https://www.docker.com/sites/default/files/d8/2019-07/vertical-logo-monochromatic.png" width="25" alt="Docker Logo">

---

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/NestJS-10.0.0-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Next.js-14.0.0-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"/></a>
  <a href="#"><img src="https://img.shields.io/badge/MongoDB-7.0-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/></a>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/TanStack-5.0.0-FF4154?style=for-the-badge&logo=react-query&logoColor=white" alt="TanStack"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Swagger-3.0-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" alt="Swagger"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Docker-24.0-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/></a>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Notion-Documentation-000000?style=for-the-badge&logo=notion&logoColor=white" alt="Notion"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Postman-API_Testing-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman"/></a>
</p>

</div>

<div align="center">

```diff
+ Plataforma de Aprendizaje Inteligente de Cálculo con IA 🤖
! Versión Actual: 1.0.0-beta
# Estado: En Desarrollo Activo
```

</div>

<div align="center">

|  💻 Requisitos Mínimos   | 🚀 Tecnologías Principales | 🛠️ Herramientas de Desarrollo |
|------------------------|-------------------------|----------------------------|
| Node.js >= 18         | NestJS                 | Docker                    |
| MongoDB >= 7.0        | Next.js                | Postman                   |
| Docker >= 24.0        | TanStack Query         | Notion                    |
| RAM >= 4GB            | JWT Authentication     | Git                       |

</div>

## 🎯 Visión General

Math-IA's revoluciona el aprendizaje del cálculo combinando la potencia de la IA con pedagogía moderna. Nuestra plataforma ofrece:

<div align="center">

```mermaid
graph LR
    A[Estudiante] --> B[Contenido Adaptativo]
    B --> C[Práctica Interactiva]
    C --> D[Evaluación IA]
    D --> E[Retroalimentación]
    E --> A
```

</div>

### ✨ Características Destacadas

<div align="center">

| 🤖 IA | 📊 Visualización | 🎯 Aprendizaje | 🤝 Colaboración |
|------|-----------------|---------------|----------------|
| Tutor Virtual | Gráficas 3D | Ejercicios Adaptativos | Foros en Tiempo Real |
| Análisis de Errores | Animaciones | Rutas Personalizadas | Grupos de Estudio |
| Sugerencias Smart | Manipulación Interactiva | Evaluación Continua | Tutoría P2P |

</div>

## 🚀 Inicio Rápido

<div align="center">

```bash
# 🔨 Instalación en un paso
docker-compose up -d
```

</div>

<details>
<summary>📝 Configuración Detallada</summary>

```bash
# 1. Clonar repositorio
git clone https://github.com/tu-usuario/math-ias.git

# 2. Configurar ambiente
cp .env.example .env

# 3. Instalar dependencias
npm install

# 4. Iniciar servicios
docker-compose up -d

# 5. Ejecutar migraciones
npm run migrations
```

</details>

## 📚 Stack Tecnológico Detallado

<div align="center">

| Backend | Frontend | DevOps | Herramientas |
|---------|----------|---------|--------------|
| ![NestJS](https://img.shields.io/badge/NestJS-10.0.0-E0234E) | ![Next.js](https://img.shields.io/badge/Next.js-14.0.0-black) | ![Docker](https://img.shields.io/badge/Docker-24.0-2496ED) | ![Postman](https://img.shields.io/badge/Postman-Latest-FF6C37) |
| ![MongoDB](https://img.shields.io/badge/MongoDB-7.0-47A248) | ![TanStack](https://img.shields.io/badge/TanStack-5.0.0-FF4154) | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-Latest-2088FF) | ![Notion](https://img.shields.io/badge/Notion-Latest-000000) |
| ![Swagger](https://img.shields.io/badge/Swagger-3.0-85EA2D) | ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.0-38B2AC) | ![Nginx](https://img.shields.io/badge/Nginx-Latest-009639) | ![VSCode](https://img.shields.io/badge/VSCode-Latest-007ACC) |

</div>

## 🏗️ Arquitectura

<div align="center">

```mermaid
graph TD
    A[Cliente] -->|HTTP/WS| B[Load Balancer]
    B --> C[Next.js Frontend]
    C -->|API| D[NestJS Backend]
    D -->|Queries| E[MongoDB]
    D -->|Cache| F[Redis]
    D -->|Search| G[Elasticsearch]
```

</div>

## 📊 Estructura del Proyecto

<div align="center">

```plaintext
math-ias/
├── 📂 backend/               # API NestJS
│   ├── 📂 src/              # Código fuente
│   │   ├── 📂 modules/      # Módulos
│   │   ├── 📂 common/       # Utilidades
│   │   └── 📂 config/       # Configuración
├── 📂 frontend/             # App Next.js
│   ├── 📂 src/             
│   │   ├── 📂 components/   # Componentes
│   │   ├── 📂 pages/       # Páginas
│   │   └── 📂 hooks/       # Hooks
└── 📂 docker/              # Config Docker
```

</div>

## 🔄 CI/CD

<div align="center">

| Ambiente | Branch | Deploy | Status |
|----------|--------|---------|---------|
| 🧪 Dev | `develop` | Auto | [![Dev](https://img.shields.io/badge/dev-passing-success)]() |
| 🚦 Stage | `staging` | Manual | [![Stage](https://img.shields.io/badge/staging-testing-yellow)]() |
| 🚀 Prod | `main` | Manual | [![Prod](https://img.shields.io/badge/prod-stable-success)]() |

</div>

## 📈 Estado del Proyecto

<div align="center">

| Métrica | Estado |
|---------|--------|
| Cobertura de Tests | ![Coverage](https://img.shields.io/badge/coverage-87%25-brightgreen) |
| Build Status | ![Build](https://img.shields.io/badge/build-passing-success) |
| Dependencies | ![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-success) |
| Code Quality | ![Quality](https://img.shields.io/badge/quality-A-success) |

</div>

## 📖 Documentación

<div align="center">

| Recurso | URL |
|---------|-----|
| 📚 API Docs | `http://localhost:3001/docs` |
| 📝 Wiki | [Project Wiki](https://notion.com/math-ias) |
| 🎥 Demos | [Video Tutorials](https://youtube.com) |

</div>

## 🤝 Contribución

<div align="center">

```mermaid
gitGraph
    commit
    branch feature
    checkout feature
    commit
    commit
    checkout main
    merge feature
    commit
    commit
```

</div>

## 📞 Contacto

<div align="center">

| Canal | Link |
|-------|------|
| 📧 Email | [desarrollo@math-ias.com](mailto:desarrollo@math-ias.com) |
| 💬 Discord | [Servidor Math-IA's](https://discord.gg/math-ias) |
| 🐦 Twitter | [@math_ias](https://twitter.com/math_ias) |

</div>

## 📄 Licencia

<div align="center">

MIT © [Math-IA's Team](LICENSE)

</div>