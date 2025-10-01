# C++ Program for Garden Area Calculation

```cpp
#include <iostream>
using namespace std;

int main() {
    // Define dimensions of the garden
    double length = 10.0;  // in meters
    double width = 5.0;    // in meters
    
    // Calculate area using the formula: Area = Length × Width
    double area = length * width;
    
    // Display the result
    cout << "Rectangular Garden Dimensions:" << endl;
    cout << "Length: " << length << " meters" << endl;
    cout << "Width: " << width << " meters" << endl;
    cout << "Area: " << area << " square meters" << endl;
    
    return 0;
}
```
# Enhanced Version with User Input
```cpp
#include <iostream>
using namespace std;

// Function to calculate area
double calculateArea(double l, double w) {
    return l * w;
}

int main() {
    double length, width;
    
    // Get user input
    cout << "Enter the length of the garden (meters): ";
    cin >> length;
    
    cout << "Enter the width of the garden (meters): ";
    cin >> width;
    
    // Calculate area
    double area = calculateArea(length, width);
    
    // Display results
    cout << "\nGarden Area Calculation:" << endl;
    cout << "========================" << endl;
    cout << "Length: " << length << " meters" << endl;
    cout << "Width: " << width << " meters" << endl;
    cout << "Area: " << area << " square meters" << endl;
    
    return 0;
}
```
## How to Run in VSCode

1.    **Create a new file** in VSCode and save it as <code>garden_area.cpp</code>

2.    **Copy and paste** either code version into the file

3.    **Compile and run** using these steps:

        *   Open Terminal in VSCode (Ctrl + `)

        *   Compile: g++ garden_area.cpp -o garden_area

        *   Run: ./garden_area (Linux/Mac) or garden_area.exe (Windows)

## Expected Output

For your specific garden (10m × 5m), the program will display:
```text
Rectangular Garden Dimensions:
Length: 10 meters
Width: 5 meters
Area: 50 square meters
```
The first program uses your fixed dimensions, while the second allows you to calculate areas for different garden sizes. Both implement the area formula Area = Length × Width and provide a complete, runnable solution for your VSCode environment.
