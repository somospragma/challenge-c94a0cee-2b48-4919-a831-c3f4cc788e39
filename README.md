# Fortaleciendo la seguridad en una aplicación web

Una aplicación web de banca en línea necesita mejorar su seguridad para proteger los datos de los usuarios. El sistema debe implementar encriptación de datos sensibles, protección contra inyección SQL y manejo seguro de contraseñas. El objetivo es asegurar que los datos de los usuarios estén protegidos y que la aplicación sea resistente a ataques comunes.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Seguridad web |
| **Nivel** | junior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 3-4 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: JDK 17+, Maven 3.9+, IDE con soporte Java.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Ejecuta `mvn compile` en la raíz. Si no hay errores, estás listo.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Encriptación de datos sensibles

**Objetivo:** Implementar encriptación para proteger los datos sensibles de los usuarios.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Identifica los datos sensibles que deben ser encriptados.
- Diseña un mecanismo para encriptar y desencriptar estos datos.

**Entregable:** Mecanismo de encriptación y desencriptación funcional.

<details>
<summary>Pistas de conocimiento</summary>

- La encriptación debe ser bidireccional.
- Considera el impacto en el rendimiento.

</details>

### Fase 2: Protección contra inyección SQL

**Objetivo:** Implementar medidas para proteger la aplicación contra inyección SQL.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Identifica las entradas de usuario que podrían ser vulnerables a inyección SQL.
- Diseña un mecanismo para validar y sanear estas entradas.

**Entregable:** Mecanismo de validación y saneamiento de entradas funcional.

<details>
<summary>Pistas de conocimiento</summary>

- Usa parámetros preparados para las consultas SQL.
- Considera el uso de listas blancas para validar entradas.

</details>

### Fase 3: Manejo seguro de contraseñas

**Objetivo:** Implementar un mecanismo seguro para el manejo de contraseñas.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Diseña un mecanismo para almacenar contraseñas de forma segura.
- Implementa un proceso para la verificación de contraseñas.

**Entregable:** Mecanismo de almacenamiento y verificación de contraseñas funcional.

<details>
<summary>Pistas de conocimiento</summary>

- Usa hash con sal para almacenar contraseñas.
- Considera el uso de bibliotecas de seguridad para la verificación.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es la encriptación de datos sensibles y por qué es importante en una aplicación web?
- **comoSeUsa**: ¿Cómo implementarías la protección contra inyección SQL en una aplicación web?
- **erroresComunes**: ¿Cuáles son los errores comunes al manejar contraseñas de forma segura y cómo los evitarías?

## Criterios de Evaluacion

- Implementar encriptación de datos sensibles.
- Implementar protección contra inyección SQL.
- Implementar manejo seguro de contraseñas.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
