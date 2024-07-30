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

- **Gestión de Paciente:** Verificación de Paciente, Creación de Historia Clínica, Generación de Tarjeta de Admisión, Evaluación Psiquiátrica
- **Gestión de Transacciones:** Generación de Cuenta Corriente
- **Secretaría:** Programación de Cita

### Caja

- **Gestión de Clientes:** Solicitud y Verificación de Información del Cliente
- **Gestión de Transacciones:** Registro del Monto a Abonar, Emisión del Recibo de Caja

### Teleconsulta

- **Gestión de Paciente:** Registro, Verificación de Disponibilidad, Programación de Cita
- **Gestión de Transacciones:** Generación de Orden de Pago, Envío de Documentos, Confirmación de Pago
- **Soporte Técnico:** Envío de Recibo y Link

### Hospitalización

- **Gestión de Hospitalización:** Generación de Ficha, Elección de Paciente y Módulo, Registro de Información
- **Gestión de Deudas:** Generación de Deuda según Tarifario, Categoría y Módulo

### Atención de Pacientes

- **Gestión de Paciente:** Recepción y Admisión, Evaluación Inicial, Planificación de Tratamiento, Seguimiento y Evaluaciones, Cierre del Caso

## Portafolio de Servicios

### Admisión Paciente

- **Registro de Pacientes:** Verificar Paciente, Crear Historia Clínica, Generar Tarjeta de Admisión, Evaluar Paciente
- **Procesamiento de Pagos:** Generar Cuenta Corriente
- **Programación de Citas:** Programar Cita

### Caja

- **Manejo de Información de Clientes:** Solicitar Información, Verificar Datos
- **Procesamiento de Pagos:** Registrar Monto, Emitir Recibo

### Teleconsulta

- **Registro de Pacientes:** Registrar Paciente, Verificar Disponibilidad, Programar Cita
- **Procesamiento de Pagos:** Generar Orden de Pago, Enviar Documentos, Confirmar Pago
- **Envío de Comunicaciones:** Enviar Recibo, Enviar Link de Videoconferencia

### Hospitalización

- **Manejo de Hospitalización:** Generar Ficha de Hospitalización, Elegir Paciente y Módulo, Registrar Información de Internamiento
- **Procesamiento de Deudas:** Generar Deuda según Tarifario, Categoría y Módulo

### Atención de Pacientes

- **Registro de Pacientes:** Recepción y Admisión, Evaluación y Diagnóstico
- **Planificación de Tratamiento:** Plan de Tratamiento
- **Seguimiento de Pacientes:** Seguimiento y Evaluaciones
- **Cierre de Caso:** Cierre del Caso

## Arquitectura

![Arquitectura](ruta/a/tu/imagen/arquitectura.png)

---

_Escuela Profesional de Ciencia de la Computación_
