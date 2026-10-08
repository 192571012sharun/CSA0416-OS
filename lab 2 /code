#include <stdio.h>

int main()
{
    FILE *s, *d;
    char ch;

    s = fopen("source.txt", "w");
    fprintf(s, "Operating System Lab");
    fclose(s);

    s = fopen("source.txt", "r");
    d = fopen("destination.txt", "w");

    while ((ch = fgetc(s)) != EOF)
    fputc(ch, d);

    fclose(s);
    fclose(d);

    printf("File copied successfully");

    return 0;
}

