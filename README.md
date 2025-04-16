the code attached is the generated assembaly.

In addition to being in the blackboard submission, my observations are here as well:

Observation 1: There are a lot more lines in the assembly, the amount of increase however does not vary much between examples. for example, 36 lines of c++ translates to 134 lines of assembly, whereas 13 lines of c translates to 50 in addmatsSimple, and in submattsSubr 18 lines translates to 89 lines. while it is hard to say if this trend will stay the same as the code becomes larger, there seems to be a 1 to (4-5) ratio in lines of c/c++ to assembly.

Observation 2: based on my limited understanding (so far) of assembly, it seems like one has to almost hard code in different addresses to look at and move. While this works fine for static arrays, i do wonder how this would translate when dealing with dynamic arrays and whatnot? (i have some ideas but would love to see it in action).

Observation 3: Very basic observation that movl seems to be the most used command in assembly for all three simple programs, and I would imagine this trend extends past this to more complex one's as well. I do wonder how many ways there may be to accomplish this task, would it be possible to not use movl?

Observation 4: the process of defining global items in assembly does not always happen at the top, though sometimes it does. I need to learn how the computer knows where to start reading, and double check my assumption that it simply runs through things line by line, jumping when necessary.

Observation 5: at the beginning of each assembly program, it shows the file for the original c or c++ program, and at the end of each program it contains a line for ".ident "GCC: (MinGW.org GCC-6.3.0-1) 6.3.0", under the LFE0 section.

I could add more observations if i continued to study the material and researched the answers to my current questions, however I think this will suffice for now.
