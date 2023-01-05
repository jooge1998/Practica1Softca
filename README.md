PRACTICA DE GIT Y GITHUB

1) Crear un repositorio en vuestro GitHub llamado Practica1Softca 

![repositorio](/CAPTURAS/repo.png)

2) Clonar vuestro repositorio en local.

```sh
git clone
```

![clonar](/CAPTURAS/clone.png)

3) Crear (si no lo habéis creado ya) en vuestro repositorio local

```sh
nano readme.md
```

![readme](/CAPTURAS/readme.png)

4. hacer un commit inicial con el mensaje commit inicial.

```sh
git add .
git commit -m "commit inicial"
```
5. Subir los cambios al repositorio remoto.

```sh
git push
```
![push](/CAPTURAS/commit.png)

6. Crear en el repositorio local un fichero llamado privado.txt.

```sh
touch privado.txt
```
![ignore](/CAPTURAS/ignor_fic.png)

7. Crear en el repositorio local una carpeta llamada privada.

```sh
mkdir privada
```
![ignore](/CAPTURAS/ignor_dir.png)

8. Realizar los cambios oportunos para que tanto el archivo como
la carpeta sea ignorada por git.


```sh
nano .gitignore
```
9. Añadir fichero 1.txt al repositorio local.

```sh
touch 1.txt
```

![ignore](/CAPTURAS/fiche_1.png)

10. Crear un tag v0.1.

```sh
git tag -a v0.1 -m "version 0.1"
```
![ignore](/CAPTURAS/tag0.1.png)

11. Subir los cambios al repositorio remoto.

```sh
git push --tags
```
![ignore](/CAPTURAS/subir_tag.png)


