


#### FLUXOGRAMA

```mermaid
flowchart TD
A([INICIO])--> B{{Declare uma idade}}
B --> C[/I1/]
C --> D{I1 >= 18}
D --TRUE--> E{{Já pode retirar a CNH}}
D --FALSE--> F[I2 = 18 - I1]
F --> G{I2 <= 18}
G --TRUE--> H{{Deve esperar o I2 ser = a 18}}
G --FALSE--> D
E --> I([FIM])
H --> I







```

#### PSEUDOCODIGO

```mermaid
flowchart TD
ALGORITMO
VERIFICAR I1, I2 NUMERICOS
ESCREVA "Declare uma idade"
LEIA I1
SE I1 >= 18 ENTAO
	ESCREVA "Já pode retirar a CNH"
SENAO 
	I2 = 18 - I1 
	SE I2 <= 18 ENTAO
		ESCREVE "Deve sua idade ser igual a 18"
	SENAO
		ESCREVA "Verifique novamente sua idade"
FIM





```
