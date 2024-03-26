# PrimeNumbers

## Overview
This repository contains a C# console application that efficiently calculates and prints all prime numbers up to 10,000. The program is built using .NET 8 LTS, ensuring long-term support and compatibility with modern .NET features.

## Algorithm
The application utilizes a classic algorithm for identifying prime numbers, which are numbers greater than 1 that have no positive divisors other than 1 and themselves.

### IsPrime Method
The `IsPrime` method is the core of the algorithm. It follows these steps:
1. Eliminate all numbers less than 2, as they are not prime.
2. Confirm that 2 is prime, being the only even prime number.
3. Exclude all other even numbers, as they are divisible by 2.
4. For odd numbers greater than 2, check for divisibility by all odd numbers up to the square root of the number in question.

If no divisors are found, the number is prime.

## Methods
- `Main`: Iterates through numbers from 2 to 9,999 and prints each prime number using the `IsPrime` method.
- `IsPrime(int number)`: Determines if a given number is prime.

## Usage
To run the program, ensure you have .NET 8 LTS installed. Clone the repository, navigate to the source directory, and execute the following command:

```shell
dotnet run
The console will display all prime numbers up to 10,000.
```
## Contribution
Contributions to improve ReverseDigits are welcome. Please feel free to fork the repository, make changes, and submit a pull request.

## Authors

Mohammadhassan Tohidi @mht83

