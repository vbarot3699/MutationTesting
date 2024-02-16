# MutationTesting

This project contains a simple implementation of a triangle validation system using NUnit for testing. The main purpose is to determine whether a set of three angles can form a valid triangle.

## Files

- **TriangleTests.cs:** Contains NUnit test cases to validate the `ValidTriangle` method in the `Triangle` class.

- **Triangle.cs:** Implements the `ValidTriangle` method, which checks if a given set of angles can form a valid triangle.

## How to Use

1. Clone or download the repository to your local machine.

2. Open the solution in your preferred C# IDE.

3. Navigate to the `TriangleTests` class in the `NUnitDemonstration` namespace.

4. Run the tests to check if the `ValidTriangle` method is working as expected.

## Test Cases

The test cases cover various scenarios, including:

- Valid equilateral triangles
- Invalid triangles with angle sum less than 180
- Invalid triangles with angle sum greater than 180
- Invalid triangles with negative angles
- Invalid triangles with zero or negative value angles
- Valid triangles with obtuse angles
- Invalid triangles with large angle sums
- Valid triangles with equal angles (both two and three equal angles)
- Valid triangles with three different angles

## Note

The `ValidTriangle` method in the `Triangle` class has been intentionally mutated to return opposite messages, causing the test cases to fail. This demonstrates the importance of maintaining correct implementation to ensure accurate triangle validation.

## Contributions

Feel free to contribute to this project by creating new test cases, improving the implementation, or fixing any issues. Submit a pull request with your changes.
