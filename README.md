#include <stdio.h>
// fundamentos e técnicas avançadas (nível mestre)
int main() {
    // Dados da carta 1 - Pernambuco
char dados1 [] = "Carta 1";
char estado1[] = "Pernambuco";
int codigo1 = 26;
char nome1[] = "Pernambuco"; 
unsigned long int populacao1 = 9058931;
float area1 = 98312;
float PIB1 = 28867.0;
int pontos_turisticos1 = 120;

    // Cálculo da densidade 1
float densidade1 = populacao1 / area1;

    // Cálculo PIB per capita 1
float pib_per_capita1 = PIB1 / (float) populacao1;

    // Super poder 1
float super_poder1 = populacao1 + area1 + pib_per_capita1 + pontos_turisticos1 + (1.0 / densidade1);

    // Exibindo dados 1
printf("dados1: %s\n", dados1);
    printf ("\n");
printf("estado: %s\n", estado1);
printf("codigo: %d\n", codigo1);
printf("nome: %s\n", nome1);
printf("populacao: %lu\n", populacao1);
printf("area: %.2f km²\n", area1);
printf("PIB: %.2f milhoes\n", PIB1);
printf("pontos_turisticos: %d\n", pontos_turisticos1);
printf("densidade populacional: %.2f hab/km²\n", densidade1);
printf("pib_per_capita: %.8f milhoes/hab\n", pib_per_capita1);
printf("super_poder: %.2f\n", super_poder1);
                     printf("\n");

    // Dados da carta 2 - Rio de Janeiro
char dados2 [] = "Carta 2";
char estado2[] = "Rio de Janeiro";
int codigo2 = 21;
char nome2[] = "Rio de Janeiro";
unsigned long int populacao2 = 16055174;
float area2 = 120.0;
float PIB2 = 359640.0;
int pontos_turisticos2 = 150;

    // Cálculo da densidade 2
float densidade2 = populacao2 / area2;

    // Cálculo do PIB per capita 2
float pib_per_capita2 = PIB2 / (float) populacao2;

    // Super poder 2
float super_poder2 = populacao2 + area2 + pib_per_capita2 + pontos_turisticos2 + (1.0 / densidade2);

    // Exibindo dados 2
printf("dados2: %s\n", dados2);
       printf ("\n");
printf("estado: %s\n", estado2);
printf("codigo: %d\n", codigo2);
printf("nome: %s\n", nome2);
printf("populacao: %lu\n", populacao2);
printf("area: %.2f km²\n", area2);
printf("PIB: %.2f milhoes\n", PIB2);
printf("pontos_turisticos: %d\n", pontos_turisticos2);
printf("densidade populacional: %.2f hab/km²\n", densidade2);
printf("pib_per_capita: %.8f milhoes/hab\n", pib_per_capita2);
printf("super_poder: %.2f\n", super_poder2); printf ("\n");

// desenvolvendo a logica do jogo (nível aventureiro) 
    //comparacao de cartas 
    printf ("resultado dos codigos"); 
              printf ("\n\n");
       if (populacao1 > populacao2) {
    printf("populacao: carta %d\n", 1);
} else if (populacao2 > populacao1) {
    printf("populacao: carta %d\n", 2);
} else if (populacao1 = populacao2) {
    printf("Empate entre as cartas!\n");
       }
    if (area1 > area2) {
    printf("area: carta %d\n", 1);
} else if (area2 > area1) {
    printf("area1: carta %d\n", 2);
} else if (area1 = area2) {
    printf("Empate entre as cartas!\n");
    }
    if (PIB1 > PIB2) {
    printf("PIB: carta %d\n", 1);
} else if (PIB2 > PIB1) {
    printf("PIB: carta %d\n", 2);
} else if (PIB1 = PIB2) {
    printf("Empate entre as cartas!\n");
       }
    if (pontos_turisticos1 > pontos_turisticos2) {
    printf("pontos_turisticos: carta %d\n", 1);
} else if (pontos_turisticos2 > pontos_turisticos1) {
    printf("pontos_turisticos: carta %d\n", 2);
} else if (pontos_turisticos1 = pontos_turisticos2) {
    printf("Empate entre as cartas!\n");
       }
    if (densidade1 < densidade2) {
    printf("densidade: carta %d\n", 1);
} else if (densidade2 > densidade1) {
    printf("densidade: carta %d\n", 2);
} else if (densidade1 = densidade2) {
    printf("Empate entre as cartas!\n");
       }
    if (pib_per_capita1 > pib_per_capita2) {
    printf("pib_per_capita: carta %d\n", 1);
} else if (pib_per_capita2 > pib_per_capita1) {
    printf("pib_per_capita: carta %d\n", 2);
} else if (pib_per_capita1 = pib_per_capita2) {
    printf("Empate entre as cartas!\n");
       }
           if (super_poder1 > super_poder2) {
    printf("super_poder: carta %d\n", 1);
} else if (super_poder2 > super_poder1) {
    printf("super_poder: carta %d\n", 2);
} else if (super_poder1 = super_poder2) {
    printf("Empate entre as cartas!\n");
}
}
