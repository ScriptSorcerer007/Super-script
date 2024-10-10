#include<stdio.h>
int main(){
	int decimal , i, bin;
	printf("Enter decimal number  =");    //input
	scanf("%d" , &decimal );
	printf("Decimal  :  %d\n",decimal);   //Decimal
    printf("Binary conversion  :  ");     
	for (i=31 ; i>=1 ; i--){              //Binary conversion
		bin = (decimal >> i ) &1; 
		printf("%d",bin);
	}
     printf("\n");
	 printf("Octal conversion  :  %o\n",decimal);   //Octal conversion
	 printf("Hexadecimal conversion  :  %X\n",decimal);   //Hexadecimal conversion
	 return 0;	
}# Super-script
