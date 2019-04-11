# Text-Editor
Implemented Using C++ Object Oriented Programming.

We used the cursor position as ‘divider’ and maintained two stacks to hold characters on either side. All characters to the left of cursor are pushed on the ‘left’ stack All characters to its right, are pushed on the ‘right’ stack.

Use 2 stacks to depict the text editor

| Task | Operation |
| --- | --- |
| Insert a character/word  | push it on the left Stack |
| Delete a character using DEL | perform pop operation on the right stack |
| Delete a character using Backspace| perform pop operation on the left stack|
| Move cursor to the left | copy the required characters from left stack to right stack|
| Move cursor to the right | copy the required characters from right stack to left stack|
| To replace |  Use a combination of move cursor with DEL and insert operations|
