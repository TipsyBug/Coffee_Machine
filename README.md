# Coffee Machine

Java Project @JetBrains Academy

A program that simulates the operations of a coffee machine. It offers a variety of drinks at different prices and with varying resource requirements. The program tracks the coffee machine's inventory and allows for restocking supplies and withdrawing funds.

## Prerequisites

This program requires Java to compile and run.

## Installation

- Download this repository and unzip the .zip file in your desired location.
- Open a terminal, then navigate to the project root.
- Compile the program using the command ```javac "Coffee Machine\task\src\machine\CoffeeMachine.java"```.
- Run the program using the command ```java -cp "Coffee Machine\task\src" machine.CoffeeMachine```.

## Example of use

Predefined initial resources: 400 ml of water, 540 ml of milk, 120 g of coffee beans, 9 disposable cups, $550 in cash.

The symbol > represents the user input. Notice that it's not the part of the input.

```
> java -cp "Coffee Machine\task\src" machine.CoffeeMachine
Write action (buy, fill, take, remaining, exit):
> buy
What do you want to buy? 1 - espresso, 2 - latte, 3 - cappuccino, back - to main menu:
> 2
I have enough resources, making you a coffee!
Write action (buy, fill, take, remaining, exit):
> buy
What do you want to buy? 1 - espresso, 2 - latte, 3 - cappuccino, back - to main menu:
> 1
Sorry, not enough water!
Write action (buy, fill, take, remaining, exit):
> remaining
The coffee machine has:
50 of water
465 of milk
100 of coffee beans
8 of disposable cups
557 of money

Write action (buy, fill, take, remaining, exit):
> fill
Write how many ml of water do you want to add:
> 600
Write how many ml of milk do you want to add:
> 0
Write how many grams of coffee beans do you want to add:
> 400
Write how many disposable cups of coffee do you want to add:
> 22
Write action (buy, fill, take, remaining, exit):
> remaining
The coffee machine has:
650 of water
465 of milk
500 of coffee beans
30 of disposable cups
557 of money

Write action (buy, fill, take, remaining, exit):
> 
```
