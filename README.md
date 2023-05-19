# Diagrama-de-clases-UML-de-cosecha-propia
## Enunciado:
Una alquiler de coches desea registrar todos los coches y contratos de alquiler que realiza diariamente en cada sucursal y por quien (empleado y cliente) se realiza el contrato de alquiler deseamos registrar también el cobro, la marca, el modelo de coche y en que sucursal se ha realizado el contrato.
## Relaciones: 
La clase Coche tiene una relación de composición con la clase Marca (un coche pertenece a una marca 1:1) y con la clase Modelo (un coche pertenece a un modelo 1:1). 

La clase Alquiler tiene una relación de asociación con la clase Coche (un alquiler involucra un coche 1:1) y con la clase Cliente (un alquiler es realizado por un cliente 1:1). 

La clase Sucursal tiene una relación de agregación con la clase Coche (una sucursal puede tener varios coches 1:N) y una relación de asociación con la clase Empleado (una sucursal tiene varios empleados 1:N). 

La clase Cliente tiene una relación de agregación con la clase Alquiler (un cliente puede tener varios alquileres 1:N). 

La clase Empleado tiene una relación de agregación con la clase Alquiler (un empleado puede tener varios alquileres 1:N) y una relación de asociación con la clase Cobro (un empleado registra cobros 1:N). 

La clase Cobro tiene una relación de asociación con la clase Alquiler (un cobro está asociado a un alquiler 1:1). 

![image](https://github.com/DavidTous/Diagrama-de-clases-UML-de-cosecha-propia/assets/118205695/a8bf469d-767d-40a5-87ca-1366adc91543)
