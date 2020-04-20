# cloud-functions-firebase
Ejemplos de crear una cloud function en firebas

Quiero agradecerles por ver este tutorial sobre cloud functions en firebase.

## ¿Qué son las cloud functions ?
Las clouds functions son funciones que se ejecutan como código del lado del servidor sin neceesidad que tengamos que configurar un servidor para algún lenguaje.

## Pasos para crear una cloud function
### Crear un proyecto en firebase
### Instalación
1. Deberá instalar Node.js y npm

2. Instalar firebase CLI:

    ```
    npm install -g firebase-tools
    ```
    Si le sale error al momento de instalar pueda que no este actualizado para ese caso ingrese la siguiente línea: 
    ```
    npm cache clean --force
    npm i -g firebase-tools
    ```
    Iniciamos sesión con firebase 
    ```
    firebase login
    ```
    Creamos
    ```
    firebase init
    ```
    ingresamos *yes* para proceder
    ```
    ? Are you ready to proceed? Yes
    ```
    Escogemos la opción functions 
    ```
        ? Which Firebase CLI features do you want to set up for this folder? Press Space to select features, then Enter to confirm your choices. (Press <space> to select, <a> to toggle all, <i> to invert
        selection)
        [] Database: Deploy Firebase Realtime Database Rules
        [] Firestore: Deploy rules and create indexes for Firestore
        [x] Functions: Configure and deploy Cloud Functions
        [] Hosting: Configure and deploy Firebase Hosting sites
        [] Storage: Deploy Cloud Storage security rules
        [] Emulators: Set up local emulators for Firebase features
    ```
    ```
        ? Please select an option:
         > Use an existing project
        Create a new project
        Add Firebase to an existing Google Cloud Platform project
        Don't set up a default project
    ```
    Seleccionamos el proyecto  que vamos a instalar
    
    ```
    ? What language would you like to use to write Cloud Functions? (Use arrow keys)
    > JavaScript
    TypeScript
    ```
    Después seleccionamos yes
    ```
    ? Do you want to use ESLint to catch probable bugs and enforce style? Yes
    ```
    Damos yes a las dependencias de npm
    ```
    ? Do you want to install dependencies with npm now? Yes
    ```


2.  