usuario=samuel?email=samuel@gmail.com

{
"usuario": "samuel",
"email": "samuel@gmail.com"
}


Crear Role ==> Selecciona CloudFormation ==> Filtrar AwsLambdaExecute
Siguiente
Nombre de Rol: CloudFormationServiceRole
Politica:  AwsLambdaExecute

El archivo CFnServiceRole.json esta personalizado
Cambiar su region y su account ID

Ejemplos:
Mi regi�n y account ID
arn:aws:iam::771861526154:user/awsUser
arn:aws:lambda:us-east-1:771861526154:function:functionV1

Luego de reeemplazar copiar el contenido de CFnServiceRole.json
Entrar al Rol CloudFormationServiceRole
Click en A�adir una pol�tica insertada
Y copiar el contenido del archivo dentro de la pesta�a JSON

CLick en revisar la politica
Nombre de Politica: CFNLambdaPolicy
Guardar


