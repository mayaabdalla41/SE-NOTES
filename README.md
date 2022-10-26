# SOFTWARE ENGINEERING DS NOTES 
## Notes from 9/28/22

- Markdown is text with code marked in, can mark what is code, yet making it separate from the word format 

- can make bullet points and insert pictures by certain markdown code 
- Python is a language, no complier, reads text out of file as code directly, interpreter so we can edit it and run it then it prints it out with return values 
- Printer command works! 

- Numbers, strings —> Python is more picky about type being wrong than Java 
- 2 categories: 
- scalar: a value, an integer, float, decimals, scientific notation.
``` Ex. 5 is an integer
- nonscaler: strings, lists, objects, HAVE INTERNAL STRUCTURE. Ex. 5.0 now is interpreted as a decimal 
- Python more picky, so 5/2 it had to covert it to 5.0/2.0 = 2.5 
```


- Numbers with decimal are called a "float", all numbers in JS are floats but not in Python 
- JS always a float means never have to do conversions 
- Operators we use in JS are the same 
- infix operators + - / x 
- a + b 
- a // b division but ignore remainder 
- a xx b --> a^b 
- n = 5, no declarations are needed but also means all variables are declared locally and hard to do it globally 
```
ex: n = 5, 
      def func: 
      n= 5
      THESE TWO Ns ARE DIFFERENT BECAUSE HAVE TO ASSUME ALL IS LOCAL. 
- No triple ===, n == 5 equality test 
- Java has == and ===, == does the same thing === does in JAVA so python only uses == 
```


 Variables are implied 
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
    
    
Dont know a and b until after function is run, because we haven't given it value yet   
```
EXAMPLE: 
def maxVal(a,b):
    if (a >b):
      return a
    else: 
      return b 
      
 print(maxVal(20,30)) ---> runs the f(a,b) with 20 and 30 then prints 30 after going through the function. Define and then call
 ```  
 ```
 - In java we write (logical operators in java are "&&" "!!" "!")             in python we write (logical operators are "and" "or" "not")
 if (a > b && c > b)                                                             if (a > b and c > b):
 ```
 
 
10/13/22 NOTES 

- py.game is the library we are using 

- 3rd party of py.game on actions from the user it'll run --> pygame_gui is the third party game 
- gui is the graphical user interface (buttons) 

- pygame.init () must be run before pygame 

- background is set by surface elements in pygame (RGB colors)
- surface is how much of the background we want covered 
- fills --> images, colors 
- manager handles everything as easy as possible 
--> create manager element, finds every element we use (280 different gui)
- constantly checking the clock tick
- 1000th of a frame is good 
- To adjust anything on the screen we HAVE to use the blit function 
--> anytime we want to change anything on screen 
- Manager.draw.ui(screen) --> adds everything on the screen 
- Vector 2 math --> how pygame makes stuff move, uses friction, gravity, 
- Vector so everything is 2d
- Basic vector math in both dimensions 
- ENTIRELY based on the top left cornor and guis can be built on top of each other, 
- Everything you create is another layer 
- Three different axes -x (horizontal) y (vertical)

```
Everything is a pygame rectangle 
![]<img width="713" alt="Screen Shot 2022-10-19 at 3 18 06 PM" src="https://user-images.githubusercontent.com/97997997/196783968-b6c2afd1-3d1f-467b-a845-06c1706e1306.png"> 
```

-https://pygame-gui.readthedocs.io/en/v_060/layout_guide.html#horizontal-vertical-positioning
- Pygame is for vector math and moving effects 
- Quick start guide is where to find how to make a button 

- FOR HW TO SUBMIT GO TO COMMITS THEN HIT PULL WHEN DONE


10/26/2022 NOTES 
- pull request is a request of the changes you made to the file you forked 
- branches are all in main 
- merge pull request will apply to upstream pull request 
- review code before to the upstream so then the code is reviewed before going to the original project so then it can edit it and make sure its good before 
- "open" means hey look at my data do you want it, the conversation is currenlty open 
- diff --> shows what has changed, deleting and adding data to the file 
- every change in GIT is an either adds or substracts 
- "files changed" is the net result of all the commits 
- rest of notes in shared doc
