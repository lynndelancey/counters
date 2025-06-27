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

