# Elementos
Documentación de los elementos de CSS que se utilizaron
* box-sizing: border-box

## box-sizing: border-box
Sin box-sizing el tamaño de un div por ejemplo sería:
* width + padding  + border  = actual width del div
* height + padding + border  = actual height del div

Con box-sizing en el tamaño de un div estará incluido el padding y el border

Sin box-sizing estos dos divs son de distinto tamaño:

```css
.div1{
    width: 100px;
    height: 30px;
}

.div2{
    width: 100px;
    height: 30px;
    padding: 20px;    
}
```

Pero con box - sizing sí cumple que son exactamentente del mismo tamaño

```css
.div1{
    width: 100px;
    height: 30px;
    box-sizing: border-box;
}

.div2{
    width: 100px;
    height: 30px;
    padding: 20px;
    box-sizing: border-box;
}
```