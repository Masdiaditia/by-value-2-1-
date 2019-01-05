# by-value-2-1-

#include<stdio.h>
#include<conio.h>

int a=4;
void getAGlobal()
{
    printf("A Global adalah %d alamatnya %p\n",a,&a);
}
void fungsi_by_value(int a)
{
    a = a * 3;
    printf("A by value adalah = %d alamatnya adalah %p\n",a,&a);
}
int main()
{
    int a = 5;
    getAGlobal();
    printf("A main adalah = %d alamatnya adalah %p\n",a,&a);
    fungsi_by_value (a);
    printf("A main setelah fungsi dipanggil adalah =%d alamatnya adalah %p\n",a,&a);
    getch();
}
© 2019 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About


hasil![img](https://github.com/Masdiaditia/by-value-2-1-/blob/master/by%20valuie2(1)))).png?raw=true)
