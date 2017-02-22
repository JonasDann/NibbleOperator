# NibbleOperator
A WIP Logisim 4-bit CPU

Instruction set:

+ mov ax, [addr] - Moves value of ax register to [addr] in RAM
+ mov bx, ax - Moves value of bx register to ax register
+ mov [addr], bx - Moves value in [addr] in RAM to bx register
+ add - Adds value of bx register to value of ax register and stores the result in ax register
+ inc - Increments value of ax register and stores the result in ax register
+ dec - Decrements value of ax register and stores the result in ax register
+ sub - Substracts value of bx register from value of ax register and stores the result in ax register
+ xor - XORs value of ax register with value of bx register and stores the result in ax register
+ or - ORs value of ax register with value of bx register and stores the result in ax register
+ and - ANDs value of ax register with value of bx register and stores the result in ax register
+ shl - Shifts the value of ax register to the left and stores the result in ax register
+ shr - Shifts the value of ax register to the right and stores the result in ax register
+ jez [addr] - Jumps to [addr] if value of ax register equals zero

!Currently none of the instructions are implemented!
