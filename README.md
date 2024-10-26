# Programando_em_C_1
Pedido ao usuario tem valores inteiros e fazendo a soma entre eles.

Codigo 100% funcional

// Desenvolvedor.: Adalberto Fernnandes
// Sistema Versão.: v1.0
// Peça ao usuário para digitar três valores inteiros e imprima a soma deles

#include<stdio.h>
#include<stdlib.h>
#include<locale.h>

int main(){
	// Aqui temos uma biblioteca que permite o acentos das palavras no codigo
	setlocale(LC_ALL, "Portuguese");
	// Declarando as variaveis e seus tipos de dados
	int valor1, valor2, valor3, soma = 0;
	// Solicitando ao usuario que digite três valores
	printf("Digite o primeiro valor: ");
	scanf("%d", &valor1);
	printf("Digite o segundo valor: ");
	scanf("%d", &valor2);
	printf("Digite o terceiro valor: ");
	scanf("%d", &valor3);
	// Fazendo a soma dos valores digitados pelo usuario
	soma = valor1 + valor2 + valor3;
	// Mostrando o valor final da soma entre os valores
	printf("A soma dos três valores é %d: ", soma);
	
	return 0;
}
