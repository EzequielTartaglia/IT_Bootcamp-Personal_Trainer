#### Configuraciones iniciales

```bash
# Configurar nombre
git config --global user.name "NombreDeGithub"

# Configurar email
git config --global user.email "tucorreodegithub@mail.com"

# Habilitar colores
git config --global color.ui auto
```

```bash
# Verificar nombre
git config --global user.name

# Verificar email
git config --global user.email
```

#### Inicializar repositorio

```bash
# Iniciar repositorio
git init
```

```bash
# Agregar todos los cambios
git add .
git commit -m "Initial Commit"
```

```bash
# Cambiar nombre de rama principal de master a main
git branch -m master main
```

#### Utilizar otro repositorio (clonar)

Nota: Recuerda logearte en tu cuenta de github desde el Visual Studio Code (abajo a la izquierda)

```bash
# Clonar repositorio
git clone https://github.com/UsuarioGithub/´NombreDelProyecto.git
```
