# (Vi) Unimproved

I followed along with this tutorial to create the base editor and added features to add basic vim movements: https://viewsourcecode.org/snaptoken/kilo/01.setup.html

## Features

Vum has three modes: NORMAL, INSERT, and VISUAL

### Normal mode
Allows user to execute special movements and controls. Default mode.

Key bindings:
- H, J, K, L : MOVE CURSOR
- X : DELETE CHARACTER
- I : ENTER INSERT MODE
- W : GO TO START OF NEXT WORD
- E : GO TO END OF NEXT WORD
- B : GO TO PREVIOUS WORD
- O : INSERT NEW LINE AND ENTER INSERT MODE
- _ : HOME
- $ : END
- P : PLOP TEXT THAT HAS BEEN YOINKED
- Ctrl-Q : QUIT
- Ctrl-S : SAVE
- Ctrl-F : FIND

### Insert mode
Allows user to input text.

Key bindings:
- ARROW KEYS : MOVE CURSOR
- ESC : ENTER NORMAL MODE
- BACKSPACE
- DELETE
- HOME
- END
- PAGE UP
- PAGE DOWN

### Visual mode
Allows user to select text by moving the cursor and copy selected text.

Key bindings:
- H, J, K, L : MOVE CURSOR
- W : GO TO START OF NEXT WORD
- E : GO TO END OF NEXT WORD
- B : GO TO PREVIOUS WORD
- _ : HOME
- $ : END
- Y : Yoink selected text
