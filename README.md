# tabuada-linguagem-c-
#include <stdio.h>

int tabuadaNumero(int num1){
    for(int i =0 ; i <= 10 ; i++){
         printf(" %i x %i = %i\n", num1, i, num1* i);
    }
}

  int main(){
      int num1;
      printf("Digite o numero desejado para fazer tabuada : \n");
      scanf("%i",&num1);
      
      int resultadoTabuadaNumero = tabuadaNumero(num1);
  }
    
    
    
    
    
    
