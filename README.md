# Flloatwer

Hi, im flloatwer. One of my other nicknames is also JulSM.

## CPU Overview


### Key Features

- **Instruction Set**: Includes basic operations like `copy`, `jmp`, `cmp`, `add`, `sub`, `jsub`, `ret`, and specialized I/O instructions.
- **Memory Model**: Utilizes a 16-bit address space with dedicated areas for TTY output, keyboard input, and general-purpose registers.
- **I/O Handling**: Supports basic input and output operations, allowing interaction with peripherals such as a TTY (terminal) and keyboard.
- **Programming Interface**: Provides a straightforward assembly-like language for programming and simulating CPU operations.

### Example Assembly Code

Here's a sample of assembly-like code:

```plaintext
0x0000 copy 0x0001 0x0002 ; Copy value from address 0x0001 to 0x0002
0x0003 jmp 0x0010         ; Jump to address 0x0010
0x0006 cmp 0x0004 0x0005  ; Compare values at addresses 0x0004 and 0x0005
0x0009 add 0x0007 0x0008  ; Add values from addresses 0x0007 and 0x0008
0x000C sub 0x000A 0x000B  ; Subtract value at address 0x000B from address 0x000A
0x000F jsub 0x0015        ; Jump to subroutine at address 0x0015
0x0012 ret                ; Return from subroutine
0x0015 tty 0xFFFF         ; Print value at address 0xFFFF to TTY
0x0018 keyboard            ; Read keyboard input and store in address 0xFFFE

### Datasheet in repo (datasheet.odt)

### What i want:
I would be extremly happy, if somebody makes this CPU in **logisim-evolution**, as an .circ file.