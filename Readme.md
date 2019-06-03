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
Mi región y account ID
arn:aws:iam::771861526154:user/awsUser
arn:aws:lambda:us-east-1:771861526154:function:functionV1

