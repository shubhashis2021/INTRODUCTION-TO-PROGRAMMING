# ASSIGNMENT-1
This project is created to submit itp assignment files of team-11

# TEAM MEMBERS
ENROLL.NUMBER AND GITHUB USERNAME

iec2021042-shubhashis2021

iec2021043-Storm2002Coder

iec2021044-RITAM-DAS

iec2021045-aryans08

Group No-"11"

Faculty Name-"Md. Javed Sir"

Mentor Name- "Md. Meraz Sir"

# PROCEDURE
• When the compilation begins at first, the compiler asks for the order of the 2D Array from the user.
▪ Enter size of the array as 3 (from console)
▪ Thus the array, arr[3][3] is now declared i.e. n=3
▪ Now the compiler asks from the console to enter the elements in array and the elements are entered row wise.
1 2 3
0 4 8
0 0 6
▪ Now p is a dummy variable which stores n-1 i.e. 3-1 =2. The variable p has been introduced to avoid the error caused by precedence of operator.
▪ Number = nxp/2 = 3x2/2 = 3 (minimum number of zeros in a triangular matrix)
▪ Further compiler will ask console to input 1 or 2 for checking upper or lower triangularity of matrix respectively using the message - “Enter 1 for checking 
upper Triangularity of the matrix or enter 2 for checking the lower triangularity”.
▪ Suppose 1 is input by the console. Now the compiler will execute case 1 of switch case.
▪ For the value i=0, j will take values upto j=0, j=1 and j=2 and simultaneously arr[0][0], arr [0][1], arr[0][2] will be checked for value 0 for i=j or i>j 
accordingly and thus value of “c” or “f” will be updated for each iteration of the inner loop.
▪ Now if f=1, then the compiler will print “not a triangular matrix” and the compiler will come out of the outer loop else i will be incremented to be 1 and
gradually to 2 and thus the other positions like arr[1][0], arr[1][1], arr[1][2], arr[2][0], arr[2][1], arr[2][2] will be checked similarly and value of “c” and “f” 
will be updated.
Finally it will check that value of c = number and f ≠ 1, if found true, it will print “it is a triangular matrix” else it will print “not a triangular matrix”.

# ALGORITHM
• Take input from the user for the size of double dimension array (n).
• Define an integer array arr[n][n] and take input from console for the elements of the array arr[n][n].
• Calculate the minimum number of zeros that should be present in any triangular matrix of order n by the formula n(n-1)/2 and store 
it in any variable(number).
• Define a switch case with 2 cases for checking the upper and lower triangularity of the matrix.
• For checking the upper triangularity, set conditions to check arr[i][j] ≠ 0, for all i=j and arr[i][j]=0 for all i>j and set a flag variable 
(f=1) and counter (c++) variable respectively.
• For checking the lower triangularity, set conditions to check arr[i][j] ≠ 0, for all i=j and arr[i][j]=0 for all i<j and sets a flag 
variable (f=1) and counter (c++) variable respectively.
• If the value of counter variable (c)= number and f ≠ 1 then the given matrix is triangular else print the matrix is not triangular. 

# TIME COMPLEXITY                                                                                                                    
To our program there can be six completely different 
cases, i.e., there can be 6 different kinds of matrices that 
can be inputted to which may get the same of different 
results. 
• Upper Triangular matrix of order 3x3: Let the 
time taken to execute case 1 be t1. 
We take the matrix
1 2 3 
0 4 5 
0 0 6
To check upper triangularity we input 1. The 
program runs and gives us the result that this is 
an upper triangular matrix. Time taken to execute 
this case comes out to be 0.006138s.
• Lower Triangularity Matrix of order 3x3: Let the 
time taken to execute case 2 be t2.
We take the matrix
5 0 0
4 4 0
5 2 3
To check lower triangularity we input 2. The 
program runs and gives us the result that this is a 
lower triangular matrix.
Time taken to execute this case comes out to be 
0.004718s.
• A Matrix having 0 as its diagonal elements: Let 
the time taken to execute case 3 be t3.
We take a matrix:
0 3 4 
1 0 6
2 7 0
Suppose now we check for upper triangularity by 
inputting 1. The result comes out to be that this is 
not a triangular matrix.
Time taken to execute this case is 0.009538s.
• A 3x3 Non-Triangular Matrix: Let the time taken 
to execute case 4 be t4.
We take a matrix:
1 2 3
4 5 6 
7 8 9
Suppose now we check for lower triangularity by 
inputting 2. The result shows that this is not a 
triangular matrix. 
Time taken to execute case 4 comes out to be 
0.003591s.
• A 3x3 Diagonal Matrix: Let the time taken to 
execute case 5 be t5.
We take a matrix:
1 0 0
0 1 0
0 0 1
We input 1 to check upper triangularity of this 
matrix. The result clearly shows us that this is 
not an upper triangular matrix. The time taken to 
execute this case comes out to be 0.00338s.
• A 3x3 matrix having a single non-zero term in its 
non-diagonal elements: Let the time taken to 
execute this case be t6.
1 2 0 
0 2 0
0 0 3
We input 1 to check upper triangularity of the 
matrix. The result tells us that this is an upper 
triangular matrix.
The time taken to execute case 6 comes out to be 
0.006472s.
To calculate the time complexity, we take sum of 
time (corresponding to each case) and divide it 
by the number of cases.
Hence time complexity = t1+t2+t3+t4+t5+t6
 6
The time complexity hence comes out 
to be 0.0056395 seconds 
                                                                                                                       
# CONCLUSION
▪ Our program helps to determine whether the matrix inputted by the user is an upper or 
lower triangular matrix. Moreover, it is also capable of identifying if the matrix is not a 
triangular matrix.
▪ It is a very user friendly and menu driven program a gives freedom to the user to check 
for upper and lower triangularity.

                                                                                                                       
                                                                                                                       
                                                                                                                       
