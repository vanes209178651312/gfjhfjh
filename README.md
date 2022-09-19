#include <iostream>
using namespace std;
int main() {
	int age;
	cout << "please enter age here:" << endl;
	cin >> age;
	if (age <= 13) {
		cout << "your to young.Go away" << endl;
	}
	else if (age < 18) {
		cout << "please get parent permission." << endl;
	}
	else if (age = 40) {
		cout << "you may play but the game plays in 8-bit mode" << endl;
	}
	else {
		cout << "welcome to the game!" << endl;
	}
}
