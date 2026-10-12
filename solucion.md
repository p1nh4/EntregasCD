# Solución — Tema 1: Git

## Ejercicio 1 — Primer repositorio Git

```console
$ git log --oneline
d8de51a (HEAD -> master) creacion carpeta src
f6de403 configuracion inicial
837042a creacion repositorio e ficheiro readme
```

## Ejercicio 2 — Ramas y merge

```console
$ git log --oneline --graph --all
*   fee3673 (HEAD -> master) Merge: integra la gestion de usarios
|\
| * 4c7b5e6 (feature/gestion-usuarios) creacion atributos privados de la classe usuarios
| * 9e7424c creacion gestion usuarios
* |   1f32c0e Merge: integra la gestion de libros
|\ \
| |/
|/|
| * 05a49f0 (feature/gestion-libros) creacion atributos privados de la classe libro
| * e19165c Creacion clase libro
|/
* d8de51a creacion carpeta src
* f6de403 configuracion inicial
* 837042a creacion repositorio e ficheiro readme
```

## Ejercicio 3 — Conflictos de merge

```console
$ git commit -m "conflitos merge resuelto en el saludo al usuario"
[master 958a026] conflitos merge resuelto en el saludo al usuario

$ git log --oneline --graph --all
*   958a026 (HEAD -> master) conflitos merge resuelto en el saludo al usuario
|\
| * 8138d01 (feature/nuevo-saludo) modificacion del saludo al usuario
* | ae5d26d modificacion del saludo al usuario
|/
* eae428a creacion metodo que devuelve un saludo
```

## Ejercicio 4 — Simulación de Git Flow

```console
$ git log --oneline --graph --all --decorate
*   f1d9f1c (HEAD -> develop) Merge: hotfix error de precio en develop
|\  
* \   a08939b Merge: release 1.0 en develop
|\ \  
| | | *   d1c8cf4 (tag: v1.0.1, main) Merge: hotfix error de precio en main
| | | |\  
| | | |/  
| | |/|   
| | * | c3ecac6 (hotfix/error-precio) Correccion del error de precio
| | |/  
| | *   fd40040 (tag: v1.0) Merge: release 1.0 en main
| | |\  
| | |/  
| |/|   
| * | 40b05ef (release/1.0) Actualizacion version 1.0 en el readme
|/ /  
* |   bb8cf20 Merge: integra el carrito de compra
|\ \  
| |/  
|/|   
| * c4a7dc6 (feature/carrito-compra) Anadidos mas articulos al carrito
| * dcede13 Creacion carrito con primer articulo
|/  
* 8d6df68 Creacion repositorio y fichero readme
```
