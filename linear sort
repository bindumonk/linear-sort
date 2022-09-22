#include<stdio.h>
int main(){
    int n;
    printf("Enter the no.of elements\n");
    scanf("%d",&n);
    int a[n];
    int pos;
    printf("Enter the elements to be sorted\n");
    for(int i=0;i<n;i++){
        scanf("%d",&a[i]);
    }
    
    for(int k=0;k<n;k++){
        int min=a[k];
        pos=k;
        int l=k+1;
        while(l<n){
            if (a[l]<min){
                min=a[l];
                pos=l;
            }
            l+=1;
        }
        int temp=a[pos];
        a[pos]=a[k];
        a[k]=temp;
       
    }
    for (int p=0;p<n;p++){
        printf("%d ",a[p]);
    }
}
