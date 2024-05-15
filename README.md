This code is designed to generate test cases and corresponding output files for a given problem. It includes functions to create inputs and outputs in various formats such as integers, strings, arrays, and matrices. The test cases are randomly generated based on specified constraints, and the output files are generated by applying the provided `solve` function to the generated inputs.
Currently user will have to modify the solve function on their own in notebook file and then modify every other function as per requirement
# Usage

1. **Installation**: No installation is required. Simply download or clone the code repository to your local machine.

2. **Running the Code**:
   - Make sure you have Python installed on your system.
   - Open a terminal or command prompt.
   - Navigate to the directory containing the code files.
   - Run the main Python script using the command `testCaseGenerator.ipynp`.

3. **Customization**:
   - Modify the `solve` function as per the requirements of your problem.
   - Adjust the constraints and logic in the `createInputs` and `createOutputs` functions to match the problem statement.
   - Specify the input and output directories, question name, and number of test cases as needed in the `main` function.

# Files

- `testCaseGenerator.ipynb`: Main Python script containing functions to generate test cases and outputs.
- `inputs/`: Directory to store input files.
- `outputs/`: Directory to store output files.

# Requirements

- Python 3.x
- Standard Python libraries: `math`, `random`, `os`, `string`

# Contributors

- [Mokshit](https://github.com/Mokshit-123)
