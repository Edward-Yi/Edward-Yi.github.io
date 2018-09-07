---
layout: essay
type: essay
title: Why make it harder for experts?
# All dates must be YYYY-MM-DD format!
date: 2018-09-06
labels:
  - Questions
  - StackOverflow
---

## What do I mean?

To better explain this, you have a challenge with two bowls of food, one is filled with a lot of food and the other does not have much but is extremely spicy. My answer would be to go for the less spicy food because it will not be as painful finishing it than the extremely spicy food. This is where how experts on a field like to think, they want a challenge that will make them think, possibly learning something new, and race to answer a difficult question that has suddenly presented itself. Compare this with asking a vague and short question where these experts would have to ask some questions and pull whatever answers they can out of you.

## Do I have to give them a challenge?

Not really, you may want to take a break from a challenge or do some light workouts by looking over some simple problems. Its like giving help to a new person at the gym before the big heavyweight goes to do his own thing, giving an easy to answer problem before doing their own challenge. Lets be honest you are not going to be lifting 100 pounds if you have never done any heavy lifting in your life. If we take this analogy in mind, it is the same concept, you get stuck trying to do something and you need help to fix a mistake or do it optimally.

## Examples of some smart way and not smart way

```
Q: Yarn: Procedure for redeploying JavaScript dependencies to Production Server (usage of `yarn.lock` file)

I've read the documentation on Yarn, and I know the lock file is supposed to be committed to VC. See this and which explains at a high-level why the lock file is necessary, and this which lists a bunch of commands without much explanation of what they actually do!

I've also read a lot of questions on StackOverflow which asks about whether the lock file should be committed to VC.

However, all the documentation and SO threads seems to overlook the detail that I want to know, which is the following; What is the correct procedure (the correct bunch of commands to run) for:

Updating the yarn.lock file when I need to (i.e. in the development environment where I want to pull the latest minor versions and update the lock file to reflect this)
For keeping my lock file in sync with other developers to ensure that they are developing/testing from the exact same dependency versions, and
For updating/re-synching the node_modules directory on the production server (i.e. to ensure that the production server isn't running on a different/breaking version of dependent packages)
I ask partly because in the past while doing a git pull on the server, I've faced messages telling me that the yarn.lock file has been updated independently of the development/VC process. As far as I'm concerned, this should never be allowed to happen.
```

In this question, this person already goes over where they looked and how they did not or could not find the answer to their problem. They give some detail and background information of their current problem and gives us further detail about what their problem is, in an easy to read and structured way.

The following program increases/decreases the value of A and B until A is equal to X and B is equal to Y. Find the bug:

```
Q: Find the bug in the code

The following program increases/decreases the value of A and B until A is equal to X and B is equal to Y. Find the bug:

public static void MakeTheNumbersMatch(int a, int b, int x, int y)
    {
        while(a!=x && b!=y)
        {
            if(a> x)
            {
                a--;
            }
            else
            {
                a++;
            }
            if(b>y)
            {
                b--;
            }
            else
            {
                b++;
            }
        }
    }
I am having a hard time finding the bug. Can someone help?
```
The person that requested help sounds like he is demanding help when he initially says "find the bug", after his explanation of what the code should do. It also feels like there was no effort to debug the program, looking over the code without going over what it is doing, step by step.
