# Printf

## Intro
Custom printf function made for alx (https://alx-intranet.hbtn.io/projects/228).

## Description
This function write its output to the stdout (standard output stream). 

## convertion specifiers:
+ %c: Prints a single character.
+ %s: Prints a string of characters.
+ %d: Prints integers.
+ %i: Prints integers.
+ %b: Prints the binary representation of an unsigned decimal.
+ %u: Prints unsigned integers
+ %x: Prints the hexadecial representation of an unsigned decimal in lowercase letters
+ %X:Prints the hexadecial representation of an unsigned decimal in uppercase letters
+ %r: Prints a reversed string
+ %R: Prints the Rot13 interpretation of a string

## Example
```C
#include "holberton.h"
#include <stdio.h>
/**
 * main - Entry point
 *
 * Return: Always 0
 */

int main(void)
{
  _printf("%c\n", "ALX"); //output A
  _printf("%r\n", "hello"); //output olleh
   
  return (0);
}
```
