# GateLib

This is a Python library of (somewhat) general-purpose functions I've made while writing programs. Older versions of this file can be found in several of my other repos, but I'll keep the most up-to-date version here. Every function in this library is written by me unless stated otherwise. Some highlights include the following:

##### makeChoice
A function that asks a multiple choice question.

##### encodeSeed, decodeSeed, and verifySeed
Functions for converting a set of user choices to/from a seed (a generated integer or string).

##### File Path Management
Functions that do things with file paths, such as writing a value to a file at a given address, splitting a file path into an array of its components, or creating a directory, even when its parent directories currently don't exist.

##### Array Management
Functions that do things with arrays, such as counting how many values overlap between two arrays, or checking if one array is an ordered subset of another.

##### Console/Terminal Management
Functions that alter the console output, such as clearing the screen or erasing the most recent lines.

##### String Manipulation
Functions that print strings for specific scenarios, such as formatting a long string to add line breaks after N characters with defined indents, or converting a number of bytes to its most significant form (e.g. "5000000" becomes "4.769 MB")
