# Sistema de Gestión de Seguridad de la Información (SGSI) y Gobernanza de Riesgos

Proyecto integrador de Maestría en Ciberseguridad enfocado en el diseño, implementación y auditoría de un Sistema de Gestión de Seguridad de la Información (SGSI) para una empresa multinacional del sector automotriz con 35,000 empleados y sedes de diseño en Múnich.

---

## 🎯 Resumen Ejecutivo y Alcance
El proyecto aborda la transición de una postura reactiva y permisiva hacia un modelo de ciberresiliencia y cumplimiento corporativo, alineando la seguridad técnica con los objetivos de negocio y protegiendo propiedad intelectual crítica (diseños premium y manufactura robotizada).

* **Organización:** Empresa multinacional automotriz (35,000 colaboradores).
* **Alcance Técnico:** Mainframes IBM z15, infraestructura de red Cisco, bases de datos (Oracle, DB2, SQL Server) y 15,000 estaciones de trabajo.
* **Marcos de Referencia:** ISO/IEC 27001:2022, COBIT 2019, NIST CSF, GDPR y Tratados OMPI/WIPO.

---

## 🏛️ Marcos de Gobernanza y Cumplimiento

### 1. ISO/IEC 27001:2022 (Ciclo PDCA)
* **Plan:** Delimitación del alcance del SGSI, identificación de activos y valoración de riesgos bajo el Anexo A.
* **Do:** Implementación de controles técnicos y administrativos (RBAC, migración de antivirus gratuito a EDR corporativo, política de respaldos 3-2-1).
* **Check:** Monitoreo continuo de cumplimiento y eventos vía SIEM (Splunk) y DAM (Database Activity Monitoring).
* **Act:** Ajuste dinámico de controles, remediación de brechas de Shadow IT y programas de concientización periódicos.

### 2. COBIT 2019 (Gobierno y Gestión de TI)
* Separación formal entre el Gobierno corporativo (evaluación y dirección del Consejo) y la Gestión técnica (ejecución y monitoreo por TI).
* Alineación de controles de continuidad con metas directivas (KPIs de recuperación y disponibilidad).
* Formalización del Registro de Riesgos para la aceptación y tratamiento de riesgos residuales por la Alta Dirección.

### 3. NIST Cybersecurity Framework (CSF)
* Evolución progresiva desde el Nivel 1 (Parcial / Reactivo) hacia el Nivel 4 (Adaptativo), integrando automatización con SOAR y detección de anomalías.

---

## 🛡️ Estructura del Repositorio

* **`/docs`**: Contiene el documento integral del proyecto ejecutivo (`U8AI_ProyectoFinalLAVG.pdf`).
* **`/policies`**: Catálogo completo de las 25 políticas de seguridad formalizadas para software, hardware, información confidencial, seguridad ambiental y recursos humanos.

---

## 📊 Metodologías y Herramientas Aplicadas

| Metodología / Entregable | Propósito en el Proyecto |
| :--- | :--- |
| **Análisis FODA** | Diagnóstico contextual de vulnerabilidades internas y amenazas externas del entorno automotriz. |
| **Método DELPHI** | Consenso anónimo de expertos para priorizar la remediación de riesgos críticos bajo recursos finitos. |
| **Matriz RASCI** | Asignación clara de roles de gobernanza (Responsible, Accountable, Support, Consulted, Informed). |
| **Análisis BIA y BCP/DRP** | Definición de RTO/RPO, continuidad operativa y diseño de un Hot Site fuera de la zona sísmica de Múnich. |
| **Plan de Auditoría Técnica** | Cronograma de auditoría y pruebas de evidencia para Bases de Datos, Resiliencia y Red Core. |

---

## ⚖️ Cumplimiento Legal y Regulatorio
* **GDPR (Reglamento General de Protección de Datos):** Tratamiento legal de datos personales de la plantilla y telemetría en la sede europea (Múnich).
* **Propiedad Intelectual (OMPI / WIPO):** Protección legal de patentes y planos industriales contra espionaje y fuga de información.
* **Acuerdos de Confidencialidad (NDA):** Responsabilidad contractual vinculante para colaboradores y contratistas externos.
