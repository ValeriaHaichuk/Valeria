#include <stdio.h>

int main()
{
int nomer, a[6];
for (int i = 1; i < 999999; i++)
{
nomer = i;
for (int j = 5; j >= 0; j--)
{
a[j] = nomer % 10;
nomer /= 10;
}
if (a[0] + a[1] + a[2] == a[3] + a[4] + a[5])
printf("%d%d%d%d%d%d\n", a[0], a[1], a[2], a[3], a[4], a[5]);
}
return 0;
}
