# Boot Camp

The main point of this is for you to gain a general understanding of things that you will come into contact with on a regular basis. The structure for each task is organised as follows:
1) You do a course, tutorial or watch some videos
2) Practice what you learnt
3) Solve some problems using the knowledge you gained


## Structure

This is experimental and I will add content as you progress. For each topic, you will be expected to learn, understand and find a solution within +-2 days (at my discretion). 


## Topic 1: Git 
Git is the most popular version control system out there. Open source communities publish their code on Github, other git hosted service providers include GitLab and BitBucket, and more. Understanding the basics of git allows you to work in a professional environment where git is used religiously (or should be). 

Always commit regularly, add descriptive log messages and pull before you try to push (especially when collaborating).

### Day 1

#### Course
I have found a course on data camp that will be useful for you to do. 

https://www.datacamp.com/courses/introduction-to-git-for-data-science

You can access chapter 1 for free, however the rest requires an enterprise account. You can use mine, I'll login to my account for you tomorrow.

There are some tutorials and courses that you can find online to supplement the course above. 

Remember, learn as much as you can in day 1 because day two will be problem solving and doing things under time constraints. 

#### Create some accounts

- register an account on gitlab.com (you probably already have one if you are looking at this page)
- register a github account

Time to solve some problems....

#### Baby Steps
- create a bootcamp subfolder in meraka_experimental_dev
- create a sub folder for you
- create a repository for Topic 1:Git
- add a readme file to the repository

If at first you don't succeed, find out what may be the reason for failure before asking for help. This forces you to gather information about the problem so you better understand the relevance of the solution. 

### Day 2

#### Tasks
The tasks set forth for day two will be done in conjunction with the Python coding tasks
You will be required to do the following sequentially:
- create a repository for the python task
- commit a readme file
- protect your master branch
- set your privilege on the repository to developer and mine to maintainer/owner
- create a branch for you to work in
- write your code and commit at regular intervals to show your progress over time
- when you're satisfied with your code, create a merge request for master
- populate the required merge request fields
- submit it to me
- correct the code review corrections
- resubmit
- once your code is merged into master, create a new branch for optimizations
- make your changes for the required optimizations.
- print performance metrics to the console
- commit, create a merge request and submit it
- address code review comments
- get a coffee because you deserve it!


## Topic 2: Python
We predominantly work with Python for most of our tasks. Python supports rapid prototyping with its easy syntax and small learning curve. There are multiple resources and packages available to support some truly complex systems. 

The coding tasks in day 3 will be basic programs, your code will be examined and critiqued on readability, efficiency, maintainability and usability.

### Day 2
Lets start off with something easy so that we can understand your coding skills in terms of readability, efficiency, maintainability and usability.

Before you submit any code, make sure that:
- There must be a way to supply the application with the input data via text file
- The application must run
- You should provide sufficient evidence that your solution is complete by, as a minimum,
indicating that it works correctly against the supplied test data

#### Fibonacci Sequence

How difficult on a scale of 1-10 do you anticipate this task to be?

##### First Attempt

Write python code that will output the nth value in the Fibonacci sequence given an integer n as input.

Once you have a basic piece of code functional, test it on the following values and print the answer and how long it took to compute to the console:
- 1
- 2
- 5
- 10
- 20
- 30
- 50
- 100

Once you're happy, stop making edits and commit your code and submit it for review via a merge request. If it's getting stuck executing, don't worry about that just yet.


**** STOP AND WAIT FOR YOUR CODE REVIEW ****


Now that you have gone through a code review answer the following:
- Did your execution get stuck? Why do you think this is so?
- What happens if you give negative values as input?
- How can you improve performance?
- Can I input text that's not a number? What happens?
- Is there documentation instructing me how to run the code?
- What can you do to make it run for input of n=1000,2000,5000?
- Can it run for n=100000?


##### Second Attempt

Now that you've gotten feedback from your code review and answered the questions set for you, go on and update your code to address the shortfalls and submit again for code review.


##### Outcomes
- Any surprises?
- Did your program work as expected from the first run?
- What did you learn?

#### Merchants Guide to the Galaxy

##### Notes on the task
Since I know that you're gonna power through the Fibonacci sequence in no time, design and implement a solution to the Merchants Guide to the Galaxy.

- Ensure that you can support your design decisions with reasoning
- Take the lessons from the Fibonacci sequence and make sure your code is robust
- Make sure its readable
- Follow the process outlined in the task section of Day 2 Git
 
##### Problem Definition

You decided to give up on earth after the latest financial collapse left 99.99% of the earth's population
with 0.01% of the wealth. Luckily, with the scant sum of money that is left in your account, you are
able to afford to rent a spaceship, leave earth, and fly all over the galaxy to sell common metals and
dirt (which apparently is worth a lot).
Buying and selling over the galaxy requires you to convert numbers and units, and you decided to
write a program to help you.
The numbers used for intergalactic transactions follows similar convention to the roman numerals
and you have painstakingly collected the appropriate translation between them.
Roman numerals are based on seven symbols:

| Roman Numeral | Decimal Value |
| ------ | ------ |
| I | 1 |
| V | 5 | 
| X | 10 |
| L | 50 | 
| C | 100 |
| D | 500 | 
| M | 1000 |

Numbers are formed by combining symbols together and adding the values. For example, MMVI is
1000 + 1000 + 5 + 1 = 2006. Generally, symbols are placed in order of value, starting with the largest
values.

When smaller values precede larger values, the smaller values are subtracted from the larger values,
and the result is added to the total. For example, MCMXLIV = 1000 + (1000 − 100) + (50 − 10) + (5
− 1) = 1944.
• The symbols "I", "X", "C", and "M" can be repeated three times in succession, but no more.
(They
may appear four times if the third and fourth are separated by a smaller value, such as XXXIX.)
"D", "L", and "V" can never be repeated.
• "I" can be subtracted from "V" and "X" only. "X" can be subtracted from "L" and "C" only. "C"
can
be subtracted from "D" and "M" only. "V", "L", and "D" can never be subtracted.
• Only one small-value symbol may be subtracted from any large-value symbol.
• A number written in [16]Arabic numerals can be broken into digits. For example, 1903 is
composed of 1, 9, 0, and 3. To write the Roman numeral, each of the non-zero digits should
be
treated separately. In the above example, 1,000 = M, 900 = CM, and 3 = III. Therefore, 1903 =
MCMIII.
(Source: Wikipedia ( [17]http://en.wikipedia.org/wiki/Roman_numerals)
Input to your program consists of lines of text detailing your notes on the conversion between
intergalactic units and roman numerals.
You are expected to handle invalid queries appropriately.

Test input:
- glob is I
- prok is V
- pish is X
- tegj is L
- glob glob Silver is 34 Credits
- glob prok Gold is 57800 Credits
- pish pish Iron is 3910 Credits
- how much is pish tegj glob glob ?
- how many Credits is glob prok Silver ?
- how many Credits is glob prok Gold ?
- how many Credits is glob prok Iron ?
- how much wood could a woodchuck chuck if a woodchuck could chuck wood?

Test Output:

- pish tegj glob glob is 42
- glob prok Silver is 68 Credits
- glob prok Gold is 57800 Credits
- glob prok Iron is 782 Credits
- I have no idea what you are talking about

##### Outcomes
- Did you learn anything?
- What problems did you run into?


### Day 3

#### Text processing

##### Generating ngrams
Write a python script that will do the following, given a text file:
- split the text on whitespace
- convert all text to lowercase
- choose a word boundary
- add word boundary to start and end of each word
- generate unigrams, bigrams and trigrams for each word. (1-grams,2-grams,3-grams)
- store words with their associated ngrams appropriately for easy access
- ensure that your code allows for a text file to be provided via the command line
- test for errors and apply appropriate error handling
- test your code on a small text file that you can manually validate to ensure that everything works as expected

##### Frequency counts
After generating your ngrams, create a python script that will:
- generate a frequency count of each word in the file
- generate a frequency count of each ngram in the file as well (for n=1,2,3,4)
- write your output to the appropriate files

## Topic 3: REST web services

### Day 4

### Day 5

## Topic 4: Android

### Day 6

### Day 7
