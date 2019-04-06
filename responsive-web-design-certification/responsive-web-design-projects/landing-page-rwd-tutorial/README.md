# Full Screen Landing Page

### Responsive HTML5/CSS Tutorial.

*Baseado no tutorial de [Drew Ryan](https://youtu.be/Y5SHm53WFEk)*

Neste tutorial, foi criada uma página web única, também conhecida como Landing 
Page.

O objetivo é demonstrar como criar uma landing page simples, mas responsiva.

Além disso, como é de costume em landing pages, seu layout, ocupando 100% da 
altura do display atual, emula o efeito de paginação. 

**Notas**

- A página foi divida com tags `section` para separar a paginação.
- As tags `html` e `body` foram setadas com altura e largura de 100%.
- Para melhor posicionamento da `div class="intro"`, sua propriedade 
`display`, foi setada como `table`.
- Além disso, seu `background` foi setado com o valor `cover`, posicionado em 0.
- Desta forma, a `div class="inner"` teve que ser setada como 
`display: table-cell;`.
- Por fim, foi criada uma *media query* definindo que uma janela de até 600px terá
 configurações distintas de telas maiores, exemplo: 

```html
@media screen and (max-width: 600px)
```

Assim, quando visualizada em dispositivos menores, como smartphones, alguns 
elementos serão reajustados proporcionalmente.




        
