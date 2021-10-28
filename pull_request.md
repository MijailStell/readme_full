
Comparto los pasos operativos para usar pull request (suponiendo que las ramas ya están configuradas)
-	Regla: nadie puede subir cambios a la rama desarrollo, si no pasamos por un proceso de aprobación. Evidentemente hay otras reglas, pero mínimamente debemos tener la sugerida.

Flujo operativo de pull request:
-	1. Escenario de Cálidda - rama main, desarrollo y feature01 en ese orden de jerarquía.

![1](https://user-images.githubusercontent.com/1031887/139347386-fca801fa-ec6a-4a99-bab3-229f5b9a71b4.png)

A)	El solicitante
-	1. Supongamos que tenemos cambios en la rama feature01 y requerimos subirlos a rama desarrollo.
![2](https://user-images.githubusercontent.com/1031887/139347395-94fe8316-f113-4b0f-b854-85a0b20ddb2c.png)

-	2. A la izquierda es la rama donde se requiere subir el cambio (desarrollo), a la derecha la rama de donde viene el cambio (feature01). Además vemos que por la política de la rama, se exige al menos un aprobador.
![3](https://user-images.githubusercontent.com/1031887/139347408-dc641408-8304-4ffe-b0b2-78fb549ca057.png)

-	3. Elegir la cantidad mínima solicitada por la regla configurada (1 aprobador)

![4](https://user-images.githubusercontent.com/1031887/139347429-418140f9-015a-4bb6-ad40-85cf463f5cd1.png)

-	4. Crear el pull request.
![5](https://user-images.githubusercontent.com/1031887/139347442-45989d32-7635-4c7f-a3c7-ca95f84f7865.png)

-	5. El resumen de la solicitud, indicando que se necesita un aprobador. Github envía un correo al aprobador(es).
![6](https://user-images.githubusercontent.com/1031887/139347456-bc0a31bf-9f94-4549-934c-2fa7b4c83074.png)

B)	El aprobador
-	1. Este es el correo que le llega al aprobador (es)
![7](https://user-images.githubusercontent.com/1031887/139347467-9d6bd111-3563-44a0-a925-83573c199409.png)

-	2. Hace clic en el enlace #7 (este número varía dependiendo del número de pull request existentes). Se mostrará la pantalla donde el aprobador debe revisar y dar su aprobación, comentario o rechazo.
![8](https://user-images.githubusercontent.com/1031887/139347473-c47b5e91-522b-47bb-83d3-93bb4e32a685.png)

-	3. El aprobador debe revisar los cambios solicitados, y en el mejor de los casos comentar su revisión como exitosa.
![9](https://user-images.githubusercontent.com/1031887/139347482-f7cc7332-0661-407a-a61a-93e0b7c602dd.png)

-	4. Se habilita el botón de pull request, en caso todo esté OK y sin conflictos.
![10](https://user-images.githubusercontent.com/1031887/139347488-d0ccb6b7-3160-416f-a313-87617189038a.png)

-	5. Confirmar merge.

![11](https://user-images.githubusercontent.com/1031887/139347500-5c8bb5bb-0f78-410a-ad1b-2d38e1b86b16.png)

-	6. Resumen de la aprobación. Se muestra que se hizo merge desde la rama feature01 a la rama desarrollo y el pull request fue cerrado.
![12](https://user-images.githubusercontent.com/1031887/139347538-914c70fa-623e-452b-b25b-718b43d31a86.png)

C)	El solicitante
-	1. En tiempo real puede ver la aprobación. Y la opción de eliminar la rama (esto es una buena práctica para ramas con obsolescencia mayor a 30 días de haberla integrado)
![13](https://user-images.githubusercontent.com/1031887/139347548-93bfae40-d345-4bd0-8dfe-ab14bb680f1b.png)

-	2. También llega un correo automático de cada una de las aprobaciones.
![14](https://user-images.githubusercontent.com/1031887/139347561-4520724e-b13d-4636-8be2-e7e1722908ca.png)

-	3. Finalmente github envía un correo a todo el equipo asociado al repositorio, notificando la integración.
![15](https://user-images.githubusercontent.com/1031887/139347572-2f7c6798-8ccd-4b27-8ce9-7f2dc59bf635.png)

-	4. Desde el repositorio podrá ver la lista de pull request y su estado. En este caso, se aprecia que el último pull request (el #7 para el ejemplo), ya fue cerrado.
![16](https://user-images.githubusercontent.com/1031887/139347582-3ddbd379-7907-460d-9954-bd2e2b5016ca.png)

Saludos.
