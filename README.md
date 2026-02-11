Este ejercicio consiste en diseñar una Clase de Python con sus atributos y métodos que permita gestionar una tienda de maquillaje mediante el uso de OOP. 

Los métodos que constan en el Jupyter Notebook evfinal_1_definitivo_sincoment ayudan a gestionar el inventario de dicha tienda. 

Estos métodos permiten al usuario (suponemos que el dueño de la tienda) añadir nuevos productos o nuevas unidades que vayan recibiendo, así como ver el inventario, buscar en él y actualizarlo. 

También se pueden eliminar productos que ya no se vendan en la tienda y calcular el valor total de los productos que tiene la tienda en stock.

El sistema utiliza una lista de diccionarios para almacenar la información de cada producto, en este caso nombre, precio y cantidad. 

Para arrancar el proyecto por favor ejecuta el código que te proporciono a continuación:

glowy = TiendaOnline("mi tienda")

Este código le dará un nombre a la tienda y a partir de ahí se pueden ejecutar los siguientes métodos:

      *.agregar_producto(nombre, precio, cantidad):
      
        > Añade un nuevo producto al inventario o actualiza la cantidad si ya existe.
        
      *.ver_inventario()
      
        > Muestra todos los productos disponibles con su precio y cantidad.
        
      *.buscar_producto(nombre)
      
        > Busca un producto específico dentro del inventario.
        
      *.actualizar_stock(nombre, cantidad)
      
        > Modifica la cantidad disponible de un producto.
        
      *.eliminar_producto(nombre)
      
        > Elimina un producto del inventario.
        
      *.calcular_valor_inventario()
      
        > Calcula el valor total del inventario en función del precio y la cantidad de cada producto.
