#### FLUXOGRAMA

```mermaid
flowchart TD
A([INICIO]) --> B{{Digite a primeira nota: }}
B --> C[/Nota1/]
A --> D{{Digite a segunda nota: }}
D --> E[/Nota2/]
C --> F[MEDIA == Nota1 + Nota2 / 2]
E --> F
F --> G{MEDIA >= 7}
G --TRUE--> H[O aluno está aprovado com media: MEDIA]
G --FALSE--> I[O aluno está reprovado com media: MEDIA]
H --> J([FIM])
I --> J

```  


#### PSEUDOCODIGO

```
ALGORITMO verificar_MEDIA
Declare Nota1, Nota2, MEDIA NUMERICO
ESCREVA "Digite a primeira nota do aluno: "
LEIA Nota1
ESCREVA "Digite a segunda nota do aluno: "
LEIA Nota2
MEDIA = (Nota1 +Nota2) / 2
SE MEDIA >= 7 ENTAO
	ESCREVA "O aluno foi aprovado com média igual: ", MEDIA
SENAO
	ESCREVA "O aluno foi reprovado com médiaa igual: ", MEDIA
FIM ALGORITMO 






```
                                                                                                                                                                                                                                                                                                                                                                                 
  

                                                                                                                                                                                                                                                                                                                                                                                 
  

