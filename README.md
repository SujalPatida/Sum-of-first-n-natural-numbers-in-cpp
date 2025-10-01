#include <iostream>
using namespace std;

int main() {
    int n, sum = 0;
    cout << "Enter a positive integer: ";
    cin >> n;

    if (n < 1) {
        cout << "Please enter a number greater than 0." << endl;
    } else {
        for (int i = 1; i <= n; i++) {
            sum += i;  // sum = sum + i
        }
        cout << "Sum of first " << n << " natural numbers is: " << sum << endl;
    }

    return 0;
}
