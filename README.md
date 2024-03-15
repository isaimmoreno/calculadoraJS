# calculadoraJS
Una calculadora Demo

1. El método document.querySelector(.display) toma el primer elemento con clase "display". Esto significa que guarda en la variable display una referencia al div que contiene los números de la pantalla de la calculadora.

2. El método document.querySelectorAll("button") toma todos los elementos dentro de una NodeList. Esto significa que se guardará en una colección de nodos en la variable buttons.

3. El atributo button.TextContent devuelve el texto dentro de la variable button. Esta última variable contiene uno de los elementos del NodeList de la variable buttons. Anteriormente se guardó el NodeList con todos los botones del documento y se hace un ciclo foreach que hace que se recorra todo el NodeList. Cada elemento de esta lista se guarda en la variable button y se extrae el texto con button.TextContent, guardandose en la variable buttonText.

4. La parte de buttons.foreach(button) => {...} es un ciclo que evalua cada elemento del NodeList buttons.

5. El método button.addEventListener("click", () => {}) agrega un EventListener en el elemento de la variable button. El primer parámetro "click" significa que estará atento cuando se de click en el botón referenciado. El segundo parámetro es una función flecha que define lo que se hará cada vez que se haga click.