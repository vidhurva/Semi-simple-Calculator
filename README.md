# Semi-simple-Calculator
A C++ Program that challenges users to answer an Addition, Subtraction, Multiplication or Division Question

#include <iostream>
#include <cmath>
using namespace std;
  
int main()
{
  
// variables and assignments 
  
   int choice, num1, num2;
   double num3, num4;
  
   choice = ('1', '2', '3', '4', '5');
  
  // initialization
  
          cout << " Welcome to the Math Tutor Program " << endl;
          cout << " Main Menu " << endl;
          cout << " Press a Number on Your Keyboard that Corresponds to the Operation (Or Press 5 to exit) " << endl    ;
          cout << " 1: Addition " << endl;
          cout << " 2: Subtraction " << endl;
          cout << " 3: Multiplication " << endl;
          cout << " 4: Division " << endl;
          cout << " 5: Exit " << endl << endl;
          cout << " Enter a Choice: ";
          cin >> choice;
  
  // the loops within loops
  
     while(choice !=5)
     {
          if(choice == 1)
          {
          num1 = (rand() % 10)+1;
          num2 = (rand() % 10)+1;
          num3 = num1 + num2;
  
          cout << " What is " << num1 << " + " << num2 << " ? ";
          cin >> num4;
  
                  if(num4 == num3)
          {
                  cout << " Correct " << endl;
 }
  
                  else if(num4 != num3)
          {
                  cout << " Your answer is incorrect. The correct answer is : " << num3 << endl;
          }
  
          }
  
          if(choice == 2)
          {
          num1 = (rand() % 10)+1;
          num2 = (rand() % 10)+1;
          num3 = num1 - num2;
  
          cout << " What is " << num1 << " - " << num2 << " ? ";
          cin >> num4;
  
                  if(num4 == num3)
          {
                  cout << " Correct " << endl;
          }
                  else if(num4 != num3)
          {
                  cout << " Your answer is incorrect. The correct answer is : " << num3 << endl;
          }
          }
  
          if(choice == 3)
          {
          num1 = (rand() % 10)+1;
          num2 = (rand() % 10)+1;
          num3 = num1 * num2;
  
          cout << " What is " << num1 << " * " << num2 << " ? ";
          cin >> num4;
  
                  if(num4 == num3)
          {
                  cout << " Correct " << endl
          }
                  else if(num4 != num3)
          {
                  cout << " Your answer is incorrect. The correct answer is : " << num3 << endl;
          }
          }
  
          if(choice == 4)
         {
          num1 = (rand() % 10)+1;
          num2 = (rand() % 10)+1;
          num3 = num1 / num2;
 
         cout << " What is " << num1 << " / " << num2 << " ? ";
         cin >> num4;
 
                 if(num4 == num3)
         {
                 cout << " Correct " << endl;
         }
                 else if(num4 != num3)
         {
                 cout << " Your answer is incorrect. The correct answer is : " << num3 << endl;
         }
         }
 
 // initialization repeats until user presses 5
 
         cout << " Main Menu " << endl;
         cout << " Press a Number on Your Keyboard that Corresponds to the Operation (Or Press 5 to exit) " << endl    ;
         cout << " 1: Addition " << endl;
         cout << " 2: Subtraction " << endl;
         cout << " 3: Multiplication " << endl;
         cout << " 4: Division " << endl;
         cout << " 5: Exit " << endl << endl;
         cout << " Enter a Choice: ";
         cin >> choice;
 
 
 
         if(choice == 5)
         {
         cout << " Have a nice day! " << endl;
         break;
         }
    }
         return 0;
 }
