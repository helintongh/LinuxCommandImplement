# LinuxCommandImplement
 Implement linux command.
 Author is helintongh.

# Implemet' principle


When we enter an instruction in the shell.

graph LR
	A[INPUT]
	B[shell parsing instruction]
	C[search for environment variables (find the path to your input)]
	D[If find it,execution.else execution false tip.]
	E[execution]

	A->B
	B->C
	C->D
	D->E

# ls