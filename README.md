# crack interviews of Google, Facebook, Amazon.

Here I’ll try to focus on how I prepared and what worked for me. You might want to try the same if you are targeting any FAANG or a similar company.

There are three main skill sets that all of these companies test the candidates on:

PS/ DS/ Algo:

Coding — Speed + correctness + code quality
System Design
For each of these skill sets, I’ll try to cover the below three aspects that would be important for your interviews:

What is the expectation?
How to prepare?
How to test if your preparation is good enough?

## PS/ DS/ Algo Interview:

Normally you’ll have at least 1–2 rounds focussed on Data Structures related problems and coding them. You really need to ace these rounds to score an offer.

# What is the expectation:

You should be able to solve the problem given to you as efficiently as possible.
You should use the Data Structure that is most optimal for solving the given problem.
You should be able to code it up and the code needs to work, in one attempt if possible.
All of this under 40 minutes. The lesser the better.

## How to prepare:

Know about the process
# Time: Get to know the interview process from your recruiter. Ask them things like how many rounds are there, how long is each round, how many questions are usually asked in a round, etc. This would give you a hint about how much time you have to solve a problem and code it up.
Let’s say a company normally asks 2 simple DS questions in an hour long interview, that leaves you with almost 25 minutes per problem, with some buffer.
# Difficulty: Now try to look at some problems that this company has asked recently and try to gauge the difficulty level. Don’t look at articles that are more than 3 months old. Companies change their process and hiring bars often and normally they don’t repeat the questions very frequently.
Know most of the important Data Structures
You should be comfortable with at least Arrays, Stacks, Queues, Heaps, Maps, Trees (Binary at least), and Graphs. Don’t spend too much time on complex Data structures as most companies do not expect you to know everything but they expect you to know the basics well.
- If you are books person, unlike me, one of the best books out there is Introduction to Algorithms — By Thomas Cormen.
- If you are not a books person, like me, there are a bunch of websites that have a lot of articles and videos that you could refer.

# How to test if your preparation is good enough:

Leetcode is one platform that can give you a good insight into your preparation level. Try to achieve the below targets for at least 80% of the problems that you attempt:
For Medium level problems, try to solve them within 20 minutes and in two attempts.
For Hard level problems, try to solve them within 35 minutes and at max in three attempts.
If you are not achieving both of these for most of the problems, you’ll need a bit more practice. And if you are solving most of the problems in this 20/35 mins time frame, you are very likely to clear any company that you appear for, from the DS/ Algo standpoint.

# System Design Interview:

If you are applying for a Senior Engineer/ Lead/ Architect/ or a more senior role, this is without doubt the most important interview in your whole process. If this round goes wrong, nothing else would matter. Make sure you are well prepared for this.

# What is the expectation:
You should be able to design a system that satisfies the requirements given to you and scales well.
Your design should not restrict the addition of new features.
You should be able to compare various alternatives and choose the most optimal one. For example, SQL vs NoSQL, or using TCP vs UDP.
You should know about various topics that are relevant from a system design standpoint. Some of them are covered in this article.

## How to prepare:

There are various sources that you can use for system design interview preparation. I used the below two sources to prepare for my system design interviews.
Practise at work:
While you are in your current job, you can always keep designing various systems when you get a chance and get feedback from your peers. You should also look at the systems that others are designing and try to understand why they took certain decisions and what were the tradeoffs that they considered.
Read about what the Tech Giants are doing:
Many companies have their Tech blogs in which they talk about the biggest challenges that they faced and how they tackled them. This will give you an insight into the state of the art tech stuff. The ones that I would recommend are:
Facebook Engineering: https://engineering.fb.com/
Uber Engineering: https://eng.uber.com/
Netflix Tech Blog: https://netflixtechblog.com/
All this might take some time, easily a couple of years, to get a good amount of first-hand experience of designing scalable systems.

# Here is a shortcut:

To speed up the process, I am sharing the resources that I used, and you could use the same.

# System Design Interview Checklist:

These are the things you must cover as part of your system design. You can have a look at my checklist here.
# Some Examples:
Based on my learning and experience, I have created a few videos on how I would design some of the biggest systems out there. These will give you a good idea about how you can drive the interview.

# How to test if your preparation is good enough:

Go for a mock interview with someone who you think is good in System Design. Could be a friend of yours or a senior at work. If you are not comfortable with this, then there are various companies offering mock interviews with engineers from Google, Facebook etc. Based on their feedback you would clearly know if you are ready for your system design interview.

# Coding Interview:

This usually happens along with PS/ DS/ Algo rounds in most of the companies. Some companies also give you a functional problem statement and you are supposed to come up with a working solution for it. Some very common examples would be a Logging library, Authentication Library, Parking Lot implementation etc. This at times becomes similar to an LLD Interview.

# What is the expectation:

You should be able to write a clean working code that fulfills the given functional requirement.
The code should be modular, bug-free and should not break.
It should be easy to add more features. Let’s say you are building an Authentication Library supporting Username/ Password and OTP based Auth flow as per the requirements then it should be easy enough to add an OAuth based flow or a SAML based flow in this library.
The code should be easy to read. If it is a functional problem statement like the ones mentioned above then it should use the correct design patterns, class structure and properly defined functional interfaces.
It should be testable i.e. each function should do one thing and do it well.
Code reusability should be taken care of. Many people copy code from one place to another and make small changes to it to make it work. That’s a place where you want to look at some modularization.

# How to prepare and test if your preparation is good enough:

If it’s a DS/ Algo based coding round, you can prepare for it while you prepare for your DS/ Algo round. If you are hitting the targets for your DS/ Algo round (20/35 minutes), you are well prepared for it. Usual pitfalls are that people miss out on the edge cases, so make sure you handle those.
If it’s a functional coding interview, then the best way to prepare is to practise some sample problems and get the code reviewed by your peers. You should also try running some static code analysers on your code to check your code quality. Alternatively, you could do an LLD mock interview which should give you a good insight into your code quality.
