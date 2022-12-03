Lab4(Vim)
Part 1

Task:Changing the name of the start parameter and its uses to base.

-A description/screenshot of typing /apple<Enter> and the cursor jumping to the start of apple
```
After I ssh into the server, cd to skill-demo1
Then I typed "vim TestDocSearch" to open the file so I can edit my code with vim now.

-I pressed ESC just to make sure im in the normal mode.
-Since my task is to change "start" into "base" And my first task is to type /apple<Enter> to make the cursor jumping to the start of apple, in this case im changing start into base so i typed /start which jumps me to the start of "start"

```
![Image](https://raw.githubusercontent.com/13G031/cse15l-lab-reports/main/Screenshot%202022-12-02%20193718.png)
  
A description/screenshot of typing ce, switching into input mode and deleting the word apple

```
-After I pressed /start<Enter> Which brings me to the word "start" then I typed "ce" which Delete the word "Start" then switched into insert mode, Then I filled in "base".
```
  ![Image](https://raw.githubusercontent.com/13G031/cse15l-lab-reports/main/Screenshot%202022-12-02%20220239.png)
  
A description/screenshot of typing banana<Esc>, replacing the text and returning to insert mode
```
After I typed "banana" which is base I pressed <ESC> which replace the text then returning back to insert mode.
```
  ![Image](https://raw.githubusercontent.com/13G031/cse15l-lab-reports/main/2.png)
  
A description/screenshot of typing :w<Enter, saving the changes
```
After Im done with editing the texts, I pressed <ESC> just to make sure im in normal mode, then I typed :w<Enter> So I can save the change that I made earlier. 
```
   ![Image](https://raw.githubusercontent.com/13G031/cse15l-lab-reports/main/3.png)

Part 2

1.Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?
```
First style I will clone it and then locally edit my file in VScode and then Scp into ssh server then run it

For Second style will directly log into SSH server clone it, then use Vim to edit my code Then save it. either way will work
```
What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)
```
I think we should use vim, It is easy to access on remote server, a useful tool that we can use for editing code in our project. 
```
