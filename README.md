# QX Lean 4

**Verificación formal de reglas de negocio con Inteligencia Artificial y Lean 4.**

QX Lean 4 es una aplicación de escritorio para Windows que analiza el código fuente de un proyecto, identifica **reglas de negocio, validaciones, restricciones e invariantes** y las transforma en propiedades formales que son verificadas mediante **Lean 4**.

Su objetivo es **verificar formalmente las reglas de negocio del software y generar evidencia matemática sobre su cumplimiento.**

---

## 🚀 ¿Cómo funciona?

QX Lean 4 ejecuta automáticamente un pipeline de análisis compuesto por las siguientes etapas:

**1. Conexión:** Establece la conexión con el proveedor de Inteligencia Artificial y prepara el entorno de análisis.

**2. Análisis del proyecto:** Examina la estructura y el código fuente del proyecto seleccionado para obtener el contexto necesario para la verificación.

**3. Extracción de reglas:** La IA detecta y documenta reglas de negocio, restricciones, validaciones e invariantes presentes en el código.

**4. Formalización Lean 4:** Convierte las reglas identificadas en propiedades y teoremas expresados en lenguaje formal.

**5. Verificación formal:** Lean 4 comprueba si las propiedades formalizadas pueden ser demostradas bajo las condiciones establecidas.

**6. Resultado:** Genera el informe de verificación con las reglas detectadas, su evidencia en el código y el estado obtenido para cada propiedad.

---

## 💻 Lenguajes compatibles

| Lenguaje   | Extensiones   |
| ---------- | ------------- |
| Python     | `.py`         |
| TypeScript | `.ts`, `.tsx` |
| JavaScript | `.js`, `.jsx` |
| Java       | `.java`       |
| C#         | `.cs`         |
| Go         | `.go`         |
| Ruby       | `.rb`         |

---

## 📊 Estados de verificación

| Estado              | Descripción                                                                                                     |
| ------------------- | --------------------------------------------------------------------------------------------------------------- |
| **DEMOSTRADA**      | La propiedad fue formalmente verificada por Lean 4 bajo las condiciones establecidas.                           |
| **NO DEMOSTRADA**   | La propiedad fue formalizada, pero Lean 4 no logró completar su demostración bajo las condiciones establecidas. |
| **NO VERIFICADA**   | No fue posible obtener una formalización válida que permitiera realizar la verificación.                        |
| **SIN CRÉDITOS**    | El análisis no pudo continuar debido a que la cuenta del proveedor de IA no dispone de créditos suficientes.    |

> **Nota:** El estado **NO DEMOSTRADA** no implica necesariamente que exista un defecto en el código. Indica que la propiedad pudo formalizarse, pero no fue posible demostrarla bajo las condiciones y formalización generadas para el análisis.

---

## ⚙️ Requisitos

* **Windows 10 o Windows 11 (64 bits).**
* **Conexión a Internet** para realizar el análisis mediante Inteligencia Artificial.
* **Cuenta de OpenRouter** con créditos disponibles para el procesamiento de los análisis.

---

## 📥 Instalación

1. Descarga la versión **v0.1.2** desde [Releases](https://github.com/SQCorE-Technologies/qx-lean4/releases/tag/v0.1.2).
2. Ejecuta el instalador: **`QX Lean 4_0.1.2_x64-setup.exe`**.
3. Sigue el asistente de instalación.
4. Abre **QX Lean 4**.

---

## 🔄 Flujo de análisis

1. **Abre QX Lean 4.**
2. Ingresa a **Configuración** y conecta tu cuenta de **OpenRouter**.
3. Selecciona la estrategia de modelos:
   * **Económica:** optimiza el consumo de créditos.
   * **Máxima calidad:** utiliza modelos con mayor capacidad de razonamiento para obtener análisis más precisos.
4. **Selecciona la carpeta** del proyecto que deseas analizar.
5. Pulsa **Verificar** para iniciar el análisis.
6. Revisa las **reglas de negocio detectadas**, la evidencia obtenida y el resultado de la verificación formal.
7. **Exporta los resultados en formato JSON** para su posterior análisis o integración.
