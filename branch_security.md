Comparto los pasos para realizar la protección de reglas de los repositorios en github.

-	En cada repositorio, configurar reglas para las ramas desarrollo y main al menos, por ejemplo:
1.	Ir configuración
2.	Seleccionar ramas.
3.	Seleccionar agregar reglas
 
![1](https://user-images.githubusercontent.com/1031887/139345332-3da02a13-c681-4d33-8172-30399845ef67.png)

4.	Ingresar el nombre de la rama a configurar.
5.	Seleccionar los criterios para asegurar la rama. Mínimamente los mostrados en la imagen.
6.	Finalmente crear la regla.
 
![2](https://user-images.githubusercontent.com/1031887/139345480-402611f4-3a5f-4500-b2bb-c0e63c757c58.png)

Al finalizar, se podrá ver las reglas configuradas. Se sugiere aplicar la misma regla para la rama principal (main).
 
![3](https://user-images.githubusercontent.com/1031887/139345532-b3613c1a-0443-4f00-b72a-933a13e5dcc7.png)

Fuente

En el ejemplo, cada vez que se intente subir cambios a la rama desarrollo, el usuario no podrá realizarlo a menos que realice un pull request , el cuál debe ser revisada y aprobada por al menos un colaborador).
 
![4](https://user-images.githubusercontent.com/1031887/139345568-3327a5e1-efe8-4210-94f1-0387de55ec64.png)

Evidentemente, existen más restricciones, pero lo mencionado en el ejemplo cubre la necesidad mínima de seguridad. 

Saludos,

