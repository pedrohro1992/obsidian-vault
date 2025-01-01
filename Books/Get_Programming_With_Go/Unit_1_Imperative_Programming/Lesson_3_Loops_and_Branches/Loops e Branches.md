##### TRUE OR FALSE

em Go declaramos true ou false da seguinte forma:

**var walkOutiside** = true

var **takeTheBluePill** = false

##### COMPARACOES

Um outro jeito de chegar em um valor true ou false e comparando dois valores
##### RAMIFICACOES COM IF 

Um computador usa valores boleanos ou comparacoes para escolher entre diferentes caminhos dentro de um if statement, como demonstrado em lesson3/if/if.go

##### OPERADORES LOGICOS(Logical Operators) 

Em Go, o operador logico **||** significa **or(ou)**  e o operador logico **&&** significa **and(e)**
Usamos operadores logicos para checar multiplas condicoes de uma so vez, usamos a tabela verdade para saber a saida das operacoes

O codigo presente em _logical-operators/leap.go_ determina se o ano 2100 vai ser um ano bisexto ou nao.
As regras para determinar se um ano sera bisexto ou nao, sao as seguintes:
 - Qualquer ano que e divisivel por 4 mas nao e divisivel por 100
 - Ou qualquer ano que e divisivel por 400

Como a maioria das linguagens de programacao,  Go usa _short-circuit logic_. 
Se a primeira condicao for verdadeira(o ano e divisivel por 400) nao a necessiade de validar o que vem depois do __||__ entao, e ignorado

O operador __&&__ funciona de forma oposta, o resultado e falso a nao ser que as duas condicoes forem verdadeiras. Se a year nao e divisivel por 4, nao tem necessidade de validar a proxima condicao

O operador logico __not(!)__ inverte um valor booleano, de _false_ para _true_ e vice e versa, o codigo em _logical-operators/torch.go_ mostra uma mensagem se o jogador nao tem uma uma tocha(torch) ou se a tocha nao tiver acessa(lit)

##### RAMIFICANDO(BRANCHING) COM SWITCH

Quando compramos um valor com varios outros, Go prove o statement switch, detalhado em _lesson03/switch/concise-switch.go_

Ou, pode se usar o switch statement com condicoes para cada caso, quase como usar _if...else_. Uma feature unica do __switch__ e a keyword __falltrouth__ que executa o corpo do proximo __case__. Como demonstado em _lesson03/switch/switch.go_ 

##### REPETICOES COM LOOPS

Ao inves de escrever o mesmo codigo diversas vezes, a keyword __for__ repete o codigo, o codigo em _lesson03/loops-repetition/countdown.go_ faz o loop ate que __count__ seja igual a 0

Antes de cada interecao, a expressao __count > 0__ e avaliada e essa avaliacao produz um valor booleano. Se o valor for __false__ (__count__ = 0), o loop termina, caso contrario, ele roda o corpo do loop(o codigo entre { }).

Um loop infinito nao especifica uma condicaco para o __for__, mas ainda pode sair fora do loop com __break__ a qualquer momento. O codigo em _lesson03/loops-repetions/infinity.go_ faz a orbita em um circulo 360 graus e para aleatoriamente





