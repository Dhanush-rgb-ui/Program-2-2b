#  Module-2 Day-2 SEB
## AIM:
To write a C program to print pattern series:

<img width="87" height="292" alt="image" src="https://github.com/user-attachments/assets/14b38609-9c23-4dbc-9805-379052e698da" />

## Program:
```c
#include <stdio.h>
int main(){
    int n,i,j;
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=i;j++){
            if(j==1 || j==i||i==n){
            printf("*");
        }
        else{
            printf(" ");
        }
        }
        printf("\n");
    }
    return 0;
}
```
## Output:
<img width="277" height="161" alt="image" src="https://github.com/user-attachments/assets/97748775-cfc1-4bdb-8032-0a63d75d4bd8" />
