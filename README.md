# conflicts-
#include <stdio.h>
int main() {

    int firstNumber, secondNumber, thirdNumber, sum;

    printf("Enter three integers to add: ");
    scanf("%d %d %d", &firstNumber, &secondNumber, &thirdNumber);

    // calculating the sum
    sum = firstNumber + secondNumber + thirdNumber;

     // displaying sum
    printf("Sum of three numbers is %d", sum);
    return 0;
}
