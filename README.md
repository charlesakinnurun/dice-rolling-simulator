# 🎲 Dice Rolling Simulator

A simple Python **Dice Rolling Simulator** that uses the `random` module to simulate rolling one or more six-sided dice.

## 📌 Project Description

This beginner-friendly Python project demonstrates how to generate random numbers and use loops to simulate dice rolls.

The program can:

* 🎲 Roll a single die
* 🎲 Roll two dice
* 🎲 Roll a die multiple times
* 🔢 Generate random values between **1 and 6**

## 🛠️ Technologies Used

* **Python 3**
* `random` module

## 💻 Code Examples

### 1. Roll One Die

```python
import random

print("🎲", random.randint(1, 6))
```

The `random.randint(1, 6)` function generates a random integer between **1 and 6**, representing the result of rolling a standard six-sided die.

### 2. Roll Two Dice

```python
import random

a = random.randint(1, 6)
b = random.randint(1, 6)

print("🎲", a, "🎲", b)
```

This generates two independent dice rolls and displays both results.

### 3. Roll a Die Five Times

```python
import random

for i in range(5):
    print("🎲", random.randint(1, 6))
```

The `for` loop repeats the dice roll **5 times**, producing a new random result each time.

## 🧠 What I Learned

This project helped me practice:

* Using Python's `random` module
* Generating random integers with `randint()`
* Storing values in variables
* Using `for` loops
* Understanding repeated random events
* Printing formatted output

## ▶️ How to Run

1. Make sure Python is installed.
2. Clone this repository:

```bash
git clone https://github.com/your-username/dice-rolling-simulator.git
```

3. Navigate into the project:

```bash
cd dice-rolling-simulator
```

4. Run the Python program:

```bash
python dice.py
```

## 📊 Example Output

```text
🎲 4
🎲 1
🎲 6
🎲 3
🎲 5
```

Each execution can produce different results because the dice rolls are randomly generated.

## 🚀 Possible Improvements

Future versions could include:

* Allowing the user to choose the number of dice
* Allowing the user to choose how many times to roll
* Calculating the total of multiple dice
* Keeping track of roll statistics
* Creating a graphical user interface
* Adding different types of dice such as D4, D8, D10, D20, and D100

## 📄 License

This project is open source and available for learning and educational purposes.
