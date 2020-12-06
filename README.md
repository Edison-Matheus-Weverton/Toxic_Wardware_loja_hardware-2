# Toxic_Wardware_loja_hardware-2



#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <windows.h>
#include <locale.h>
#define estcoo 523
#define estcpu 811
#define estmram 675
#define estpdv 731
#define estpm 800

int main()
{
    setlocale(LC_ALL,"");
    int resp,resp2,cad=0;
    float cart;
    char nome[70];

    printf("\n\n================================================================================\n\n");
    printf("\t\t\t\tToxic Hardwares\n\n");
    printf("\n================================================================================\n\n");

    printf(" Toxic hardwares é uma loja voltada para a venda de peças de informática que atende a qualquer pessoa do país virtualmente, o frete varia de acordo com sua região e os produtos são sempre bem embalados visando a segurança do produto.\n");
    Sleep(2000);
    printf("\n Seja bem vindo!\n");
    system("pause");
    system("cls");

    do{printf("\n\n================================================================================\n\n");
    printf("\t\t\t\tToxic Hardwares\n\n");
    printf("\n================================================================================\n\n");
    printf("\n Selecione o que deseja ver agora\n\n 1= Cadastro\n 2= Produtos\n 3= Salário dos funcionários\n 4= Estoque\n 5= Fornecedores\n 6 = Despesas\n 7 = Vendas\n 8 = Marcas\n 9= Tamanho\n 10= Valor dos Fretes\n 11 = Formas de pagamento\n 12 = Sair");
    printf("\n\n Digite o número: ");
    scanf("%d",&resp);

    switch (resp)
    {case 1:  system("cls");

        if(cad==0){
         printf(" Insira seu nome: ");
         fflush(stdin);
         gets (nome);
         fflush(stdin);
         printf("\n Insira o saldo em seu cartão: R$ ");
         scanf("%f",&cart);
         system("cls");
         printf(" OK, usuário cadastrado com sucesso\n\n\n");

         cad=1;
         }
         else {
            printf(" Ops, você já está cadastrado!\n\n\n");
         }
        system("pause");
        system("cls");
    break;

    case 2: do {
        system("cls");
        printf("\n O dinheiro atual na sua carteira é de R$%.2f\n\n",cart);
        printf(" 1-> Cooler\n\n");
        printf(" 2-> CPU\n\n");
        printf(" 3-> Memória RAM\n\n");
        printf(" 4-> Placa de vídeo\n\n");
        printf(" 5-> Placa-mãe\n\n");
        printf(" 6-> Voltar\n\n");
        printf("\n\n Digite o número: ");
        scanf("%d",&resp2);

        switch (resp2){
        case 1: system("cls");
        printf(" \n");
        system("pause");
        system("cls");
        break;

        case 2: system("cls");
        printf(" \n");
        system("pause");
        system("cls");
        break;

        case 3: system("cls");
        printf(" \n");
        system("pause");
        system("cls");
        break;

        case 4: system("cls");
        printf(" \n");
        system("pause");
        system("cls");
        break;

        case 5: system("cls");
        printf(" \n");
        system("pause");
        system("cls");
        break;

        default: system("cls");
        printf(" Por favor, insira um número válido!\n\n\n");
        system("pause");
        system("cls");
        break;
        }
    }while(resp2!=6);
    break;

    case 3: system("cls");
    printf("\n O salário do Cleyton da Silva é R$1.045,00\n O salário da Roberta Fonseca é R$1.045,00\n O salário do Felipe Dias Lima é R$1.045,00\n O salário do Freddie Aragão Lanna é R$2.435,00\n O salário da Carmen é R$3.431,00\n O salário do Bartolomeu Marazzo Frota é R$4.567,00\n\n");
    system("pause");
    system("cls");
    break;

    case 4: system("cls");
    printf(" Temos em estoque:\n %d Coolers\n %d CPUs\n %d Memórias RAM\n %d Placas de vídeo\n %d Placas-mãe\n\n",estcoo, estcpu,estmram,estpdv,estpm);
    system("pause");
    system("cls");
    break;

    case 5: system("cls");
    printf("\n Kabum - https://m.kabum.com.br/\n");
    printf("\n Terabyteshop - https://www.terabyteshop.com.br/\n");
    printf("\n Ednaldo Pereira tel: (11)99935-2764\n");
    system("pause");
    system("cls");
    break;

    case 6: system("cls");
    printf("\nEnergia para manter o sistema ativo = R$1.000 -- 3.000");
    printf("\nGasto com funcionarios = R$13.568,00");
    printf("\nGasto com produtos = R$0 -- R$15.000");
    printf("\nMaquinário e serviços = R$12.500,00");
    printf("\nCustos Gerais = R$20.000 -- R$100.000\n\n");
    system("pause");
    system("cls");
    break;


    case 7: system("cls");
    printf("\nAtualmente nossa empresa não possui o numero exato de vendas, mas acreditamos que seja por volta de 36,858 mil produtos\n\n");
    system("pause");
    system("cls");
    break;


    case 8: system("cls");
    printf("\nMarcas dos Coolers = GAMEMAX e EVGA");
    printf("\nMarca das Memorias Ram = CORSAIR, PCCOOLER e TRIDENTZ");
    printf("\nMarcas das Placas de Vídeo = EVGA, GIGABYTE, PNY e ASUS");
    printf("\nMarcas das Placas-Mãe = ASROCK, GIGABYTE e ASUS\n\n");
    system("pause");
    system("cls");
    break;


    case 9: system("cls");
    printf("\nTamanho dos Coolers = 135 x 80 x 154.5mm");
    printf("\nTamanho das Memorias Ram = 5cm x 0.5cm");
    printf("\nTamanho das Placas de Vídeo = - Altura: 111.15 mm Comprimento: 285.37 mm Largura: 2.2 slots");
    printf("\nTamanho das Placas-Mãe = Modelo mATX 24.4 cm por 24 cm (9.6 polegadas por 9.5 polegadas)\n\n");
    system("pause");
    system("cls");
    break;

    case 10: system("cls");
    printf("\nFrete para Sul e Sudeste = R$70,00");
    printf("\nFrete para Norte = R$89,00");
    printf("\nFrete para Nordeste= R$120,00");
    printf("\nFrete para Centro -Oeste = R$65,00\n\n");
    system("pause");
    system("cls");
    break;

    case 11: system("cls");
    printf("\nPaypal = 2 por cento de taxa para pagamento á vista");
    printf("\nCartão de Credito = 15 por cento de taxa em até 12x");
    printf("\nBoleto Bancario = 10 por cento de Desconto");
    printf("\nTransferência = 5 por cento de desconto\n\n");
    system("pause");
    system("cls");
    break;


    case 12: system("cls");
    break;

    default: system("cls");
    printf(" Por favor, insira um número válido!\n\n\n");
    system("pause");
    system("cls");
    break;}} while (resp!=12);
        printf(" Obrigado pela escolha!\n\n Volte sempre!\n");
    return 0;
}
