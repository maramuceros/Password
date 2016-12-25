#include <stdio.h>
#include <stdlib.h>
#include <ctype.h>
#include <string.h>
#include <math.h>

int main()
{
    int password;

    printf("Enter your password \n");
    scanf(" %s", &password);


    if(isupper(password)){
        if(isdigit(password)){}

        if(isalpha(password)){}

        printf("Awesome password");

    }else{
        printf("Not a good password");
    }


    return 0;
}


