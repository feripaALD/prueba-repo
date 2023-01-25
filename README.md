# Práctica primeiro repo en GITHUB
## Comandos empregados: 
```bash
git init
```

> Inicialización do repositorio local

```
 git add .
```
>Añadimos os cambios realizados en toda a carpeta 

```
    git commit -m
```
>Garda os cambios xunto con unha breve explicación que dará o usuario

``` 
git remote add origin
```
>Añadimos o link do noso repositorio ó archivo
```
git branch -M
```
> Permite crear, enumerar y eliminar ramas, así como cambiar su nombre
```
git push -u
```
> Subir a información do directorio de traballo ao repositorio en rede.

```
git remote
```
>Sincronizar repositorio local co repositorio de github

```
git clone
```
>Copiamos o que temos en github para traballar con eso en local.

```
git restore <file>
```
>Desfai os cambios feitos nese ficheiro e volvemos á versión anterior.
```
git restore --staged <file>
```
> Desfai o git add dun ficheiro pero mantén os cambios feitos no working directory
```
git checkout -- <file>
```
> Fai o mesmo que o restore <file>
```
git clean -f 
```
>Desfai cambios feitos e volve á versión do repositorio
```
git reset
```
>Desfai o git add pero mantén os cambios no working directory
```
git reset --soft HEAD~1
```
>Desfai o commit pero mantén os cambios no index e no working directory
```
git reset --hard HEAD~1
```
>Desfai TODOS os cambios.

```
git branch
``` 
>Creamos rama secundaria

```
git checkout
``` 
>Cambiamos de rama

```
git merge
``` 
>Mesturamos os cambios de ambas ramas
