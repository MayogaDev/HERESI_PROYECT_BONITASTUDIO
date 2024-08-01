# PLATAFORMA DE PROCESOS EN EL CENTRO DE SALUD MENTAL MOISES HERESI FARWAGI - Desarrollo de Software Empresarial

## Nombre del Equipo de Trabajo e Integrantes

- **Equipo de Trabajo**: Desarrollo de Software Empresarial
- **Integrantes**:
  - Piero Emiliano Vizcarra Vargas
  - Sebastian Agenor Zamalloa Molina
  - Javier Wilber Quispe Rojas
  - Andrea Lopez Condori
  - Jharold Mayorga Villena

## Cliente: Organización Real

- **Nombre**: Centro de Salud Mental Moisés Heresi Farwagi
- **Ubicación**: Av. Pumacahua s/n, Cerro Colorado
- **Organización**: Sociedad de Beneficencia Pública de Arequipa
- **RUC**: 20120958136
- **Web**: [https://sbarequipa.org.pe/](https://sbarequipa.org.pe/)

## Propósito del Proyecto

El propósito del proyecto es mejorar y optimizar los procesos internos del Centro de Salud Mental Moisés Heresi Farwagi mediante el desarrollo de una aplicación BPM (Business Process Management). Esta aplicación permitirá una mejor gestión y automatización de procesos clave, mejorando la eficiencia y la calidad de atención a los pacientes.

## Visión General: Aplicación BPM

La aplicación BPM desarrollada contará con una página de aplicación y un menú que permita la gestión integral de los siguientes procesos de negocio:
- Admisión de Pacientes
- Caja
- Teleconsulta
- Hospitalización
- Atención al Paciente

### Objetivos

1. Mejorar la calidad de atención a través de diagnósticos, tratamientos y seguimientos efectivos de los trastornos mentales.
2. Promover la humanización de la asistencia, brindando un trato digno, respetuoso y empático a los pacientes.
3. Combatir la discriminación y el estigma asociados a los trastornos mentales.

### Rubro

El Centro de Salud Mental Moisés Heresi Farwagi pertenece al rubro de la salud, específicamente a la categoría de Salud Mental y Adicciones. Ofrece servicios de atención ambulatoria y cuenta con instalaciones para la internación de pacientes.

### Misión

Contribuir a un desarrollo humano sostenible, mejorando las condiciones y calidad de vida de la población, brindando servicios de salud que satisfagan sus necesidades y respondan a las expectativas de la ciudadanía.

### Visión

Ser un sistema de salud fortalecido legal, tecnológica y presupuestalmente, cuyas instituciones presten servicios de salud eficientes y oportunos, contribuyendo al mejoramiento continuo de las condiciones y calidad de vida de la población.

## Procesos de Negocio

### 1. Admisión de Pacientes

#### Descripción

El proceso de admisión de pacientes está diseñado para asegurar una evaluación y tratamiento eficientes desde la llegada del paciente, creación de historia clínica, programación de citas y generación de cuenta corriente.

#### Proceso

- **Inicio**: Comienza con el proceso de verificación del paciente.
- **Actividades**:
  - Verificación del paciente (nuevo o recurrente).
  - Crear historia clínica (para nuevos pacientes).
  - Buscar registros existentes (para pacientes recurrentes).
  - Generar cuenta corriente según el tarifario.
  - Programar citas necesarias.
  - Evaluación psiquiátrica.
- **Fin**: Finaliza con la generación de citas programadas y la evaluación psiquiátrica.

### 2. Caja

#### Descripción

El proceso para gestionar las transacciones financieras de los pacientes.

#### Proceso

- **Inicio**: Comienza con la solicitud de información del cliente.
- **Actividades**:
  - Solicitar información del cliente.
  - Registrar el monto a abonar.
  - Emitir el recibo de caja.
- **Fin**: Finaliza con la emisión del recibo de caja.

### 3. Teleconsulta

#### Descripción

El proceso para la gestión de consultas a distancia, desde la admisión hasta la confirmación de citas virtuales.

#### Proceso

- **Inicio**: Comienza con la verificación del paciente.
- **Actividades**:
  - Verificar si el paciente es nuevo o recurrente.
  - Crear historia clínica digital (para nuevos pacientes).
  - Buscar registros existentes (para pacientes recurrentes).
  - Generar cuenta corriente según el tarifario.
  - Programar citas necesarias.
  - Enviar documentos y confirmaciones.
- **Fin**: Finaliza con la confirmación de citas y envío de documentos.

### 4. Hospitalización

#### Descripción

El proceso para la admisión y gestión de pacientes hospitalizados.

#### Proceso

- **Inicio**: Comienza con la verificación del paciente.
- **Actividades**:
  - Verificar si el paciente es nuevo o recurrente.
  - Generar ficha de hospitalización.
  - Registrar información de internamiento.
  - Generar deuda según el tarifario.
- **Fin**: Finaliza con la generación de la ficha de hospitalización y la deuda correspondiente.

### 5. Atención al Paciente

#### Descripción

El proceso para asegurar una evaluación y tratamiento integrales y continuos de los pacientes.

#### Proceso

- **Inicio**: Comienza con la recepción y admisión del paciente.
- **Actividades**:
  - Recepción y admisión del paciente.
  - Evaluación inicial del paciente.
  - Planificación del tratamiento.
  - Seguimiento y evaluaciones periódicas.
  - Cierre del caso.
- **Fin**: Finaliza con el cierre del caso.

## Dominio, Área Funcional y Subsistemas

### Admisión Paciente

| Proceso                | Subproceso               | Dominio            | Área Funcional        | Subsistema/Servicio       |
|------------------------|--------------------------|--------------------|-----------------------|---------------------------|
| Admisión de Pacientes  | Verificación de Paciente | Gestión de Paciente| Administración de Pacientes | Registro de Pacientes |
|                        | Creación de Historia Clínica | Gestión de Paciente | Administración de Pacientes | Manejo de Historias Clínicas |
|                        | Generación de Tarjeta de Admisión | Gestión de Paciente | Administración de Pacientes | Manejo de Historias Clínicas |
|                        | Evaluación Psiquiátrica  | Gestión de Paciente | Administración de Pacientes | Manejo de Historias Clínicas |
|                        | Generación de Cuenta Corriente | Gestión de Transacciones | Tesorería | Procesamiento de Pagos |
|                        | Programación de Cita     | Gestión de Citas   | Secretaría             | Programación de Citas     |

### Caja

| Proceso  | Subproceso             | Dominio           | Área Funcional        | Subsistema/Servicio       |
|----------|------------------------|-------------------|-----------------------|---------------------------|
| Caja     | Solicitud de Información del Cliente | Gestión de Clientes | Secretaría             | Manejo de Información de Clientes |
|          | Verificación de Datos  | Gestión de Clientes | Secretaría             | Manejo de Información de Clientes |
|          | Registro del Monto a Abonar | Gestión de Transacciones | Tesorería | Procesamiento de Pagos |
|          | Emisión del Recibo de Caja | Gestión de Transacciones | Tesorería | Procesamiento de Pagos |

### Teleconsulta

| Proceso      | Subproceso           | Dominio            | Área Funcional        | Subsistema/Servicio       |
|--------------|----------------------|--------------------|-----------------------|---------------------------|
| Teleconsulta | Registro de Paciente | Gestión de Paciente| Administración de Pacientes | Registro de Pacientes |
|              | Verificación de Disponibilidad | Gestión de Paciente | Administración de Pacientes | Registro de Pacientes |
|              | Programación de Cita | Gestión de Paciente| Administración de Pacientes | Programación de Citas |
|              | Generación de Orden de Pago | Gestión de Transacciones | Tesorería | Procesamiento de Pagos |
|              | Envío de Documentos  | Gestión de Transacciones | Tesorería | Manejo de Documentos |
|              | Confirmación de Cita | Gestión de Paciente| Administración de Pacientes | Programación de Citas |
|              | Envío de Recibo y Link | Gestión de Comunicación | Soporte Técnico | Envío de Comunicaciones |

### Hospitalización

| Proceso         | Subproceso              | Dominio              | Área Funcional        | Subsistema/Servicio       |
|-----------------|-------------------------|----------------------|-----------------------|---------------------------|
| Hospitalización | Generación de Ficha de Hospitalización | Gestión de Hospitalización | Administración de Pacientes | Manejo de Hospitalización |
|                 | Elección del Paciente   | Gestión de Hospitalización | Administración de Pacientes | Manejo de Hospitalización |
|                 | Elección del Módulo     | Gestión de Hospitalización | Administración de Pacientes | Manejo de Hospitalización |
|                 | Registro de Información de Internamiento | Gestión de Hospitalización | Administración de Pacientes | Manejo de Hospitalización |
|                 | Generación de Deuda según Tarifario | Gestión de Deudas | Tesorería | Procesamiento de Deudas |
|                 | Generación de Deuda según Categoría | Gestión de Deudas | Tesorería | Procesamiento de Deudas |
|                 | Generación de Deuda según Módulo | Gestión de Deudas | Tesorería | Procesamiento de Deudas |

### Atención de Pacientes

| Proceso          | Subproceso                | Dominio              | Área Funcional        | Subsistema/Servicio       |
|------------------|---------------------------|----------------------|-----------------------|---------------------------|
| Atención de Pacientes | Recepción y Admisión      | Gestión de Paciente | Administración de Pacientes | Registro de Pacientes |
|                  | Evaluación Inicial        | Gestión de Paciente  | Administración de Pacientes | Evaluación y Diagnóstico |
|                  | Plan de Tratamiento       | Gestión de Paciente  | Administración de Pacientes | Planificación de Tratamiento |
|                  | Seguimiento y Evaluaciones Periódicas | Gestión de Paciente | Administración de Pacientes | Seguimiento de Pacientes |
|                  | Cierre del Caso           | Gestión de Paciente  | Administración de Pacientes | Cierre de Caso |

## Portafolio de Servicios

### Admisión Paciente

| Subsistema/Servicio | Funcionalidad          | Operación                       |
|---------------------|------------------------|---------------------------------|
| Registro de Pacientes | Mantener Paciente     | Verificar Paciente, Crear Historia Clínica, Generar Tarjeta de Admisión, Evaluar Paciente |
| Procesamiento de Pagos | Procesar Transacciones | Generar Cuenta Corriente        |
| Programación de Citas | Mantener Cita         | Programar Cita                  |

### Caja

| Subsistema/Servicio | Funcionalidad              | Operación                       |
|---------------------|----------------------------|---------------------------------|
| Manejo de Información de Clientes | Mantener Información del Cliente | Solicitar Información, Verificar Datos |
| Procesamiento de Pagos | Procesar Transacciones  | Registrar Monto, Emitir Recibo  |

### Teleconsulta

| Subsistema/Servicio | Funcionalidad             | Operación                       |
|---------------------|---------------------------|---------------------------------|
| Registro de Pacientes | Mantener Paciente        | Registrar Paciente, Verificar Disponibilidad, Programar Cita |
| Procesamiento de Pagos | Procesar Transacciones  | Generar Orden de Pago, Enviar Documentos, Confirmar Pago |
| Envío de Comunicaciones | Mantener Comunicación  | Enviar Recibo, Enviar Link de Videoconferencia |

### Hospitalización

| Subsistema/Servicio | Funcionalidad             | Operación                       |
|---------------------|---------------------------|---------------------------------|
| Manejo de Hospitalización | Mantener Hospitalización | Generar Ficha de Hospitalización, Elegir Paciente, Elegir Módulo, Registrar Información de Internamiento |
| Procesamiento de Deudas | Procesar Deudas       | Generar Deuda según Tarifario, Generar Deuda según Categoría, Generar Deuda según Módulo |

### Atención de Pacientes

| Subsistema/Servicio | Funcionalidad              | Operación                       |
|---------------------|----------------------------|---------------------------------|
| Registro de Pacientes | Mantener Paciente         | Recepción y Admisión            |
| Evaluación y Diagnóstico | Evaluar Paciente       | Evaluación Inicial              |
| Planificación de Tratamiento | Mantener Plan de Tratamiento | Plan de Tratamiento             |
| Seguimiento de Pacientes | Mantener Seguimiento  | Seguimiento y Evaluaciones      |
| Cierre de Caso       | Mantener Cierre de Caso   | Cierre del Caso                 |

## SOA: Servicios de Soporte a Tareas Automáticas en Procesos de Negocio

Basado en el estándar OpenAPI y la herramienta Swagger.

### Recurso: Paciente

- **Propósito**: Gestión de la información de pacientes.
- **Operaciones disponibles**:
  - **GET** /pacientes: Obtener lista de pacientes.
  - **POST** /pacientes: Crear un nuevo paciente.
  - **PUT** /pacientes/{id}: Actualizar información de un paciente.
  - **DELETE** /pacientes/{id}: Eliminar un paciente.

### Recurso: Cita

- **Propósito**: Gestión de citas médicas.
- **Operaciones disponibles**:
  - **GET** /citas: Obtener lista de citas.
  - **POST** /citas: Programar una nueva cita.
  - **PUT** /citas/{id}: Actualizar una cita.
  - **DELETE** /citas/{id}: Cancelar una cita.

### Modelos

- **Paciente**: Incluye atributos como nombre, DNI, dirección, teléfono, historia clínica.
- **Cita**: Incluye atributos como fecha, hora, tipo de consulta, profesional asignado.


## Arquitectura de Modelo de Datos de Negocio

![image](https://github.com/user-attachments/assets/53399857-bfe6-410a-9a6e-19706dfccad9)
El diagrama de modelo de dominio muestra la arquitectura de un sistema de gestión de pedidos médicos. Los principales elementos (entidades) incluyen Paciente, Enfermera, Doctor, Ordenes, Empleado de Material, Empleado de Suministros, Inventario de Suministros, Cantidad y Artículo, y Orden de Verificación. Cada entidad tiene atributos específicos, como códigos, nombres, teléfonos y correos electrónicos. Las relaciones entre entidades se representan mediante líneas de conexión, indicando interacciones como el cuidado del paciente por la enfermera, la aprobación de pedidos por el doctor, la gestión de inventarios por los empleados de suministros, y la verificación de disponibilidad de artículos. Esto permite una clara visualización de cómo se relacionan y manejan los pedidos y suministros en el sistema.

---

## Diagrama de Composición de Servicios vía Procesos de Negocio
![image](https://github.com/user-attachments/assets/37ddeb17-4f0a-46a3-898e-617ad510a5e1)

---

_Escuela Profesional de Ciencia de la Computación_
