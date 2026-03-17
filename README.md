
# ☁️ Proyecto Cloud en Azure – Static Web App + API Serverless + Cosmos DB + Alertas + CI/CD + DevOps

Este proyecto demuestra una arquitectura cloud moderna utilizando servicios gratuitos de Azure, integrando prácticas de desarrollo, monitoreo, automatización y DevOps.  
Está diseñado para mostrar habilidades relevantes para certificaciones como **AZ‑900**, **AZ‑204** y conceptos aplicables a **AZ‑400**.

---

## 🚀 Arquitectura del Proyecto

### Servicios utilizados:
- **Azure Static Web Apps (Free Tier)**: Hosting global con CDN y despliegue automático desde GitHub.  
  Azure for Students proporciona acceso gratuito a servicios seleccionados, incluidos entornos para despliegues web y herramientas de aprendizaje. 
  
- **Azure Functions**: API serverless con escala automática y costos basados en consumo.

- **Azure Cosmos DB (Free Tier)**: Base de datos NoSQL con 1000 RU/s gratis.

- **Azure Monitor**:  
  - Alertas de métricas  
  - Activity Logs  
  - Dashboards  
  - Integración con aplicaciones  
  Azure Monitor permite centralizar métricas, logs y alertas de recursos para un monitoreo integral.

- **Cost Management + Budgets**:  
  - Presupuestos al 50%, 75% y 90% para evitar agotar crédito.  
  Las suscripciones de Azure for Students permiten revisar saldo y uso desde el portal mediante herramientas de patrocinio y gestión de costos. 

- **GitHub Actions (CI/CD)**:  
  Pipeline automatizado para build y deploy del frontend y backend.

---

## 🧩 Flujo de Trabajo DevOps (concepto alineado a AZ‑400)

Este proyecto implementa un flujo simplificado inspirado en prácticas de DevOps comunes:

1. **Control de versiones** con GitHub.  
2. **CI (Integración continua)** mediante GitHub Actions:
   - Instalación de dependencias  
   - Build de frontend  
   - Ejecución de pruebas unitarias  
3. **CD (Entrega continua)**:
   - Despliegue automático a Azure Static Web Apps  
4. **Infraestructura declarativa (opcional)**:
   - Templates Bicep para provisionar recursos  
5. **Monitoreo continuo**:
   - Dashboards en Azure Monitor  
   - Alertas por métricas y eventos  
6. **Governanza y FinOps**:
   - Presupuestos y control de crédito  

> Estas prácticas reflejan conceptos de DevOps (automation, CI/CD, monitoring, governance) y son consistentes con funcionalidades de Azure.

---

## 📁 Estructura del Repositorio

/frontend               <-- Aplicación estática
/api                    <-- Azure Functions (API serverless)
/infra/alertas          <-- Configuraciones de alertas y dashboards
/infra/bicep            <-- Infraestructura como código IaC
/docs                   <-- Diagramas y documentación
README.md





---

## 👤 Autor

**Mayela Alanis**  
Cloud‑Oriented Frontend & Serverless Developer  
GitHub: https://github.com/aalanissn
