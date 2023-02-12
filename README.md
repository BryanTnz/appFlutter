# appFlutter

1) Crear una Aplicacion en Firebase, y nos genera un archivo llamado "google-services.json". Lo pegamos en "android/app"

<image>![image](https://user-images.githubusercontent.com/66330281/218320007-4c1d34a7-a9bb-4aa9-94ce-e9c0a0dc65ab.png)
</image>


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
