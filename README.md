# 🧮 Counters: Concurrency in C++

## Overview
This project demonstrates basic concurrency using C++ `std::thread`. It creates two threads:
- One counts **up** from 0 to 20.
- Once completed, the second counts **down** from 20 to 0.

## How It Works
Thread 1 performs an upward count, then signals Thread 2.
Thread 2 waits for the signal using a condition variable and performs the downward count.

## How to Run
1. Clone the repository:
git clone https://github.com/lynndelancey/counters.git

2. Navigate to the folder:
cd counters

3. Compile the code:
g++ -std=c++11 -pthread -o counters main.cpp

4. Run the executable:
./counters


## Sample Output
Count Up: 0 ... Count Down: 20 ...


## Key Concepts
- Threads and synchronization
- Condition variables and mutex locking
- Performance considerations
- Secure use of `std::string` and primitive data types

## Author
Lynn DeLancey
