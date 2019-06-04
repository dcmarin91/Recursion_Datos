# Ejercicio Recursion aplicado a estructuras de datos

## Ejercicio Reverse String

```
var reverseString = function(s) {
    if(s===""){
        return "";
    }
    return reverseString(s.slice(1))+ s[0];
};
console.log(reverseString("hola mundo"))

```
