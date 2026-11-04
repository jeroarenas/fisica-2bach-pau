[![Física 2.º Bachillerato — apuntes para la PAU](img/social_preview.png)](fisica2bach_parte1.pdf)

# Física 2.º Bachillerato — apuntes autocontenidos para la PAU

Apuntes de Física de 2.º de Bachillerato pensados para preparar la PAU: ni un formulario telegráfico ni un libro de texto extenso, sino un resumen **autocontenido** que explica de dónde sale cada fórmula, con ejemplos resueltos y una selección de problemas graduados.

📄 **[Descargar el PDF](fisica2bach_parte1.pdf)**

## A quién va dirigido

A quien tiene **base técnica** y necesita **ponerse al día rápido** con la Física de 2.º de Bachillerato: el caso típico es una madre o un padre con formación científica o de ingeniería que quiere ayudar a su hijo con la PAU, pero hace años que no ve este temario. Los libros de texto son demasiado extensos para eso y los formularios, demasiado escuetos; esto está en medio.

También sirve a profesores particulares, docentes de otras materias, universitarios que dan clases y estudiantes avanzados que quieren entender de dónde sale cada fórmula en lugar de memorizarla.

## Contenido (Parte 1, primer trimestre)

1. Magnitudes y unidades
2. Cálculo vectorial: componentes, producto escalar y vectorial, momento de un vector
3. Cinemática: posición, velocidad, aceleración, componentes intrínsecas, tiro horizontal
4. Dinámica: momento lineal e impulso, momento angular y su conservación, tabla de paralelismos traslación/rotación
5. Interacción gravitatoria: leyes de Kepler, ley de gravitación, deducción de la 3.ª ley
6. Trabajo, energía, fuerzas conservativas y energía potencial gravitatoria
7. Satelización: velocidad orbital, energía orbital, lanzamiento y escape
8. Campo gravitatorio: intensidad, variación con la altura, superposición
9. Formulario resumen con tabla de variables, unidades y constantes
10. **42 problemas** (2 sencillos, 2 medios y 2 tipo PAU por tema) con soluciones

### Qué lo hace distinto

- **Nada de "magia"**: se deduce de dónde sale cada fórmula, también sin integrales cuando hace falta (por ejemplo, `a_n = v²/R`, `E_c = ½mv²`, `E_p = −GMm/r` como área bajo la curva, la 3.ª ley de Kepler).
- Recuadros **"Idea clave"** y **"Ojo"** con las interpretaciones físicas y los errores más frecuentes.
- Figuras propias para los conceptos que mejor se entienden dibujados.

Próximamente: Parte 2 (campo eléctrico, magnetismo e inducción) y Parte 3 (ondas, óptica y física moderna).

## Compilar

Requiere una distribución LaTeX estándar (TeX Live o MiKTeX) con `tcolorbox`, `pgfplots` y `tikz`:

```bash
pdflatex fisica2bach_parte1.tex
pdflatex fisica2bach_parte1.tex   # segunda pasada para el índice
```

También se puede subir el `.tex` a [Overleaf](https://www.overleaf.com) y compilarlo allí.

## Cómo se ha elaborado

Estos apuntes se han redactado con la ayuda de **Claude** (asistente de IA de Anthropic), que generó borradores de texto, figuras, ejemplos y problemas a partir de las indicaciones, preguntas y correcciones del autor. El contenido ha sido revisado por el autor y los resultados numéricos se han comprobado por cálculo.

## Erratas y contribuciones

Si encuentras un error o quieres proponer una mejora, abre una [issue](../../issues) o una *pull request*. Toda corrección es bienvenida.

## Licencia

[![CC BY-NC-SA 4.0](https://img.shields.io/badge/licencia-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es)

© 2026 Jerónimo Arenas García. Este trabajo se distribuye bajo la licencia [Creative Commons Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es) (texto completo en [`LICENSE`](LICENSE)).

Puedes copiarlo, redistribuirlo y adaptarlo citando la autoría, sin fines comerciales y compartiendo tus versiones con la misma licencia.
