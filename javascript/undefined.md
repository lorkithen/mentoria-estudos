# undefined

O valor **undefined** � retornado quando voc� usa uma propriedade do objeto
que n�o existe, ou uma vari�vel que tenha sido declarada, mas que nunca teve
um valor atribuido a ela.
Voc� pode verificar se uma vari�vel existe comparando-a a **undefined.**

Nesse exemplo podemos ver se a vari�vel x foi declarada.

```javascript
if (x == undefined) {
   document.write("comparing x to undefined <br/>");
}
```