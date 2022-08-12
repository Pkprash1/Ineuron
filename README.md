1. print: Hello
#include<stdio.h>
int main()
{
    printf("Hello");
    getch();
}
2. print: Hello
       Students
#include<stdio.h>
int main()
{
    printf("Hello\nStudents");
    getch();
}
3. print: "MySirG"
#include<stdio.h>
int main()
{
    printf("\"MySirG\"");
    getch();
}
4. print: Area of circle
#include<stdio.h>
int main()
{
    int R;
    float A;
    printf("Enter R: ");
    scanf("%d",&R);
    A=3.14*R*R;
    printf("Area of circle is %f having the radius %d",A,R);
    getch();
}
5. print: the length of string using printf function
#include<stdio.h>
int main()
{
    int x=printf("pnsgj");
    printf("\n%d",x);
    getch();
}
6. print: "Hello, Amit Kumar"
#include<stdio.h>
int main()
{
    printf("\"Hello, Amit Kumar\"");
    getch();
}
7. Print: %d
#include<stdio.h>
int main()
{
    printf("%%d");
    getch();
}
8. print: \n
#include<stdio.h>
int main()
{
    printf("\\n");
    getch();
}
9. print: \\
#include<stdio.h>
int main()
{
    printf("\\\\");
    getch();
}
10. print: DD/MM/YYYY 
#include<stdio.h>
int main()
{
    int date,month,year;
    printf("enter date, month and year in DD/MM/YYYY formate: ");
    scanf("%d/%d/%d",&date,&month,&year);
    printf("Day-%d, Month-%d, Year-%d",date,month,year);
    getch();
}
11. print: HH:MM
#include<stdio.h>
int main()
{
    int hour,minute;
    printf("enter time in HH:MM formate: ");
    scanf("%d:%d",&hour,&minute);
    printf("%d Hour and %d Minute",hour,minute);
    getch();
}
12. Find Output
int main()
{
    int x=printf("ineuron");
    printf("%d",x);
    return 0;
}
Output=7



