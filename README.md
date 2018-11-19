# Scala-Buffer

## Description
A Scala project that uses the command line to manipulate StringBuilder text using the functions that have been implemented. The StringBuilder splits up the inputted String into an indexed sequence of characters and then this can be interacted with through inputting the function, these include moving the cursor to different indexes, deleting characters within a region or quickly replacing specific characters with another.

## Functions Currently Implemented
al() - Move the cursor left

ar() - Move the cursor right

go() - Move the cursor to a specific index

tl() - Move the cursor to the left-most index

tr() - Move the cursor to the right-most index

dr() - Save the current cursor position as a 'marker'

da() - Set the marker position to 0 and cursor to the end index

es() - Insert the inputted string at the current cursor position

xd() - Copy the contents of selected region from the marker to the cursor position

xp() - Delete the contents that was selected with the xd() function

ee() - Delete the character after the cursor position

ed() - Delete the character before the cursor position

cc() - Invert the case of each character within the selected region (lower/upper case)

sc() - Replace all the characters that are a specific letter, within the selected regio, with a different letter 

dd() - Delete duplicate characters within the selected region

ff() - Locate the next occurrence of a letter after the cursor positon

fb() - Locate the previous occurrence of a letter before the cursor position

## Testing
Testing has been carried out using JUnit 4 (BufferTest.scala) and 100 tests to ensure that each of the functions work with all different types of input to produce the correct expected output.