# Solidity Learning

info: [https://docs.soliditylang.org/en/v0.8.30/](Solidity Docs)
 ---
# Structures in Solidity

# Types

## Value Tpyes
### Boleans
 - Bool: Representa valores booleanos que pueden ser true or false.

### Integers
 - `Uint` (unisigned integers): enteros sin signo Cantidad de bits: 256,128,64,32,16,8.
 - `Int` (signed integers): enteros con signo. Rango: -2,147,483,648 -> 2,147,483,647
### Fixed Point Numbers (size variable)
 - `unfixed` (unsigned fixed point number)
 - `fixed` (signed fixed point number)

Keywords `ufixedMxN` and `fixedMxN`, 
 - M representa la cantidad de bits que ocupa el tipo. M debe ser divisible por 8 e ir de 8 a 256 bits 
 - N representa cuántos decimales diposnibles hay. N debe estar entre 0 y 80, inclusive.

### Address
Address: Representa direcciones Ethereum. Estas son direcciones de cuentas o contratos inteligentes en la red Ethereum.

### Contract Types
### Fixed size byte arrays
 - Array: Representa una lista de elementos del mismo tipo. Puede ser un array estático de tamaño fijo o un array dinámico.

### Address Literals
### Rational and Integer Literals
### String Literals and Types
### Unicode Literals 
### Hexadecimal Literals
 - `Byte32`: Se utiliza para almacenar datos en bruto de longitud fija y realizar operaciones criptográficas, comparaciones de igualdad y almacenamiento de datos estructurados.

### Enums
 - `Enum`: Representa un tipo de dato que puede tener uno de varios valores predefinidos.
User-defined Value Types 

### Complex Data Structures

## Reference Type
## Mapping Type
Mapping: Es una estructura de datos que asigna claves a valores. Es similar a un diccionario o tabla hash.

