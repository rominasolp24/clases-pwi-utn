# Si empezamos de 0: 
    *git init
    *git add .
    *git commit -m "comentario X"
    *git branch -M main
# Debemos crear un repo en github 
    *git remote add origin (pegar link del repo)
    *git push -u origin main


# Podemos usar git status para obtener una informacion detallada de nuestro repo

# Si estoy actualizando:
    *git add .
    *git commit -m "comentario x"
    *git push

# Si me equivoque al poner el git remote usamos el comando:
    *git remote set-url origin <URL_CORRECTA>

# Para ver que origen remoto tengo:
    *git remote -v