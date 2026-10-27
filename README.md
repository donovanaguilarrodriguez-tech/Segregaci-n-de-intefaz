# Segregaci-n-de-intefaz
En lugar de crear una clase base enorme con todas las acciones posibles para un producto, el comportamiento se dividio en interfaces independientes.
La interfaz Enviable sirve para productos que requieren envio fisico.
La interfaz Expirable sirve para productos con fecha de vencimiento.
La interfaz Remplazable sirve para productos que tienen garantia o reemplazo.
Las clases como Fisico o Digital solo implementan las interfaces que realmente les corresponden, evitando tener metodos vacios o innecesarios.
