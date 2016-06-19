### Respuestas Ejercicio 1

# Comando paso 11

`git reset --hard HEAD~1`

Si no usamos el flg --hard, volvemos atrás pero manteniendo Working Copy

# Comando paso 12

`git reflog`
`git reset --hard 4bab7df`

Busco el Commit anterior y voy al estado al que lleva. Deshice cambios y
los vuelvo a aplicar

# Comando paso 13

No, porque están en lista, y solo avanza el puntero.

# Comando paso 19

Si, El fichero está con Markdown y con tags HTML. Nos quedamos el Markdown así que editamos, resolvemos el conflicto y hacemos un commit

# Comando paso 21

No, solo avanza el puntero

# Comando paso 25

`git log --graph --decorate --pretty=oneline`

# Comando paso 26

Podría ser ya que tras haberse fusionado styled con master, title está en lista

# Comando paso 27

`git reset HEAD~1`

# Comando paso 28

`git checkout -- git-nuestro.md`

# Comando paso 29

`git branch -D title`

# Comando paso 30

`git reflog`
`git reset --hard a00ba76`

# Comando paso 32

`git reset --hard 4bab7df`

# Comando paso 33

`git reset --hard b520512`

**En el paso 30 me di cuenta de que había editado el titulo con tres asteriscos en lugar de tres almohadillas, así que hay un commit adicional para solventarlo**
