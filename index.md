## Debugging 

# Part 1: EdStem Conversation.

# Student question: 
![Image](Screenshot 2023-06-05 at 1.07.40 PM.png)
![Image](Screenshot 2023-06-05 at 1.08.05 PM.png)

# 1: TA Response and thread: 
* TA:
![Image](Screenshot 2023-06-05 at 1.18.42 PM.png)

* Student:
![Image](Screenshot 2023-06-05 at 1.24.47 PM.png)

* TA:
![Image](Screenshot 2023-06-05 at 1.28.30 PM.png)

# 2: Fixed bug:
![Image](Screenshot 2023-06-05 at 1.37.59 PM.png)
Here we can see that the big was fixed and it was the CPATH in the file grade.sh, without the right CPATH, it wasn't finding the wrong implementation of the tests and going straight to the first echo string. After fixing the bug, we can see that the JUnit tests ran correctly and now show 2/4 passed.

# 3: Information:
* What was needed was referring to the JUnit library correctly with the right bash command from grade.sh.
* This is what grade.sh looked like before fixing it.
* ![Image](Screenshot 2023-06-05 at 1.35.40 PM.png)
* I ran the bugged code with `bash grade.sh https://github.com/ucsd-cse15l-f22/list-methods-lab3`
* The only thing to edit was the CPATH, which was not correctly referring to JUnit. Adding `lib/` to the command fixes the bug.


---

# Part 2: Reflexion.
During the second half of the quarter I feel like I learned a lot of things that I didn't know about terminals and bash. Before this class I had only learned about Python and Java and the terminal was simply used to run methods. But it made me look realize how uselful it can be, I personally really like how we can edit through the terminal and I really liked vim too.

I think my favorite topic was vim, it was simple but very useful and I'm sure I'll be using it more in the future.
