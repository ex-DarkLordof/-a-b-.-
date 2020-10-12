#include <iostream>
using namespace std;

int main()
{
	int a;
	int a1;
	int a2;
	int a3;
	int a4;
	cout << "Enter 4-digit num: ";
	cin >> a;
	a1 = a % 10;
	a2 = a % 100 / 10;
	a3 = a / 100 % 10;
	a4 = a / 1000;
	cout << "Result: " << a1 << a2 << a3 << a4;
}
