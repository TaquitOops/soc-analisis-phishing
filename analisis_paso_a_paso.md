# Documentación del Análisis Técnico

## Fase 1: Inspección del Correo Electrónico

### 1. Análisis del Encabezado
Se identificaron dos señales críticas de alerta en el encabezado del mensaje:
* **Dominio Falso:** El remitente utiliza `@gmail.org`, lo cual es inconsistente con el dominio corporativo `@imaginarybank.com`.
* **Error en el Asunto:** Se detectó la falta de ortografía "ecsecutiv" en el campo de asunto.

### 2. Elementos de Engaño (Ingeniería Social)
El atacante utilizó varios elementos para intentar dar legitimidad al mensaje:
* Uso de cargos corporativos ("Execs", "CFO").
* Inclusión de marcas registradas ficticias (ExecuTalk©).
* Iconografía de múltiples sistemas operativos (Windows, Mac, Android) para simular profesionalismo.

## Fase 2: Análisis de la Página Web
Al investigar las opciones de descarga, se analizó el sitio de destino:

* **URL:** `http://my.site.net/pwnexecs/`
* **Hallazgo:** El uso de un hosting genérico y la palabra **"pwn"** (jerga de ciberataque) confirma que el sitio es malicioso y está diseñado para capturar credenciales o distribuir malware.

## Fase 3: Conclusión de la Investigación
Tras evaluar los IoCs (Indicadores de Compromiso), se determinó que el correo **debe ponerse en cuarentena** inmediatamente para proteger la integridad de la red del Banco Imaginario.
