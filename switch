#include <stdio.h>
#include <locale.h>

char nome[100], email[100], tel[15], end[100];
int op;

void cadastro(){
    printf("Digite o nome: ");
    scanf("%s", nome);

    printf("Digite o e-mail: ");
    scanf("%s", email);

    printf("Digite o telefone: ");
    scanf("%s", tel);

    printf("Digite o endereço: ");
    scanf("%s", end);
}

void imprimir(){
    printf("Nome: %s\n E-mail: %s\n Telefone: %s\n Endereço: %s\n", nome, email, tel, end);
}

int main(){
    setlocale(LC_ALL, "");

    printf("Digite 1 - para fornecedor 2 - para cliente: \n");
    scanf("%i", &op);

    switch (op) {
        case 1:
             printf("Cadastro fornecedor\n");
             cadastro();
             system("cls");
             imprimir();
             break;
        case 2:
             printf("Cadastro cliente\n");
             cadastro();
             system("cls");
             imprimir();
             break;
        default:
             printf("Opção inválida");
             break;
    }

    return 0;
}
