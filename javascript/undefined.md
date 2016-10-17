# undefined

O valor **undefined** é retornado quando você usa uma propriedade do objeto
que não existe, ou uma variável que tenha sido declarada, mas que nunca teve
um valor atribuido a ela.
Você pode verificar se uma variável existe comparando-a a **undefined.**

Nesse exemplo podemos ver se a variável x foi declarada.

```javascript
if (x == undefined) {
   document.write("comparing x to undefined <br/>");
}
```