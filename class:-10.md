#  “Error Handling & Debugging”

* understanding how the code executes in the interpreter.
* the debug is the problem and the process we do to fix it call debugging.
* the browser has a powerful tool to show where is the error.
* using a console in the browser could make to handle any error. If your browser supports debugging, you can use console.log() to display JavaScript values in the debugger window:
* "Example
***
<!DOCTYPE html>
<html>
<body>


<script>
a = 5;
b = 6;
c = a + b;
console.log(c);
</script>
</body>
</html> 


* DeDebugging is the process of finding errors. It involves a process of deduction.
* There ‘is Developer Tools’ to debug your work.
* If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.

* The console helps narrow down the area in which the error is located, so you can try to find the exact error.

* Html has a new form that is easier to be used JavaScript has 7 different types of errors. each creates its own error object, which can tell you its line number and gives a description of the error.
* If you know that you may get an error, you can handle it gracefully using the try, catch, finally statement. Use them to give your users helpful; feedback.


![Debugging](https://miro.medium.com/max/2100/1*LHpmsxV3f2znpxhuAFuIqA.png)
