// C Program to add 2 numbers
#include<stdio.h>
int sum (int x, int y) {
    return x+y;
}

int main () {
    int a = 5; int b = 10;
    printf("The sum of %d and %d is %d", a, b, sum(a,b));
    return 0;
}
