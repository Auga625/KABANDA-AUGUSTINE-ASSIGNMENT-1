//Write a c program that calculates the average of marks got by a student in three subjects ie Physics, Chemistry, Math assume for each subject four different tests were conducted; assignment, coursework, mid term, end of term.
#include <stdio.h>

int main() {
    int physics[4], chemistry[4], math[4];
    
    printf("Enter marks for physics (Assignment,Coursework,midterm and end of term)\n");
    int i=0;
    while(i<4){
        scanf ("%d",&physics[i]);
        i++;
    }
        printf("Enter marks for chemistry (Assignment,Coursework,midterm and end of term)\n");
int r=0;
    while(r<4){
        scanf ("%d",&chemistry[r]);
        r++;
    }
        printf("Enter marks for math (Assignment,Coursework,midterm and end of term)\n");
    int t=0;
    while(t<4){
        scanf ("%d",&math[t]);
        t++;
    }
    
 int a= (physics[0]+physics[1]+physics[2]+physics[3])/4;

int b= (chemistry[0]+chemistry[1]+chemistry[2]+chemistry[3])/4;

int c= (math[0]+math[1]+math[2]+math[3])/4;
int d=(a+b+c)/3;
printf("Physics Average:%d\n",a);
printf("chemistry Average:%d\n",b);
printf("Math Average: %d\n",c);
printf("Total Average: %d",d);
    return 0;
}

