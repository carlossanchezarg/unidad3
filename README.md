# Módulo 1:HTML y CSS 
# Unidad 3:CSS inicial


## HTML: index.html

```html
<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="UTF-8">  
        <meta name="viewport" content="width=device-width, initial-scale=1.0">  
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title>Trabajo práctico 3</title>
        <link rel="stylesheet" href="style.css">  
    </head>
    <body>
            <img class="caja_flor" src="imagen/filter_vintage-24px.svg" alt="Flor">
    </body>
</html>
```

## CSS: style.css

```css
body{
    margin:75px 350px;
    padding: 0px;
    background-color:#00FF00; 
    height: 700px;
    width: 700px;
}


.caja_flor{
    background-color:yellow;
    filter:invert(28%) sepia(82%) saturate(7482%) hue-rotate(355deg) brightness(102%) contrast(120%);
    height: 500px;
    width: 500px;
    display:block;   
}
```

## Resultados:

[Mostrar pagina]https://carlossanchezarg.github.io/unidad3/
