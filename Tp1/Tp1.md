# Trabajo Práctico N°1:
###### Sistemas de control de versiones

---
## Índice

- [1. Instalar Git](#1-instalar-git)
- [2. Crear un repositorio local y agregar archivos](#2-crear-un-repositorio-local-y-agregar-archivos)
- [3. Crear un repositorio remoto](#3-crear-un-repositorio-remoto)
- [4. Familiarizarse con el concepto de Pull Request](#4-familiarizarse-con-el-concepto-de-pull-request)
- [5. Mergear código con conflictos](#5-mergear-código-con-conflictos)
- [6. Algunos ejercicios online](#6-algunos-ejercicios-online)
- [7. Crear Repositorio de la materia](#7-crear-repositorio-de-la-materia)

---
## 1. Instalar Git

![](<images/1.png>)

Como se puede observar en la imagen, git ya se encontraba  instalado en su versión 2.17.1

---
## 2. Crear un repositorio local y agregar archivos

```bash
benjamin@benjamin-Lenovo-Z40-75:~/Borrar/Repo TP1$ git init
Inicializado repositorio Git vacío en /home/benjamin/Borrar/Repo TP1/.git/
```
![](<images/2.png>)

![](<images/3.png>)

![](<images/4.png>)

![](<images/5.png>)

---
## 3. Crear un repositorio remoto

![](<images/6.png>)

```bash
benjamin@benjamin-Lenovo-Z40-75:~/Borrar/Repo TP1$ git remote add origin https://github.com/BenjaCimatti/Repo-TP1.git

benjamin@benjamin-Lenovo-Z40-75:~/Borrar/Repo TP1$ git branch -M main

benjamin@benjamin-Lenovo-Z40-75:~/Borrar/Repo TP1$ git push -u origin main
Username for 'https://github.com': BenjaCimatti
Password for 'https://BenjaCimatti@github.com':
Contando objetos: 4, listo.
Delta compression using up to 4 threads.
Comprimiendo objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (4/4), 387 bytes | 387.00 KiB/s, listo.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/BenjaCimatti/Repo-TP1.git
 * [new branch]      main -> main
Rama 'main' configurada para hacer seguimiento a la rama remota 'main' de 'origin'.
```

---
## 4. Familiarizarse con el concepto de Pull Request

![](<images/7.png>)

```bash
benjamin@benjamin-Lenovo-Z40-75:~/Borrar/Repo TP1$ touch pullrequest.md
```
![](<images/7.1.png>)

![](<images/7.2.png>)

![](<images/8.png>)

```bash
benjamin@benjamin-Lenovo-Z40-75:~/Borrar/Repo TP1$ git commit -m "Nueva rama, con pullrequest.md"
[localBranch 9f65568] Nueva rama, con pullrequest.md
 2 files changed, 2 insertions(+)
 create mode 100644 pullrequest.md
```

![](<images/9.png>)

![](<images/10.png>)

![](<images/11.png>)

![](<images/12.png>)

![](<images/13.png>)

---
## 5. Mergear código con conflictos

![](<images/15.png>)

![](<images/14.png>)

![](<images/16.png>)

![](<images/17.png>)

```bash
benjamin@benjamin-Lenovo-Z40-75:~/Borrar/Repo TP1$ git push -u origin main
Username for 'https://github.com': BenjaCimatti	
Password for 'https://BenjaCimatti@github.com': 
Contando objetos: 5, listo.
Delta compression using up to 4 threads.
Comprimiendo objetos: 100% (5/5), listo.
Escribiendo objetos: 100% (5/5), 678 bytes | 678.00 KiB/s, listo.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/BenjaCimatti/Repo-TP1.git
   d3a4da5..7b2c234  main -> main
Rama 'main' configurada para hacer seguimiento a la rama remota 'main' de 'origin'.
```
![](<images/18.png>)

![](<images/19.png>)

![](<images/20.png>)

![](<images/21.png>)

- LOCAL es la version local de la rama
- REMOTE es la version remota de la rama
- BASE es una version de la rama con el merge a medio terminar donde los conflictos estan marcados:

El codigo entre <<<< HEAD y ===== es lo que existe en la version local

El codigo entre ===== y >>>> es lo que existe en la version remota

![](<images/22.png>)

![](<images/23.png>)

![](<images/24.png>)

## 6. Algunos ejercicios online

![](<images/25.png>)

![](<images/26.png>)

![](<images/27.png>)

![](<images/28.png>)

![](<images/29.png>)

## 7. Crear Repositorio de la materia

- https://github.com/BenjaCimatti/ANT