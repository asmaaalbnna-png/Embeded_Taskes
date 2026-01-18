#include <stdio.h>

int main()
{
int Arr[5],sum =0;
for(int n=0;n<5;n++){
printf("please,Enter element");
scanf("%d",&Arr[n]);
//sum+=Arr[n];
}
//printf("%d",sum);

for(int i=0;i<5;i++){
    for(int j=0;j<4;j++){
        if(Arr[j]>Arr[j+1]){
            int temp = Arr[j];
            Arr[j]   = Arr[j+1];
            Arr[j+1] = temp;
        }
    }
}
printf("%d",Arr[4]);
}
