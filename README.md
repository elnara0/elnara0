#include<math.h>
#include <iostream>
using namespace std;

int main() {
	double num;
	num = (sqrt(12)) * (1 - (1 / (3 * 3.)) + (1 / (5 * (pow(3, 2)))) - (1 / (7. * (pow(3, 3)))) + (1. / (9 * (pow(3, 4)))) - (1 / (11. * (pow(3, 5)))));
	cout << num;
	return 0;
}
