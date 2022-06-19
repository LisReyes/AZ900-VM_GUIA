# MÁQUINA VIRTUAL AZ900
Está es una guía para crear el recurso de Máquina Virtual dentro de Azure.
<br> Se detallara paso a paso para que sea de fácil comprensión.

## Paso 1
<br> En el inicio del portal Azure seleccionamos "Máquina Virtual". <br>
![image](https://user-images.githubusercontent.com/99461145/174494733-5a185bf1-007d-499a-a8a8-cbf9630dca4f.png)
<br> Un vez dentro le damos clic en la secuencia siguiente. <br>
![image](https://user-images.githubusercontent.com/99461145/174494809-293bba10-db86-402d-83cf-a062bac1a079.png)

## Paso 2
### Ingreso de datos
Le asignaremos los valores que deaseamos a nuestra Máquina Virtual <br>
<ul>
  <li> Nos aseguramos que nuestra suscripcion sea de tipo student </li>
  <li> Creamos un grupo de recursos, este contendra nuestra máquina virtual dentro de la nube, le asignamos 'lab01-dr' </li>
  <li> Nombramos nuestra máquina virtual como 'mv01-dr' </li>
  <li> La región seleccionada es (US) Central US </li>
  <li> Las opciones de disponibilidad son para tener respaldada nuestra información en otro centro de datos en caso de que el primero falle,pero debido a que solo es una prueba no los requerimos </li>
  <li> Mantenemos la seguridad en Estándar </li>
  <li> En imágen seleccionamos Windows Server 2019 Datacenter - Gen2. El cual sera nuestro sistema operativo con el que trabajara la VM </li>
  <li> Seleccionamos el tamaño de nuestra máquina virtual para eso podemos ir a la pestaña 'ver todos los tamaños' y decidir el que nos convenga, para esta situación me decidí por el 'DS2' que esta dentro de 'Tamaños de generaciones anteriores', asegurandonos que estemos en la región de Central US </li>
  <li> Le asignamos un nombre de usuario y contraseña ¡RECUERDA QUE SON LOS DATOS PARA PODER CONECTARTE A TU MÁQUINA VIRTUAL!</li>
  <li> Aceptamos para usar la licencia existente de Windows Server. </li>
  ![image](https://user-images.githubusercontent.com/99461145/174499178-c2cf47a0-0867-472c-ad23-62102f74c648.png)
  ![image](https://user-images.githubusercontent.com/99461145/174499197-c89ae70a-e0a9-453d-8d84-7c737e186908.png)

</ul>


## Pestaña: Disks(Discos)
<ul> <li> Dejamos los datos predeterminado del disco duro.

.

. </li>
     <li> ![image](https://user-images.githubusercontent.com/99461145/174499275-eae7581c-db84-41bc-acae-06025836f50e.png) </li>

</ul>

## Pestaña: Networking (Redes)
<ul> <li> Automaticamente se le asigna una red virtual, mascara de subred y los puertos predeterminados.

.

. </li>
     <li> ![image](https://user-images.githubusercontent.com/99461145/174499352-27161e49-70a9-44ef-9d2f-a09df9cf7181.png) </li>

</ul>

## Pestaña: Management (Administración)
<ul> <li> Mantenemos las opciones predeterminadas de Azure.

.

. </li> ![image](https://user-images.githubusercontent.com/99461145/174499389-93d13f49-e096-4e2f-b7bc-6628a1542c70.png) </li>
</ul>

## Pestaña: Advancend (Opciones avanzadas)
<ul> <li> Mantenemos las opciones predeterminadas de Azure.

.

. </li>
          <li> ![image](https://user-images.githubusercontent.com/99461145/174499457-9e2498d5-57f9-452c-9d77-486b639ce1da.png) </li>
</ul>

## Pestaña: Tags (Etiquetas)
<ul> <li> Las etiquetas nos sirven para cuando hay muchas personas trabajando dentro de una organización, es importante saber quien esta subiendo que cambios.

En el campo nombre es muy usual poner: CreatedBy y para el campo valor ponemos por quien fue creado.
Podemos observar que hay 12 recursos que se crean de manera automatica

Agregamos otra etiqueta con Nombre:Area y Valor:Skilling
Finalizamos con una ultima, Nombre:Ciclo y Valor:7maEd </li>
     <li> ![image](https://user-images.githubusercontent.com/99461145/174499511-4e92c3c4-ece3-4148-a16d-8a81887f3519.png) </li>
</ul>

## Pestaña: Review and Create (Revisar y Crear)
<ul> <li> Revisamos que toda la información corresponda con la que nosotros asignamos.

 Le damos clic en Crear

. </li>
     <li> ![image](https://user-images.githubusercontent.com/99461145/174499829-49c0b4c5-5fe2-4cdd-bd73-4090ab3dcef3.png) </li>
  
  <li> Para verificar nuestro máquina virtual nos vamos a 'ir al recurso'.

 Le damos clic 

. </li>
     <li> ![image](https://user-images.githubusercontent.com/99461145/174499892-37573b58-d0b2-4066-8fed-c2f4be27a0b1.png) </li>
  
  <li> Comenzamos a explorar nuestra Máquina Virtual para esto:

 Le damos clic en conectar
 
 Luego en RDP

. </li>
     <li> ![image](https://user-images.githubusercontent.com/99461145/174499990-db845cec-c53b-47a3-a592-c3c45fae101a.png) </li>
  

</ul>

### PASO 3: Conexión y verificación de nuestra VM
  <li> Descargamos el archivo RDP

 este nos servira para establecer conexion con nuestra VM recordando las credenciales asignadas
 
 

. </li>
     <li> ![image](https://user-images.githubusercontent.com/99461145/174500137-17686cfe-c3a1-44ae-9189-7fbe0fde7f6e.png)</li>
  

 <li> Aceptamos la conexón Remota

 
 
 

 .</li>
     <li> ![image](https://user-images.githubusercontent.com/99461145/174500190-40f61f2f-0832-4415-af0f-664d165c286d.png)</li>
     
     
<li> Ingresamos nuestras credenciales 

 
 
 

 .</li>
     <li>![image](https://user-images.githubusercontent.com/99461145/174500231-ed054225-dd85-45f2-8036-bcfa1847e8f4.png) </li>
     
     <li> Una vez ingresemos correctamente neustras credenciales nos mostrara la siguiente pantalla, que es nuestra Máquina Virtual, podemos navegar en INternet, crear archivos descargar programas, etc.
 
 
 

 .</li>
     <li>![image](https://user-images.githubusercontent.com/99461145/174500302-4d1cdfc9-1d2a-482a-855d-4dd68519e5f2.png) </li>
</ul>


### Paso 4: Eliminación del recurso (Máquina Virtual) 

<ul> <li> Nos dirigimos al Home de Azure

 Le damos clic en Grupo de recursos

. </li>
     <li> ![image](https://user-images.githubusercontent.com/99461145/174500330-1a51e715-2667-450e-b7e8-f4f5e8149482.png) </li>
  
  <li> Le damos clic en nuestra Máquina Virtual.

 Le damos clic en Eliminar grupo de recursos

. </li>
     <li> ![image](https://user-images.githubusercontent.com/99461145/174500357-b1760ca4-0e8d-4cec-9206-3887fa95756d.png) </li>
  
  <li> Para eliminar nos pide ingresemos el nombre de nuestro recurso

  Una vez ingresado le damos en Eliminar 
 

. </li>
     <li>![image](https://user-images.githubusercontent.com/99461145/174500404-dca0c7c8-2ef3-4463-a405-afdea8660b49.png) </li>
  
   <li> ¡NO OLVIDES ELIMINAR NetworkWatcherRG!

  el cual se encarga de vigilar la red del grupo de recursos

. </li>
     <li>![image](https://user-images.githubusercontent.com/99461145/174500404-dca0c7c8-2ef3-4463-a405-afdea8660b49.png) </li>
  

</ul>

## ¡FELICIDADESQ

<p> ¡Lo lograste, creaste tu primera maquina virtual en Azure! recuerda siempre es recomendable mantener limpia nuestra área de recursos.
