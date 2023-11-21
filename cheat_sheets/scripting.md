# Bash Scripting Cheat Sheet

## Table of Contents

- [Shebang](#shebang)
- [Variables](#variables)
- [Input and Output](#input-and-output)
- [Conditional Statements](#conditional-statements)
- [Loops](#loops)
- [Functions](#functions)
- [Command Line Arguments](#command-line-arguments)
- [Error Handling](#error-handling)
- [File Operations](#file-operations)

## Shebang

### Specify Bash Interpreter
```bash
#!/bin/bash
```

## Variables

### Assign Variable
```bash
variable_name="value"
```

### Use Variable
```bash
echo $variable_name
```

### Read User Input
```bash
read -p "Enter value: " user_input
```

## Input and Output

### Redirect Output to File
```bash
command > output.txt
```

### Redirect Output and Errors to File
```bash
command &> output_errors.txt
```

### Read from File
```bash
while read line; do
  echo $line
done < filename.txt
```

## Conditional Statements

### If-Else Statement
```bash
if [ condition ]; then
  # code block for true condition
else
  # code block for false condition
fi
```

### Case Statement
```bash
case $variable in
  pattern1)
    # code block for pattern1
    ;;
  pattern2)
    # code block for pattern2
    ;;
  *)
    # default code block
    ;;
esac
```

## Loops

### For Loop
```bash
for item in list; do
  # code block
done
```

### While Loop
```bash
while [ condition ]; do
  # code block
done
```

## Functions

### Define Function
```bash
function_name() {
  # code block
}
```

### Call Function
```bash
function_name
```

## Command Line Arguments

### Access Command Line Arguments
```bash
$1, $2, ..., $n
```

### Check Number of Arguments
```bash
if [ $# -eq 0 ]; then
  echo "No arguments provided."
fi
```

## Error Handling

### Exit Script with Error Code
```bash
exit 1
```

## File Operations

### Check if File Exists
```bash
if [ -e filename ]; then
  # code block
fi
```

### Check if Directory Exists
```bash
if [ -d directory ]; then
  # code block
fi
```

Feel free to contribute to this cheat sheet by adding more scripting-related commands or improving existing examples. Follow the [Contributing](../CONTRIBUTING.md) guidelines.
