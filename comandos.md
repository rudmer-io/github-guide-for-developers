## Configurar git
git config --global user.name "rudmer-io"
git config --global user.email "rdmrio@email.com"

## Inicializar git
git init

## Añadir ficheros al commit
git add .

## Commit
git commit -m "Primer commit"

## Sincronizar repositorio

git pull origin main 
### Bajar los cambios del repositorio remoto 👇

git push origin main 
### Subir los cambios al repositorio remoto 👆

## Crear una etiqueta de un commit 📑 🏷
git tag version-1.0 9c1294f6e3defa9c3baf6c73be1c7157eb261b5f

## Crear una rama nueva 🌵
git checkout -b nueva-caracteristica
ó
git branch nueva-caracteristica

## Enviar su rama al repositorio remoto 🏹🌵
git push -u origin nueva-caracteristica

## Cambiarse de rama ⚡🌵
git checkout -b nueva-caracteristica

## Eliminar una rama 👻🌵
git branch -d nueva-caracteristica




