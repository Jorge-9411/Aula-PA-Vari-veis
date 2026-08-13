
/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(int argc, char *argv[]) {
	
	char continuar = 'S';
	float soma = 0;
	
	while(toupper(continuar)== 'S')
	{
		float novoValor;
		printf("Digite o valor a ser somado:");
		scanf("%f", &novoValor);
		
		soma += novoValor;
		printf("Soma total: %.2f\n", soma);
		
		printf("Deseja continuar inserindo valores? (S ou N)");
		scanf(" %c", &continuar);
	}
	
	printf("Fim do programa!");
	
	return 0;
}
