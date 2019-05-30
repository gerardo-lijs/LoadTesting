# Load Testing
Simple methods to help you simulate CPU load

Code in CPU.cs

Feel free to use this in your projects/blogs for testing scaling, responsiveness, etc. Expensive prime number method used taken from the book [C# 7.0 in a Nutshell by Joseph and Ben Albahari](http://www.albahari.com/nutshell/)

# Async Usage
Loads all available CPU cores to 100% by running an expensive operation (prime numbers) for the specified number of seconds. In this example 15 seconds.

await LoadTesting.CPU.SimulateExpensiveMethodAsync(15);

# Sync Usage
Loads all available CPU cores to 100% by running an expensive operation (prime numbers) for the specified number of seconds. In this example 15 seconds.

LoadTesting.CPU.SimulateExpensiveMethodAsync(15);
