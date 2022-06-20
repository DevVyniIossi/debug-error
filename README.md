# Tratamento de Erros

Neste repositório você encontrará a atividade prática proposta pelo curso "Debugging e Error Handling" do BootCamp da TQI da DIO - Digital Innovation One, ministrado pela [stebsnusch](https://github.com/stebsnusch).

## Atividade: validação de erros por tipo

O objetivo é que a função receba um array e retorne ele caso o seu tamanho corresponda ao número enviado como parâmetro na função. Caso contrário, um erro será lançado.

- Crie uma função que recebe um array e um número
- Realize as seguintes validações
  - Se os parâmetros não forem enviados, lance um erro do tipo `ReferenceError`
  - Se o array não for do tipo 'object', lance um erro do tipo `TypeError`
  - Se o número não for do tipo 'number', lance um erro do tipo `TypeError`
  - Se o tamanho do array for diferente do número enviado como parâmetro, lance um erro do tipo `RangeError`
- Utilize a declaração `try...catch`
- Filtre as chamadas de catch por cada tipo de erro utilizando o operador `instanceof`

## Links Auxiliares

- [Objeto Error](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Error)
- [instanceof](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Operators/instanceof)
- [typeof](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Operators/typeof)
- [try...catch](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/try...catch)

# Software Utilizado

\- Microsoft Visual Studio Editor

## Linguagem Utilizado

- JavaScript