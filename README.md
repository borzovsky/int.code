# int.code

#include <iostream>

int main() {
    // Declare variables
    double length, width, area;
    
    // Get input from the user
    std::cout << "Enter the length of the rectangle: ";
    std::cin >> length;
    
    std::cout << "Enter the width of the rectangle: ";
    std::cin >> width;
    
    // Calculate the area
    area = length * width;
    
    // Print the result
    std::cout << "The area of the rectangle is: " << area << std::endl;
    
    return 0;
}
