![enter image description here](https://raw.githubusercontent.com/sergiecode/console-table-tutorial/master/console-table-tutorial.jpg)


# Tutorial sobre `console.table` de JavaScript

Este es un tutorial sobre cómo usar la función `console.table` de JavaScript para mostrar datos en una tabla en la consola del navegador.

## Introducción

La función `console.table` es una herramienta muy útil para mostrar datos de una manera más visual y organizada en la consola del navegador. En lugar de mostrar los datos en una lista larga y desordenada, `console.table` muestra los datos en una tabla fácil de leer.

## Cómo usar `console.table`

Para usar `console.table`, simplemente pasa tus datos como un objeto o un array a la función. Por ejemplo:

    const data = [
          { name: 'John', age: 30 },
          { name: 'Jane', age: 25 },
          { name: 'Bob', age: 40 }
        ];
    
    console.table(data);

Este código mostrará los datos en una tabla en la consola:

| (index) | name | age |
|----------|----------|----------|
| 0    | John   | 30   |
| 1    | Jane   | 25   |
| 2    | Bob   | 40   |

Puedes incluso mostrar sólo ciertas columnas de los datos:

     const data = [
          { name: 'John', age: 30, city: 'New York' },
          { name: 'Jane', age: 25, city: 'Los Angeles' },
          { name: 'Bob', age: 40, city: 'Chicago' }
        ];
    console.table(data, ['name', 'city']);

Este código mostrará sólo las columnas 'name' y 'city' en la tabla:

| (index) | name | age |
|----------|----------|----------|
| 0    | John   | New York|
| 1    | Jane   | Los Angeles|
| 2    | Bob   | Chicago |


## Conclusión

La función `console.table` es una herramienta muy útil para mostrar datos de una manera más visual y organizada en la consola del navegador. Es fácil de usar y puede ahorrarte tiempo al mostrar los datos en una tabla fácil de leer. Espero que este tutorial te haya sido útil.
