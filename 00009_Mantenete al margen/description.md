¿Y el `margin`? :thinking: Nos permite ajustar cuánto nos separamos de otras cajas ya que es el margen exterior. En nuestro caso, el logo es el contenido del elemento `img` (una caja) y vamos a separarlo del slogan, que es un elemento `h2` (otra caja), aplicando un margen.
Al igual que `padding` la regla del reloj :watch: también aplica para `margin`. Es decir, en vez de crear esta regla:

```css
.logo {
  margin-top: 10px; 
  margin-right: 5px; 
  margin-bottom: 5px; 
  margin-left: 0px; 
}
```

Podríamos sencillamente reemplazarla por esta:

```css
.logo {
margin: 10px 5px 5px 0px;
}
```

 ¡Veamos! :eyes:

>  Agregá la declaración a la clase `slogan` para que el logo se separe del texto por `50px`.
