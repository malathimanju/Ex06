# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<title>WEB_EX NO_06</title>

<script type="text/javascript">
function sum()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
    alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("U Grade");
}
}
</script>
</head>
<body bgcoloR="skyblue">
<h1 onmouseover="sum()">
VIEW YOUR GRADE</h1> <BR>
  <H2>CLICK ABOVE</H2>

</body>
</html>
```


## OUTPUT
![op1](https://github.com/malathimanju/Ex06/assets/165985843/294776b7-15ba-4fcd-bfb9-be74151ffc87)
![op2](https://github.com/malathimanju/Ex06/assets/165985843/98e6e586-6499-4945-bcb3-418dd047c6a1)
![op3](https://github.com/malathimanju/Ex06/assets/165985843/b003fe1a-4d17-40f3-8a02-8a4a40b33393)
![op4](https://github.com/malathimanju/Ex06/assets/165985843/9ebe3284-ff21-4601-a41a-7ef87b9edafe)
![op5](https://github.com/malathimanju/Ex06/assets/165985843/cff94d73-d44a-4ea7-8ce1-91a43c662460)
![op6](https://github.com/malathimanju/Ex06/assets/165985843/4997322a-98c1-46c4-b991-a1aa63d331aa)







## RESULT
  Student result using JavaScript is created successfully.
