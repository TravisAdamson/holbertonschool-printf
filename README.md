# _printf

_printf is a function recreating the standard library function printf

## Why?

The purpose of this project is to learn how and why printf reacts to certain input. 

## Usage

_printf("valuetobeprinted")
_printf will accept the following values to indicate the type of value to be printed:
	d = number including a decimal point
	i = integer (whole number only)
	c = char (Single character)
	s = char * (string value that includes multiple chars)
	% = Triggers the function to look for an above value

# returns 'int'
_printf returns the number of characters that were printed if successful.

# returns '-1'
_printf returns a -1 if it failed for any reason, even if characters have been printed.

# My Repository

This repository contains a man page for the `_printf` function.

[man_3_printf](man_3_printf)

## Authors

Travis Adamson - https://github.com/TravisAdamson
<br />
Evan Markle - https://github.com/EJMarkle
