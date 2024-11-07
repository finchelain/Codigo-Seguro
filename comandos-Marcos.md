#Vamos a clonar el repositorio

*Paso 1: inicializamos nuestro repositorio local >>git init
*Paso 2: Nos traemos el directorio remoto>> git clone https://github.com/xxx/pps.git
*Paso 3: Añadimos los cambios necesarios
                    <<. Modificar enlaces a radarin_o>>
*Paso 4: Añadimos los cambios al stage>> git add .
*Paso 5: Registramos los cambios >> git commit –m “Configuracióninicial
*Paso 6: Subimos nuestros cambios  al remoto >> git push origin master


#Crear una rama:
##Ver enque ramaestamo
*$ git Branch
##Cambiar de rama
*$ git checkout master
##Ver los cambios entre ramas
*$ git diff --stat master rama1
##Fusionar rama
*$ git checkout master
*$ git merge --no-ff rama1
##Eliminarla rama
*$ git branch -d rama1

##Paso 1:Vamos a crear una rama develop en nuestro remote>>
 *git checkout -b develop
 *git push origin develop,



