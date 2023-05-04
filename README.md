# Assembly-ARQ1

05.
Write a complete assembly language program to implement the following C
program:

#include <stdio.h>
int main(){
  int number;
  printf(" \n%s","Enter an integer: ");
  scanf("%d",&number);
  number=7-number*3;
  printf(" \n%s%d\n\n","The integer is: ",number);
  return 0;
}

06.
Given Ohm’s law from the complete program at the end of this chapter and
Watt’s law as W = IE, where W stands for the number of watts, write a complete
assembly language program to prompt for and input the number amperes and
ohms, and then calculate both the number of volts and number of watts. The
form of the input and output can be found below, and as always be careful with
the vertical and horizontal spacings:

Input and Output
Enter the number of amperes: 5
Enter the number of ohms: 4
The number of volts is: 20
The number of watts is: 100

07.
Write a complete assembly language program to prompt for and input the
temperature in degrees Fahrenheit, calculate the degrees in Celsius, and then
output the degrees in Celsius. The equation to be used is C = (F −32)/9 * 5,
where C stands for Celsius and F stands for Fahrenheit. Note that the answer
will be off slightly due to using integers and be very careful to use the proper
order of operations. The form of the input and output can be found below. Be
sure to use proper vertical and horizontal spacings:

Input and Output
Enter the degrees in Fahrenheit: 100
The degrees in Celsius is: 35
