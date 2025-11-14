# DC Motor Direction Control Using 8051
## Aim:
To implement a DC Motor Direction Control Using 8051 
## Apparatus Required:
Laptop with Keil uVision software
<br>Proteus Design Suite
## Algorithm:
1. Start the program.
2. Open C program text file.
3. Type the program.
4. Select the hex file creation before building the program.
5.Build/compile the program.
6. Start debugging.
7. Open Proteus Software & design circuit as per circuit diagram.
8. Copy the hex file to 8051 controller.
9.Simulate the circuit in Proteus software.
## Program :
```
mp = 0;
mn = 0;

while (1)
{
    mp = 1;
    mn = 0;
    for (a = 1; a < 40000; a++) {
        ;   // empty delay loop
    }

    mp = 0;
    mn = 1;
    for (a = 1; a < 40000; a++) {
        ;   // empty delay loop
    }
}
}
```
## Output :
<img width="890" height="682" alt="image" src="https://github.com/user-attachments/assets/90e4496a-59ec-48fc-8970-3fb342434cbf" />

## Result:
The DC Motor direction control using 8051 microcontroller has been successfully implemented and simulated using Keil and Proteus.
