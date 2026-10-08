<!-- ============================================================
  README DE PERFIL DE GITHUB
  1. Crea un repositorio PÚBLICO con el mismo nombre que tu usuario
  2. Marca "Add a README"
  3. Pega este contenido y sube también header.svg y footer.svg al repo; edita "Tu Nombre" dentro de header.svg; reemplaza TU-USUARIO (stats), y los [CORCHETES] de contacto
============================================================ -->

<div align="center">

<img src="./header.svg" width="100%" alt="header" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=36BCF7&center=true&vCenter=true&width=700&lines=11%2B+a%C3%B1os+convirtiendo+requisitos+en+productos;Arquitecturas+Serverless+en+AWS+%E2%98%81%EF%B8%8F;Migraciones+GCP+%E2%86%92+AWS;Angular+%C2%B7+React+%C2%B7+Ionic+%C2%B7+Spring+Boot+%C2%B7+Django;Automatizo+despliegues%2C+no+excusas+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

![Años](https://img.shields.io/badge/Experiencia-11%2B%20a%C3%B1os-0A66C2?style=for-the-badge&logo=github&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Serverless-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Madrid](https://img.shields.io/badge/Madrid-Espa%C3%B1a-C60B1E?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

---

## 👨‍💻 Sobre mí

Desarrollador **full stack** con más de **11 años de experiencia** liderando equipos y entregando productos **móviles y web** para clientes corporativos y proyectos internos.

Mi enfoque es simple: **convertir requisitos en productos operativos**, reduciendo tiempos de despliegue y elevando la calidad mediante **automatización e integración continua**.

```text
🔭 Ahora trabajo en     →  Spring Boot + Angular on-premise (TRC)  ·  Django + Angular + ML (Medical Data)
🌱 Liderando            →  Plataforma de facturación electrónica con la DGII (Rep. Dominicana)
☁️ Especialidad         →  Serverless en AWS · Microservicios · CI/CD
🧠 Me apasiona          →  OCR, Computer Vision y automatización de procesos
🎯 Filosofía            →  Si se repite más de dos veces, se automatiza
```

---

## 🛠️ Stack tecnológico

<div align="center">

**Lenguajes**

<img src="https://skillicons.dev/icons?i=py,js,ts,nodejs,java&theme=dark" alt="lenguajes" />

**Frontend & Mobile**

<img src="https://skillicons.dev/icons?i=angular,react,ionic,html,css&theme=dark" alt="frontend" />

**Backend & APIs**

<img src="https://skillicons.dev/icons?i=django,express,spring&theme=dark" alt="backend" />

**Cloud & DevOps**

<img src="https://skillicons.dev/icons?i=aws,gcp,docker,kubernetes,jenkins,bitbucket,git,linux&theme=dark" alt="cloud" />

**Diseño & Gestión**

<img src="https://skillicons.dev/icons?i=figma,jira&theme=dark" alt="herramientas" />

</div>

<details>
<summary><b>📋 Ver detalle completo por categoría</b></summary>
<br/>

| Categoría | Tecnologías |
|:--|:--|
| **Lenguajes** | Python · JavaScript · TypeScript · Node.js |
| **Frontend** | Angular · React · Ionic · Microfrontends · PrimeNG |
| **Backend & APIs** | Django REST · Spring Boot · Express · RESTful APIs |
| **AWS** | Lambda · EC2 · S3 · Elastic Beanstalk · Amplify · CloudFormation · Serverless Framework |
| **Mensajería** | SQS · SNS · ActiveMQ · EventBridge |
| **CI/CD & Repos** | Bitbucket Pipelines · Jenkins · Git · OpenShift |
| **Data & ML Ops** | OCR · Computer Vision (firmas y rostros) · Web Scraping · Machine Learning |
| **Contenedores** | Docker · Kubernetes · VPS · Monitoreo y logging |
| **Metodologías** | Agile · Liderazgo de equipos · Diseño con Figma · Pruebas automatizadas |

</details>

---

## ☁️ Arquitectura que me gusta construir

Un ejemplo del tipo de pipeline serverless que he llevado a producción para procesamiento documental:

```mermaid
flowchart LR
    A[📄 Documento subido] -->|Trigger| B[(S3)]
    B --> C{{Lambda<br/>OCR + Clasificación}}
    C --> D[[SQS]]
    D --> E{{Lambda<br/>Procesamiento}}
    E --> F[[SNS]]
    F --> G[📊 Plataforma Web<br/>Angular / React]
    H((EventBridge)) -.orquesta.-> C
    H -.orquesta.-> E

    style B fill:#FF9900,color:#fff,stroke:#cc7a00
    style C fill:#2c5364,color:#fff
    style E fill:#2c5364,color:#fff
    style D fill:#d6336c,color:#fff
    style F fill:#d6336c,color:#fff
    style G fill:#0A66C2,color:#fff
```

---

## 📈 Resultados que hablan

<div align="center">

| 🚀 Impacto | 📌 Dónde |
|:--:|:--|
| **−80%** en tiempo de procesamiento | Automatización de ingesta documental con OCR (Tooles) |
| **15,000+** documentos digitalizados y categorizados | Pipeline OCR sobre AWS Lambda para CorTolima |
| **−20%** en tiempo de desarrollo front | Librería de componentes reutilizables (NXS / Carvajal) |
| **−50%** en tiempo de respuesta a QA | Mejora de procesos de entrega (NXS) |
| **500+** usuarios alcanzados | Modernización de plataformas y visión artificial |

</div>

---

## 💼 Trayectoria profesional

```text
2026 ─ hoy   ▸ TRC ·················· Full Stack (Spring Boot, Angular, Jenkins, OpenShift)
2025 ─ hoy   ▸ Medical Data ········· Líder de APIs hospitalarias (Django) + Angular + ML
2024 ─ 2025  ▸ NXS Oficial ·········· Microfrontends Angular, Ionic, Spring Boot, ActiveMQ/SQS
2023 ─ 2024  ▸ Tooles ··············· OCR + Serverless AWS (Lambda, SQS, SNS, EventBridge)
2021 ─ 2023  ▸ FabioArias ··········· Migración a AWS, CI/CD, detección de firmas y rostros
2020 ─ 2025  ▸ geww media & tech ···· Líder técnico · Migración GCP → AWS (Finky)
2009 ─ 2025  ▸ Freelance ············ Soluciones web y móviles end-to-end
2015 ─ 2021  ▸ Iglesia de Dios ······ Project Manager de proyectos tecnológicos
2014 ─ 2015  ▸ Dynamic Consultants ·· Consultor técnico (módulos financieros y BI con QlikView)
```

<details>
<summary><b>⭐ Proyectos destacados</b></summary>
<br/>

- 🏛️ **Plataforma para ministerio:** microcomponentes en Spring Boot y vistas en Angular, despliegue con Git + Jenkins + OpenShift (100% on-premise).
- 🏥 **Plataforma hospitalaria:** APIs en Django, front en Angular y flujos acelerados con machine learning.
- 🧾 **Facturación electrónica DGII:** liderazgo técnico del proyecto de facturación para República Dominicana.
- 📱 **Sindispetrol (Ecopetrol):** app móvil Android/iOS con Ionic + Angular y portal administrativo. *Rol: líder técnico.*
- 🔁 **Migración Finky:** migración completa de GCP a AWS (APIs, front y despliegues en EC2/Elastic Beanstalk).
- 🛒 **E-commerce Jireth:** tienda online completa, de catálogo a gestión de pedidos.
- 🩺 **App de telemedicina:** aplicación móvil con backend en Python para gestión de información clínica.
- ✍️ **Visión artificial:** detección de firmas y rostros desplegada en Lambdas.

</details>

---

## 📊 Estadísticas de GitHub
<div align="center"> <img src="./profile-summary-card-output/tokyonight/3-stats.svg" height="170" alt="stats" /> <img src="./profile-summary-card-output/tokyonight/2-most-commit-language.svg" height="170" alt="lenguajes" /> </div>


---

## 🤝 Hablemos

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectemos-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/[TU-LINKEDIN])
[![Email](https://img.shields.io/badge/Email-Escr%C3%ADbeme-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:[TU-CORREO])
[![Portfolio](https://img.shields.io/badge/Portfolio-Visitar-2c5364?style=for-the-badge&logo=googlechrome&logoColor=white)]([TU-WEB])

<br/>

*💬 Pregúntame sobre: arquitecturas serverless en AWS, migraciones a la nube, CI/CD, microfrontends con Angular o cómo llevar OCR a producción.*

<img src="./footer.svg" width="100%" alt="footer" />

</div>
