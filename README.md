# Variables-and-Comparison-Operators-Tasks

# Task 1
Assign a variable with each datatypes covered in the
previous workshop

The datatypes previous covered were “Boolean”, “String”, “Int”
Notes:

$BoolanVar = $True

![image](https://user-images.githubusercontent.com/91616284/160639377-15ba554d-99dd-4848-8f12-ffdc243d02a5.png)


$StringVar = "This is a string"

![image](https://user-images.githubusercontent.com/91616284/160639502-87e24b8b-92c9-4442-bd3f-2b0c7b6dee3e.png)


$IntVar = 42

![image](https://user-images.githubusercontent.com/91616284/160639614-3e91cf87-1a46-4845-a5a3-7e0a5a734b30.png)


# Task 2
List all variables currently loaded in to memory.
The noun within the cmdlet is “Variable”

Notes:

Get-Variable

![image](https://user-images.githubusercontent.com/91616284/160640668-bcb2550c-84db-4a2a-bcc5-2b8c4ff03e15.png)


# Task 3
Multiple two Int variables together
PowerShell can perform basic maths operators, such as “+”, “-“ and “*”
Notes:

$IntVar1 = 4

![image](https://user-images.githubusercontent.com/91616284/160641581-25ba6adf-8326-4344-9070-134f422fe1c0.png)


$IntVar2 = 10

![image](https://user-images.githubusercontent.com/91616284/160641672-1f368520-3870-4435-9f7e-8987070c566b.png)


$IntVar1 * $IntVar2

![image](https://user-images.githubusercontent.com/91616284/160641731-f6ec4594-c16d-4b5f-91db-21f421bee3b9.png)


# Task 4
First declare two Int variables. Then divided the first
variable by the second and assign the result to a
variable named $VariableResult
The easiest way to do this is within the Integrated Scripting Environment
(ISE) using multiple lines of code
Notes:

$IntVar3 = 10

![image](https://user-images.githubusercontent.com/91616284/160642111-265c2d16-b319-411e-90ef-d6829dcac6fc.png)


$IntVar4 = 2

![image](https://user-images.githubusercontent.com/91616284/160642161-ebf7c355-aa0c-418c-af3d-18fa33ead3ee.png)


$VariableResult = $IntVar3 / $IntVar4

![image](https://user-images.githubusercontent.com/91616284/160642223-fdc0ad6e-b1a3-4305-8049-5ec07dee54eb.png)


# Task 5
Typecast a Variable as a “String” and assign it a value
of 5

Remember to normal brackets [] rather than curly brackets {} when
typecasting a variable
Notes:

[String]$TypecastVar = 5

![image](https://user-images.githubusercontent.com/91616284/160642406-44584e52-f2c7-4d31-b3a8-94a67a62d33d.png)
