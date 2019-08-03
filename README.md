# ParityCode_FindingErrors
ASSEMBLY LANGUAGE Using Parity Code, Find the errors given by assignment


**HW6– Assembly Language Programming – Due date March 18th **

1.	In digital signal processing, it is important to implement some fast algorithms that make initial processing of a digitized signal stream. 
In this programming assignment, the students have to write a subroutine that is used in digital signal processing to make a preliminary estimation of the noise level in the signal.
The subroutine, which counts the number of 1s in a word, must be based on an algorithm, where the passes through the loop are equal to the number of 1s. For example, if the word is 0010070F(16)  your loop has to run 8 times and the count of 1s has to be 8. 
(Hint: First significant operation in the loop should be to decrement (subtract 1) the given word. What is the next? Read again about logical operations!!!).


2.	Assembly program that implements the decoding algorithm of Hamming 1-bit error correcting code. In the following table, the first line is a word that is encoded in Hamming code (16 information bits, parity even bits P0-P4, Pall).

1	0	0	0	1	1	0	0	0	1	1	0	1	1	0	0	1	1	1	0	1	0
21	20	19	18	17	P4	15	14	13	12	11	10	9	P3	7	6	5	P2	3	P1	P0	Pall

Write a program that follows all steps of decoding:
•	Pall check (Pall calculated = or != Pall received).
•	Calculating of the Correcting Code.
•	Select the case: single error, double error, no errors.
•	In case of single error, correct the wrong bit.

Remark: Please present: 
•	The source code .s (sent by email).
•	Printout of the program.
