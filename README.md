# Coffee Machine
---
Java Project @JetBrains Academy

A program that simulates the operations of a coffee machine. It offers a variety of drinks at different prices and with varying resource requirements. The program tracks the coffee machine's inventory and allows for restocking supplies and withdrawing funds.

## Prerequisites

This program requires Java to compile and run.

## Installation

- Download this repository and unzip the .zip file in your desired location.
- Using the command line, navigate to /Coffee Machine/.
- Compile the program using the command ```javac -d . CoffeeMachine.java```.
- Run the program using the command ```java machine.CoffeeMachine```.

## Example of use

Predefined initial resources: 400 ml of water, 540 ml of milk, 120 g of coffee beans, 9 disposable cups, $550 in cash.

The symbol > represents the user input. Notice that it's not the part of the input.

```
Write action (buy, fill, take, remaining, exit): 
> remaining

The coffee machine has:
400 of water
540 of milk
120 of coffee beans
9 of disposable cups
$550 of money

Write action (buy, fill, take, remaining, exit): 
> buy

What do you want to buy? 1 - espresso, 2 - latte, 3 - cappuccino, back - to main menu: 
> 2
I have enough resources, making you a coffee!

Write action (buy, fill, take, remaining, exit): 
> remaining

The coffee machine has:
50 of water
465 of milk
100 of coffee beans
8 of disposable cups
$557 of money

Write action (buy, fill, take, remaining, exit): 
> buy

What do you want to buy? 1 - espresso, 2 - latte, 3 - cappuccino, back - to main menu: 
> 2
Sorry, not enough water!

Write action (buy, fill, take, remaining, exit): 
> fill

Write how many ml of water do you want to add: 
> 1000
Write how many ml of milk do you want to add: 
> 0
Write how many grams of coffee beans do you want to add: 
> 0
Write how many disposable cups of coffee do you want to add: 
> 0

Write action (buy, fill, take, remaining, exit): 
> remaining

The coffee machine has:
1050 of water
465 of milk
100 of coffee beans
8 of disposable cups
$557 of money

Write action (buy, fill, take, remaining, exit): 
> buy

What do you want to buy? 1 - espresso, 2 - latte, 3 - cappuccino, back - to main menu: 
> 2
I have enough resources, making you a coffee!

Write action (buy, fill, take, remaining, exit): 
> remaining

The coffee machine has:
700 of water
390 of milk
80 of coffee beans
7 of disposable cups
$564 of money

Write action (buy, fill, take, remaining, exit): 
> take

I gave you $564

Write action (buy, fill, take, remaining, exit): 
> remaining

The coffee machine has:
700 of water
390 of milk
80 of coffee beans
7 of disposable cups
$0 of money

Write action (buy, fill, take, remaining, exit): 
> exit
```
