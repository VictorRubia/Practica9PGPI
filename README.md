# Práctica 9 PGPI

> Repositorio para la práctica 9 de PGPI

### Responsable de Proyecto

Víctor José Rubia López

### Responsable de tarea A

Víctor Machado Fernández

### Responsable de tarea B

Sergio Mesas Yélamos

## Realización de tareas

**1. Ramas existentes**:

![foto](imgs/branches.png)

En la rama Tarea A y Tarea B se han creado los archivos correspondientes a las Tareas A y B por parte de los responsables de cada tarea.

**2. Finalización de la tarea A**

Los comandos realizados para unirlos a la rama main son los siguientes

```bash
# Añadimos los nuevos archivos creados en la rama 
$ git add * 
$ git commit -m "comentario" 
$ git push 
# Cambiamos a la rama develop para ponerla al día 
$ git checkout main
$ git pull 
# Volvemos a nuestra rama para ponerla al día 
$ git checkout TareaA
$ git rebase main
$ git push 
# Finalmente unimos la rama desde develop 
$ git checkout main
$ git merge TareaA
$ git push
# Borramos la rama finalizada
$ git branch -d TareaA
```