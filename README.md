#include<stdio.h>
int main()
{
    int af,bb,sum,sign=0;
    int n=10000;
    for(;n<100000;n++){
    for(int i=10;i<n;i*=10)
    {
        af=n/i;
        bb=n%i;
        sum+=af*bb;
    }
        if(sum==n)
    {
        printf("%d ",n);
    }
        sum=0;
    }
}
//变种水仙花
//试一试，第一次用，先上传一个看看
