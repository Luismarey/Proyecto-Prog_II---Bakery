# Propuesta Inicial de Proyecto – Programación Orientada a Objetos

**Carrera:** Ingeniería de Software  
**Materia:** Programación Orientada a Objetos  
**Periodo:** Segundo Parcial / Proyecto Final  
**Estudiante(s):** *Luis Mateo Aguirre Soliz*  
**Fecha de entrega:** *AAAA-MM-DD*  

---

## 1. Datos Generales del Proyecto

| Campo | Descripción |
|--------|-------------|
| **Nombre del proyecto:** | Sistema Administrativo de una Panadería
| **Tipo de aplicación:** | ☐ Escritorio / Web 
| **Lenguaje / entorno de desarrollo:** | *C# .NET 8.0 con ASP.NET Core (Web) o Windows Forms/WPF (Escritorio)* |
| **Repositorio Git (URL):** | *https://github.com/Luismarey/Proyecto-Prog_II---Bakery* |
| **Uso de Inteligencia Artificial:** | ☐ Sí |

**Si usas IA, explica brevemente cómo y en qué etapa contribuye:**  
La Inteligencia Artificial se utilizará en las siguientes etapas:

* Diseño de arquitectura: Consulta sobre patrones de diseño y mejores prácticas en POO
* Optimización de código: Revisión de lógica de negocio y refactorización
* Generación de datos de prueba: Creación de datasets realistas para testing
* Documentación: Asistencia en documentación técnica y comentarios de código.   
* Resolución de bugs: Análisis de errores y sugerencias de solución


Nota: Todo código generado por IA será comprendido, adaptado y validado personalmente antes de su implementación.

---

## 2. Descripción del Proyecto

### Resumen breve
Describe tu proyecto en máximo **8 líneas**: qué hace, a quién está dirigido, y qué problema busca resolver.

>   
 Este proyecto consiste en desarrollar un Sistema Administrativo Integral para la panadería de mi familia, que permita controlar y gestionar todas las operaciones del negocio de manera eficiente. El sistema abarcará desde el registro de ventas hasta la gestión de inventarios, producción y recursos humanos.
 
El proyecto está diseñado para ser implementado en tres materias complementarias:

* Programación Orientada a Objetos (POO): Arquitectura, lógica de negocio y estructuras de datos
* Base de Datos II: Diseño y gestión de la base de datos relacional
* Interacción Humano-Computador (IHC): Diseño de interfaces intuitivas mediante wireframes y mockups

Problema que resuelve: Actualmente, la panadería maneja sus operaciones de forma manual o con sistemas desintegrados, lo que dificulta el control de inventarios, genera pérdidas por falta de seguimiento de productos y complica la toma de decisiones estratégicas.
Beneficiarios: Propietarios, personal administrativo, vendedores, panaderos y clientes de la panadería.”

### Objetivos principales
1.  Gestionar ventas de manera eficiente: Permitir el registro rápido de ventas diarias, calcular totales automáticamente, gestionar diferentes formas de pago y generar comprobantes de venta.
2.  Controlar inventario en tiempo real: Administrar el stock de productos terminados y materias primas, alertar sobre niveles críticos de inventario y rastrear movimientos de entrada/salida.
3.  Optimizar la producción diaria: Planificar la producción según demanda histórica, registrar órdenes de producción con consumo automático de materias primas 
4.  Administrar recursos humanos: Gestionar información del personal (panaderos, vendedores, repartidores), controlar roles y permisos del sistema, y registrar asistencias y turnos laborales.
5.  Facilitar la toma de decisiones: Generar reportes de ventas, productos más vendidos, análisis de rentabilidad y estadísticas de demanda.

---

## 3. Diseño Técnico y Aplicación de POO

### Principios de POO aplicados
Marca los que planeas usar:
- [ ] Encapsulamiento (atributos privados y métodos públicos)
- [ ] Uso de constructores
- [ ] Herencia
- [ ] Polimorfismo
- [ ] Interfaces o clases abstractas

### Clases estimadas
- **Cantidad inicial de clases:** 25 - 30  

  **A. Entidades del Sistema para el Dominio**

- Módulo de Personas (8 clases)
- Módulo de Productos e Inventario (6 clases)
- Módulo de Ventas (5 clases)
- Módulo de Producción (4 clases)
-  Módulo de Localización (3 clases)

   **B. Gestores / Servicios (6 clases)**

   **C. Acceso a Datos (DAOs) (8 clases)**


### Persistencia de datos
- [ ] Base de datos relacional: SQL Server / MySQL / PostgreSQL
- [ ] RM opcional: Entity Framework Core para mapeo objeto-relacional
- [ ] Archivos de configuración: JSON/XML para parámetros del sistema
- [ ] Wireframes y Mockups: Figma/Balsamiq para diseño de interfaces

---
## 4. Funcionalidades Principales

| Nº | Nombre de la funcionalidad | Descripción breve | Estado actual |
|----|-----------------------------|-------------------|----------------|
| 1 |     CRUD de Productos     |  Crear, leer, actualizar y eliminar productos terminados y materias primas. Incluye nombre, precio, categoría, unidad de medida y foto. | ☐ Planeada |
| 2 |     CRUD de Personas      |  Gestión completa de clientes, empleados (vendedores, panaderos, repartidores), proveedores y administradores con sus roles específicos.  | ☐ Planeada |

---

## 5. Compromiso del Estudiante

Declaro que:
- Entiendo los criterios de evaluación establecidos en las rúbricas.
- Presentaré una demostración funcional del proyecto.
- Defenderé el código que yo mismo implementé y explicaré las clases y métodos principales.
- Si usé herramientas de IA, comprendo su funcionamiento y las adapté al contexto del proyecto.

**Firma:** Luis Mateo Aguirre Soliz 
---

## 6. Validación del Docente *(completa el profesor)*

| Campo | Detalle |
|--------|---------|
| **Visto bueno del docente:** | ☐ Aprobado para desarrollar ☐ Requiere ajustes ☐ Rechazado |
| **Comentarios / Observaciones:** |  |
| **Firma docente:** |  |
| **Fecha de revisión:** |  |

---

> **Instrucciones para entrega:**
> - Guarda este archivo como `README.md` dentro de tu repositorio Git.  
> - Completa todas las secciones antes de tu presentación inicial.  
> - No borres las casillas ni el formato para garantizar uniformidad del curso.  
> - El docente revisará y aprobará esta propuesta antes del desarrollo completo.

---
