===Points To Ponder====:
Q(1): Why did the cd command get special mention in this assignment? 

	A(1): the cd command gets special mention because cd doens't have an executable file, and it's rather a shell builtin. However, other commands and exec() tend to look for an executable file to run under the name of the command passed in.

Q(2): Can your shell run scripts? Why or why not?

	A(2): No, my shell doesn't run scripts. Because, it can only run specific commands, and their corresponding arguments. So, it only knows how to pass things to execvp(), or call a system call. This shell can't handle regular languages.

Q(3): Does Ctrl-D exit your shell? Why or why not?

 	A(3): Yes Ctrl-D exits the shell because the while loop keeps going until it finds an End of File character.