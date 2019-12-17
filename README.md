# Directorio de desarrolladores de Lytica (Práctica de Git)

Repositorio para practicar el flujo de git.

## Objetivo

Se debe crear una página web que muestre el nombre, un hobby y la comida favorita de cada uno de los desarrolladores de Lytica.
Además las tarjets deben de estar clasificadas por equipos.

## Instrucciones

Existe ya una base de código para crear tarjetas de cada desarrollador, todos trabajaran sobre el archivo *index.html*.

1. Cada desarrollador debe de crear una *Rama de desarrollador*
1. En esa rama deberán hacer sus cambios, que consistirán en copiar el código de *Estructura de la tarjeta* y agregarlo al código del *index.html* en la sección que corresponda.
1. Deben de hacer por lo menos un commit y el mensaje de este debe ser descriptivo.
1. Cuando terminen deben de hacer push al repositorio y hacer un pull request a su respectiva *Rama de equipo*
1. Deben de asegurarse de que el líder de su equipo mezcle su rama.
1. El líder de equipo a su vez debe de hacer pull requests a la rama master y asegurarse de que sea mezclada, en caso de haber conflictos debe avisarle a los desarrolladores que lo generaron y juntos encontrar una solución.

**Las dudas sobre git las deben de resolver con su líder de equipo, con sus compañeros o investigando por su cuenta**

El directorio final puede verse en https://lyticamx.github.io/git-practice/

## Tipos de ramas

#### Rama de desarrollador

Cada desarrollador debe crearla y ponerle cualquier nombre, aquí es donde se harán los commits que contengan las tarjetas.

#### Rama de equipo

Ya están creadas, sólo podrán hacer mezclas hacia ella los líderes de equipo de Lytica, el objetivo es mezclar ahí las ramas de los desarrolladores. Tienen el prefijo *team_*

#### Rama master

No pueden hacerse commit sobre ella, sólo el encargado del repo la puede mezclar y sólo está permitido que se le mezclen ramas de equipo.

## Estructura de la tarjeta

Para asegurar que su tarjeta sea responsiva pueden copiar y pegar el siguiente template:

```
<div class="col-md-4">
    <div class="card">
    <div class="card-body">
        <h5 class="card-title py-2">Mi nombre</h5>
        <h6 class="card-subtitle mb-2 text-muted">Hobby</h6>
        <p class="card-text">Aquí va mi hobby</p>
        <h6 class="card-subtitle mb-2 text-muted">Comida favorita</h6>
        <p class="card-text">Aquí va mi comida favorita</p>
    </div>
    </div>
</div>
```