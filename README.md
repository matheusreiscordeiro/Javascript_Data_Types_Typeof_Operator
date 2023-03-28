# Javascript_Data_Types_Typeof_Operator

<br/>

O operador typeof é um operador unário em JavaScript que retorna uma string indicando o tipo de dados de uma expressão. Ele é frequentemente usado para verificar o tipo de dados de uma variável ou valor, especialmente quando a natureza da entrada do usuário é desconhecida.

Aqui estão alguns exemplos de como usar o operador typeof em JavaScript:

<br/>

```
// Verificando o tipo de uma variável
const myVariable = 42;
console.log(typeof myVariable); // Output: 'number'

// Verificando o tipo de uma string
const myString = 'Olá, mundo!';
console.log(typeof myString); // Output: 'string'

// Verificando o tipo de uma função
function myFunction() {
  return 'Eu sou uma função';
}
console.log(typeof myFunction); // Output: 'function'

// Verificando o tipo de um objeto
const myObject = { name: 'João', age: 30 };
console.log(typeof myObject); // Output: 'object'

// Verificando o tipo de um array
const myArray = [1, 2, 3, 4, 5];
console.log(typeof myArray); // Output: 'object'

// Verificando o tipo de um valor nulo
const myNull = null;
console.log(typeof myNull); // Output: 'object'

// Verificando o tipo de um valor indefinido
let myUndefined;
console.log(typeof myUndefined); // Output: 'undefined'
```

<br/>

Nestes exemplos, o operador typeof é usado para verificar o tipo de dados de diferentes valores. Ele retorna uma string que representa o tipo de dados da expressão. Por exemplo, o valor 42 tem o tipo 'number', a string 'Olá, mundo!' tem o tipo 'string', e a função myFunction tem o tipo 'function'.

É importante observar que o operador typeof tem algumas peculiaridades. Por exemplo, ele retorna 'object' para objetos, incluindo arrays e valores nulos, o que pode ser confuso. Além disso, ele retorna 'function' para funções, mas as funções são tecnicamente objetos em JavaScript. Portanto, o operador typeof nem sempre fornece uma verificação precisa do tipo de dados.
