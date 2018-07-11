- Diego-Resende-Alves-calcularidade
- programa que descobre aidade de calquer pessoa

#include<stdio.h>

int main(){

int anodenascimento;
int anoatual;
int idade;

printf("\n+++++++++++++++++++++++++++ PROGRAMA CALCULAR IDADE ++++++++++++++++++++++++++++\n\n\n");

printf("\nDIGITE O ANO EM QUE VOCE NASCEU E LOGO EM SEGUIDA O ANO ATUAL:\n");
scanf("%i", &anodenascimento);
scanf("%i", &anoatual);

idade = anoatual - anodenascimento;

printf("\n\nA SUA IDADE E %i ANOS\n", idade);
printf("VOCE NASCEU EM %i\n", anodenascimento);
printf("VOCE ESTA EM %i\n\n\n", anoatual);

printf("PRESSIONE ENTER PARA ACESSAR MAIS OPCOES\n\n");
system("pause");
system("cls");

void fecharprograma();
fecharprograma();

system("pause");
return 0;

}

void fecharprograma(){
int fechar;

printf("\n\n+++++++++++++++++++++++++++PROGRAMA CALCULAR IDADE+++++++++++++++++++++++++++++\n\n\n");

printf("1: MATER O PROGRAMA ABERTO\n0: FECHAR O PROGRAMA\n\n");
printf("DIGITE 0 OU 1 DE ACORDO COM A OPçAO ESCOLHIDA:\n");
scanf("%i", &fechar);
if(fechar == 1){
printf("PRESSIONE ENTER PARA MANTER O PROGRAMA ABERTO\n");
system("pause");
system("cls");
int main();
main();

}

if(fechar == 0){
printf("PRESSIONE ENTER PARA FECHAR O PROGRAMA\n");
system("pause");
system("cls");

}

system("pause");
return 0;
}



AUTOR: DIEGO RESENDE ALVES/SISTEMA DE INFORMAÇÃO/UNIS/MG
