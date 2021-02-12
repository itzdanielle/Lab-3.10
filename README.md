# Lab-3.10
#include <iostream>
#include <iomanip>
using namespace std;

int main()
{
	int	quantity = 22;		// contains the amount of items purchased 
	double itemPrice = 10.98;	// contains the price of each item
	double totalBill= 241.5600;	
  
	cout << setprecision(2) << fixed;	// formatted output 
	
	cout << "Please input the number of items bought\n";
	cin >> quantity;

	cout << "What was the price?\n"; // Fill in the prompt to ask for the price.
  cin >> itemPrice; // Fill in the input statement to bring in the price of each item.
  totalBill = quantity * itemPrice; 
	cout << "The total bill is $" << totalBill << endl; // Fill in the assignment statement to determine the total bill.
  // Fill in the output statement to print total bill,
	// with a label to the screen.

}
