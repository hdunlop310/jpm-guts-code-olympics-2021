# Halloween Bag Generator

The idea for this challenge is that when you are creating goody bags for halloween trick or treaters, it can be hard to work out how many sweets should go in each bag to make it fair, this challenge would aim to solve this problem. It would try to make each bag as equal and fair as it can. There are a number of ways this program could take its inputs:
- Via user input: It would ask the user how many sweets they have and how many bags they want to make. The program would then output each bag's contents for the user.
- Via a file that it reads in
## Example 1

Program: 
```
How many sweets do you have?
```
User: 
```
10 Twixs, 10 Smarties, 40 Gold Coins, 20 Lollipops, 20 Haribos.
```

Program: 
```
How many bags would you like to make?
```
User:
``` 
5.
```

Program: 
```
The following amount of each sweet should go in each bag:
    - 2 Twixs 
    - 2 Smarties 
    - 8 Gold Coins
    - 4 Lollipops
    - 4 Haribos
```

## Example 2

Input file:
```
number of sweets, sweet_type
10,                  Twixs
10,                  Smarties
40,                  Gold Coins
20,                  Lollipops
20,                  Haribos.

number of bags = 5
```

The program would then read this file in and generate the following output:

Program: 
```
The following amount of each sweet should go in each bag:
    - 2 Twixs 
    - 2 Smarties 
    - 8 Gold Coins
    - 4 Lollipops
    - 4 Haribos
```