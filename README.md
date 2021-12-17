# Lecture-15-part-1
#include <iostream>
#include <cmath>
using namespace std;
int main(){
	double x;
	cout << "Enter any number to see its square-root and cube-root: "; cin >> x;
	cout << "\nSquare-root: " << sqrt(x);
	cout << "\nCube-root: " << cbrt(x);

	return 0;
}

**//You say hello, I say goodbye	**
#include <iostream>
using namespace std;
void function() {
	cout << "Welcome to my program" << endl;
}
void function1() {
	cout << "End of program" << endl;
}
int main(){
	function();
	system("pause");
	function1();
	return 0;
}
