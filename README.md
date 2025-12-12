# 🚀 Framework de Automatización: SauceDemo & API Testing

## 📌 Propósito del Proyecto
Este ecosistema de pruebas fue diseñado para garantizar la calidad y estabilidad de la plataforma **SauceDemo**, integrando pruebas de **UI** y **API**.  
Se implementaron patrones de diseño como **Page Object Model (POM)** para asegurar mantenibilidad, escalabilidad y trazabilidad del código.  
Incluye gestión de datos dinámicos y un sistema completo de reportes y evidencias.

---

## 🛠️ Stack Tecnológico

| Categoría              | Herramientas |
|-----------------------|--------------|
| Lenguaje              | Python 3.x |
| Testing Framework     | Pytest |
| Automatización UI     | Selenium WebDriver |
| Pruebas de API        | Requests |
| Generación de Datos   | Faker |
| Formatos de Datos     | JSON / CSV |
| Reportes              | Pytest-HTML & Logging |

---

## 📂 Arquitectura del Repositorio
📂 pages/ → Clases del Page Object Model (selectores y acciones)
📂 tests/ → Suites de pruebas (UI y API)
📂 datos/ → Archivos estáticos (.json, .csv) para pruebas basadas en datos
📂 utils/ → Funciones helpers reutilizables (lectura de archivos, config)
📂 logs/ → Log técnico de la ejecución
📂 reports/ → Reportes HTML + capturas de pantalla (screens/)
📂 assets/ → Recursos visuales
📄 conftest.py → Fixtures y configuración global de Pytest
📄 run_tests.py → Script principal de ejecución de la suite


---

## 📊 Gestión de Resultados y Trazabilidad

### 1. Reporte HTML Ejecutivo  
Generado como `reporte.html`, con detalle visual del estado de cada test.

### 2. Evidencia Visual  
Capturas automáticas en `reports/screens/` ante fallos en pruebas UI.

### 3. Logs Detallados  
Registro técnico completo en `logs/suite.log`.

---

## 🚀 Guía de Ejecución

Ejecutar la suite completa desde la terminal:

```bash
python run_tests.py

📈 Interpretación de Resultados

El reporte HTML permite analizar:

Status: éxito, fallo o error de cada caso.

Performance: tiempo de ejecución por módulo.

Debugging: acceso directo a capturas de pantalla en fallos.

🧪 Cobertura de Pruebas
Automatización UI (SauceDemo)

Autenticación con credenciales válidas e inválidas.

Generación dinámica de usuarios con Faker.

Visualización de inventario y ordenamiento.

Flujo completo de compra.

Automatización API (Reqres.in)

Implementación de métodos GET, POST y DELETE.

Verificación de códigos de estado (200, 201, 204, 400).

Validación de estructuras y esquemas JSON.

👤 Autora

Ariana Ruiz
Especialista en Control de Calidad y Automatización de Procesos.
Enfocada en soluciones que promuevan la trazabilidad, eficiencia y mejora continua en el ciclo de vida del software.

Este framework representa una solución integral y escalable para la automatización de pruebas.
Su arquitectura modular permite incorporar nuevos escenarios con mínimo esfuerzo, siguiendo buenas prácticas profesionales del mundo QA.
