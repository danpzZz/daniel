# daniel
Proyecto inicial para devops

# Comandos Básicos de Git

## Configuración Inicial
git config --global user.name "Tu Nombre"
git config --global user.email "correo@ejemplo.com"

## Inicializar Repositorio
git init

## Ver Estado del Proyecto
git status

## Agregar Archivos
git add archivo.txt
git add .

## Crear Commit
git commit -m "Mensaje del commit"

## Ver Historial
git log
git log --oneline

## Conectar con GitHub
git remote add origin URL_DEL_REPOSITORIO
git remote -v

## Subir Código
git push -u origin main
git push

## Descargar Cambios
git pull
git fetch

## Clonar Repositorio
git clone URL_DEL_REPOSITORIO

## Manejo de Ramas
git branch
git branch nombre-rama
git checkout nombre-rama
git checkout -b nombre-rama

## Fusionar Ramas
git merge nombre-rama

## Eliminar Rama
git branch -d nombre-rama

## Cambiar Nombre de Rama Principal
git branch -M main

## Ver Cambios
git diff

## Deshacer Cambios
git checkout -- archivo.txt
git reset
git reset --soft HEAD~1

## Etiquetas (Tags)
git tag v1.0
git tag

## Flujo Básico de Trabajo
git status
git add .
git commit -m "Descripción"
git push
