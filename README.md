## Sistema de Gestión de Gimnasio - TPI Base de Datos II

Este proyecto consiste en el desarrollo de una Base de Datos integral para la gestión, administración e interacción de un gimnasio.

## Contexto Académico
Este sistema fue desarrollado en el marco de la materia Base de Datos 2 (Año 2026) de la Tecnicatura Universitaria en Programación - UTN FRGP.

## Integrantes del equipo
·    Colombo Carmela
·    Gennoni Bruno
·    Martinez Lautaro
·    Versellone Franco

## Descripción del Sistema
La aplicación permite optimizar la operativa diaria del gimnasio, permitiendo a los usuarios y administradores:

* **Gestión de Socios:** Registro y control de información personal.
* **Control de Salud:** Validación obligatoria de Apto Médico vigente para inscripciones.
* **Administración de Clases:** Control de cupos en tiempo real por actividad.
* **Planes y Pagos:** Gestión de membresías y recaudación por planes.

La base de datos respalda la lógica del sistema, gestionando entidades como:
* Socios
* Instructores
* Actividades y Clases
* Membresías y Planes
* Pagos e Inscripciones

## ⚙️ Componentes Técnicos

### 🛡️ Triggers
* `trg_ValidarAptoMedico`: Impide la inscripción de un socio si su certificado médico está vencido.
* `trg_NoBorrarSocios`: Implementa seguridad de datos evitando la eliminación accidental de registros de socios.

### ⚡ Procedimientos Almacenados
* `sp_InscribirSocio`: Automatiza la inscripción y actualiza automáticamente el cupo de la clase.
* `sp_CambiarInstructorClase`: Permite la reasignación rápida de instructores a clases existentes.

### 📊 Vistas
* `vw_DisponibilidadClases`: Reporte en tiempo real de vacantes por actividad y horario.
* `vw_IngresosPorPlan`: Resumen administrativo de recaudación segmentado por tipo de membresía.

Grupo 67

---
**Grupo 67 - 2026**
