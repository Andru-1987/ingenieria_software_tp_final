| Campo a Validar                       | Carga datos basura a Franquicias  |
| :---                                  |                    :----: |
| ID                                     | #0003-formulario-franquicia          |
| Nombre de caso de prueba               | Validación Front-end| 
| Descripción y/o obsevación             | Validación de uso de REGEXP y de recursos de CSS para no permitir la carga de datos no válidos|

---

Stubs - init-data                     

    - Conexión a una red.
    - Acceder al endpoint indicado : https://kentucky.com.ar/franquicias
    carga con registros random y caracteres extraños no encode latin-1
    
---

Steps                                  
- Ingresar al endpoint
- Ingresar los datos en los siguientes inputs:
<img src="./images/%230003-data-stub-junk.png" width=100%>
- _Se puede realizar por medio de un proceso automatizado Selenium o Mocka_
- Hacer click sobre enviar

---
Response esperado:\
Notificacion de que no ha sido cargado los datos o que no permita el proceso del formulario

Response:
<img src="./images/%230003-no-carga.png" width=100%>


| Campo a Validar                       | Carga datos basura a Franquicias |
| :---                                  |                    :----: |
|Bug reportado                          | #00011-carga-junk-data|
|Estado de prueba                       | Success   |
|Responsable de diseño de test          | Anderson Ocaña    |      
|Responsable de ejecución test          | Anderson Ocaña    |      
