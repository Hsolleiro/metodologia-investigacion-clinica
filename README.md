# Metodología de la Investigación Clínica

Herramienta didáctica interactiva para la asignatura de Metodología de la Investigación Clínica.

**Escuela Internacional de Medicina, Universidad Anáhuac Cancún**
Autora: Dra. Helena Solleiro Villavicencio

Sitio publicado: https://hsolleiro.github.io/metodologia-investigacion-clinica/

---

## Qué contiene

**Del dato clínico a la conclusión.** Recorrido interactivo por tres bloques de la metodología de la investigación en ciencias de la salud, con ejemplos de la práctica clínica:

| Módulo | Contenido | Enlace directo |
|---|---|---|
| 1 | Alcance de la investigación: exploratorio, descriptivo, correlacional y explicativo. Dial de resolución, correlaciones espurias, matriz de diagnóstico metodológico, árbol de decisión y el recorrido completo de un proyecto real | [#alcance](https://hsolleiro.github.io/metodologia-investigacion-clinica/#alcance) |
| 2 | Hipótesis nula y alterna, pruebas unilaterales y bilaterales con curva de rechazo interactiva, los cinco pasos del contraste y ejercicios de traducción de preguntas clínicas | [#hipotesis](https://hsolleiro.github.io/metodologia-investigacion-clinica/#hipotesis) |
| 3 | Valor p, nivel e intervalo de confianza con simulación de 100 estudios, errores tipo I y II, potencia, calculadora de tamaño de muestra, tamaño del efecto, variables y escalas de medición | [#fundamentos](https://hsolleiro.github.io/metodologia-investigacion-clinica/#fundamentos) |
| 4 | Autoevaluación de 10 casos con retroalimentación inmediata | [#practica](https://hsolleiro.github.io/metodologia-investigacion-clinica/#practica) |

Es un solo archivo HTML. No requiere instalación, servidor, cuenta ni conexión a bases de datos. Funciona en computadora, tableta y teléfono.

## Cómo usarla en clase

- Proyecta la herramienta y recorre el dial de alcances o la curva de rechazo mientras explicas, cambiando los parámetros según las preguntas del grupo.
- La simulación de 100 intervalos de confianza sirve para mostrar en vivo por qué alrededor de 5 de cada 100 estudios fallan sin que nadie haya hecho nada mal.
- Los enlaces con anclaje de la tabla anterior llevan directo al módulo del día, útiles para compartir en el aula virtual o en un código QR.
- La autoevaluación puede resolverse individualmente al cierre del tema o en parejas como actividad de discusión.
- Ninguna respuesta se guarda ni se transmite: todo ocurre en el navegador del estudiante.

## Estructura del repositorio

```
.
├── index.html          La herramienta completa
├── CITATION.cff        Datos para citar el recurso
├── LICENSE             Licencia de uso
└── .nojekyll           Evita que GitHub Pages procese los archivos con Jekyll
```

## Si más adelante agregas otra herramienta

Cuando haya una segunda unidad conviene separar las cosas: mueve la actual a `estadistica/index.html` usando el renombrado con diagonal en el editor de GitHub, coloca la nueva en su propia carpeta y deja en la raíz un `index.html` que funcione como portada con las ligas a cada una. Mientras solo exista una herramienta, tenerla en la raíz es lo más práctico.

## Licencia

Este material se distribuye bajo licencia [Creative Commons Atribución, No Comercial, Compartir Igual 4.0 Internacional (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es).

Puedes copiarlo, adaptarlo y usarlo en tus propios cursos siempre que reconozcas la autoría, no lo utilices con fines comerciales y compartas las adaptaciones bajo la misma licencia.

## Nota sobre asistencia de inteligencia artificial

En la elaboración de esta herramienta se utilizó asistencia de inteligencia artificial para la redacción de textos y el desarrollo del código. La selección de contenidos, los ejemplos clínicos, la verificación conceptual y la revisión final son responsabilidad de la autora.

## Cómo citar

> Solleiro Villavicencio, H. (2026). *Metodología de la Investigación Clínica: herramientas interactivas*. Universidad Anáhuac Cancún, Escuela Internacional de Medicina. https://hsolleiro.github.io/metodologia-investigacion-clinica/

## Aviso

Los ejemplos son ilustrativos y tienen fines docentes. No sustituyen guías de práctica clínica ni la asesoría de un metodólogo o bioestadístico para el diseño de un protocolo real. Los cálculos de tamaño de muestra son aproximaciones con distribución normal, útiles para docencia y para una primera estimación.
