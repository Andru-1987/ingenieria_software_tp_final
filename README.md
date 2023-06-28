TRABAJO INTEGRADOR PARA INGENIERIA DE SOFTWARE
---
### NOMBRE Y APELLIDO :  Anderson Ocaña Torres


REQUERIMIENTOS:
* Seleccione una aplicación web a testear, pegue una imagen de la pantalla a testear en el archivo a entregar.
* Diseñe 3 casos de prueba a ejecutar.
* Ejecute los casos de prueba del punto 2 e indique los resultados.

  
---
web site seleccionada:  
-   [KENTUCKY](https://kentucky.com.ar/)
---

Orden de procesos de QA:
- Validacion del front-end, observar todos los productos disponibles de la franquicia. Se deben observar los siguientes productos disponibles:
    - endpoint : https://kentucky.com.ar/productos
    - Pizzas
    - Empanadas
    - Postres
    - Bebidas
    
    _[LINK A QA TEST](./caso_prueba_1/caso_prueba.md)_

---

- Validar funcionamiento sobre los campos de inserción de datos en la base de datos para el endpoint: 
    - endpoint: https://kentucky.com.ar/rrhh

    _[LINK QA TEST](./caso_prueba_2/caso_prueba.md)_

---


- Validar que el proceso de inserción de datos no permita insertar data basura, obteniendo un proceso de validación desde el front-end tanto con expresiones regulares.
    - endpoint: https://kentucky.com.ar/franquicias

    _[LINK QA TEST](./caso_prueba_3/caso_prueba.md)_


Reporte de Procesos de QA
---

ID : #0001-front-end
Descripcion : No se obtienen las categorias en el sector principal del endpoint

Error: categorias no desplegadas

Status Bug : Error persistente.
