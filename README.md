## Migthy Ducks Hockey League

# ✏️ Desafio integrador GitHub: Crear y configurar un repositorio de github

1. Una vez iniciada la sesión, desde la vista dashboard o repositories de http://github.com, crea un nuevo repositorio dando click en el botón: New

2. Define el nombre del repositorio, a modo de ejemplo: hockey. Agrega readme, no crees el gitignore ni elijas una licencia.

3. Ten en cuenta que copiar un repositorio remoto en local es más fácil cuando no está vacío. Debemos dar click en el botón: Code

4. Copia el link HTTPS que nos proporciona Github para poder clonar el repositorio.

5. Abre Visual Studio Code en el directorio de trabajo y ejecuta en la consola:

```sh
git clone pegarlink
```

6. Observa y accede a la carpeta recién creada para empezar a trabajar en la página web.

7. Desde la rama principal “main/master” crea y muévete a la rama “develop” con git checkout -b develop

8. Modifica el contenido del archivo readme.md del repositorio local por el contenido del readme provisto en el proyecto de la liga de hockey.

9. Prepara los cambios con git add readme.md

10. Commitea los cambios con git commit -m “readme”

11. Sube los cambios con git push origin develop

12. Desde la rama “develop” vamos a generar todas las ramas necesarias para desarrollar el proyecto. Crea y muévete a la rama de trabajo “index” ejecutando git checkout -b index

13. Copia el archivo index.html de la liga de hockey y pegalo en el repositorio local.

14. Prepara los cambios con git add index.html

15. Commitea los cambios con git commit -m “index page”

16. Sube los cambios con git push origin index

17. Vuelve a la rama de desarrollo ejecutando: git checkout develop

18. Crea y muévete a la rama de trabajo “about” (similar a #12).

19. Copia el archivo about.html de la liga de hockey y pegalo en el repositorio local. Prepara, commitea y sube los cambios a Github (similar a #14, #15 y #16)

20. Vuelve a la rama de desarrollo.

21. Crea y muévete a la rama de trabajo “contact”.

22. Copia el archivo contact.html de la liga de hockey y pegalo en el repositorio local. Prepara, commitea y sube los cambios a Github.

23. Vuelve a la rama de desarrollo.

24. Crea y muévete a la rama de trabajo “assets”.

25. Copia las carpetas “styles” y “files” de la liga de hockey y pegalas en el repositorio local.

26. Prepara todos los archivos con  git add .

27. Luego commitea y sube los cambios a Github.

28. Desde Github crea las solicitudes de integración (PR) necesarias:

- Primero index hacia develop (resuelve conflictos y fusiona).

- Luego about hacia develop (resuelve conflictos y fusiona).

- Luego contact hacia develop (resuelve conflictos y fusiona).

- Finalizar con assets hacia develop (resuelve conflictos y fusiona).

29. Al terminar fusiona la rama de desarrollo con la rama principal.

30. Borra del repositorio remoto (Github) y del repositorio local las ramas que ya fueron integradas.