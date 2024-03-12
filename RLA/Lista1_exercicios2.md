


#### FLUXOGRAMA

```mermaid
flowchart TD
A([INICIO]) --> B{{Digite seu sálario:}}
B --> C[/S1/]
C --> D{S1 >= 500}
D --TRUE--> E[S1 * 1.1 = S2]
D --FALSE--> F[S1 * 1.2 = S2]
E --> G{{S2}}
F --> G
G --> H([FIM])

```
#### PSEUDOCODIGO

```mermaid
flowchart TD
ALGORITMO verificar_NOVO SALARIO
DECLARE S1, S2 NUMERICOS
ESCREVA "Digite seu salario atual: "
LEIA S1
SE S1 >= 500 ENTAO
	S2 = S1 * 1.1
SENAO
	S2 = S1 * 1.2
ESCREVA "Seu novo salario é: ", S2
FIM ALGORITMO
```
