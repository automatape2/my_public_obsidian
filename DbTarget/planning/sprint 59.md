# ☑️ 3038-4. Code Refactoring Guidelines and Implementation Plan
- ☑️ Crear directrices (pautas) detalladas para refactorizar
    - Elegir patrones de diseño (hacer ejemplos)
    - Enfatizar testing y calidad de codigo
- ☑️ Dividir el proceso de refactorización en tareas prácticas.
    - Asignar responsable y fechas limites
    - Crear calendario para todo el proceso de refactorización
---
# ☑️ 3039-5. Risk Management and Communication
- ☑️ Identificar riesgos y desafios en refactorizacion
    - Plan de mitigacion por riesgo
- ☑️ Definir canales de comunicación y las herramientas de colaboración
---
# ✅ 3025-Development and database standards for backend and DB
https://skolerom.atlassian.net/wiki/spaces/MA/pages/1274871809/Coding+Guidelines
---
# ☑️ 3019-Redo Dev Environment
## Solución
- ✅ desplegar cluster kubernetes y activar dev (main app)... usando terraform, IAC... (raul)
- ✅ verificar cluster funciona (jose anicama)
    <!-- - crendenciales de cuenta aws -->
    <!-- - configurar permisos ? (jose anicama)  -->
- ✅ revisar el pipeline mainapp (jose anicama)
- ☑️ implementar
    - ✅ admin,
    - ☑️ global y
    - ✅ runner
    en el cluster kubernetes (raul)
- ✅ revisar api main app en dev
## Aceptación
- ☑️ confirmar funcionamiento de
    - ✅ api
    - ✅ admin
    - ☑️ global
    - ✅ runner
- ☑️ documentacion de confluence (Raul?)
    - como funciona los scripts de terraform
    - como funciona el pipeline y como se estan conectados con aws
    - como funciona despliegue automatizado desde repos
- ☑️ **AWS Trusted Advisor:** programar una revision semanal para revision de servicios  de aws (obsoletos, etc)
    - AWS debe informar a support.skolerom@itware.com.pe sobre servicios obsoletos
## Info adicional
Tenemos una cuenta solo para dev de aws