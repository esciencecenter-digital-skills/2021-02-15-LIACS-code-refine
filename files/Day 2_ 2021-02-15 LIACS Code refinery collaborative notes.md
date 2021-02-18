# Day 2: 2021-02-15 LIACS Code refinery collaborative notes

Day 1: https://hackmd.io/@svenvanderburg/ryz-zgP1d/edit
Day 2: https://hackmd.io/@svenvanderburg/SkB6D43Ju/edit
Day 3: https://hackmd.io/@svenvanderburg/SkM7ON2y_/edit
 
## 👮Code of Conduct
Participants are expected to follow those guidelines:
* Use welcoming and inclusive language
* Be respectful of different viewpoints and experiences
* Gracefully accept constructive criticism
* Focus on what is best for the community
* Show courtesy and respect towards other community members

Contact one of us if you think those rules have been violated.

## 🧑‍⚖️ License
All content is publicly available under the Creative Commons AttributionLicense:https://creativecommons.org/licenses/by/4.0/

## 🙋Getting help:
* icons below participants list:
  * go slower
  * go faster
  * when finished assigned task: ‘yes’ green tick icon
  * when could not finish the assigned task ‘no’ cross icon
* to ask a question, type /hand in the chat window
* to get help, type /help in the chat window
* you can ask questions in the document or chat window and helpers will try to help you

## 🎥 Instructions for working with zoom
https://tinyurl.com/zoom-in-workshop

## 🖥 Workshop website
https://escience-academy.github.io/2021-02-15-LIACS-code-refine/

## 🛠 Setup
https://escience-academy.github.io/2021-02-15-LIACS-code-refine/#setup

## 🧑‍🏫 Instructors
Sven, Jens

## 🧑‍🙋 Helpers
Victor, Alessio, Mateusz, Sander, Jeremy, Daniela

## 🗓️ Agenda
See https://escience-academy.github.io/2021-02-15-LIACS-code-refine/#schedule

## 🧠 Collaborative Notes


### Icebreaker

**If you were stuck with a filter in zoom/whatever_the_chat. What this filter should be?**

* Marie: a Cthuluh face :+1:
* Richard: I would show a nice place in the world, sunshine, good weather, ocean ... nice laptop on my lap, a Dell 2-in-1! Or a small Quantum computer!
* Mateusz: Fuji mountain
* Tom: myself - a couple of years.
* Maedeh : Ocean with the sound of waves and birds
* A cat would be ok. ;)
* Jens: the face of Sven, it would confuse people. :+1: :+1: :+1:
* Anna: Munch's The Scream, to express how I feel about my PhD and future  :+1: :scream: :+1: :+1: (or Ada Lovelace ;) )
* Bram: If also a voice filter, David Attenborough :100: 
* Yali: Elf ears.
* Ioanna: Sunglasses and mojito, beach on the background
* Reza: Richard Feynman likes pasta! :P :+1:
* Nathan: Groucho Marx mask :+1: 
* Solomiia: The Sorting Hat from HP
* Clown nose
* Charles: Smiley that changes depending on my expression during the meeting 
* Tanjona: Minion eye 
* Victor: Party hat !! 🥳🥳🥳
* Jeremie: Hal 9000. With a voice filter also. :+1: 
* Anne: Retro star trek filter
* Marios: Darth Vader :+1: :+1:


### Recap: Collaboration as part of Software Engineering

After the icebreaker Jens provides pointers on the reason behind teaching/learning software engineering skills.

> "Software engineering is programming integrated over time"

Tools and skills useful for long-term code maintenance:

* Versioning
* Code reviews
* Testing
* Documentation

There are different ways to organize your repositories. Usually it depends on the purpose of the repository: is it just for you? for a small group? the whole world?
Usually with more people collaborating you have more *branches*.
The *master*/*main* branch is often left almost untouched when collaborating with many people, and only approved and thoroughly tested commits end up in this branch; most of the development happens in (short-lived) *feature branches*.

Code reviews are useful for many reasons, they improve software quality but are also tools for learning: reviewing code from more experienced programmers is a powerful tool to improve your own programming skills.

> "Code reviews are like giving feedback" - Jens

The more the code will *last*, the more software engineering tools and skills should be involved in the development process.
The more people will *collaborate* on the project, the more software engineering tools and skills should be involved in the development process.


### Exercise 1: Discussion

- Why do you write tests/ Why do you not write tests?
- Write reasons into the collabroative document?

#### Answers:

* Testing is quite important!
* I don't do testing, just not familiar with it yet :) And affraid that it will take too much time.
* I do testing -> because my full code takes a couple of days to run so I need each part to be tested before. I don't do unit testing (though I think I might need it) -> because it feels like 'too much', it takes a lot of time I think.
* I don't do testing
* I probably should, but to be honest, I hardly do, I just run the main file ao, I just run the main file 
* I test code in the sense that I evaluate output of my code/ functions but once it works I often get rid of that testing part (prob there are better approaches) and I test with small parts of data first before running it for all.
* I do some testing, mostly for 'library' type code that does not change frequently but *really* needs to work
* I'm not sure if this can be considered as a test, but I normally work with a huge dataset, when designing an algorithm, I check the result with a very small part of the dataset and make sure if the algorithm mathematically is correct. Is it testing?
* You can use TDD = test driven development: first write code for tests and then write the code itself. In some way you need to test it. Better make the test upfront! Further you can use test vectors to test larger pieces of code. For example data set can be used as test vector, you evaluate the known outcome.
    * You *can* use TDD, but **DO** you actually do it? ;) If I get a space of my peers or managers ... need to convince them!
    * Agree, getting the timing right is an issue. You want to run quick experiments to see if your ideas are somewhat useful -- the actual development/making experiments stable comes later.
* I do not think I do testing. Or maybe I do not understand what is testing. 
* Script files that run the code and I check if I get the expected results (or crash). In research we often try stuff and the time constraint is high and the proper testing is not done.
* I test because it save me time: I am much less likely to break old (functioning) code by new additions.
* Tests are also useful for "Expectation management" -> you need to know where you are going with your code to write good tests which helps planning development (and yes I wish I would actually stick to this)
* To help with my sanity checks. If the input doesn't generate the expected output, testing helps to narrow down the problem.
* All my testsing is centered around visual reviewing of the adequacy of the results. No real tests are made, as don't really know how to make them for my type of code/project;
* I realized I do quite a lot and just save them on a back burner folder with the intention that they will be so useful for the future, I struggle to keep track. I would like to find a methodology to make it easier, cleaner and reusable
* I do it but it's far too ad-hoc: basically write a new function, check if it does what I expect, then never look at it again until something else inexplicably breaks
* I use tests to make sure that contributions do not break standard use cases of a code 
* I see the value of testing but I do not think I do it in a systematic fashion. I do test my functions and inspect the output. I also use testing to figure out bugs or incorrect output in my code.
 

### Testing

Why tests?

* Tests help preserving expected functionality
* Tests help users of your code
* Tests help other developers
* Tests help manage complexity

We don't we use the equality operator to test floating point numbers?
It is because of the way computers represent floating point numbers.


### Exercise 2: Testing locally

Please use https://coderefinery.github.io/testing/pytest/


### Automated Testing

CI: Continuous Integration
CD: Continuous Deployment

Using CI it is possible to have *pipelines* (e.g. a series of commands) executed on the GitLab/GitHub servers after you commit code.
Useful for things such as testing your code before accepting a commit or merge request.
Also useful to check your build process, or code correctness, on different platforms, architectures, compilers.


### Exercise 3: Testing using Gitlab CI till 11:30

See https://coderefinery.github.io/testing/gitlab-ci/

Note: the instruction 'Select “CI/CD” from your Gitlab repository page' means the 'Add CI/CD' button above the list of files, not the tab in the sidebar. Also 'Verify that the test suite now fails on the “Actions” tab.' should point to the 'CI/CD -> Pipelines' tab ("Actions" is GitHub terminology)

### Break until 11:50

### QUESTION: are you a 1st year PhD student at LIACS? Add your name so we can count.
Answer: 7 out of ~30


### Modular code development

#### What is modular code development for you?

* Functional approach, clear input and output and little state modifications.
* Reusable code chunks
* writing code in steps :+1: 
* Writing code such that small independent pieces of functionality are separate functions with clear names. Sometimes I do this 'bottom-up', i.e. first come up with small functions and combine them later, or 'top-down' i.e. writing long functions first and then breaking out smaller pieces, e.g. when they are repeated.
* breaking code into little, useful chunks :+1: :+1: 
* Always have a working prototype? (I have no clue)
* Write pieces of codes such that they don't depend to much from each other, and that I can easily reuse a part in an other project. (API like code)
* coding in different blocks that can operate independently
* Being able to (conveniently, i.e., in chunks or blocks) swap out any internal functionality without changing the input-output structure or breaking the rest of the code
* Using object-oriented programming and functions
* Break code into parts, such that each part are independant.
* One function - one task; One class - one problem; No big unseparable blocks of code; New features should be added easily; 
* A nice structure where each component has its own responsibility and (abstract) interface. 
* Clearly defined roles for each functions/modules. Low interdependance 
* Each function should be responsible for a specific task, having few dependencies on other functions
* Being able to work on a part of the code without having to understanding the whole
* Code subdivided into smaller parts to help reusability, readibility, etc
* Modular code development is building code in separate, largely interchangable sections, or “modules”.

Modularity is not always easy, it may happen than writing modular code the development time will grow instead of shorten.
Sometimes it is not necessary to have good looking modular code if the code is to be abandoned soon.
Modular code is an extra step, it adds a *cost* to your development process.

Properties of good bulding blocks of modular code:

* Clear interface
* Good name
* Testable
* No side effects
* No state

### Follow along 1:

- Propose ways to improve the code by addding them to the collaborative document. 

#### Suggestions for Jens

* :heavy_check_mark: Make the output file name dynamic, not 25.png but `str(num_measurements)` something
    * `f'{num_measurements}.png'` is the most modern way do to this (Python >= 3.6)
* :heavy_check_mark: Make it into a function that takes the num of measurements as input
* :heavy_check_mark: Use numpy to calculate the mean (or even better: pandas)  :+1:
    * You can use pandas to calculate the mean with `temperatures.mean()` :+1:
    * Why? that adds a dependency you can easily avoid?
        * why? because writing something as simple as the *mean* is actually hard :)
        * and invites errors
* Related: add a file with all dependencies? 
* Read the specific column that you like by its index, not the column name
* :heavy_check_mark: Make a function that accepts the `num_measurement`
* you could start writing a test 
* definition?
* Is it a good idea to have everything in one line BTW? I'm really not fan of this method.
* Make all constants variables? Define them in the beginning. Configuration class with all parameters? Filename, texts, color of plot ...
* :heavy_check_mark: Create a read_file function 
* :heavy_check_mark: Create a plot_temperature function 
* Create default values in your function to create versatility: for example in readfile you could add a column = "Air temperature (degC)".
* :heavy_check_mark: Plot should have a title, axis labels, legend :+1:
* If you run this code for a different measurement value, you have to change the file name, that's why I suggested to use the dynamic file name which is using the num_measurements inside
* use column name as an argument; it may be different in an other file
* :heavy_check_mark: Add `if __name__ == '__main__':` clause
* :heavy_check_mark: Add optional commandline arguments using `argparse` you can also use sys.args
Example using Python's builtin [`argparse`](https://docs.python.org/3/library/argparse.html#module-argparse) module:
```
parser = argparse.ArgumentParser()
parser.add_argument('--num-measurements', type=int)
# ... 
# add other arguments here
# ...
args = parser.parse_args()
# use given value as `args.num_measurements`
```


### Feedback for today
Just add your name (or not if you want to give anonymous feedback) with your feedback for today!

#### What went well?
* Good hands-on examples.
* I thought that the code testing was really helpful as I thought it would be much more difficult. Definitely going to try to incorporate it into my workflow. 
* the last part was nice, refactoring code
* good explanation with interative way
* I found the topics we covered today well chosen. I also liked the interactive and collaborative exercises
* Challenging exercises, found the topics covered interesting (again, liked the set up of interactive/ collaborative part and presentation)
* Nice pace, good explanations
* good skill level needed/achieved was not too slow/fast
* It really worked at making me think that testing doesn't take **that** much time in the end
* I really enjoyed this, time flew! great programme covered
* nice explanations, good topcs covered, exercise on code improvement was very helpful, nice interaction
* I found the pace much better than yesterday (yesterday was a bit slow for me) :+1: :+1: 
* I found the slides good, the topics helped me think about how to organise my code etc.


#### What could be improved?
* Third excercise was a bit unclear at the beginning
* The continous integration exercise was too long and a bit unclear.
* Time could be managed a little more strictly so that we could have spent some more time on modular code.
* I actually would have liked to spent less time on modular code ;)
* Little time for excersis 3, and less clear what is going on. 
* Perhaps sharing the exercises before to set up a few files would help with 'jumping' directly to do the exercises with the other people
* Time was not enough for exo 3. :+1:
* It would be great if you could find a collaborative document tool that actually works when 10+ ppl are editing it at the same time. I stopped contributing at some point because of the mess. :+1: :+1:



## Q&A

- Is [pytest-cpp](https://pypi.org/project/pytest-cpp/) a useful tool for automating tests when you're also working in C++? Does anybody have experience with this?
    - Alessio: many C++ projects use this: [Google Test](https://github.com/google/googletest)
    - there is also catch2 and boost.test which are quite common.
- And is there a good automated testing tool for Scala that anybody knows of?
    - they are called testing frameworks, but I do not know which one is popular in Scala, but there is one for sure. 
- Do people keep local archives of useful code chunks? How do you organize those? :+1:
    - gist.github.com is a nice way to store snippets of code, both available for public and private.



## 📚 Resources

* [GitLab Flow](https://docs.gitlab.com/ee/topics/gitlab_flow.html)
* [GitHub Flow](https://guides.github.com/introduction/flow/)
* [Netherlands eScience Center's guide: Version Control](https://guide.esciencecenter.nl/#/best_practices/version_control)
* [Netherlands eScience Center's guide: Code Review](https://guide.esciencecenter.nl/#/best_practices/code_review)
* [What Every Computer Scientist Should Know About Floating-Point Arithmetic](https://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html)
* [Comparing floating point numbers](https://stackoverflow.com/questions/4915462/how-should-i-do-floating-point-comparison)
* Talk on YouTube: ["Naming is Hard: Let's do Better"](https://www.youtube.com/watch?v=MBRoCdtZOYg&ab_channel=CppCon)
* Book: [Clean Code](https://www.goodreads.com/book/show/3735293-clean-code)


## Ideas for "integration exercises"

Check this list of "homework exercises" for something that you can/want to integrate into your daily work

* Ask the PI of your project which licence you should use for your code
* Find out if the members of your research group have a liacs gitlab account and what kind of projects they are sharing there
* Ask one of your group members if you can review their code. Spend as much time as you want on this review - try giving a couple of positive feedback points and a couple of points that can be improved.
* Do you have a project on github? Check this exercise and use github-actions to automatically run tests on your project  https://coderefinery.github.io/testing/gh-actions/
* Show a colleague how to set up a read-the-docs for their project
* Open a merge request on a colleague's project (something basic: suggest a licence, contribute to the README) - be kind, especially if it is someone who didnt attend this workshop
* Ask a colleague if they can give you feedback on your project; maybe even by opening an issue on gitlab and assigning them to that issue


## Ideas for the call-back session

* How can we motivate each other to code review?
* How did you organize code review in your group?


## List of escience courses

https://escience-academy.github.io
