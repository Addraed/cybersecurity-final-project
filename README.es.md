<!-- hide -->
# 🔐 Proyecto Final de Ciberseguridad

> Proyecto final del Bootcamp de Ciberseguridad en [4Geeks Academy](https://4geeksacademy.com). Un ejercicio práctico completo que simula un incidente de seguridad real: análisis forense, pentesting, remediación de vulnerabilidades y planificación de respuesta a incidentes sobre un servidor Debian comprometido.

*This documentation is also [available in English](README.md)*

---

## 📌 Descripción del Proyecto

Este proyecto simula el rol de un analista de ciberseguridad responsable de recuperar y asegurar un servidor crítico que ha sido comprometido. El ejercicio se divide en tres fases que cubren el ciclo completo de respuesta ante incidentes.

---

## 🗂️ Entregables

| Archivo | Descripción |
|---------|-------------|
| `informe_pentesting_MRMF.pdf` | Informe de pentesting |
| `informe_incidente_ciberseguridad_MRMF.pdf` | Informe del incidente de seguridad |
| `plan_recuperacion_MRMF.pdf` | Plan de recuperación y continuidad |
| `presentacion_análisis_cibersec_MRMF.pdf` | Presentación ejecutiva (PDF) |
| `presentacion_análisis_cibersec_MRMF.pptx` | Presentación ejecutiva (PPTX) |
| `diagrama_red_proyecto_final_mockup.pkt` | Diagrama de red (Cisco Packet Tracer) |
| `VM_REMEDIADA.md` | Documentación de la VM remediada |

---

## 🔍 Fase 1 – Análisis Forense y Remediación del Hack

**Objetivo:** Identificar cómo fue comprometido el servidor, bloquear el exploit y restaurar la seguridad.

- Revisión de logs del sistema (`/var/log/auth.log`) para rastrear el acceso del atacante
- Identificación de procesos sospechosos, usuarios no autorizados y backdoors
- Escaneo de rootkits y malware
- Detención de servicios comprometidos y reversión de los cambios del atacante
- Endurecimiento del firewall, actualización de paquetes y rotación de credenciales

📄 **Informe:** `informe_incidente_ciberseguridad_MRMF.pdf`

---

## 🕵️ Fase 2 – Detección de Vulnerabilidades y Pentesting

**Objetivo:** Encontrar y explotar una segunda vulnerabilidad, documentar el proceso y aplicar correcciones.

- Escaneo completo del sistema con `Nmap` y herramientas relacionadas
- Detección y explotación de una mala configuración independiente del hack original
- Documentación de la cadena de explotación y los pasos de escalada de privilegios
- Aplicación de remediación: cierre de puertos, restricción de accesos, corrección de configuraciones

📄 **Informe:** `informe_pentesting_MRMF.pdf`

---

## 📋 Fase 3 – Plan de Respuesta a Incidentes y SGSI ISO 27001

**Objetivo:** Diseñar un plan formal de respuesta a incidentes y un Sistema de Gestión de Seguridad de la Información.

- Plan de respuesta desarrollado siguiendo las guías **NIST SP 800-61** (Identificar → Contener → Erradicar → Recuperar)
- Definición de políticas DLP y mecanismos de protección de datos (copias de seguridad, cifrado, controles de acceso)
- **SGSI alineado con ISO 27001**: análisis de riesgos, políticas de seguridad y planes de acción

📄 **Informes:** `plan_recuperacion_MRMF.pdf` · `presentacion_análisis_cibersec_MRMF.pdf`

---

## 🗺️ Diagrama de Red

Topología de red diseñada con **Cisco Packet Tracer**, reflejando la infraestructura actual y los cambios de seguridad recomendados.

📁 `diagrama_red_proyecto_final_mockup.pkt`

---

## 🛠️ Herramientas y Tecnologías

`Debian Linux` · `Nmap` · `SSH` · `MySQL` · `Apache` · `FTP` · `Packet Tracer` · `NIST SP 800-61` · `ISO 27001`

---

## 👤 Autor

**Addraed**
Bootcamp de Ciberseguridad · 4Geeks Academy

---

## 📄 Licencia

Este proyecto fue desarrollado como parte de un ejercicio de bootcamp estructurado, creado originalmente por [@rosinni](https://github.com/rosinni) y colaboradores de [4Geeks Academy](https://4geeksacademy.com). Los informes y contenidos elaborados por Addraed se comparten con fines educativos.
<!-- endhide -->
