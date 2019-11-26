# Configurar git

Git identifica a la persona que realiza un cambio y a la persona que lo agrega al repositorio, para ello necesita que configures tu usuario y tu email.

¿Por qué el email? git esta basado en un sistema por el que unos desarrolladores trabajaban antes de existir git (se enviaban los cambios por correo) A su entender el email es una información importante sobre quien hace un cambio por eso se necesita.

NOTA: En realidad el email no tiene que ser real, no se hace ninguna comprobación sobre él.

```
git config --global user.name Nombre
git config --global user.email mi@correo.com
```

Es suficiente para configurar git
