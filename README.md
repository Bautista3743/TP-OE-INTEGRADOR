# TP-OE-INTEGRADOR
TPI - Organización Empresarial

Automatización del Proceso de Solicitud de Vacaciones mediante Chatbot

Objetivo

Automatizar el proceso de solicitud de vacaciones mediante un chatbot que valide información, consulte una base de datos simulada y registre solicitudes.

Tecnologías Utilizadas

- Python
- Pandas
- OpenPyXL
- BPMN 2.0
- GitHub

Estructura del Proyecto

TPI/
├── chatbot_vacaciones.py
├── empleados.xlsx
├── README.md
├── BPMN_ASIS.png
├── BPMN_TOBE.png
└── Informe.pdf

Base de Datos Simulada

El archivo "empleados.xlsx" contiene:

Legajo| Nombre| Días Disponibles
1001| Juan Pérez| 15
1002| Ana Gómez| 5
1003| Pedro Ruiz| 0
1004| María López| 20

Flujo del Sistema

1. El usuario ingresa su legajo.
2. El sistema valida la existencia del empleado.
3. Consulta los días disponibles.
4. Solicita la cantidad de días.
5. Aprueba o rechaza la solicitud.
6. Actualiza el saldo disponible.

Autor

Alumno de la Tecnicatura Universitaria en Programación a Distancia.
