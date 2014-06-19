#Exam Questions <img src="../../Resources/exam.png" width=50px alt="Tick Sheet">

##Instructions
Edit this document and answer the questions in the sections surrounded by ```.

There are 30 marks available and are awarded grades as follows:

|Score|Grade|
|-----|-----|
|<6|U|
|6+|G|
|9+|F|
|12+|E|
|15+|D|
|18+|C|
|21+|B|
|24+|A|
|27+|A*|


##Data Representation

###1 - Why do we represent data using binary when using computers *(1 mark)*

```
because it is easier for the computer to process as there are only two modes; on and off
```
###2 - How would we represent the number 147 in binary? *(1 mark)*
```
10010011
```
###3 - Can you convert the hexadecimal number **b5** to denary, there is a mark for you working. *(2 marks)*
```
181   -   5=5 B=176
```
###4 - Here is a function written is **pseudocode**.
```
FUNCTION validUser (users , user)
    FOR x <-1 to LEN(users)
        IF users[x] = user
			RETURN True
		ENDIF
	ENDFOR
	RETURN False
ENDFUNCTION
```

(a) What type of data is **users**? **(1 mark)**
```
variable
```

(b) What type of data is returned by this function? **(1 mark)**
```
Boolean
```

##Errors
###6 - This program is supposed to find the mean of a list of numbers and print it out for the user:
```
line1:		tot <- 0
line2:		nums <- [1,6,4,2,5,3]
line3:		FOR x <- to LEN(nums)
line4:			tot <- nums[x]
line5:		ENDFOR
line6:		mean <- tot
line7:		OUTPT mean
```

(a) On which line is there a **syntax** error? **(1 mark)**
```
7
```

(b) What is meant by a **syntax** error? **(1 mark)**
```
misuse of a programming function resulting in a program crash
```

(c) Identify a logical error in the program and suggest how this might be fixed. **(2 marks)**
```
answer here
```

(d) Describe and give an example of the 3rd kind of programming error. **(2 marks)**
```
Runtime error
An error that makes the program crash during its runtime.
dividing by zero, referencing missing files, calling invalid functions, or not handling certain input correctly.
```

##Algortithms
###7 - Write an **algorithm** that if given a list of numbers could find the largest. Try to use [pseudocode](http://filestore2.aqa.org.uk/subjects/AQA-GCSE-COMPSCI-W-TRB-PSEU.PDF).
```

A= Current number
B= Next number
C= Largest number


recieve numbers
A=C
If B>C then B=C        #Repeat however many times nessecary
display C


```

##Networking
###8 - Research the following methods (*topologies*) for connecting devices to a network. In each case give a description and at least 1 advantage and 1 disadvantage.

**Bus Topology (6 marks)**
```
Describe: Uses a central 'bus' cable with other smaller outgoing wires to send data to each client.

Advantages: Good for Local area networking as the method is very linear

Disadvantages: There is a high limit on cable length and the number of clients that can be involved
```

**Ring Topology (6 marks)**
```
Describe: Sends data between each client system originating from the server in a circular layout

Advantages: Requires a less powerful server as data is being sent to only the first client system

Disadvantages: Not robust; if a client system breaks the ones after it do the same due to the ring layout
```

**Star Topology (6 marks)**
```
Describe: Sends data to clients from the server directly in individual pathways

Advantages: Minimal reliance on the client; if one system malfunctions it wont result in others doing so

Disadvantages: Requires a more powerful server to handle each client system being sent data
```
