# Crear un commit

Tal como vimos git es un control de versiones descentralizado. Eso significa que no hay que conectarse a ningún servicio, servidor o base de datos para almacenar los cambios.

¿Como iniciamos un repositorio donde guardar los cambios de git?

```
mkdir prueba
git init
```

Y ya hemos creado un repositorio

```
echo hola > file1
```

Y ya hemos creado contenido en nuestro espacio de trabajo

```
git status
```

Veremos que git no sabe nada de ese fichero

```
git add .
```

Ahora git lo ha marcado para almacenarlo

```
git commit -m "Primera versión"
```

Ahora git ya ha registrado este cambio.

Para poder ver este cambio podemos usar

```
git show
git log
```
