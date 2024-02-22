# Notes-on-VIM

This repo contains notes on VIM and NEOVIM

# Modes in VIM

There are 4 modes in VIM:

	1. Normal mode - In this mode you can move around the file
	2. Insert mode - In this mode you can insert text into the file
	3. Visual mode - In this mode you can select the text lines in the file
	4. Command mode - In this mode you can give diffenet commands to vim

# Normal Mode in VIM

This is use to traverse around the file.

There are a lot of tricks to traverse the file in an efficient manner

	K - Upward
	J - Downward
	H - Left
	L - Right

	W - It hops over by word
	B - walks backwards by hoping over a word

	Commnad Count Motion

	8K - this will jumps the cursor by 8 lines 
	
# Commnad Mode in VIM

	DD - Delete a line
	U - Undo an action 
	Ctrl + R - Redo an action 

# Adding commnad with a motion 
	
	D2J - Delete 2 lines below from the position
	D2W - Delete 2 words from the position
	
# Insert Mode in VIM
		
	I - is used to enter into insert mode to be able to type stuff
	Ctrl + C - This is used to exit the insert mode
	A - is also used to go into insert mode

	
	Note - Generally insert mode starts on the left hand side of the character
	if you want to move one character ahead you can press 'a'

# Visual Mode in VIM
	
	V - To go into visual mode 
	Y - yanks (copies the selected portion)
	P - pastes the copied snippet

	Shift + V - Visual line mode, this can be used to select the entire line of code

	To paste over something : You need to first select, copy and then select again and then paste

	Note : Yanking and deleting has the same buffer and when you delete something and then paste it, it will paste the last copied line




