# Práctica 4 - Desarrollo de Software Empresarial

## Introducción

### Objetivo del Reporte

El objetivo del reporte es comprender y graficar el funcionamiento del Centro de Salud Mental Moisés Heresi Farwagi, proporcionando una evaluación detallada de los procesos y funciones clave para identificar áreas de mejora y optimización.

## Empresa Seleccionada

- **Nombre:** Centro de Salud Mental Moisés Heresi Farwagi
- **Ubicación:** Av. Pumacahua s/n, Cerro Colorado
- **Organización:** Sociedad de Beneficencia Pública de Arequipa
- **RUC:** 20120958136
- **Web:** [sbarequipa.org.pe](https://sbarequipa.org.pe/)

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

### Admisión de Pacientes

El proceso de admisión de pacientes asegura una evaluación y tratamiento eficientes. Comienza con la verificación de si el paciente es nuevo o recurrente, y se crean o buscan los registros necesarios.

#### Sectores/Roles Involucrados

- Personal de Admisión
- Secretaría
- Tesorería

#### Información necesaria

- Historia clínica
- Tarifario del hospital
- Horario disponible de personal psiquiátrico
- Agenda de citas

### Caja

El proceso de caja gestiona la información del cliente y la transacción de pagos.

#### Sectores/Roles Involucrados

- Cajero
- Sistema de punto de venta (POS)

#### Información necesaria

- Información del cliente: nombre, DNI, dirección, teléfono.
- Información de productos o servicios: descripción, precio, cantidad.
- Forma de pago: efectivo, tarjeta de crédito o débito.

### Teleconsulta

La teleconsulta asegura una evaluación y tratamiento eficientes a distancia, gestionando las citas y pagos de manera virtual.

#### Sectores/Roles Involucrados

- Personal de Admisión
- Secretaría
- Tesorería
- Soporte Técnico

#### Información necesaria

- Historia clínica digital
- Tarifario del hospital
- Horario disponible de personal psiquiátrico
- Agenda de citas
- Conexión y equipo tecnológico del paciente

### Hospitalización

El proceso de hospitalización asegura una evaluación y tratamiento eficientes, verificando y registrando los datos necesarios.

### Atención al Paciente

Este proceso incluye la admisión, evaluación, planificación de tratamiento y seguimiento de los pacientes para asegurar una atención integral.

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

## Arquitectura de Modelo de Datos de Negocio

![image](https://github.com/user-attachments/assets/53399857-bfe6-410a-9a6e-19706dfccad9)


---

_Escuela Profesional de Ciencia de la Computación_
