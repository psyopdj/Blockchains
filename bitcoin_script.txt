// Student: Tyler Stubbs (tjs986)
// This is a test file to demonstrate using bitcoin script. The script takes
// user input from stack and compares the hash output of it to a hard-coded
//number's hash output to check for equivalency

//Stack Elements
//The user should enter a number here
<>

//Witness script
<12>
<12>
OP_ADD
OP_SHA256
OP_SWAP
OP_SHA256
OP_EQUAL
