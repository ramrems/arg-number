#include <stdio.h>
#include <stdlib.h>
#include <math.h>

int argnum_bul(int sayi){
    int n,r,toplam=0,orgsayi=sayi;
while(sayi>0)
{
r=sayi%10;
toplam=toplam+(r*r*r);
sayi=sayi/10;}
    if (orgsayi==toplam){
       return 0;}
}

int main(){
int n;
printf("sayi giriniz");
scanf("%d",& n);
if (argnum_bul(n)==0){
     printf("bu sayi armstrong");}
  else{ printf("armstrong degil");}
  return 0;
}
