# Solución — Tema 1: Git

## Ejercicio 1 — Primer repositorio Git

```console
$ git log
commit 4a642b7662ae037b97e3b5d091d68ba73cb4c221 (HEAD -> master)
Merge: 0e2f39f 19db471
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 22:14:49 2026 +0100

    Merge branch 'feature/gestion-usuarios'

commit 0e2f39f515b088003e42530bb0f140d7ebe4a1b8
Merge: af415a4 a0c3964
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 22:14:19 2026 +0100

    Merge branch 'feature/gestion-libros'

commit 19db4715db57adb739baa0cd28067e90d652cec1 (feature/gestion-usuarios)
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 22:13:02 2026 +0100

    agregar atributos usuario

commit 0a3d33ac3848ec2752e63767b240a4615c561f72
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 22:12:34 2026 +0100

    creacion usuario

commit a0c39642703be42fbabf94092d96c8a839037c29 (feature/gestion-libros)
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 22:10:41 2026 +0100

    agregar atributos libro

commit 4f114b2127706924bf9834d35ae0e2c5710e6549
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 22:10:10 2026 +0100

    creacion libro

commit af415a412946b069d3865c25a7a1969527a34e94
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 21:58:00 2026 +0100

    agegado carpeta dados

commit 7cfc88366c1cd59e9a6589872e84e1b8c2df83f0
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 21:57:24 2026 +0100

    anadiendo gitignore

commit 0d1c38e03f93d7f1aeddcf1f073802f2192cd967
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 21:56:37 2026 +0100

    creando el readme
```

## Ejercicio 2 — Ramas y merge 
## y 
## Ejercicio 3 — Resolución de conflictos

```console
$ git log
commit bc3b3966b2ba8ecc1d75b76c38c6fcf255bee4e3 (HEAD -> master)
Merge: 0ac2ef0 b7787d8
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 22:37:50 2026 +0100

    resolver conflicto merge

commit 0ac2ef0262ce91e1e34e978acf3b0f09b5015047
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 22:35:08 2026 +0100

    modificacion en main

commit b7787d89eff087031bd3fa612b63917e51f577fe (feature/nuevo-saludo)
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 22:34:42 2026 +0100

    modificacion mensaje en nueva rama

commit 702735f759211b56d2f9f1c5914c2aecb0a252da
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 22:34:02 2026 +0100

    agregar mensaje
```

## Ejercicio 4 — Simulación de Git Flow

```console
$ git log
commit 2226e74487e2b4c8b7cbf4cdc7a4e0e43fd5e554 (HEAD -> main, tag: v1.0.1)
Merge: a9f58b0 bd8d078
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 23:23:22 2026 +0100

    correcion release

commit bd8d078ff8f2d4b2d114d458d10394758c6ea437 (hotfix/error-precio)
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 23:22:51 2026 +0100

    correcion error

commit a9f58b0274e70e4ab2688a711d571f2f3e026abb (tag: v1.0)
Merge: 4c738ef 1efd563
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 23:17:00 2026 +0100

    fusion version 1.0

commit 1efd5633413476e7ab07627c5e245f3af4168ddb (release/1.0)
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 23:14:15 2026 +0100

    version 1.0

commit 1176f96b3deb96d6430c37f562b5d115d9627b2b
Merge: 4c738ef 4625aaa
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 23:13:10 2026 +0100

    merge carrito

commit 4625aaa3dac76e97bd4fc2b8a5c3077e506027d8 (feature/carrito-compra)
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 23:12:46 2026 +0100

    agregar articulos

commit bb96b8405fa1a73b8339c407e5f2e261cf2d3858
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 23:12:30 2026 +0100

    agregar carrito

commit 4c738ef33caecb9842b1da0c22b7459440d8588b
Author: p1nh4 <p1nh4@protonmail.com>
Date:   Tue Oct 13 23:10:21 2026 +0100

    commit inicial
```
