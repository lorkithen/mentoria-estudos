# Tipagem do Javascript

Algumas linguagens s�o classificadas pela sua tipagem. � uma caracter�stica de
determinadas linguagens de programa��o. A tipagem utilizada no javascript � a **tipagem din�mica**.
Esse tipo de tipagem n�o � necess�rio definir o tipo das vari�veis ao declar�-las, para isso basta
usar a palavra "var". 

Exemplo:
```javascript
var nome;
nome = "fulano"";
var idade =  30;
```

Em outras tipagem por exemplo h� uma verifica��o dos tipos usados em dados e vari�veis
para garantir que sempre est� sendo usado um tipo que � esperado em todas as situa��es.
Na tipagem din�mica isso tamb�m ocorre, mas ela � feita em cima do dado em si,
que no javascript as vari�veis podem conter qualquer tipo de dado.

## Vantagens e Desvantagens

### Desvantagens
> Descobre os erros no �ltimo momento.
> A perfomance costuma ser inferior
> Exigem testes em cima dos tipos
> O programador precisa entender e documentar o c�digo para saber os tipos.
> Os tipos de dados s�o resolvidos em tempo de execu��o.

### Vantagens
> Facilita o experimento
> Flexibilidade
> Facilita pequenos programas
> Altera��es podem ser assimiladas sem altera��o no c�digo espec�fico
> Conciso

#### Tipagem Fraca

O javascript possui uma tipagem fraca. � aquela onde necessariamente voc� precisa
explicitar o tipo de dado. Basicamente a vari�vel pode se auto-tipar de acordo
com o valor atribu�do. 

