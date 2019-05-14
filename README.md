# Python For Datascience

## Key board shortcuts in IPython Shell
#### Navigation shortcuts
| Keystroke 									 	| Action 		    													|
| :---------------------------- | :-----------------------------------  |
|Ctrl-e 	 	| Move cursor to the beginning of the line|
|Ctrl-a 											 	| Move cursor to the end of line          |
|Ctrl-b (or the left arrow key)	| Move cursor back on character						|
|Ctrl-f (or the rignt arrow key)| Move cursor forword on character				|

#### Text Entry  shortcuts 
| Keystroke 									 	| Action 		    													|
| :---------------------------- | :-----------------------------------  |
|Backspace key	 	| Delete previous character in line|
|Ctrl -d | Delete next character|
|Ctrl-k |Cut text from cursor to end of line |
|Ctrl-u | Cut text from beginning of line to cursor|
|Ctrl-y | Yank text that was previously cut |
|Ctrl-t | Transpose previous two characters|


#### History Commands
| Keystroke 									 	| Action 		    													|
| :---------------------------- | :-----------------------------------  |
|Ctrl-p| Access previous commands is history|
|Ctrl-n | Access next command in history|
|Ctrl-r | Reverse search through command history|

#### Miscellaneous Commands
| Keystroke 									 	| Action 		    													|
| :---------------------------- | :-----------------------------------  |
|Ctrl-I| Clear terminal screen|
|Ctrl-c | Interrput current python command|
|Ctrl-d | Exit Ipython session|

#### Partial list of debugging commands
| Command 									 	| Description 		    													|
| :---------------------------- | :-----------------------------------  |
|list| Show the current location in the file|
|h(elp)| Show a list of commands, or find help on an specific command|
|q(uit)| Quit the debugger and the program|
|c(Continue)| Quit the debugger; continue in the program|
|n(ext)| Go to the next step of the program|
|<enter>| Repeat the previous command|
|p(rint)| Print variables|
|s(tep)| Step into a subroutine|
|r(eturn)| Return out of a subroutine|


#### Profiling and Timing Code
Time the execution of a single statement
`%time`

The repeated execution of a single statement for more accuracy
`%timeit`
Run the code with profiler
`%prun`
Run code with line-by-line profiler
`%lprun`
Measure the memory use of a single statment
`%memit`
Run code with the line-by-line memory profiler
`%mprun`


#### Timing Code Snippets: %timeit and %time
`In[1] %timeit sum(range(100))`
`10000 loops, sebt of 3: 1.54 us per loop`
