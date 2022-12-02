# MICROSERVICIO PDF

Microservicio que genera un PDF de una transacción exitosa con los parametros enviados mediante QueryParams

El servicio se encuentra desplegado en AWS, puede usar la siguiente ruta para realizar las pruebas requeridas:

End point:
`https://41ci70xjbe.execute-api.us-east-2.amazonaws.com/dev/`

Ejemplo:

`https://41ci70xjbe.execute-api.us-east-2.amazonaws.com/dev/?name=juan&monto=12&cod_operacion=10056&message=Transacci%C3%B3n%20exitosa`

### nota

Puede reutilizar el codigo y desplegar en su propia cuenta siguiendo los siguientes pasos:

1. Clonar el repositorio.
2. Ejecutar `npm i` para instalar las dependencias
3. Ejecutar `nest build`para compilar el proyecto
4. Ejecutar `serverless deploy` para desplegar el proyecto en aws. Debe tener configurada su cuenta en aws-cli
