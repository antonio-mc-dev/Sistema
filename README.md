
# Git y Git Hub
Git es un sistema de control de versiones distribuido que rastrea los cambios en el código de forma local. GitHub es una plataforma en la nube que aloja repositorios Git, facilitando la colaboración, el almacenamiento y la gestión de proyectos de desarrollo en equipo. En resumen: Git es la herramienta, GitHub es el servicio.


## Inicio de Repo Local Git y  Git Hub

To deploy this project run

```bash
  git init
  git add . 
  git commit - m "first commit"
  git remote add origin "url de tu repo creada en Git Hub"
```

## Creacion y manejo de Branchs(Ramas)

To deploy this project run

```bash
  git switch -c "rama nueva" #para crear y cambiar ala rama
  git switch "rama nueva" #para crear rama neuva sn cambiarme a esta
  git branch -d "rama" #elimina de manera local
  git push origin --delete "rama" #elimina en la rama remota en Git Hub
```