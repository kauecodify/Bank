# Bank
#include <stdio.h>
int main (){
    int n;
    
    printf("\n(1) para Saldo\n (2) para Extrato (3) para Saque\n (4) para Sair");
    printf("\nInforme a operação desejada: ");
    
    scanf("%d", &n);
    
    switch(n) {
        
        case 1: 
        printf("\nSaldo");
        break;
        
        case 2:
          printf("\Extrato");
          break;
          
        case 3:
        
        printf("\n Saque");
        break;
        
        default:
        
         printf("\nInválido");
        
    }
    
    return 0;
    
}  
