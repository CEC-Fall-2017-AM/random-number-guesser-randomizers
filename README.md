#include <iostream>
#include <time.h>
#include <stdlib.h>
#include <ctime> 
using namespace std;

int main() {

	srand(time(NULL));
	//
	int num = rand() % 100 + 1;
	int input;

	cout << "Input a number from 1 to 100" << endl;
	

	while (true) {
		
		cin >> input;

		if (input == num) {
			cout << "That's the number" << endl;
		}

		

		else if (input <= num) {
				cout << "The number is larger than that" << endl;
				system("pause");
			}

		else if (input >= num) {
				cout << "The number is smaller than that" << endl;
				system("pause");
			}

	}

}
