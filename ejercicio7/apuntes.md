REGLAS DEL RESPONSIVE

1: meta viewport

2: todas las imagenes con las siguientes propiedades:
    width: 100%;
    height: auto;
    display:block; 
Ejemplo:
img {
    width: 100%;
    height: auto;
    display: block;
}

3: las imagenes no pueden tener anchos fijos, pero si pueden tener anchos máximos.
Un  ancho fijo es una medida estilo 700px, pero si podemos tener medidas porcentuales estilo 90%
LO mejor es combinar max-width con width.
Ejemplo: 
.container {
    max-width: 1140px;
    width: 95%;
    margin: 0 auto;
}

DIFERENCIAS ENTRE section.container & section. container (SELECTORES)
main section.container = dentro de main hay section con la clase container

main section. container = dentro de main hay etiquetas con la clase container

Todo lo que salga fuera del elemento que se esconda: (MASCARA)
overflow: hidden;