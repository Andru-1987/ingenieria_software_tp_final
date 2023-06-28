| Campo a Validar                       | Validacion del front-end  |
| :---                                  |                    :----: |
| ID                                     | #0001-front-end           |
| Nombre de caso de prueba               | Muestra de productos en el endpoint   | 
| Descripción y/o obsevación             |Validar que en el endpoint indicado  se deberá observar los siguientes tipos de productos :    
    - Pizzas
    - Empanadas
    - Postres
    - Bebidas

---

Stubs - init-data                     

    - Estar conectado a una red.
    - Acceder al endpoint indicado : https://kentucky.com.ar/productos
    - Verificar la cantidad de casos de productos generales disponibles
    
---

Steps                                  
- Ingresar al endpoint
- Hacer un barrido de los productos y las imágenes presentadas
- Puede levantar el status de prueba por medio de Selenium y validar las categorías presentadas
- Ingresar a cualquier producto (bebidas) y validar que los productos sea distinto de cero

---
Response esperado:\
Se debería esperar una grilla con 4 sectores principales y que al ingresar a cualquier de ellos (caso de prueba bebidas), debería contar con un mínimo de 15 productos.

Response
<img src="./images/%230001-front-end-pizzas_productos.png" width=100%>


| Campo a Validar                       | Validacion del front-end  |
| :---                                  |                    :----: |
|Bug reportado                          | #00010-categorias-no-presentadas|
|Estado de prueba                       | Bug Persistente   |
|Responsable de diseño de test          | Anderson Ocaña    |      
|Responsable de ejecución test          | Anderson Ocaña    |      
