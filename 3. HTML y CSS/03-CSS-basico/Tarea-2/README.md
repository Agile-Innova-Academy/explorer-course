# Ejercicio 2
Crear una aplicación en donde se puedan integrar los siguientes estilos con Pseudoclases y pseudoelementos de css

```css
#palabra { 
  &::before {
    color: #c62828;
    content: "___ ";
  }
  &::after {
    color: #2e7d32;
    content: " *";
  }
}

#texto {
  &::after {
    color: #2e7d32;
    content: ": esto no lo he escrito en el";
  }
}

#revoloteado {
  &:hover {
    color: #6a1b9a;
  }
}

```
