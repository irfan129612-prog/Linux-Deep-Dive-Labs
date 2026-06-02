# Lab 48 - Command Chaining

## Overview

This lab explores command chaining operators used to execute multiple commands efficiently.

## Commands Practiced

```bash
mkdir new_directory && cd new_directory
echo "Hello" && cd non_existent_directory
cd non_existent_directory || echo "Directory does not exist"
echo "Start"; cd non_existent_directory; echo "End"
```

## Key Concepts

- Conditional Execution
- Command Chaining
- Error Handling
- Shell Automation

## Practical Outcome

Successfully chained commands using logical operators.
