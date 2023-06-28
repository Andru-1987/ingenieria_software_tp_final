| Campo a Validar                       | Formulario RRHH  |
| :---                                  |                    :----: |
| ID                                     | #0002-formulario          |
| Nombre de caso de prueba               | Inserción de registros en el backend del proyecto | 
| Descripción y/o obsevación             | Se procede a cargar los inputs, incluyendo un archivo random en formato pdf, validando las entradas y sus tipos de registros lógicos|

---

Stubs - init-data                     

    - Conexión a una red.
    - Acceder al endpoint indicado : https://kentucky.com.ar/rrhh
    - Tener disponible el adjunto : 
[ADJUNTO](./pdf_loader/Resume.pdf)
    
---

Steps                                  
- Ingresar al endpoint
- Ingresar los datos en los siguientes inputs:
<img src="./images/%230002-formulario-RRHH.png" width=100%>
- _Se puede realizar por medio de un proceso automatizado Selenium o Mocka_
- Hacer click sobre enviar

---
Response esperado:\
Luego de la carga válida cuando los datos fueron ingresados y cargado el archivo pdf

Response
<img src="./images/%230002-formulario-RRHH-success.png" width=100%>


| Campo a Validar                       | Formulario RRHH |
| :---                                  |                    :----: |
|Bug reportado                          | #00011-No-carga-de-pdf|
|Estado de prueba                       | Success   |
|Responsable de diseño de test          | Anderson Ocaña    |      
|Responsable de ejecución test          | Anderson Ocaña    |      
