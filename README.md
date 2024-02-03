'Author: Lexi Warren
'Date: 3/2/24
'Program description: A grade calculator
'Notes: Used >= to make sure all numbers are covered because in the task 60 doesn't return anything

TextWindow.Write("Enter your grade: ")
percentage = TextWindow.ReadNumber ()

If (percentage >= 80) Then
    TextWindow.WriteLine("Grade A")
ElseIf (percentage >= 70) Then
    TextWindow.WriteLine("Grade B")
ElseIf (percentage >= 60) Then
    TextWindow.WriteLine("Grade C")
Else
    TextWindow.WriteLine("You failed, work harder!")
EndIf
