# balanceSheetMatch
Take in balance sheet items and output the items with calculated results according to the order the user wants them in

To demo this tool, try the following input:

Number of items: 2
Items: Pay dividends.(4800).Borrow from bank.39000
Commands: 21c

Output:
Borrow from bank: 39000
Pay dividends: (4800)
34200

Explanation:
() around a number means that number is to be interpreted as negative
Want second item before the first item, so 21
c means calculate, aka the numbers we've seen since the previous c get added together.
So 39000 + (-4800) = 34200