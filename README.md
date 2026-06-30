# TP-OE-INTEGRADOR
Chatbot para la Automatización de Solicitudes de Vacaciones
Trabajo Práctico Integrador – Organización Empresarial
Integrantes
Bautista Mariani
Bruno Gatti
Descripción

Este proyecto corresponde al Trabajo Práctico Integrador de la materia Organización Empresarial de la Tecnicatura Universitaria en Programación.

El objetivo consiste en analizar un proceso administrativo real utilizando herramientas de análisis organizacional y desarrollar una propuesta de mejora mediante la automatización del proceso de solicitud de vacaciones de la empresa ficticia TecnoMarket S.A.

La solución implementada consiste en un chatbot desarrollado en Python que permite validar el legajo del empleado, consultar automáticamente el saldo de días disponibles y aprobar o rechazar solicitudes de vacaciones según las reglas de negocio establecidas.

Objetivos
Analizar el proceso actual de solicitud de vacaciones.
Aplicar la Teoría General de Sistemas (TGS).
Modelar el proceso utilizando BPMN 2.0.
Automatizar el proceso mediante un chatbot.
Implementar reglas de negocio.
Simular una base de datos utilizando Excel.
Validar el funcionamiento mediante casos de prueba.
Documentar el proyecto siguiendo criterios académicos.
Tecnologías utilizadas
Python 3
OpenPyXL
Microsoft Excel
BPMN 2.0
Git y GitHub
Estructura del proyecto
TP-OE-INTEGRADOR/
│
├── chatbot_vacaciones.py
├── empleados.xlsx
├── README.md
├── Informe_TPI.pdf
├── BPMN_AS_IS.png
├── BPMN_TO_BE.png
└── Capturas/
Funcionamiento
El usuario ejecuta el programa.
Ingresa su número de legajo.
El sistema verifica que exista.
Consulta automáticamente el saldo de vacaciones.
Solicita la cantidad de días.
Valida la información ingresada.
Aprueba o rechaza la solicitud.
Actualiza automáticamente el saldo disponible.
Reglas de negocio
El legajo debe existir.
El saldo debe ser mayor que cero.
La cantidad solicitada debe ser positiva.
No es posible solicitar más días de los disponibles.
Si la solicitud es aprobada, el saldo se actualiza automáticamente.
Robustez

El simulador contempla distintos escenarios de error:

Legajo inexistente.
Legajo con formato inválido.
Cantidad negativa.
Cantidad igual a cero.
Solicitud superior al saldo disponible.
Empleado sin días disponibles.

Estas validaciones permiten mantener la integridad de la información y garantizar un funcionamiento estable.

Ejecución

Instalar las dependencias:

pip install openpyxl

Ejecutar el programa:

python chatbot_vacaciones.py
Control de versiones

El proyecto se encuentra alojado en GitHub para facilitar el control de versiones y el trabajo colaborativo.

Durante el desarrollo se utilizó Git para registrar la evolución del proyecto y mantener una copia segura del código y de la documentación.

Seguridad

Para la autenticación con GitHub se recomienda utilizar Personal Access Tokens (PAT) en lugar de contraseñas, ya que permiten asignar permisos específicos, mejorar la seguridad y reducir el riesgo de accesos no autorizados.

Uso de Inteligencia Artificial

Durante el desarrollo se emplearon herramientas de Inteligencia Artificial Generativa como apoyo para el análisis del proceso, la elaboración de documentación y la generación de propuestas iniciales de código.

Todas las respuestas obtenidas fueron revisadas, verificadas y adaptadas manualmente para cumplir con los requisitos del proyecto y con las observaciones realizadas por la cátedra.

Estado del proyecto

Versión 2.0 – Entrega corregida

Se incorporaron las mejoras solicitadas por la docente:

Aplicación de la Teoría General de Sistemas.
Diagramas BPMN AS-IS y TO-BE.
Diccionario de Datos.
Manual de Usuario.
Casos de prueba.
Documentación de robustez.
Explicación del uso de IA.
Trazabilidad del desarrollo.
Documentación sobre GitHub y Personal Access Token (PAT).
