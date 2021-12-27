
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
#include <stdlib.h>

    void main()
    { 
     
        int colume = 1, line = 1, rows, space;
        int ro = 0;
        printf("how many rows do you want?\n");
        scanf("%d", &rows);

        while (rows <= 0)
        {
            printf("WRONG WRONG!!");
        }
        printf("ok\n");
        space = rows;
        for (line = 1; line <= rows; line++)
        {
               for (colume = 1; colume <= line; colume++)
               {

                   printf("**");

               }

        printf("\n");

        do
        {
            printf("yes");
            space - 1;
        }
        while (space <= 0);

        }
        system("pause");
    }


