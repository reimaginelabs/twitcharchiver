# Twitchlib Coding Standards and Naming Conventions

This document has been generated and discussed with the Twitchlib team as a standard of coding practices to be used in this library.

MS Standards : https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/inside-a-program/coding-conventions

## Layout

Write only one statement per line.
Write only one declaration per line.
Add at least one blank line between method definitions and property definitions.
Single line IF statements use curly brackets in-line.

## Region
Use Regions to tidy up code. (Private Variables, Public Variables, Propteries, etc...)

## Commenting
Begin comment text with an uppercase letter.
Do not create formatted blocks of asterisks around comments.

## Strings
Use string interpolation to concatenate short strings, as shown in the following code.
To append strings in loops, especially when you are working with large amounts of text, use a StringBuilder object.
Implicit Typed Variables
Do not use var when the type is not apparent from the right side of the assignment.
Avoid the use of var in place of dynamic.
Use implicit typing to determine the type of the loop variable in for and foreach loops.

## Linq
Use meaningful names for query variables.
Use implicit typing in the declaration of query variables and range variabl-es.

## Other
Start a private variable name with '_' character.
Use PascalCase for methods and Properties.
Use camelCase for variables.
Use implicit typing for local variables when the type of the variable is obvious from the right side of the assignment,
  or when the precise type is not important. Excluding primitive variables (string,int,etc..)
