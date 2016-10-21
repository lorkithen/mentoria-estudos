# Tipagem do Javascript

Algumas linguagens são classificadas pela sua tipagem. É uma característica de
determinadas linguagens de programação. A tipagem utilizada no javascript é a **tipagem dinâmica**.
Esse tipo de tipagem não é necessário definir o tipo das variáveis ao declará-las, para isso basta
usar a palavra "var". 

Exemplo:
```javascript
var nome;
nome = "fulano"";
var idade =  30;
```

Em outras tipagem por exemplo há uma verificação dos tipos usados em dados e variáveis
para garantir que sempre está sendo usado um tipo que é esperado em todas as situações.
Na tipagem dinâmica isso também ocorre, mas ela é feita em cima do dado em si,
que no javascript as variáveis podem conter qualquer tipo de dado.

## Vantagens e Desvantagens

### Desvantagens
> Descobre os erros no último momento.
> A perfomance costuma ser inferior
> Exigem testes em cima dos tipos
> O programador precisa entender e documentar o código para saber os tipos.
> Os tipos de dados são resolvidos em tempo de execução.

### Vantagens
> Facilita o experimento
> Flexibilidade
> Facilita pequenos programas
> Alterações podem ser assimiladas sem alteração no código específico
> Conciso

#### Tipagem Fraca

O javascript possui uma tipagem fraca. É aquela onde necessariamente você precisa
explicitar o tipo de dado. Basicamente a variável pode se auto-tipar de acordo
com o valor atribuído. 

