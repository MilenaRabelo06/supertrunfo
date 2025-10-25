

#include <stdio.h>

int main() {
    char estado;
    char cidade[40];
    char codigo[40];
    int populacao;
    float area;
    float pib;
    int pontos_turisticos;

    printf("Digite a letra do estado: ");
    scanf(" %c", &estado);

    printf("Digite o nome da cidade: ");
    scanf("%s", cidade);

    printf("Digite o código da carta: ");
    scanf("%s", codigo);

    printf("Digite a população da cidade: ");
    scanf("%d", &populacao);

    printf("Digite a área da cidade: ");
    scanf("%f", &area);

    printf("Digite o PIB da cidade: ");
    scanf("%f", &pib);

    printf("Digite o número de pontos turísticos: ");
    scanf("%d", &pontos_turisticos);

    printf("\nEstado: %c\n", estado);
    printf("Código: %s\n", codigo);
    printf("Cidade: %s\n", cidade);
    printf("População: %d\n", populacao);
    printf("Área: %.2f km²\n", area);
    printf("PIB: %.2f\n", pib);
    printf("Pontos Turísticos: %d\n", pontos_turisticos);

    return 0;
}
