# Verificador de recibos Genesis

Página única y autónoma para comprobar recibos firmados (Ed25519). Todo se calcula en el navegador: el recibo y la llave no se envían a ningún servidor.

- Código fuente: `index.html` (un solo archivo, revisable).
- SHA-256 de `index.html`: `b3ab928a2d1104852e1b63b512fb9e7154dae41606f9faf77803c67a341885ec`
- Compare ese hash con el de su copia: `sha256sum index.html`.

Para una verificación sin confiar en esta página, descargue `index.html`, revise su código y ábralo sin conexión.
