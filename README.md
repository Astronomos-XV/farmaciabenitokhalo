# farmaciabenitokhalo
Venta de todo tipo de productos hasta de los que te hacen volar ya sabe a cuales...

Profesor Isaac:
Como alcaracion cuando vaya añadir productos no ponga el campo id(Automaticamente es autoincrementado) solo ponga al añadir el producto

  {
    "nombre": "Maria al atardecer",
    "precio": 50,
  }

en postman con el metodo post

http://localhost:3000/merca
Ver todos los productos

para ver un producto en especifico es

Por ejemplo:

http://localhost:3000/merca/1

Para eliminarlo o actualizarlo es lo mismo que el ejemplo anterior solo que tienes que tomar en cuenta el delete y el put, para put es el enlace que se muestra en el ejemplo y dentro del postman se le cambia la informacion los campos por;

  {
    "nombre": "Dol",
    "precio": 500,
  }

