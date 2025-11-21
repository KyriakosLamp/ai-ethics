# Your self-assessment (Part A)
## Write down your honest answers:
    - How have you used AI for coding so far?

        YES, i have used ai in order to solve entire programm from zero to complete ( go-reloaded)
        with 0 code writen by me.On the other hand i have used ai in order to understand the complexity
        of an algorythm in order to code it myself.

    - Do you usually try problems yourself first?

        I always try the problems by myself, even if i get stuck i firstly google it for forums to get anwser,
         ai is usually my last option in order to solve something (depending on the time i have in my hands).

    - Can you explain code you've submitted without AI's help?

        I do not submit code unless i am certain that i understand it so good that i can explain it myself.

    - What would happen if AI was unavailable during an exam or job test?

        Longer completion time of the task, more effort by me in order to solve it, same results.

# Identify your current pattern: Which learner are you now? 

- **Learner A:** uses AI as an *answer generator*.
- **Learner B:** uses AI as a *learning amplifier*.

    The way i use the AI is more like learner A, i seek for an answer. As i said earlier i use AI as my last resort so i 
    have tried learning from other sources and did not succeed in a task. when the AI generate the anwser i will take it
    into consideration understand it and then try to implement it via recreating it ( or copy paste it )

# Write a brief paragraph: Where are you now, and where do you want to be?

    The way i see it one cannot use AI effectivly without having more than basic knowleadge of coding and good programming
    habbits - good practices. I use AI to speed up the proccess and be more effiecient in the given tasks. In order to keep
    doing this though i have to keep learning-exploring each language i touch strengths and weaknesses and keep evolving my
    coding skills, programming mindset, problem solving capabilities and  keep loving programming in general. I believe that
    there is no bad way of learning, via books , peer-to-peer  or AI, learning is learning. In order to be good on what you
    do you have to practice what you learned. In programming area, you have to build stuff-apps so you can test your limits
    and see the progress you achieved. 

# Palindrome solution + reflection (Part B)

    ## STEP 1: write code in Py and explain

```
def testresult(str):
    for i in range(len(str)): 
        if str[i]!=str[-i-1 ]:
            return "String is NOT a palindrom"
    return "String is a palindrom"
    
inputstr = str(input('Enter String to test palindrom: '))
print(testresult(inputstr))

```

    the program above asks for an input string ( inputstr) then passes that variable in the testresult function
    the functions returns a string that says if the input is a palindrom or not.
    in order to check if a string is a palindom we have to check if the word can be written in reverse and still be the same
    so the first char has to be the same with the last char. the second char has to be the same with the second to last char.
    in python first char is 0 and last char is -1 , second char is 1 and second to last is -2 (negative index)
    if the char we are checking is VAR the corresponding char to be checked withing a word is -VAR -1 (NEGATIVE)

## STEP 2 and 3 : ask ai and reflect

    For this example i new the negative index trick in python, but if i didnt know it whould solve the task with O(n^2) complxt.
    AI whould teach me about this neat trick in python and give me a far more efficient and simpler way of solving it.
    Also my code does not take into consideration spaces caps_lower edge cases etc. Its a small demo and i didnt polish it. If i wanted to polish it and make it bulletproof i whould have to consider the testcases myself and make sure i patch unwanted
    states. AI provided all the thought around the unwanted states and edge cases and ways to apply the fix efficiently,
    explaining very clearly and suggesting code fixes.

    **Step 3: Reflection**

- What did you learn by struggling first?
    Did not really struggle to be honest, but AI gave me usefull tips and methods. Those additions whould make the
    program more solid and i will remember them next time i will get to face similar problems.

- How is your understanding different than if you'd just asked for the solution?
    Grinding to find the correct function and having to experiment makes you stronger and helps you build
    the fundemantals. This is how you become better and get to conquer stronger problems.

- Can you now implement similar functions (reverse a string, find duplicates) without AI?
    Generic question, ofc i can, i already did, lets move on.

- What mental model did you build?
    That this piscine quest-thing is not intermediate friendly and to be honest i cannot relate to this.

## Personal Dairness contract (Pard D)
```
**I will use AI when:**

- I have tried solving a problem myself.
- I need to understand *why* something works.
- I want to explore alternative approaches.

**I will NOT use AI when:**

- I haven't tried the problem on my own. 
- I am completing an exam or assessment.
- I am still learning fundamental concepts.
- (unless i have a task with inhuman deadline)

**I know I'm using AI fairly when:**

- I can explain my code without AI's help.
- I could solve a similar problem independently.
- I feel more confident in my own understanding.

Sign and date your contract.
 
#KLAMPRIA - 21/11/2025 22:23 (UTC +2) ATHENS,GREECE 
```

# Scenario analysis (Part E)

```
1. **Interview:** You're asked to explain a caching system design. What happens if you've always relied on AI to design systems?

I whould have basic understanding at best ( if not no-understanding at all) about he topic and a real person whould
easy be able to tell if i am not familiar with the topic. As an interview scenario, i whould propably look bad 
to the interviewer and i whould lose points or even the job.

2. **Production Bug:** At 2 AM, you must debug code generated by AI months ago - but AI is offline. Can you fix it?

If i am not familiar with the code at all it will be imposible to fix it in a tight timetable.
Coordination with coworkers in order to find and fix the bug will be hard due to the time. BUT, if the AI was used
correctly, it would have created documentation so i would be able to read it and find where the bug is. In any case
pushing into production without having expert understanding about the code is a bad idea and this scenario 
is the perfect example why.


3. **New Technology:** A new library is released, and AI hasn't been trained on it yet. How do you learn it?

Documantation, forums, a small prototype project with try and error. If you always rely on AI and havent read or
experienced the try and error way of learning things, it will be terribly hard for one to follow the 
more experienced programmers.


**Reflection:** Write one paragraph explaining how using AI fairly today prepares you for real-world challenges like these.

As mentioned above, those real world scenarios are the reason why one has to use AI fairly. The most catastrophical scenario
(2) production bug, shows that you always have to know and understand the code no matter if its AI created or not, and 
always be ready to fix bugs relying only on documentation even on 2AM. Searching the web for awnsers, even the second and
third page of google search, reading documantation and manuals, try and error method, will always be used when the AI
knowleadge fall behind for any reason. Keeping in touch with traditional methods of learning is mandatory. 
```
# Skills assessment + action plan (Part F)



| **Skill** | **Description** | **Rating** | **Improvement Plan** |
| --- | --- | --- | --- |
| Problem Decomposition | Breaking down problems logically | 4/5 |   keep solving all kinds of puzzle and problems i face |
| Systems Thinking | Understanding how components interact | 2/5 |   read more manuals and do more research about languages i use and architectures |
| Critical Evaluation | Knowing when code is wrong or inefficient | 2/5 | learn about complexity O(logn) etc|
| Debugging Mindset | Investigating unexpected behavior | 4/5 |  propably learn more about ready2use debugging tools and face more difficult and complex problems  |
| Conceptual Understanding | Knowing WHY, not just HOW | 4/5 |  reach my breaking point and git good noob  |

```

- Understading code inefficiency and general complexity of algorythms in order to achieve better run times and 
shorter loops is one of the main things i have to accomplish. 
- Reading the implementations of the main fuctions of the language i use is not curretly in my calendar. I prefer using them
as they are, without wasting time to learn how things work 'under the hood'. I dont mind if i use for example a slower
fuction in a language instead of a faster one, with the same outcome but different syntax. I think i should start working
on this someday, but that day is definattely not tomorrow.
```
