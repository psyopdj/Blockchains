# Assignment 02 - Bitcoin Script

Name    : Tyler Stubbs

Email   : tjs986@utexas.edu

Discord : T-Bone#8992

## Program Inputs

The input of the script should be any integer. The user supplies an integer
and the program returns true if the integer matches the magical number of 24.

```python
<33>
```

or

```python
<24>
```

## Program Script

The script goes through the following operations:

```python
<12>            #add 12 to the stack
<12>            #add 12 to the stack
OP_ADD          #take the top two items on the stack and add their sum to the stack
OP_SHA256       #take the top item on the stack and add its sha256 hash back to the stack
OP_SWAP         #swap the top two items on the stack
OP_SHA256       #take the top item on the stack and add its sha256 hash back to the stack
OP_EQUAL        #check that the two items are equal
```

## Result

The `OP_EQUAL` result should evaluate to true if the user provides <24> as an input, otherwise
it will evaluate to false.

## Resources

**Script Wiz IDE**  
https://ide.scriptwiz.app
