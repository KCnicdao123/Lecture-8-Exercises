# Lecture-8-Exercises

//Days of the Month

#include <iostream>
using namespace std;

int main() {
	cout << "Enter a month to know its number of days. (1 for Jan, 2 for Feb, etc.) \n";
	int month;
	cin >> month;
	switch (month) {
	case 1:
		cout << "January has 31 days" << endl;
		break;
	case 2:
		cout << "Febuary has 28 days" << endl;
		break;
	case 3:
		cout << "March has 31 days" << endl;
		break;
	case 4: 
		cout << "April has 30 days" << endl;
		break;
	case 5:
		cout << "May has 31 days" << endl;
		break;
	case 6:
		cout << "June has 30 days" << endl;
		break;
	case 7:
		cout << "July has 31 days" << endl;
		break;
	case 8:
		cout << "August has 31 days" << endl;
		break;
	case 9:
		cout << "September has 30 days" << endl;
		break;
	case 10:
		cout << "October has 31 days" << endl;
		break;
	case 11:
		cout << "November has 30 days" << endl;
		break;
	case 12:
		cout << "December has 31 days" << endl;
		break;
	default:
		cout << "Invalid input" << endl;
		break;
	}
}
  
  --------------------------------------------------------------
  
 //Fuel Me Up
  
  #include <iostream>
using namespace std;

int main() {
	cout << "Welcome. What type of gas would like to refuel? (P for petrol or D for diesel)" << endl;
	char gas;
	cin >> gas;
	switch (gas) {
	case 'P':
	case 'p':
		cout << "How many litres of Petrol would you want to refill?" << endl;
		int litres;
		cin >> litres;
		if (litres <= 0) {
			cout << "invalid input" << endl;
		}
		else {
			cout << "That would be AED " << litres * 2.60 << endl;
		}
		break;
	case 'D':
	case 'd':
		cout << "How many litres of Diesel would you like to refill?" << endl;
		int litres2;
		cin >> litres2;
		if (litres2 <= 0) {
			cout << "invalid input" << endl;
		}
		else {
			cout << "That would be AED " << litres2 * 2.55 << endl;
		}
		break;
	default:
		cout << "Invalid input" << endl;
		break;

	}
}
----------------------------------------------------
//Switching Temperature
                                   
#include <iostream>
using namespace std;

int main()
{
    cout << "What temperature would you like to conert into? (C for celsius or F for Fahrenheit)\n";
    char temp;
    cin >> temp;
    switch (temp) {
    case 'C':
    case 'c':
    {
        cout << "Please enter a temperature value \n";
        double temp2;
        cin >> temp2;
        cout << temp2 << " degrees Fahrenheit is " << (temp2 - 32) * 5 / 9 << " " << " degrees in Celsius." << endl;
        break;
    }
    case 'F':
    case 'f':
    {
        cout << "Please enter a temperature value \n";
        double temp3;
        cin >> temp3;
        cout << temp3 << " degrees Celsius is " << (temp3 * 9 / 5) + 32 << " " << "degrees in Fahrenheit." << endl;
        break;
    }
    default:
    {
        cout << "Invalid input" << endl;
        break;
    }
    }
}
--------------------------------------------------------
 
 //Switch Grade Calculator
  
  #include <iostream>
using namespace std;

int main()
{
	cout << "Please enter student's full name. (First name, Middle name, Last name format)" << endl;
	string firstname, middlename, lastname;
	cin >> firstname >> middlename >> lastname;
	cout << "Please enter student's grade out of 100." << endl;
	int grade;
	cin >> grade;
	switch (grade) {
	case 0:
	case 1:
	case 2:
	case 3:
	case 4:
	case 5:
	case 6:
	case 7:
	case 8:
	case 9:
	case 10:
	case 11:
	case 12:
	case 13:
	case 14:
	case 15:
	case 16:
	case 17:
	case 18:
	case 19:
	case 20:
	case 21:
	case 22:
	case 23:
	case 24:
	case 25:
	case 26:
	case 27:
	case 28:
	case 29:
	case 30:
	case 31:
	case 32:
	case 33:
	case 34:
	case 35:
	case 36:
	case 37:
	case 38:
	case 39: 
	{
		cout << "The grade of " << firstname << " " << middlename << " " << lastname << " " << "is F" << endl;
		break;
	}case 40:
	case 41:
	case 42:
	case 43:
	case 44:
	case 45:
	case 46:
	case 47:
	case 48:
	case 49:
	{
		cout << "The grade of " << firstname << " " << middlename << " " << lastname << " " << "is E" << endl;
		break;
	}
	case 50:
	case 51:
	case 52:
	case 53:
	case 54:
	case 55:
	case 56:
	case 57:
	case 58:
	case 59:
	{
		cout << "The grade of " << firstname << " " << middlename << " " << lastname << " " << "is D" << endl;
		break;
	}
	case 60:
	case 61:
	case 62:
	case 63:
	case 64:
	case 65:
	case 66:
	case 67:
	case 68:
	case 69:
	{
		cout << "The grade of " << firstname << " " << middlename << " " << lastname  << " " << "is C" << endl;
		break;
	}
	case 70:
	case 71:
	case 72:
	case 73:
	case 74:
	case 75:
	case 76:
	case 77:
	case 78:
	case 79:
	{
		cout << "The grade of " << firstname << " " << middlename << " " << lastname << " " << "is B" << endl;
		break;
	}
	case 80:
	case 81:
	case 82:
	case 83:
	case 84:
	case 85:
	case 86:
	case 87:
	case 88:
	case 89:
	case 90:
	case 91:
	case 92:
	case 93:
	case 94:
	case 95:
	case 96:
	case 97:
	case 98:
	case 99:
	case 100:
	{
		cout << "The grade of " << firstname << " " << middlename << " " << lastname << " " << "is A" << endl;
		break;
	}
	default:
		cout << "Invalid input" << endl;
		break;
	} 
}

------------------------------------------------------
  
//Capital of France
  
#include <iostream> 
using namespace std;

int main()
{
	cout << "What is the capital of France? (Enter the first letter of the city)" << endl;
	char capital;
	cin >> capital;
	switch (capital)
	{
	case 'P':
	case 'p':
	{
		cout << "That is correct!" << endl;
		break;
	}
	default:
	{
		cout << "Sorry, that is incorrect. The capital of France is Paris." << endl;
		break;
	}
	}
}
----------------------------------------------------
//Switch Name that Shape
  
 #include<iostream>
using namespace std;
int main()
{
	int side;
	cout << "Enter the sides number to see the shape name (minimum 3 sides, maximum 10) \n";
	cin >> side;
	switch (side) {
	case 1:
	case 2:
	{
		cout << "You have not entered the minimum amount of sides" << endl;
		break;
	}
	case 3:
	{
		cout << "A triangle has " << side << " " << "sides.\n";
		break;
	}
	case 4:
	{
		cout << "A square/rectangle has " << side << " " << "sides\n";
		break;
	}
	case 5:
	{
		cout << "A pentagon has " << side << " " << "sides.\n";
		break;
	}
	case 6:
	{
		cout << "A hexagon has " << side << " " << "sides.\n";
		break;
	}
	case 7:
	{
		cout << "A heptagon has " << side << " " << "sides.\n";
		break;
	}
	case 8:
	{
		cout << "An octagon has " << side << " " << "sides.\n";
		break;
	}
	case 9:
	{
		cout << "A nonagon has " << side << " " << "sides.\n";
		break;
	}
	case 10:
	{
		cout << "A decagon has " << side << " " << "sides.\n";
		break;
	}
	default:
	{
		cout << "Invalid input.\n";
		break;
	}
	}

	return 0;
}
----------------------------------------------------
 //Continue
  
  #include <iostream>
using namespace std;
int main() {
	cout << "Would you like to continue? (Y/N):" << endl;
	char ans;
	cin >> ans;
	
	switch (ans) {
	case 'Y':
	case 'y':
		cout << "Continuing..." << endl;
		break;
	case 'N':
	case 'n':
		cout << "Game over" << endl;
		break;
	default:
		cout << "Invalid input" << endl;
		break;
	}
}
