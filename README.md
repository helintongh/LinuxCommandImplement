# LinuxCommandImplement
 Implement linux command.
 Author is helintongh.

# Implemet' principle


When we enter an instruction in the shell.
```mermaid
graph LR

	A[INPUT]-->B[shell parsing instruction]
	B-->C[search for environment variables (find the path to your input)]
	C-->D[If find it,execution.else execution false tip.]
	D-->E[execution]
```

# ls