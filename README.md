# 📝 Generadores de cuestionarios para Brightspace

**Herramientas HTML5 gratuitas para profesores de GED en español.**

Este repositorio aloja generadores automáticos de cuestionarios para la plataforma **Brightspace** (D2L), diseñados específicamente para apoyar la enseñanza del GED a estudiantes hispanohablantes adultos en el programa ABE/ASE de Harry S. Truman College.

Cada generador utiliza inteligencia artificial (modelo Llama 3.3 70B vía API de Groq) para crear preguntas pedagógicamente válidas a partir de un tema o texto que el docente proporciona. El resultado se descarga en formato CSV compatible con la importación masiva de Brightspace.

---

## 🚀 Acceso rápido a los generadores

| Generador | Enlace directo | Descripción |
|-----------|----------------|-------------|
| 📐 **Matemáticas** | [bs_math/](https://zhemaria.github.io/generadores/bs_math/) | Problemas de palabras, ejercicios de cálculo directo, preguntas conceptuales y análisis de datos. Cubre aritmética, álgebra, geometría, estadística y funciones. |
| 📚 **Artes del Lenguaje** | [bs_lang/](https://zhemaria.github.io/generadores/bs_lang/) | Comprensión lectora, gramática española, ortografía, vocabulario en contexto y redacción. Soporta textos informativos, narrativos, argumentativos y funcionales. |

---

## 🔑 Configuración inicial (solo la primera vez)

Antes de utilizar los generadores, cada docente necesita configurar su propia clave API personal de Groq. El proceso es **gratuito**, toma menos de cinco minutos y no requiere tarjeta de crédito.

📘 **[Descargar guía completa en PDF (4 páginas)](Instrucciones_API_Groq_para_profesores.pdf)**

### Resumen del procedimiento

1. Obtener una clave gratuita en [console.groq.com/keys](https://console.groq.com/keys) (registro con cuenta de Google).
2. Abrir cualquiera de los dos generadores. Aparecerá automáticamente el formulario de configuración.
3. Pegar la clave en el campo correspondiente y hacer clic en **Guardar**.
4. La clave queda almacenada en el navegador. **Una sola clave sirve para ambos generadores**.

---

## ✨ Características principales

- **Cuatro tipos de preguntas:** opción múltiple, opción múltiple con varias respuestas correctas, respuesta corta y verdadero/falso.
- **Cuatro niveles de dificultad:** básico, intermedio, avanzado y experto, alineados con los niveles GED.
- **Carga de PDF:** los docentes pueden subir un capítulo o material de referencia para que las preguntas se generen sobre ese contenido específico.
- **Hints pedagógicos opcionales** que guían al estudiante sin revelar la respuesta.
- **Pasos de solución opcionales** para los ejercicios de matemáticas.
- **Exportación directa a CSV** con el formato vertical que requiere Brightspace.
- **Notación matemática estándar** compatible con MathJax (x^2, sqrt(x), fracciones, etc.).
- **Privacidad garantizada:** la clave API se guarda exclusivamente en el navegador del docente. Ningún dato pasa por servidores intermedios.

---

## 🎓 Acerca del proyecto

Este recurso forma parte del ecosistema **[GEDparaHispanos.com](https://gedparahispanos.com)**, un proyecto educativo gratuito desarrollado por el profesor **José M. Fernández** (Zhema), ABE/ASE Math Master Teacher en Harry S. Truman College, City Colleges of Chicago.

El objetivo del proyecto es ofrecer herramientas digitales accesibles, basadas en los principios del Diseño Universal para el Aprendizaje (DUA), que apoyen tanto a docentes como a estudiantes adultos hispanohablantes que se preparan para el examen GED en español.

---

## 🛠️ Apoyo técnico

Si encuentra dificultades durante la configuración o el uso de los generadores, no dude en comunicarse con el autor del recurso a través del sitio principal.

**Prof. José M. Fernández (Zhema)**
ABE/ASE Math Master Teacher
Harry S. Truman College · City Colleges of Chicago
🌐 [GEDparaHispanos.com](https://gedparahispanos.com)

---

## 📄 Licencia y uso

Este recurso es de **uso libre y gratuito** para docentes que trabajan con estudiantes hispanohablantes preparándose para el examen GED en español. Se agradece la atribución al proyecto original..
