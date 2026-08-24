# Metodología de la Investigación Clínica

Herramientas didácticas interactivas para la asignatura de Metodología de la Investigación Clínica.

**Escuela Internacional de Medicina, Universidad Anáhuac Cancún**
Autora: Dra. Helena Solleiro Villavicencio

Sitio publicado: https://hsolleiro.github.io/metodologia-investigacion-clinica/

---

## Qué contiene

| Unidad | Herramienta | Temas |
|---|---|---|
| 1 | [Del dato clínico a la conclusión](estadistica/) | Alcance de la investigación (exploratorio, descriptivo, correlacional, explicativo), hipótesis nula y alterna, pruebas unilaterales y bilaterales, valor p, nivel e intervalo de confianza, errores tipo I y II, potencia, tamaño de muestra, tamaño del efecto, variables y escalas de medición |

Cada herramienta es un archivo HTML independiente. No requiere instalación, servidor, cuenta ni conexión a bases de datos. Funciona en computadora, tableta y teléfono.

## Cómo usarlas en clase

- Proyecta la herramienta y recorre el dial de alcances o la curva de rechazo mientras explicas, cambiando los parámetros según las preguntas del grupo.
- La simulación de 100 intervalos de confianza sirve para mostrar en vivo por qué alrededor de 5 de cada 100 estudios fallan sin que nadie haya hecho nada mal.
- La autoevaluación de 10 casos puede resolverse individualmente al cierre del tema o en parejas como actividad de discusión.
- Ninguna respuesta se guarda ni se transmite: todo ocurre en el navegador del estudiante.

## Estructura del repositorio

```
.
├── index.html          Página de inicio con el índice de herramientas
├── estadistica/
│   └── index.html      Unidad 1
├── CITATION.cff        Datos para citar el recurso
├── LICENSE             Licencia de uso
└── .nojekyll           Evita que GitHub Pages procese los archivos con Jekyll
```

## Cómo agregar una herramienta nueva

1. Crea una carpeta con nombre corto, en minúsculas y sin acentos ni espacios (por ejemplo `disenos-epidemiologicos`).
2. Coloca dentro el archivo HTML con el nombre `index.html`.
3. Abre `index.html` de la raíz, duplica el bloque `<a class="herramienta">` que está marcado con un comentario y cambia el enlace, el título, la descripción y los temas.
4. Guarda los cambios. GitHub Pages vuelve a publicar el sitio en menos de un minuto.

## Licencia

Este material se distribuye bajo licencia [Creative Commons Atribución, No Comercial, Compartir Igual 4.0 Internacional (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es).

Puedes copiarlo, adaptarlo y usarlo en tus propios cursos siempre que reconozcas la autoría, no lo utilices con fines comerciales y compartas las adaptaciones bajo la misma licencia.

## Nota sobre asistencia de inteligencia artificial

En la elaboración de estas herramientas se utilizó asistencia de inteligencia artificial para la redacción de textos y el desarrollo del código. La selección de contenidos, los ejemplos clínicos, la verificación conceptual y la revisión final son responsabilidad de la autora.

## Cómo citar

> Solleiro Villavicencio, H. (2026). *Metodología de la Investigación Clínica: herramientas interactivas*. Universidad Anáhuac Cancún, Escuela Internacional de Medicina. https://hsolleiro.github.io/metodologia-investigacion-clinica/

## Aviso

Los ejemplos son ilustrativos y tienen fines docentes. No sustituyen guías de práctica clínica ni la asesoría de un metodólogo o bioestadístico para el diseño de un protocolo real. Los cálculos de tamaño de muestra son aproximaciones con distribución normal, útiles para docencia y para una primera estimación.
