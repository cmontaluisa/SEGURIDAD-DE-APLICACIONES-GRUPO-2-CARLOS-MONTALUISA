# SEGURIDAD-DE-APLICACIONES-GRUPO-2-CARLOS-MONTALUISA
Proyecto académico de Seguridad de Aplicaciones enfocado en la implementación de un pipeline DevSecOps con análisis automático de vulnerabilidades, pruebas unitarias y controles de seguridad en CI/CD.

# SEGURIDAD-DE-APLICACIONES GRUPO-2-CARLOS-MONTALUISA

## Descripción

Este repositorio corresponde a un laboratorio académico de la asignatura **Seguridad de Aplicaciones**, cuyo objetivo es implementar un pipeline **DevSecOps** que automatice controles de seguridad durante el ciclo de vida del desarrollo de software.

El proyecto utiliza **.NET 8** y un pipeline de **CI/CD en GitHub Actions** para integrar pruebas automatizadas, análisis de seguridad y verificación de dependencias vulnerables.

---

## Objetivo del proyecto

Implementar un pipeline automatizado que permita:

- Integrar controles de seguridad en el ciclo de vida del desarrollo de software.
- Detectar vulnerabilidades en el código fuente.
- Identificar dependencias con vulnerabilidades conocidas.
- Ejecutar pruebas unitarias automáticamente.
- Generar reportes de seguridad y análisis de código.

Este enfoque sigue el modelo **DevSecOps**, integrando seguridad desde las primeras etapas del desarrollo.

---

## Arquitectura del Pipeline DevSecOps

El pipeline implementado en este repositorio sigue el siguiente flujo:
Developer Push
│
▼
Security Scans
├─ Secret Scanning
├─ Static Application Security Testing (SAST)
├─ Dependency Vulnerability Analysis
├─ Vulnerability Scanning
│
▼
Build
│
▼
Unit Testing
│
▼
Advanced Security Analysis
│
▼
Security Reports

---

## Controles de Seguridad Implementados

El pipeline incluye múltiples capas de seguridad:

1. Detección de secretos en el repositorio
2. Análisis estático de código (SAST)
3. Análisis avanzado de vulnerabilidades
4. Escaneo de dependencias vulnerables (SCA)
5. Escaneo de vulnerabilidades del proyecto
6. Generación de SBOM (Software Bill of Materials)
7. Ejecución de pruebas unitarias automatizadas

---

## Tecnologías utilizadas

- .NET 8  
- GitHub Actions  
- CI/CD  
- DevSecOps  
- Static Application Security Testing (SAST)  
- Software Composition Analysis (SCA)

---

## Estructura del repositorio
SEGURIDAD-DE-APLICACIONES-GRUPO-2-CARLOS-MONTALUISA
│
├── src/
│ Código fuente del proyecto
│
├── tests/
│ Pruebas unitarias
│
└── .github/
└── workflows/
Pipeline CI/CD y controles DevSecOps

---

## Resultados esperados

Al finalizar la implementación se espera contar con:

- Un pipeline CI/CD seguro.
- Automatización de pruebas de seguridad.
- Reportes automáticos de vulnerabilidades.
- Integración de seguridad en el proceso de desarrollo.

---

## Autor

**Carlos Montaluisa**  
Proyecto académico – Seguridad de Aplicaciones
