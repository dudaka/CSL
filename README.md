# CSL

## Setting Up Workspace and Workflow

- Go to the website [crackmes](https://crackmes.one) -> Search -> Choose `mexican` (Author `evilprogrammer`) -> Download
  - Difficulty -> 1. Very Easy
  - Language -> C/C++
  - Platform -> Windows
- `DIE` for the program information
- `x32dbg`

## Debugger Stepping Basics

- Graphical User Interface (GUI) and Command Line Interface (CLI) programs

- Capture The Flag (CTF), i.e. get the secret word/phrase/password/serial number

- How to CTF:
  - Open the program with `DIE` > `Advanced`
    - `Entry point`
    - `Base address` / `ImageBase`
  - Setting Preferences
    - Events > Uncheck `TLS Callbacks`, make sure all cracking project, this one is unchecked.
    - Exceptions > Ignore Range > 0000000 - ffffffff
  - Disassembly view
    - First column graph
    - Second column Memory Addresses
    - Third column OPCODES
    - Fourth column Assembly
    - Fifth column strings/comments

- What is Entry Point
- F9 Run
- F8  Step Over
- calls, conditional jumps, unconditional jumps
- EIP register
- Restart

## Stepping into Calls

- F9: Run
- F8: Step Over
- F7: Step Into a Call
- Ctrl + F9: Execute till Return
- Alt + F9: Run to User Code

## Breakpoints (BPs)

1. Setting/Removing 
  - Double click into a line
2. F9 to run to BP


## Breakpoints on Strings

1. Setting/Removing (BP)
2. F9 to run BP
3. Arguments for calls


To set a BP on a string:
1. Look for the string
- Scrolling, or
- Right click > Search for > Current Module > String References

## Preferences

- [crackmes](https://crackmes.one/)
