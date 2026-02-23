# Square-Cube-of-a-number-using-8051
# 8051 Square  Program
# Name: KAAVIYA A
# Reg no: 212224060111

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
<img width="791" height="232" alt="image" src="https://github.com/user-attachments/assets/534df022-8a50-4f83-bd2f-e699253d0763" />



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
<img width="500" height="357" alt="image" src="https://github.com/user-attachments/assets/a4a0469e-1015-4a37-bb93-8e141ea5af9f" />
<img width="645" height="412" alt="image" src="https://github.com/user-attachments/assets/01811d06-2d94-43ea-b4aa-90c7c058e7d0" />



## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


