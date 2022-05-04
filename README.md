# brief
straceViz is a utility tool, written in python, to visualize strace outputs.
Use this tool to visualize the output of Linux's [strace](https://man7.org/linux/man-pages/man1/strace.1.html) utility tool.

# Requirments
1. Linux OS
2. Python 3

# Installiation
To install this utility tool on a linux system, ensure the requirments above are met, and execute the following command:
```
pip --install straceViz
```

# Usage example
The executable `autotest` was ran using strace as follows:
```
strace -f ./autotest 2>out.strace
# strace -Tfe trace=read,write ./autotest 2>out.strace
```

Then the straceViz tool was ran as follows:
```
python ./straceViz
```

Anf the output in the same folder now includes the following files:
