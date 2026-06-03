<div align="center">

# DevOps Portfolio - Rodriguez Facundo

Path Operaciones 1 - Ingeniería en DevOps

[![TP12 Portfolio Check](https://github.com/facundo-rodriguez/devops-TP12/actions/workflows/portfolio-check.yml/badge.svg)](https://github.com/facundo-rodriguez/devops-TP12/actions)
[![Licencia MIT](https://img.shields.io/badge/licencia-MIT-green.svg)](LICENSE)
[![Hecho en WSL2](https://img.shields.io/badge/entorno-WSL2%20%2B%20Ubuntu-orange.svg)](https://ubuntu.com)

</div>

## Sobre este portfolio
Este espacio documenta mi recorrido práctico en la materia **Operaciones 1**, donde aprendí e implementé los pilares de la cultura DevOps desde los fundamentos de Linux hasta la Infraestructura como Código (IaC) y Orquestación de Contenedores de nivel empresarial.

Cada trabajo práctico cuenta con su repositorio independiente, documentación rigurosa y un script automatizado `verificar.sh` que audita su correcto funcionamiento.

---

## Stack tecnológico

| Categoría | Herramientas |
| :--- | :--- |
| **Sistemas Operativos & Scripting** | Linux (Ubuntu), Bash |
| **Control de versiones** | Git, GitHub, Gitflow |
| **Contenedores & Orquestación Local** | Docker, Docker Compose |
| **CI/CD Automation** | GitHub Actions |
| **Monitoreo & Métricas** | Prometheus, Grafana |
| **Orquestación de Producción** | Kubernetes (kubectl, K3d, Helm, Ingress NGINX, HPA) |
| **Infraestructura como Código (IaC)** | Terraform (HCL, Modules, Local State, Docker Provider) |
| **Tecnologías del Backend** | Node.js, Express |
| **Base de Datos** | MySQL (Distribuido y Cloud-Hosted en Clever Cloud) |
| **Proxy Reverso / Web Servers** | Nginx |
| **Formatos de Serialización** | YAML, HCL, JSON |

---

## Proyectos por TP

### 🛠️ Mes 1: Fundamentos de Sistemas, Redes y Git
| TP | Proyecto | Tecnologías | Enlace |
| :---: | :--- | :--- | :--- |
| **01** | Script de automatización de respaldos | Bash, Linux scripting, Cron | [→ Ver Repositorio](https://github.com/facundo-rodriguez/tp1-operaciones1) |
| **02** | Gestión de usuarios, grupos y permisos | Linux, chmod, useradd | [→ Ver Repositorio](https://github.com/facundo-rodriguez/tp2-operaciones1) |
| **03** | Ciclo de vida completo con Gitflow | Git, GitHub, branching | [→ Ver Repositorio](https://github.com/facundo-rodriguez/devops-gitflow) |
| **04** | Serialización YAML y diagnóstico de red | YAML, bash, ping, dig, curl | [→ Ver Repositorio](https://github.com/facundo-rodriguez/tp4-operaciones1) |

### 🐳 Mes 2: Contenedores, Integración Continua y Monitoreo
| TP | Proyecto | Tecnologías | Enlace |
| :---: | :--- | :--- | :--- |
| **05** | API Node.js empaquetada en Docker | Docker, Node.js, Dockerfiles | [→ Ver Repositorio](https://github.com/facundo-rodriguez/devops-TP05) |
| **06** | Aplicación de Notas Multi-contenedor | Docker Compose, MySQL, Nginx | [→ Ver Repositorio](https://github.com/facundo-rodriguez/devops-TP06) |
| **07** | Pipeline CI/CD Automatizado | GitHub Actions, Docker Hub, Hooks | [→ Ver Repositorio](https://github.com/facundo-rodriguez/devops-TP06/actions) |
| **08** | Stack de Monitoreo en Tiempo Real | Prometheus, Grafana, Node Exporter | [→ Ver Repositorio](https://github.com/facundo-rodriguez/devops-TP08) |

### ☸️ Mes 3: Orquestación, Helm e Infraestructura como Código
| TP | Proyecto | Tecnologías | Enlace |
| :---: | :--- | :--- | :--- |
| **09** | Despliegue de Microservicios en Kubernetes | kubectl, Deployments, Services, Probes | [→ Ver Repositorio](https://github.com/facundo-rodriguez/devops-TP09) |
| **10** | Orquestación Elástica con Helm Chart | Helm, Ingress NGINX, Rewrite Rules | [→ Ver Repositorio](https://github.com/facundo-rodriguez/devops-TP10) |
| **11** | Infraestructura como Código con Terraform | Terraform, HCL, Modules, Docker Provider | [→ Ver Repositorio](https://github.com/facundo-rodriguez/devops-TP11) |
| **12** | Pipeline de Validación del Portfolio Final | GitHub Actions, Repo Audit, Linter | [→ Este Repositorio](https://github.com/facundo-rodriguez/devops-TP12) |

---

## Proyecto integrador: Notes App
La aplicación integrada a lo largo de este plan de estudios es un gestor de notas real con arquitectura moderna:
* **Flujo Operativo:** Código local → GitHub Actions (CI) → Construcción de Imagen Dinámica → Docker Hub → Orquestación en Kubernetes local (CD) con autoescalado (HPA).
* **Métricas de Rendimiento:** Monitoreo activo de solicitudes y estado del contenedor mediante Prometheus y Grafana.
* **Persistencia:** Conexión segura e híbrida apuntando a base de datos distribuida en la nube de Clever Cloud.

**Repositorio del Núcleo de la App:** [devops-TP06](https://github.com/facundo-rodriguez/devops-TP06)

---

## Cómo ver cada proyecto
Cada uno de los repositorios enumerados arriba cuenta con:
1. Un archivo `README.md` detallado que explica la teoría, instalación y comandos de uso.
2. Un script en `scripts/verificar.sh` para comprobar la correcta provisión del estado operativo en la consola.
3. Configuración declarativa e inmutable para levantarse mediante una única línea de comando.

---

## Plataformas usadas
* **[Killercoda](https://killercoda.com):** Pruebas de simulación rápidas y entornos limpios.
* **[GitHub](https://github.com):** Alojamiento de repositorios y automatización con Actions.
* **[Docker Hub](https://hub.docker.com):** Registro público y distribución de imágenes empaquetadas.
