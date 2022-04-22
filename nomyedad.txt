#include <stdio.h>

int main(){
	char nombre [30];
	int edad;

	printf("ingrese su nombre: ");
	scanf("%s", nombre);
	printf("ingrese su edad:");
	scanf("%d",edad);

	printf("Hola! %s %d ", nombre, edad);
	
	return 0;
}