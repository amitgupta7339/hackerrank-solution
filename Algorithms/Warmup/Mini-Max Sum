#include <math.h>
#include <stdio.h>
#include <string.h>
#include <stdlib.h>
#include <assert.h>
#include <limits.h>
#include <stdbool.h>

int main() {
    long a,min,max,i,sum=0;
    int *arr = malloc(sizeof(int) * 5);
    for(int arr_i = 0; arr_i < 5; arr_i++){
       scanf("%d",&arr[arr_i]);
    }
    for(i=0;i<5;i++)
    {
        sum=sum+arr[i];
    }
    min=sum;
    max=0;
    for(i=0;i<5;i++)
    {
        a=sum-arr[i];
        if(a<min)
        {
            min=a;
        }
        if(a>max)
        {
            max=a;
        }
    }
    printf("%ld %ld",min,max);
    return 0;
}
