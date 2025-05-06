# 5-integer-numbers
#include <iostream>
using namespace std ;

int main () {
	int num1, num2, num3, num4, num5;
	int sum;
	double average;
	
	cout << "Enter 5 integer numbers: " ;
	
	cout << "Number 1: " ;
	cin >> num1;
	
	cout << "Number 2: " ;
	cin >> num2;
	
	cout << "Number 3: " ;
	cin >> num3;
	
	cout << "Nuber 4: " ;
	cin >> num4;
	
	cout << "Number 5: " ;
	cin >> num5; 
	
	sum = num1 + num2 + num3 + num4 + num5 ;
	average = sum / 5 ;
	
	cout << "The average is: " << average<<endl ;
	
	return 0;
}
