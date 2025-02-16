#include <stdio.h>
#include <string.h>
#include <stdlib.h>
#include <time.h>

// Let's build a number guessing game 



int main(){

    const int MAX = 100;
    const int MIN = 1;
    int guess ;
    int guesses = 0;
    int answer ;


    // using the current time as a seed 
    srand(time(0));


    // Generate a random number between MIN & MAX 
    answer = (rand() % MAX) + MIN ;

    do{
        printf(" Chose a number between 1 and a 100 :");
        scanf("%d", &guess);

        if (guess > answer ){
            printf("Too hight !\n");
        }
        else if( guess < answer){
            printf("To low !\n");
        }else {
            printf("CORRECT!\n ");
            guesses++;
        }
        
    }while(answer != guess);

 printf("***********************\n");
 printf("answer : %d\n", answer);
 printf("guesses : %d\n", guesses);
 printf("***********************");

 return 0;

}