#include <stdio.h>

int main() {
    // Dados da carta 1 - Pernambuco
char estado1[] = "Pernambuco";
int codigo1 = 26;
char nome1[] = "Pernambuco"; 
unsigned long int populacao1 = 9058931;
float area1 = 98312.0;
float pib1 = 28867.0;
int pontos_turisticos1 = 20;

    // Cálculo da densidade 1
float densidade1 = populacao1 / area1;

    // Cálculo PIB per capita 1
float pib_per_capita1 = pib1 / (float) populacao1;

    // Super poder 1
float super_poder1 = populacao1 + area1 + pib_per_capita1 + pontos_turisticos1 + (1.0 / densidade1);

    // Exibindo dados 1
printf("estado: %s\n", estado1);
printf("codigo: %d\n", codigo1);
printf("nome: %s\n", nome1);
printf("populacao: %lu\n", populacao1);
printf("area: %.2f km²\n", area1);
printf("pib: %.2f milhoes\n", pib1);
printf("pontos_turisticos: %d\n", pontos_turisticos1);
printf("densidade populacional: %.2f hab/km²\n", densidade1);
printf("pib_per_capita: %.8f milhoes/hab\n", pib_per_capita1);
printf("super_poder: %.2f\n", super_poder1);
                     printf("\n");

    // Dados da carta 2 - Rio de Janeiro
char estado2[] = "Rio de Janeiro";
int codigo2 = 21;
char nome2[] = "Rio de Janeiro";
unsigned long int populacao2 = 62110;
float area2 = 120.0;
float pib2 = 359640.0;
int pontos_turisticos2 = 58;

    // Cálculo da densidade 2
float densidade2 = populacao2 / area2;

    // Cálculo do PIB per capita 2
float pib_per_capita2 = pib2 / (float) populacao2;

    // Super poder 2
float super_poder2 = populacao2 + area2 + pib_per_capita2 + pontos_turisticos2 + (1.0 / densidade2);

    // Exibindo dados 2
printf("estado: %s\n", estado2);
printf("codigo: %d\n", codigo2);
printf("nome: %s\n", nome2);
printf("populacao: %lu\n", populacao2);
printf("area: %.2f km²\n", area2);
printf("pib: %.2f milhoes\n", pib2);
printf("pontos_turisticos: %d\n", pontos_turisticos2);
printf("densidade populacional: %.2f hab/km²\n", densidade2);
printf("pib_per_capita: %.8f milhoes/hab\n", pib_per_capita2);
printf("super_poder: %.2f\n", super_poder2);
                      printf("\n");
    
    //comparacao de cartas 
       if (super_poder1 > super_poder2) {
    printf("A carta vencedora é: %s\n", estado1);
} else if (super_poder2 > super_poder1) {
    printf("A carta vencedora é: %s\n", estado2);
} else if (super_poder1 = super_poder2) {
    printf("Empate entre as cartas!\n");
}
}
