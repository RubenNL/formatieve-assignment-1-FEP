# Assignment 1

## Assignment 1.1

Het `view-product.js` component toont een enkel product. Schrijf het component om, zodanig dat het gebruik maakt van de shadow DOM.

## Assignment 1.2

Met het `fws-product-filter` component kan je weapons filteren op categorie, type of variant. Pas de code aan, zodat de filter options getoond worden. Doe dit door het 'open' attribute op het component te reflecteren.

## Assignment 1.3

Zorg er binnen het `formatted-currency` component voor dat de `attributeChangedCallback` callback wordt afgevuurd. Lees zonodig in de syllabus terug wat hiervoor noodzakelijk is.

## Assignment 1.4

`view-cart.js` bevat het `counter-control` component. Dit component luistert naar een `change` event. Op basis van dit `change` event wordt de functie `handleCartActionChangehandleCartActionChange` uitgevoerd.

Ga naar de file `counter-control.js`. Genereer binnen de functie `emitChange` een custom 'change' event, en zorg ervoor dat het event wordt dispatched.

Na je wijzigingen zou de totale prijs moeten updaten.