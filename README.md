# SOFTWARE ENGINEERING DS NOTES 
##Notes from 9/28/22
Software Engineering DS NOTES 9/28/22
- Markdown is text with code marked in, can mark what is code, yet making it separate from the word format 
      ⋅⋅*can make bullet points and insert pictures by certain markdown code 
- Python is a language, no complier, reads text out of file as code directly, interpreter so we can edit it and run it then it prints it out with return values 
- Printer command works! 
- Type 
- Numbers, strings —> Python is more picky about type being wrong than Java 
- 2 categories: 
- —scalar: a value, an integer, float, decimals, scientific notation. Ex. 5 is an integer
- — nonscaler: strings, lists, objects, HAVE INTERNAL STRUCTURE. Ex. 5.0 now is interpreted as a decimal 
- Python more picky, so 5/2 it had to covert it to 5.0/2.0 = 2.5 
- Numbers with decimal are called a "float", all numbers in JS are floats but not in Python 
- JS always a float means never have to do conversions 
- Operators we use in JS are the same 
- infix operators + - / x 
- a + b 
- a // b division but ignore remainder 
- a xx b --> a^b 
- n = 5, no declarations are needed but also means all variables are declared locally and hard to do it globally 
ex: n = 5, 
      def func: 
      n= 5
      THESE TWO Ns ARE DIFFERENT BECAUSE HAVE TO ASSUME ALL IS LOCAL. 
- No triple ===, n == 5 equality test 
- Java has == and ===, == does the same thing === does in JAVA so python only uses == 



 - Variables are implied 
 - Colons indictate code block coming
 ```
 Ex. 
    x = 5, 
    z = 5, 
    if (x == 5): 
      print ("same")
    else: 
      print("not same")
   ```
   Code ends when python gets to the a line thats not indented 
- Same rules when function 
- Don't define variables 
- Use "def" instead of "func" 
- W3Schools --> resource for python and java language help 
- () is where the argument goes 
```
 Ex. 
    def myFunction (): 
      print('This is in a function')
    # comment (comments in Python, instead of "//" in Java) 
    # have to start with # for each comment 
    # 
- Functions have a return key word, theres a return function where it bails out 
```

- Variable Example 
- Mutliple variables to multiple values 
```
  x,y = 4,5 (4 goes to x and 5 goes to y) 
    def myfunc (): 
      return 7,8,9
    a,b,c = myfunc()
 ```
    
- dont know a and b until after function is run, because we haven't given it value yet   
```
EXAMPLE: 
def maxVal(a,b):
    if (a >b):
      return a
    else: 
      return b 
      
 print(maxVal(20,30)) ---> runs the f(a,b) with 20 and 30 then prints 30 after going through the function. Define and then call
 ```
 
 - Have to define function before calling it, print is a built in function
 INSERT PICTURE HERE 
 
 
 
 
 ```
 - In java we write (logical operators in java are "&&" "!!" "!")             in python we write (logical operators are "and" "or" "not")
 if (a > b && c > b)                                                             if (a > b and c > b):
 ```
 
 
 
    
    
    
    
    
    
    
