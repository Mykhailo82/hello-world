# hello-world
CS50

#include <cs50.h>
#include <stdio.h>


int main(void)
{
    int n;
    do
    {
    n = get_int("Height: ");
    }
    while (n > 8 || n < 1);

    for (int i = 0; i < n; i++)
    {
        for (int h = 0; h <= i; h++)
            {
            printf("#");
            }
    printf("\n");
        for (int s = n + i; s > i; s--)
    {
        printf(" ");
    }
    }

}
