# Verificador de recibos Genesis

Página única y autónoma para comprobar recibos firmados (Ed25519). Todo se calcula en el navegador: el recibo y la llave no se envían a ningún servidor.

- Código fuente: `index.html` (un solo archivo, revisable).
- SHA-256 de `index.html`: `08273ce0ebf3d2183713b7b9082a855a9fc505561b7f3a356aec217c4877f28b`
- Compare ese hash con el de su copia: `sha256sum index.html`.

Para una verificación sin confiar en esta página, descargue `index.html`, revise su código y ábralo sin conexión.
