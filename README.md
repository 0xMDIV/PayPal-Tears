# PayPal-Tears (PoC)
A small tool which parses a paypal report file (.csv) and calculates how much money you spent while using paypal.

## My parser works for german reports only! 
Feel free to change this if you want. Make sure that the file is named **Downloads.csv** or rename the file name in the python code. As it is a PoC the filename is currently static.

## Filtering payments
You are able to filter for specific payments, just add/write into **filter.list** line by line the words you want to filter. If you don't want to filter, just leave the file empty.
