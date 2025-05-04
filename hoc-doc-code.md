# Hướng dẫn cách học từ việc đọc code

Mỗi khi bạn đi hỏi một câu kiểu: "Làm như thế nào để giỏi lập trình hơn" thì câu trả lời thường sẽ là: "Làm nhiều dự án vào" hoặc "thực hành nhiều vào". Câu trả lời nghe tưởng như hợp lý, nhưng lại rất dễ khiến những người mới học lập trình thất vọng vì:

- Họ thường không biết làm gì (Làm dự án gì để lên trình?)
- Họ bị một ấn tượng là "Cứ ngồi vào viết code vậy là sẽ giỏi" mà không hề biết đến việc cần phải design trước khi code.

### Vòng lặp đọc - viết

Sẽ không bao giờ có chuyện cứ chỉ ngồi viết code là giỏi. Bạn có biết rằng phần lớn thời gian bạn sử dụng trong lập trình không phải là viết code mới mà là đọc code và sửa code không? 

Tại sao lại phải viết x trong khi người khác đã làm trước bạn rồi? 

Lập trình về cơ bản là nhận diện và gây dựng patterns!

[The DEFINITIVE way on how to LeetCode properly. (Hint: You are most likely doing it wrong!)](https://www.reddit.com/r/cscareerquestions/comments/sgktuv/the_definitive_way_on_how_to_leetcode_properly/)

DO NOT attempt to solve any questions on your own (YET!). Yes, you heard me right. I know I sound crazy. But solving ANYTHING on your own is a complete and utter waste of time. Don't even spend 5 minutes on a problem. You do not have the base knowledge yet. You will simply be getting frustrated, and spinning your wheels.

So, what do you do? simple.

Go to grokking the coding interview (no DONT buy it. Waste of money) and look at their list of patterns.

Pick one pattern, and go to leetcode. Search for problems with that pattern.

Go through each problem for the pattern, and go STRAIGHT to the solution. Do not even spend 1 second trying to solve the problem. WASTE OF TIME.

Understand the solution DEEPLY. Make notes. Google things you don't understand. Watch videos on youtube about the solution. Go to the discussion section on leetcode and see what others came up with. Play around with the solution, modify variables, etc. Basically... UNDERSTAND THE SOLUTION AS DEEPLY AS YOU CAN

Move on to the next problem, and repeat.

After you have done this for enough problems, you will feel a lightbulb going off in your head. Congrats, now you know how to solve this pattern!

Go back and pick a new pattern, and do the same thing.

Because you aren't wasting time spending hours on a problem, in just 1-3 weeks, you will have a deep understanding of all the major patterns and common solutions to these patterns. You will be able to recognize how to break down a problem into specific patterns, etc.

Once you have done 300-400 problems like this (it sounds like a lot, but remember.. you are NOT wasting hours per problem trying to solve it.. so you will go through A LOT of problems in a short amount of time.. the key is NOT to memorize, but to UNDERSTAND THE PATTERNS), you can start going through company specific questions on leetcode by buying premium. You will notice you can solve them now on your own!

Congrats, you just saved yourself months and months of headache and frustration.

> You will notice you can solve them now on your own!

There is not a single step anywhere above this line that actually suggests writing code. Implementing solutions.

No matter how well you recognize patterns, you will most certainly not write elegant and correct solutions unless you practice just doing that. At best, you'll have a bunch of off-by-one errors, at worst your code won't even flow correctly at all. This sub is full of people who swear "I understand algorithms, I just can't write them well"... and your advice is only going to create more of those.

I agree at a high level that trying to solve problems on your own can be a waste of time. But after reading the solution to a specific problem, you should revisit that same problem in a few weeks and see if you can then solve it (and ***implement*** that solution with code) on your own.

### Cách đọc hiệu quả
> =======

Programming pro tip: learn to read code. You’ll be doing a lot more reading than writing most of the time.



You get better by practicing reading and interpreting code.

I typically scan over the entire file once or twice though to see what's all involved (class definitions vs function definitions vs top-level code that executes). Then, if the entry point is in the file, I'll often start at the entry point and begin branching out from there. If a class looks central to the module's functionality, I'll look deeper into it. If you see a function used in multiple places, it's worth looking into more. Once you have a gist of what's going on without diving into the details, you can begin selectively looking into specific details as they become relevant.

> ========

practise practise practise

A good habit to get into if you feel overwhelmed is try to treat modules, classes, functions like black boxes. That is, assume they do something but do not get bogged down on the detail of it unless you need to understand exactly what is happening.

While it is important to know what your code is doing, this trick generally helps when trying to read another codebase you are unfamiliar with, as it filters the information you are trying to take in and reduces immediate information overload.

> ========
In addition to the above great advice, you can learn to use a debugger to step through the code. You can "step into" code sections you need to understand immediately and "step over" code sections you don't need their details at the moment.

This is how to quickly understand very large codebases.

If you work in a team, you can ask your team mates for clarification on those sections you've not fully understood.
====

> ======
Just over a year into my first real job, and I agree completely. Everything I've done has been modifying/adapting/adding to old code to do new things. Some if it is stuff from long gone consultants that is known to be a mess too, and as nice as it would be to start over from scratch, there's just not enough time.


> ======
I only started learning what code was ACTUALLY doing until I started messing with github projects that were finished and I could break them, mess with them, modify them and go... oooooh that's why. If I was starting from square one I'd be going straight to github so much faster. My god, all those nights of beating my head against the wall trying to understand certain basic concepts would have been so unnecessary if I'd just seen working code. Working code I can play with and see WHY it works in the first place.

I'm sure everyone learns differently but there's zero substitute for getting your hands on something that just works and copying it, emulating it, using it, modifying it etc. Fuck I wish someone made me do that sooner

### Các mẹo

I've been doing this for a long time, and a new codebase can still be a challenge.

Start with how the project is laid out. How are the modules (drivers, application code, architectural layers, utilities) laid out? If something is called "drivers/bus/i2c.c" I'll typically take the author's word for it that it's the i2c driver. Are they the type of person that keeps their headers and implementions next to each other, or in separate inc/ and src/ directories?

Reading code like a novel is generally not helpful. Some of this is preference.

I have a coworker who goes vertically: he'll start at main and dive into each function call he encounters until he gets to something deep like os, library, or platform code. Then he'll walk back up the call stack and continue on.

It drives me fucking nuts to go over code with him, mainly because it takes way too long, meetings never end on time, and it defeats the entire purpose of abstracting code or into modules. He's very methodical, though, which I can appreciate.

Which leads me to the next point: where are the abstractions in the project? This is probably the most helpful viewpoint for understanding new code. What are the "boxes and lines" in the project's block diagram? Pick a high-level box and skim through it looking for patterns. Repeat. Eventually you'll have a feeling for how all the pieces work together, and then you can start actually understanding how each box does what it does.

That's how I approach understanding large, unfamiliar code bases. Documentation provided by the author can be helpful. Doxygen can generate call graphs, which can be helpful.

But overall, over time and with practice, patterns will start jumping out at you (at all levels, architecturally down to line-by-line) and you'll get better at figuring it out more quickly as you become more familiar with industry, historical, and dumbass practices through sheer exposure.

> =======

Practice static analysis on much simpler codebases first. Here's some thing I commented on a similar question on how to get started practicing static analysis:

Practice.

Different people have different ways of understanding things. I like visualizations, so drawing things worked well for me. I would take a piece of graph paper, and draw out how my variables are represented in memory. For each, I'd label the variable, what type it is, how many bytes it is (certain assumptions about my compiler are made), and what values it contains. If it's a pointer, I would draw an arrow to the memory that it points to. Memory allocated to the stack goes on one side of the page, memory allocated to the heap go to the other side of the page.

From there, I'd simply go expression-by-expression, line-by-line and keep diagramming things out. If a variable goes out of scope, I'd cross it out. If heap-allocated memory gets freed, I'd cross it out. If something gets printed to stdout, I'd write it out somewhere.

You do enough of those, and you get really fast at it, and then you can do larger and larger parts in your head.

Eventually, it's all just pattern-recognition..


https://www.reddit.com/r/learnprogramming/comments/1272d0b/how_to_read_code_on_github/

https://www.reddit.com/r/learnprogramming/comments/olhqev/is_reading_code_a_good_way_to_learn_for_absolute/