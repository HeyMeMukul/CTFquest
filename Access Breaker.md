Open Ghidra ( Function -  FUN_001010c0 )

What the function does 

1. Reads input

2. Requires length = 0x12 (18 chars)

3. Compares each character against a transformed byte array (local_68)

4. Transformation per character:

    (*input[i] ^ bVar3) + cVar4 ^ bVar5 == local_68[i]


    With evolving values:
    
    bVar3 starts at 0x0d, +7 each round
    
    cVar4 starts at -0x11, −3 each round
    
    bVar5 starts at 0x5a, +2 each round

Reverse the equation

To recover each character:

x = ((local_68[i] ^ bVar5) - cVar4) ^ bVar3


Applying this for all 18 bytes gives a clean ASCII string.

Final Flag
SECE{rev4fun_2025}




<img width="1909" height="1043" alt="ghidra" src="https://github.com/user-attachments/assets/eda68192-01ab-4088-95a8-fbc6e33f2bbd" />
