# Diagrama-de-clases-UML-de-cosecha-propia
## Relaciones: 

La clase Coche tiene una relación de composición con la clase Marca (un coche pertenece a una marca) y con la clase Modelo (un coche pertenece a un modelo). 

La clase Alquiler tiene una relación de asociación con la clase Coche (un alquiler involucra un coche) y con la clase Cliente (un alquiler es realizado por un cliente). 

La clase Sucursal tiene una relación de agregación con la clase Coche (una sucursal puede tener varios coches) y una relación de asociación con la clase Empleado (una sucursal tiene varios empleados). 

La clase Cliente tiene una relación de agregación con la clase Alquiler (un cliente puede tener varios alquileres). 

La clase Empleado tiene una relación de agregación con la clase Alquiler (un empleado puede tener varios alquileres) y una relación de asociación con la clase Cobro (un empleado registra cobros). 

La clase Cobro tiene una relación de asociación con la clase Alquiler (un cobro está asociado a un alquiler).
![image](https://github.com/DavidTous/Diagrama-de-clases-UML-de-cosecha-propia/assets/118205695/d0df5398-b6c9-4afa-badf-97641d7468bf)
