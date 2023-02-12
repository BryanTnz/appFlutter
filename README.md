# Aplicacion Flutter CRUD y Firestore



<b>Integrantes:</b> 
- Tandazo Bryan

<b>link del video:</b> https://www.youtube.com/watch?v=bF9RRkd2HZU
<hr>

1) Crear una Aplicacion en Firebase, y nos genera un archivo llamado "google-services.json". Lo pegamos en "android/app"

![image](https://user-images.githubusercontent.com/66330281/218320007-4c1d34a7-a9bb-4aa9-94ce-e9c0a0dc65ab.png)



2) Agregamos plugins y dependencias en "android/app/src/buil.grade"

<br>
  <b>Plugins</b>
<br>
<code>apply plugin: 'com.google.gms.google-services'</code>
<br>
  <b>Dependencias</b>
<br>
    <code>dependencies {
        implementation 'com.google.firebase:firebase-analytics'
        implementation platform('com.google.firebase:firebase-bom:31.2.0')
        implementation "org.jetbrains.kotlin:kotlin-stdlib-jdk7:$kotlin_version"
    }'</code>
  
  3) En Firestore se crea una coleccion llamada "products" con dos parametros de "name" y "price"
  ![image](https://user-images.githubusercontent.com/66330281/218320651-3fedb653-c158-41b0-9eaf-dff460cd2495.png)
  
  4) Método de "Crear", establecemos lo parametros que se definieron anteriormente y con el método "pop()" vamos a crear una coleccion
![image](https://user-images.githubusercontent.com/66330281/218320763-195bb897-959c-43e5-b683-eae42db4bffc.png)

  5) Método de "Listar", con el método "colletion("name_collection")" se llamara la colección de Firestore
![image](https://user-images.githubusercontent.com/66330281/218320959-6c3868de-e549-4394-b3b1-ccabeb6f81f1.png)

  6) Método de "update", se define los parametros a modificar en este caso hay dos, "name" y "price" 
![image](https://user-images.githubusercontent.com/66330281/218321170-a43b3b1f-292c-4d9f-9701-7c5855283ea4.png)

     Una vez establecidos con el método "update" se va actualizar los valores y con el método "pop()" se va a guardar los cambios
     ![image](https://user-images.githubusercontent.com/66330281/218321273-21235251-d599-493b-8d73-7960a4dab27c.png)

  7) Método de "delete" para eliminar los documents se utiliza el método "delete()"
     ![image](https://user-images.githubusercontent.com/66330281/218321524-fd66164e-037b-42f5-a3e9-fe5e4f05f248.png)
     
  8) Funcionamiento <br>
  ![image](https://user-images.githubusercontent.com/66330281/218321829-e4c9b0ff-bc59-4c2f-8b2b-2f6d28ab8e2d.png)
  ![image](https://user-images.githubusercontent.com/66330281/218321845-832c4799-e1a2-4fa4-bc69-e269425ddb83.png)
  ![image](https://user-images.githubusercontent.com/66330281/218321851-c0925b20-1532-47fe-bedb-4bbef45fa6cb.png)
  ![image](https://user-images.githubusercontent.com/66330281/218321866-d97934a2-12c5-4da7-b50b-dd5b16ab3fb4.png)









