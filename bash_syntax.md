Basic explanation of bash syntax and examples

1) function_definitions
    Syntax: function_definition(){...}
    Description: 
2) local variables
    Syntax: local local_variable
    Description: 
3) Command substitution
    Syntax: $(...)
    Description: 
4) Variable Expansion (Parameter expansion)
    Syntax: ${variable_name}
    Descrtiption: Expands a variavble to its stored value. The curly braces {} explicitly separate the variable name from surrounding text. 
5) Pipe operator
    Syntax: |
6) Empty String test
    Syntax: [ -z "$variable"]
    Description: Returns true if the variable expands to an empty string. Commonly use din conditional statements to check whether a variable is empty or unset. 
7) Redirection of Standard Output to Standard Error
    Syntax: command >&2
    Description: Redirects standard output (stdout) to standard error (stderr), allowing normal output to be treated as error outout
8) Return status
    Syntax: return [n]
    Description: Exists the current function and returns an exit status to the caller. By convention, 0 indicates success, while a nonzero value indicates failure
9)   
