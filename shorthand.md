# Shorthand

* junção de propriedades
* resumindo
* legível

```css
{
  /*  background properties */
  background-color: #000;
  background-image: ulr(images/bg.gif);
  background-repeat: no-reppeat;
  background-position: left top;

  /*  background shorthand  */
  background: #000 url(images/bg.gif) no-repeat left top;

  /*  font properties */
  font-style :italic;
  font-weight: bold;
  font-size: .8em;
  line-height: 1.2;
  font-family:  Arial,  sans-serif;

  /*  font shorthand  */
  font: italic bold .8em/1.2 Arial, sans-serif;
}

```

##  Detalhes

* não irá conseiderar propriedades anteriores
* valores não especificados irão assumir o valor padão
* geralmente, a ordem descrita não importa, mas, se houver muitas propriedades com valores semelhantes, podemos encontrar problemas

## Propriedades que aceitam shorthand

animation, background, border borter-bottom, border-color, border-left, border-radius, border-right, boprder-style, border-top, border-width, column-ruler, columns, flex, flex-flow, font, grid, grid-area, grid-column, grid-row, grid-template, list-style, margin, offset, outline, overflow, padding, place-content, place-items, place-self, text-decoration, transition

**https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties**
