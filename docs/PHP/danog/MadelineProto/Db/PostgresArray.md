---
title: "danog\\MadelineProto\\Db\\PostgresArray: Postgres database backend."
description: ""
image: "https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png"
parent: "MadelineProto API"

---
# `danog\MadelineProto\Db\PostgresArray`
[Back to index](../../../index.html)

> Author: Daniil Gentili <daniil@daniil.it>  
  

Postgres database backend.  




## Method list:
* `initStartup(): \Generator`
* `initConnection(\danog\MadelineProto\Settings\Database\Postgres $settings): \Generator`
* `getIterator()`
* `unset(string|int $index): \Amp\Promise<array>`
* `count(): \Promise<int> The number of elements or public properties in the associated
array or object, respectively.`
* `clear(): \Amp\Promise<\Amp\Sql\CommandResult>`
* `getTable(): string`
* `isset(mixed $key): \Promise<bool> true if the offset exists, otherwise false`
* `getInstance(string $table, \danog\MadelineProto\Db\DbArray|array|null $previous, \danog\MadelineProto\Settings\Database\DatabaseAbstract $settings): \Amp\Promise`

## Methods:
### `initStartup(): \Generator`

Initialize on startup.


#### See also: 
* `\Generator`




### `initConnection(\danog\MadelineProto\Settings\Database\Postgres $settings): \Generator`

Initialize connection.


Parameters:

* `$settings`: `\danog\MadelineProto\Settings\Database\Postgres`   


#### See also: 
* [`\danog\MadelineProto\Settings\Database\Postgres`: Postgres backend settings.](../../../danog/MadelineProto/Settings/Database/Postgres.html)
* `\Generator`




### `getIterator()`





### `unset(string|int $index): \Amp\Promise<array>`

Unset value for an offset.


Parameters:

* `$index`: `string|int` <p>
The offset to unset.
</p>  


#### See also: 
* `\Amp\Promise`




### `count(): \Promise<int> The number of elements or public properties in the associated
array or object, respectively.`

Count elements.


Return value: The number of elements or public properties in the associated
array or object, respectively.


### `clear(): \Amp\Promise<\Amp\Sql\CommandResult>`

Clear all elements.


#### See also: 
* `\Amp\Sql\CommandResult`
* `\Amp\Promise`




### `getTable(): string`

Get the value of table.



### `isset(mixed $key): \Promise<bool> true if the offset exists, otherwise false`

Check if key isset.


Parameters:

* `$key`: `mixed`   


Return value: true if the offset exists, otherwise false


### `getInstance(string $table, \danog\MadelineProto\Db\DbArray|array|null $previous, \danog\MadelineProto\Settings\Database\DatabaseAbstract $settings): \Amp\Promise`




Parameters:

* `$table`: `string`   
* `$previous`: `\danog\MadelineProto\Db\DbArray|array|null`   
* `$settings`: `\danog\MadelineProto\Settings\Database\DatabaseAbstract`   


Fully typed return value:
```
\Amp\Promise<static>
```
#### See also: 
* [`\danog\MadelineProto\Db\DbArray`: DB array interface.](../../../danog/MadelineProto/Db/DbArray.html)
* [`\danog\MadelineProto\Settings\Database\DatabaseAbstract`: Base class for database backends.](../../../danog/MadelineProto/Settings/Database/DatabaseAbstract.html)
* `\Amp\Promise`




---
Generated by [danog/phpdoc](https://phpdoc.daniil.it)
