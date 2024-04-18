## Facilitar la creación de un repositorio en Github

> Objetivo: Simplificar lo cotidiano cuando actualizo un repositorio Github.


#### Sugerencia de instalación

> Clonar el repositorio desde la URL

```
    $  cd ~/
    $  git clone https://github.com/WojGeek/gitools.git

```

#### Requerimientos antes de utilizar los scripts
>
> - Crear un TOKEN en su cuenta Github:  https://github.com/settings/tokens
> 
> - Declarar dos variables de entorno 
> 
>>   MY_TOKEN="jysh_7132kasasTOKEN"
>>   GITHUB_ACCOUNT="your-username"
>
>   en el archivo **my_custom.env**  en  el directorio clonado: **gittools**
>
>

#### 1. Hacer el primer commit de manera simple


```
     $   ~/gittools/do-first-commit.sh    repository

```


#### 2.  Actualizar cambios en su repositorio

>> **Opcional**
> 
> ya que usualmente podria como de costumbre
> - git add.
> - git commit -m "your comment"
> - git push
>
>> Sin embargo, hay caso que se requiere el token para **git push**
>

```
     $   ~/gittools/update-repo.sh   repository

```