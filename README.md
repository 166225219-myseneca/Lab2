# Lab 2 repository

A function that uses command line arguments. This function will print two variables used, the script and then the script AND variables.
```import sys

def print_arguments():
    script_name = sys.argv[0]
    print("Script name:", script_name)

    if len(sys.argv) > 1:
        variables = " ".join(sys.argv[1:])
        print("Script name and variables:", script_name, variables)

# Example usage
print_arguments()```
