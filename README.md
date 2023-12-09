#include <iostream>
#include <cmath>

using namespace std;

int main() {
    // Declare variables
    double radius, area;

    // Get input from the user
    cout << "Enter the radius of the circle: ";
    cin >> radius;

    // Calculate the area
    area = M_PI * pow(radius, 2);

    // Display the result
    cout << "The area of the circle with radius " << radius << " is: " << area << endl;

    return 0;
}
