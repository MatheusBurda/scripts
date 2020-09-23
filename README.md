# Scripts

Alguns scripts que uso no meu dia a dia.

Adicionarei mais scripts ao criá-los.

## criaListaExercícios

Cria um arquivo .c para eu usar nas aulas que tem programação em linguagem c, facilitando a resolução de listas de exercícios.

O arquivo criado com parâmetro 2 para quantidade de exercícios, fica com a seguinte configuração:
```
#include<stdio.h>

/*Digite o cabeçalho do exercicio aqui*/
void exercicio1(){
/*Digite o codigo aqui*/
}

/*Digite o cabeçalho do exercicio aqui*/
void exercicio2(){
/*Digite o codigo aqui*/
}

void main(){

	int escolha;

	printf("Executar qual exercicio? ");
	scanf("%d",&escolha);

	switch(escolha){
	case 1:
		exercicio1();
		break;
	case 2:
		exercicio2();
		break;
	default:
		printf("Exercicio nao existente!!\n");
	}
}
```
Então cada exercício é uma função e posso resolver a lista inteira em um arquivo somente.
