# Square-Cube-of-a-number-using-8051
# NAME: DEJASHINI T P
# REG NO:212224060055
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV RO, #50H
MOV A, @Re
MOV B, @RE
MUL AB
INC RØ
MOV @RO,A
END
```

## OUTPUT
<img width="982" height="287" alt="image" src="https://github.com/user-attachments/assets/60e6cdcf-08f2-423b-a81d-3481c9114ab4" />



## RESULT
Thus, the square of the given data is calculated using 8051 Keil.





# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END
```


## OUTPUT
<img width="623" height="445" alt="image" src="https://github.com/user-attachments/assets/2c161ace-587e-4205-b0d6-838009937856" />
<img width="645" height="412" alt="image" src="https://github.com/user-attachments/assets/c0e3f660-38de-4953-a176-6c20a9ec4af0" />



## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


