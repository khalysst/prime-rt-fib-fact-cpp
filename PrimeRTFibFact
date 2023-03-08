#include <iostream>
#include <iomanip>
		
using namespace std; 

int main () {
	
	int choice;
	int pc, pn; 
	bool prime = true;
	bool re = true;  
	int size, si, sc; 
	int fi, num; 
	int n1, n2, n3; 
	int i, n;
	long fact; 
	char yn, Y, N;
	
	while (re)
	{
	do 
	{
	system ("cls");
	cout << "********** MENU **********" << endl;
	cout << "[1] PRIME NUMBER" << endl; 
	cout << "[2] RIGHT TRIANGLE" << endl; 
	cout << "[3] FIBONACCI SERIES" << endl;
	cout << "[4] FACTORIAL" << endl; 
	cout << "[5] EXIT" << endl; 
	cout << "**************************" << endl; 
	cout << "ENTER YOUR CHOICE: "; 
	cin >> choice; 
	
	while (choice < 1 || choice > 5)
	{
		cout << "Please enter a valid choice." << endl; 
		cout << "Enter either 1, 2, 3, 4, or 5 ONLY: ";
		cin >> choice; 
	}
	
	switch (choice)
	{
		
		case 1: 
		system ("cls"); 
		
		

			cout << "Enter a number: "; 
			cin >> pn; 
			system ("cls");
	
			if (pn == 0 || pn == 1) 
			{
			prime = false; 
			}
	
			else {
			for (pc = 2; pc <= pn / 2; ++pc) {
			if (pn % pc == 0)
			prime = false; 
			break; 
			}
			}

			if (prime)
			{
			cout << pn << " is a prime number." << endl; 
			}
			else 
			{
	
			cout << pn << " is not a prime number." << endl; 
			}
		
		a:	cout << "Return to the main menu? [Y/N]: "; 
			cin >> yn; 
			
			if (yn == 'Y') {
			continue; 
			}
			else if (yn == 'N') {
			re = false; 
			cout << "Program terminated. Thank you and have a nice day." << endl; 
			}
			else {
			goto a;
			}
			return 0;
		
		break; 
		
		case 2: 
		system ("cls"); 
		
		
			cout << "Enter the size of right triangle: ";
			cin >> size; 
			system ("cls"); 
	
			if (size > 0){
		
			for (int si = 1; si <= size; ++si)
			{
			for (int sc = 1; sc <= si; ++sc)
			{
			cout << sc << " ";
			}
		
			cout << "\n";
			}
			}
		
			else {
	
			cout << "Invalid input.";
			}
			
		b:	cout << "Return to the main menu? [Y/N]: "; 
			cin >> yn; 
			
			if (yn == 'Y') {
			continue; 
			}
			else if (yn == 'N') {
			re = false; 
			cout << "Program terminated. Thank you and have a nice day." << endl; 
			}
			else {
			goto b;
			}
			return 0;
		
		break;
		
		case 3:
		
		system ("cls"); 
		
			n1 = 1; 
			n2 = 1; 
	
			cout << "Enter a number: ";
			cin >> num;
			
			system ("cls"); 
	
			cout << n1 << " " << n2 << " "; 
	
			for (fi = 2; fi < num; ++fi)
			{
			n3 = n1 + n2; 
			cout << n3 << " ";  
			n1 = n2; 
			n2 = n3; 
			}
			
		c:	cout << "   " << endl; 
			cout << "Return to the main menu? [Y/N]: "; 
			cin >> yn; 
			
			if (yn == 'Y' || yn == 'y') {
			continue; 
			}
			else if (yn == 'N' || yn == 'n') {
			re = false; 
			cout << "Program terminated. Thank you and have a nice day." << endl; 
			}
			else {
			goto c;
			}
	
			return 0;
		
		break; 
		
		case 4:
		system ("cls");
		
			fact = 1;
			i = 1;
	
			cout << "Enter a number: ";
			cin >> n;
			
			system ("cls");
	
			cout << "The factorial of ";
			
			while (i <= n)
			{
				cout << i << " ";
				fact = fact * i;
				i++;
				
				if (i <= n) {
				cout << "* "; 
				}
			}
			
			cout << " is " << fact << endl; 
			
		d:	cout << "Return to the main menu? [Y/N]: "; 
			cin >> yn; 
			
			if (yn == 'Y') {
			continue; 
			}
			else if (yn == 'N') {
			re = false; 
			cout << "Program terminated. Thank you and have a nice day." << endl; 
			}
			else {
			goto d;
			}
			
			return 0; 
			
		break; 
		
		case 5: 
		system ("cls");
		cout << "Program terminated. Thank you and have a nice day." << endl;
		
		return 0;
		
		break; 
		
	}
	} while (choice <= 4 && choice >= 1);
	} 
	
		return 0;
	}

	
