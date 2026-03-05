# Linux Automation & Bash Scripting Journey

This repository documents my journey into Linux systems, shell scripting, and automation engineering.

I am currently building strong foundations in:

- Bash scripting
- Loop control (break vs continue)
- File redirection (>, >>)
- Conditional logic (if statements)
- Execution flow reasoning
- Script behavior simulation

---

## Why This Repository Exists

As a self-taught engineer transitioning into systems engineering, I am documenting:

- Concepts learned
- Execution flow analysis
- Practical scripts
- Mini automation projects

This repository will evolve as I progress into:

- Functions in Bash
- Input validation scripts
- Log parsing
- User management automation
- Security-focused scripting

---

## Current Concepts Mastered

### Loop Control in Bash

## break

- Immediately exits the loop.
- Used when no further iterations are needed.

## continue

- Skips the current iteration.
- Allows loop to continue processing remaining elements.

## Execution Order Matters

Placement of break or continue relative to echo statements
changes script output.

Understanding execution flow is critical in automation and security scripting.

- #!/bin/bash

# Demonstration of break vs continue in loop control

for i in 1 2 3 4 5
do
  if [ "$i" -eq 2 ]
  then
    continue
  fi

  if [ "$i" -eq 4 ]
  then
    break
  fi

  echo "Processing number: $i"
done 

### File Redirection

- `>` overwrites files
- `>>` appends to files
- Understanding data flow in automation

- # Loop Control in Bash

## break

- Immediately exits the loop.
- Used when no further iterations are needed.

## continue

- Skips the current iteration.
- Allows loop to continue processing remaining elements.

## Execution Order Matters

Placement of break or continue relative to echo statements
changes script output.

Understanding execution flow is critical in automation and security scripting.

### Security Considerations

- Case sensitivity in authentication systems
- Password entropy preservation
- Importance of controlled script termination

---

## Next Phase

- Writing structured automation scripts
- Building real-world mini projects
- Transitioning toward cybersecurity scripting

---

## Author

Self-taught systems engineer in progress.
Focused on automation, Linux systems, and cybersecurity.
