# Nested Loops Example in C++

A simple C++ program demonstrating the use of nested loops to display a pattern of output.

## Description

This program utilizes nested loops to print a structured output. The outer loop iterates twice, while the inner loop iterates three times for each iteration of the outer loop. This showcases how nested loops can be used to create more complex output patterns.

### Key Features
- Demonstrates the use of nested loops
- Simple output formatting
- Clear structure for understanding loop behavior

## Code Structure

```cpp
#include <iostream>
using namespace std;

int main() {
    for (int i = 1; i <= 2; ++i) {
        cout << "Outer: " << i << "\n";
        for (int j = 1; j <= 3; ++j) {
            cout << "Inner: " << j << "\n";
        }
    }
}
