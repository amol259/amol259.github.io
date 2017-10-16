---
layout: post
title:  "How to Approach Interview Questions!"
date:   2017-10-15 20:33:18 -0500
categories: Interviews
---
Hello and welcome to my first post! In this post I will talk about how i approach technical interview questions. This post will inlcude a high level overview, I will follow up with several post highlighting the procedure i use to solve a variety of different problems. So lets dive into it!


Interviews are usually divided into 2 sections behavioral and technical. 

<H1> Behavioral  Questions</H1>

Although most people usually shrug off the behavioral interview, it is still an important part of the interview. The good news is it's the easiest part to prepare for and once you know how to crack it, you can reuse it for all future interviews. So what are interviewers looking for with these questions?

- Metacognition about coding. Do you think about how to code well?

- Ownership/leadership. Do you see your work through to completion? Do you fix things that aren't quite right, even if you don't have to?

- Communication. Would chatting with you about a technical problem be pleasant or painful?


Now that you know what the interviewer is looking for, keep them in mind while you answer questions. To answer questions i recomend using the STAR method. 
S: Situation
T: Task 
A: Approach
R: Result

Look up a few examples of this online and format your answers to be in this manner. This gives a clear progression of the story to be told.
Some examples of common questions are:

- example of an interesting technical problem you solved
- example of an interpersonal conflict you overcame
- example of leadership or ownership
- story about what you should have done differently in a past project

<h1> Technical Questions </h1>


There are 2 different type of questions you may receive. 

1. Coding: The interviewer wants you to simply write code
2. Talking: The interviewer want to go through a high level process. Examples of these are system design questions like build a twitter clone

- Communication is key in interviews. It is better to struggle with a question and communicate than to solve a question right and have poor communication skills. 

- Make it feel like you're on a team. The interviewer wants to know what it feels like to work through a problem with you, so make the interview feel collaborative. Use "we" instead of "I".

In this post I will discuss how to solve the first type of question, be on the lookout for a future post where i discuss how to solve the second type of question.

So what do you do when you're given a technical question to solve. For this post we will use a simple question as an example and i will walk through the steps i go through to solve this.  So lets pretend i was given the following problem:
 <h4> Implement Fibbonacci sequence </h4>

So regardless of how fast you want to start coding because you know the answer the first thing to do is to slow the eff down. You don't win anything for speed and if you answer wrong you look like unqualified. After you take a breather think about what the problem is asking and start thinking outloud. 

So i would start by going " it's been a long time since I've seen a fibbonacci sequence. Is that the one where each value is the sum of the previous 2 values?". By asking this question you verify you are correct, and if you are not you immediately know before you go down a rabbit hole. 



After I get confirmation, I then think of a high level design. The steps i go about are listed below:

1) brainstorm an algorithm. draw out sample inputs and play around with them while talking and thinking out loud.

2) once you have an algorithm that you and your interviewer both feel good about (not before then!) barf out your algorithm in code onto the whiteboard or IDE. focus on getting it all down first, and jot down notes next to the things you wanna go back and double-check later

3) debug your code. look for off-by-one-errors. walk through it with a sample input.

So essentially for this problem our algorithim is that we need to keep track of the previous 2 sums to get the current sum. Some smaple inputs that are important are Fib(0) and Fib(1).

Fib(0)= 0

Fib(1)= 1

Fib(2)= 2

Fib(3)= 3

I can think of 2 ways to solve this problem: 
1. Recusion
2. Iteratively

So how do you communicate all these ideas:
I would say 

"I see 2 possible ways we can solve this problem. The first way is via recursion and is fairly simple however at high inputs the efficency of the code is not as optimal as possible. The more efficent solution would be to solve this as with a iterative approach. This would be much more efficent than recursion at inputs as it has a time complexity of O(n). "


Often time interviewers will want you to do both approaches, but if they're in a time crunch this approach shows interviewers that you understand the problem enough to find the brue force solution but you're also thinking about the efficency of your code. These are the small yet important things interviewers look for.


So from here I would write test cases for the code first. Then i would write psuedocode, and from there convert it to real code. You want to get it all down first and not worry about small errors. Get the main idea and then after its there you can check for errors and efficency. 


So lets review what we learned:
1. Communication is key for both behavioral and technical questions
2. Slow Down, dont rush through the problem
3. Ask questions, make sure you completely understand the problem before you start solving it. This will save you time and help you think of solutions.
4. Brainstorm an algorithm, play with sample inputs
5. After you have an algorithim you and the interviewer agree with, write test cases and then code. 
6. Write psuedocode and then convert. Keep the highlevel idea above small implementation details.
7. Fix small bugs in your code 
8. Relax and realize it's okay to fail

Step 8 is something that isn't talked about enough, sometimes you can practice all you can but still get a question wrong. Even if you get a question wrong you still have a chance of getting a job. Interviewers are looking for how you solve the problem, your thought process, if you test your code, code efficency. All these things factor into their decision. If you don't get the job, realize the practice is worth it. Especially if you are just starting out, the more you interview the better you will be at it.


