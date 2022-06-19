# MÁQUINA VIRTUAL AZ900
Está es una guía para crear el recurso de Máquina Virtual dentro de Azure.
<br> Se detallara paso a paso para que sea de fácil comprensión.

## Paso 1
<br> En el inicio del portal Azure seleccionamos "Máquina Virtual" <br>
![image](https://user-images.githubusercontent.com/99461145/174494733-5a185bf1-007d-499a-a8a8-cbf9630dca4f.png)
<br> Un vez dentro le damos clic en la secuencia siguiente <br>
![image](https://user-images.githubusercontent.com/99461145/174494809-293bba10-db86-402d-83cf-a062bac1a079.png)

## Paso 2
### Ingreso de datos
Le asignaremos los valores que deaseamos a nuestra Máquina Virtual <br>
<ol>
  <li> Nos aseguramos que nuestra suscripcion sea de tipo student </li>
  <li> Creamos un grupo de recursos, este contendra nuestra máquina virtual dentro de la nube, le asignamos 'lab01-dr' </li>
  <li> Nombramos nuestra máquina virtual como 'mv01-dr' </li>
  <li> La región seleccionada es (US) Central US </li>
  <li> Las opciones de disponibilidad son para tener respaldada nuestra información en otro centro de datos en caso de que el primero falle,pero debido a que solo es una prueba no los requerimos </li>
  <li> Mantenemos la seguridad en Estándar </li>
  <li> En imágen seleccionamos Windows Server 2019 Datacenter - Gen2. El cual sera nuestro sistema operativo con el que trabajara la VM </li>
  <li> Seleccionamos el tamaño de nuestra máquina virtual para eso podemos ir a la pestaña 'ver todos los tamaños' y decidir el que nos convenga, para esta situación me decidí por el 'DS2' que esta dentro de 'Tamaños de generaciones anteriores', asegurandonos que estemos en la región de Central US </li>
  <li> Le asignamos un nombre de usuario y contraseña ¡RECUERDA QUE SON LOS DATOS PARA PODER CONECTARTE A TU MÁQUINA VIRTUAL!</li>
  <li> Aceptamos para usar la licencia existente de Windows Server </li>
  </ol>
   <br>![image](https://user-images.githubusercontent.com/99461145/174498561-85163f4c-005d-4526-9b85-0a516c2ec8d9.png)
   <br>![image](https://user-images.githubusercontent.com/99461145/174498620-80c5e17e-940a-4655-be3d-bd1daffe4096.png)
   ![image](https://user-images.githubusercontent.com/99461145/174498733-cc73c600-cfbe-40db-9a29-bb14a5dfe1bb.png)
   ![image](https://user-images.githubusercontent.com/99461145/174498854-33a61456-e031-49d0-9145-1f53787505ce.png)




