# 🔢 Push_swap: The Ultimate Sorting Showdown! 🏆

## 🚀 Project Overview

Welcome to **Push_swap**, the coding challenge that turns sorting into an epic algorithm battle! Your mission? Sort a stack of numbers using the most efficient set of moves possible - because who said sorting can't be an extreme sport? 🤖

## 🎲 The Challenge

Imagine two stacks, a handful of magical operations, and one goal: sort those numbers with ninja-like precision and minimal moves!

### 🛠️ Your Sorting Toolbox
Equip yourself with these awesome stack manipulation moves:
- `sa`: Swap the top two elements in stack A (Swap Attack!)
- `sb`: Swap the top two elements in stack B (Swap Blast!)
- `ss`: Double swap madness!
- `pa`: Push from B to A (Promote Action!)
- `pb`: Push from A to B (Plunge Boldly!)
- `ra`: Rotate A upwards (Rotate Advance!)
- `rb`: Rotate B upwards (Rotate Boost!)
- `rr`: Double rotation domination!
- `rra`: Reverse rotate A (Retrograde Maneuver!)
- `rrb`: Reverse rotate B (Retrograde Backup!)
- `rrr`: Reverse rotation revolution!

## 🏋️ Your Mission

Create two programs:
1. **push_swap**: The sorting genius that generates the shortest possible instruction list
2. **checker**: The ultimate validator that checks if your sorting instructions work

### 🎯 Benchmarks of Glory
- Sort 100 random numbers in < 700 moves
- Sort 500 random numbers in < 5,500 moves

## 🚦 Getting Started

```bash
# Compile the magic
make

# Sort some numbers
./push_swap 2 1 3 6 5 8

# Validate your sorting prowess
ARG="4 67 3 87 23"; ./push_swap $ARG | ./checker_OS $ARG
```

## 🤔 Pro Tips
- Complexity is your playground
- Optimize like a coding ninja
- Every move counts!

## 🚨 Error Handling
- No duplicates allowed
- Integers only
- Prepare for epic error messages

## 🏅 Bonus Challenge
Create a custom checker program to validate your sorting algorithm!

## 🧠 Learning Objectives
- Master sorting algorithms
- Understand computational complexity
- Develop algorithmic thinking


---

**Remember:** In the world of Push_swap, sorting isn't just a task - it's an art form! 🎨🔢

Happy Sorting, Code Warriors! 💻🚀