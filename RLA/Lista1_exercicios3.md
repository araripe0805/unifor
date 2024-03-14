


#### FLUXOGRAMA
```mermaid
flowchart TD
A([INICIO])--> B{{Digite um numero inteiro}}
B --> C[/N1/]
C --> D{N1 >= 0}
D --TRUE--> E[RESTO = N1 % 2]
E --> F{RESTO = 0}
F --TRUE--> G{{O numero é par}}
F --FALSE--> H{{O numero é impar}}
D --FALSE--> I{{esse numero deve ser positivo}}
G --> J([FIM])
H --> J
I --> J


```

#### PSEUDOCODIGO


```
ALGORITMO
DECLARE N1,RESTO INTEIRO
ESCREVA "Digite um numero inteiro"
LEIA N1
SE N1 >= 0 ENTAO
	RESTO = N1 % 2
	SE RESTO = 0 ENTAO
		ESCREVA "O numero é par"
	SENAO
		ESCREVA "O numero é impar"
	FIM_SE
SENAO
	ESCREVA "O numero é positivo"
FIM_SE
FIM

```
