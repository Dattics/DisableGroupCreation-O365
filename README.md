# DisableGroupCreation Office 365
Deshabilitar la creación de grupos en Office 365, excepto para las personas indicadas en un grupo de seguridad específico.

Pasos:
1. Crear un grupo de seguridad en Office 365
2. Modificar el valor de la variable $GroupName = "<Group name>"
   Ejemplo, si el grupo creado se llama "Habilitados a crear grupos", la variable queda así:
   $GroupName = "Habilitados a crear grupos"
3. Ejecutar el PS1 con Powershell
4. Validar bloqueo  
