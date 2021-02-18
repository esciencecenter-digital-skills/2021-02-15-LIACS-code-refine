# Day 3: 2021-02-15 LIACS Code refinery collaborative notes

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
* 'Reactions':
  * go slower
  * go faster
* when finished assigned task: use :heavy_check_mark: behind your name in this doc
* when could not finish the assigned task use :negative_squared_cross_mark:  behind your name in this doc
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
What is your favourite/least favourite documentation for software? Why?
* Anna: least favourite is `matplotlib`, at least 1/3 of it seems to be either missing or out of date? :+1:
* Anne: least favourite is no documentation. Favourite is pandas. Least favourite is maybe actually Huggingface (very confusing)
* Bram: I only use docstrings for Python (Google style). I like the looks of Sphinx/Read the docs, but have never used it. Least favorite is Markdown documentation. (Docstring count as documentation?)
* Can: pandas.
* Charles: Worst is None or very little. Best: sklearn.
* Daniela: Do I read the docs?? Fav Doc: R/ggplot2 has good examples I feel; Least Fav Doc: the one for my own package, because it is not complete and didnt figure out how to add examples yet
* Diederick: The style used in R is very intuitive when used correctly 
* Duc: jupyter notebook. I can see code, text, figure and results in the document.
* Duc Anh
* Erick : Jupyter Notebook, stackoverflow
* Feibo
* Gerrit Jan: Best: Pandas (very Googlable and extensive) :+1: Worst: Plotly (https://plotly.com/python/). Not every class/ function is documented.
* Ioanna: Numpy
* Irene: pandas, stackoverflow, beautifulsoup (good), 
* Iris: best when a tutorial paper is attached to it (refering to R packages such as mokken), least favorite when it cannot be found or it only has a useless example :+1:
* Jeremie -- Best: Numpy, Pandas, Arch Wiki, in general a good software includes good documentation. Bad: matplotlib even is the software is used a lot the doc is confusing, but it's becoming better.
* Laurens -- Least favourite: snappy (non-existent), favourite: maybe sklearn? :+1: :sun_with_face: 
* Maedeh: A lot of them, recently, I used Bokeh for some inetractive plots and was super handy + Stackoverflow
* Marie -- favorite: a few working examples for each function (I usually like python documentation) + comments in the code -- least favorite: extensive comments in the code that make it hard to read :+1:
* Marieke
* Marios: No documentation (least favourite), ReadTheDocs type of documentation (favourite) :+1: 
* Matthias
* Mike
* Nathan Best: Most LaTeX packages; Worst: Most Atom packages
* Nuno 
* Rens
* Reza
* Richard: https://www.doxygen.nl/index.html or other software which generates documentation from the source code. In that case you are always aligned with the source code. Other software for example Enterprise Architect for UML designs from and to the source code. 
* Rohola Don't have any documentation for codes, add comments best option would be <- see above!
* https://readthedocs.org/ website
* Ross
* Sander -- favorite: Numpy/Matplotlib: very extensive, can almost always find what I need, or Python's documentation, also very nice. And of course the amazing documentation for my own package: [mf2](https://mf2.readthedocs.io/en/latest/?badge=latest)
* Solomiia -- favourite: Sklearn - nice, extensive documentation with loads of examples.
* Sven: Favourite: Scikitlearn (it's very well written, and saves time) Worst: rdflib (costs a lot of time searching what I need)
* Tanjona: I don't use documentation. Most of the time. Just google.
* Thomas: favourite: numpy is good. numpy is good. Least favourite: my own code. 
* Tom : Favourite: Numpy, very elaborate. :+1:  
* Xue
* Yash
* Yali: no, I didn't pay attention to documentation. I don't feel they are very useful. Normally, I google it when I have problems. :+1: 
* Ying
* Zahra


### Documentations 

#### Wishlist. What is important? Why it is important? 

* So people can understand and use my code -> user
* So people can contribute to my code -> developer
* So people can build on or adapt my code -> research
* Show people the features of your code, show what you can do with it, the potential.

*A good documentation saves time, for you, for the users, for debugging.*

### Exercise 1: Let’s discuss some examples 

Look at the documentation of 1 of these:

* https://github.com/fair-workflows/fairworkflows (even breakout rooms)
* https://github.com/NLeSC/mcfly (uneven breakout rooms)

What do you like or don’t like about documentation? Discuss in your group, 1 person takes notes in collab doc.

What do you like or don’t like about documentation of each? Discuss in your group, 1 person takes notes in collab doc. 

#### Notes on documentations

##### Sven One (mcfly)
* Very complete documentation
* There could be an installation guide for users other than Windows.
* Proving an example would be a nice practice and start for the user
* A bit difficult to find different topics -> it can be organized in a better layout

##### Sander One (mcfly)
* It looks short and that is motivating. 
* Confusing -> pointed in 3 different directions
* Good to see it has both User Manual and technical documentation.

##### Victor One (fairworkflows)
* Good: Good overview, short, clean, demo in interactive notebook
* Possible improvement: A ReadTheDocs as a separate page is more organized? How do you find the repository from Google?

##### Jeremie One (mcfly)
* Improvements: No comments in the tests, some functions in user manual are rather short 
* Good: jupyter tutorial, installation on Windows included, seperate page on what the data input should look like
* Good: Nice installation explanations
* Bad: not much comments in code


##### Sven Two (fairworkflows)
* Like the badges, not very long, no table of content of quick links
* link to relevant example is good!
* it's not clear what it's for, what is FAIR? If I don't have the background info, I don't really know what I'm looking at?
* seems like it would be really useful for someone who was looking for it, but I think it needs to section just to explain shortly what this is for without assumptions of reader's knowledge
* lack of more in-depth documentation of the functions

##### Sander Two (fairworkflows)
* :+1: Quick-start guide
* :+1: Many examples
* :+1: Link to paper/citing information provided early on (although a bibtex entry would be even better)
* :+1: Good docstrings within the code itself
* :-1: The full documentation (e.g. list of available functions) is not linked
* 

##### Victor Two (fairworkflows)
* Overview is good
* Quick start is good
* Presence of Jupyter NB with example is good
* But how how the NB looks like is not good (examples are not tested and return errors)
* In the example NB thre is no comments is the code, so it ake difficult to understand what's going on
* It has related publication  - it is nice to see how the project can be used


##### Jeremie Two
* fairworkflows
    * Nice Python notebook, but it does contain errors
    * Using Markdown is limiting in creating efficient documentation
    * only README - which is a good start but doesnt give much of an overview/ you have to search and scroll to find the inof you need
* mcfly
    * I like the Read the Docs interface

### Tutorials -- How-to Guides -- Explanation -- Reference

Tutorials -> Learning-oriented
How-To guides -> Problem-oriented
Explanation -> Understanding
Reference -> Information-oriented


### Wishlist for good documentation
* a quickstart guide (including information instructions)
* For end users + developers: Tutorials, explanation, guides, references
* clear guide document with examples.
* Last confirmed working date, especially for languages/packages that tend to depreciate things often... 
* Keeping the same format, documentation should be well-stated and with small representative examples
* Very practical steps to use the code without adaptation (including what the input should look like)
* Link to relevant publication belonging to the code (this is missing far too often) so that you know what to cite and what to read for more explanation of how this method fits in the field
* Maybe being honest about what DOESNT work (yet) :+1:
* search function/ quick way to access content 
* Relation to existing work out there


### Documentation


* Good documentation *for* humans is written *by* humans.
* It is important to document code
* It can take multiple form depending on the project and intention
* Should follow the version of the code

### Kind of documentation

* Inline comments/docstrings
    * Versioned automatically with your code, but users don't always want to search through your function documentation to find what they want
* README
    * Can also be versioned, but required source code access
* Wiki 
    * Low barrier to contribute and edit, but not versioned
* LaTeX/PDF
* HTML static site generators
    * Automatic generation
    * Can follow the code


### Ready for takeoff :heavy_check_mark::
* Anna :heavy_check_mark:
* Anne :heavy_check_mark: 
* Bram :heavy_check_mark:
* Can :heavy_check_mark:
* Charles :heavy_check_mark:
* Daniela :heavy_check_mark: 
* Diederick :heavy_check_mark: 
* Duc
* Duc Anh :heavy_check_mark: 
* Erick :heavy_check_mark:
* Gerrit Jan: :heavy_check_mark:
* Ioanna :heavy_check_mark: 
* Irene :heavy_check_mark:
* Iris :heavy_check_mark: 
* Jeremie :heavy_check_mark: 
* Laurens :heavy_check_mark: 
* Maedeh :heavy_check_mark: 
* Marios :heavy_check_mark: 
    * Question: I have a newer version of Sphinx probably it also made a Makefile file. What does that do? It also asked  if I wanted e.g., githubpages. 
        * The Makefile can be used to build the documentation for different formats (instead of sphinx-build). (make html, make pdf, and nowadays maybe also make githubpages), it fixes the sphinx versions.
          This makefile is not a new feature but has been present for a while. 
* Nathan :heavy_check_mark: 
* Reza
* Richard How to install Sphinx??
    *  It comes with anaconda / use >pip install sphinx <- that works for me on windows and miniconda3
* Rohola :heavy_check_mark: 
* Sander :heavy_check_mark: 
* Solomiia :heavy_check_mark: 
* Tanjona
* Thomas :heavy_check_mark: 
* Tom :heavy_check_mark:
* Yali :heavy_check_mark:
* Zahra

### Sphinx

Creating sphinx initial document.
```bash=
$ mkdir doc-example
$ cd doc-example
$ sphinx-quickstart
```
Defaults are good. A bunch of files should have been created. 

To see the files

```bash=
$ ls -l 
```
or for Windows 
```bash=
$ dir
```

Take a look at the file `index.rst`. It is the entry point of the documentation.

Add a new entry in the table of content (toc) for a `wishlist`. Be careful with the spacing.

```
.. Documentation test documentation master file, created by
   sphinx-quickstart on Wed Feb 17 10:05:31 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Documentation test's documentation!
==============================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   whislist



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
```

Create a new file `whislist.rst` that will be the page for the wishlist documention.
```
Our whislist for documentation
==============================


Good documentation needs
------------------------

* Good documentation *for* humans is written *by* humans.
* It is important to document code
* It can take multiple form depending on the project and intention
* Should follow the version of the code

* A list can have sublist
	* Like this
    
    
Documentation use reStructuredText 
----------------------------------

`reStructuredText primer <https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html>`_
```


Build the sphinx documentation
```bash=
$ sphinx-build . _build
```

The documentation will be created under the directory `_build`. The file `_build/index.html` is the entry point of the documentation.


### Make it beautiful!!

Edit `conf.py` and change the theme.
```
# -- Options for HTML output -------------------------------------------------

# The theme to use for HTML and HTML Help pages.  See the documentation for
# a list of builtin themes.
#
#html_theme = 'alabaster'
html_theme = 'sphinx_rtd_theme'
```
and build again.
```bash=
$ sphinx-build . _build
```
If the theme is not present, you may need to install `sphinx_rtd_theme`.
```bash=
$ pip install sphinx_rtd_theme
```
And build again.


### Exercise 2: Add content to your example documentation 

* Add an entry below `wishlist` labeled `whydocumentation` to the `index.rst` file. 
* Create a file `whydocumentation.rst` in the same directory as your `wishlist.rst` file. 
* Add some content to `whydocumentation`, rebuild with sphinx-build, and refresh the browser to look at the results 
* Add a checkmark in the list below. 

* Sander - One
   * Iris :heavy_check_mark: 
   * Tanjona: :heavy_check_mark: 
* Sander - Two
   * Laurens :heavy_check_mark: 
   * Diederick :heavy_check_mark: 
* Jeremie - One :heavy_check_mark:
   * Anne :heavy_check_mark: 
   * GJ: :heavy_check_mark: 
* Jeremie - Two :heavy_check_mark:
   * Anna :heavy_check_mark:
   * Bram :heavy_check_mark:
   * Erick :heavy_check_mark:
* Sven - One
   * Can :heavy_check_mark:
   * Tom :heavy_check_mark:
   * Ioanna :heavy_check_mark: 
* Sven - Two
   * Charles :heavy_check_mark: 
   * Duc Anh :heavy_check_mark:
* Victor - One
   * Thomas :heavy_check_mark:
   * Irene: :heavy_check_mark:
   * Rohola: :heavy_check_mark:
* Victor - Two
   * Solomiia: :heavy_check_mark:
   * Marios: :heavy_check_mark: 
   * Maedeh: :heavy_check_mark: 


#### Optional 2b: play around with rst syntax in your newly created documentation: 
See 'Experiment with the following RST syntax' in [this link](https://coderefinery.github.io/documentation/04-sphinx/#exercise-2-add-content-to-your-example-documentation)


### Exercise 3: Read the docs

* Do exercise as described in https://svenvanderburg.github.io/documentation/05-rtd/ 
* Past a link to your documentation website in the collab

#### Links:
* https://gj-word-count.readthedocs.io/en/latest/
* https://mousscharles-word-count.readthedocs.io/en/latest/?
* https://tom-word-count.readthedocs.io/en/latest/
* http://latower-word-count.readthedocs.io
* https://annedirkson-word-count.readthedocs.io/en/latest/
* https://brenting-word-count.readthedocs.io
* https://iy-word-count.readthedocs.io/en/latest/
* https://ioannapap-word-count.readthedocs.io/en/latest/
* https://maedeh-word-count.readthedocs.io/en/latest/
* https://marioskef-word-count.readthedocs.io/en/latest/
* https://laurens-word-count.readthedocs.io/en/latest/
* https://hosseinir-word-count.readthedocs.io/en/latest/
* https://solak24.readthedocs.io/en/latest/
* https://yali-word-count.readthedocs.io/en/latest/


## Bring Your Own Code lesson 

### Exercise 1: Bring Your Own Code
    * Question: When are we supposed to be back or go on a break?
In breakout rooms:

Think about what you have learned in this workshop and apply it to one of your own projects, for example:
* Move your code to a gitlab repository
* Add tests or improve existing tests
* Setup automated testing
* Setup documentation using read-the-docs

Ask questions to your fellow learners in the breakout room or be sure to ask for help from one of the helpers!

## Feedback for today
Just add your name (or not if you want to give anonymous feedback) with your feedback for today!

#### What went well:
* Duc: I really like the workshop and will follow the upcoming workshops.
* The presentation of the documentation was interesting.
* The discussion and pointers for using Sphinx and in general documentation was great!
* Sphinx was really new for me, but I think after the workshopI will be able to ue it in the future  - that is great!
* documentation part was really helpful. Also to see how this is done. 
* The time for helping those who are left behind.
#### What could be improved:
* The Sphinx was interesting, but there are many Wiki out there.
* It could maybe be helpful to do the introduction/explanation of sphinx in seperate breakouts so that they are better suited to the specific groups.
* The breakouts today were less usefull/less organised then previously
* I didn't really understand what was the purpose of bring your own code section
* Bring your own code part is difficult in this setting. 
* Today was fast.
* I see the importance of documentation, but I doubt the Sfynx and ReadTheDocs is really relevant for researchers. Usually only a few other researchers find your code, and they have already read the paper, so inline commenting suffices then. I have never seen code to reproduce a paper with a full ReadTheDocs :)


## Post workshop survey
https://www.surveymonkey.com/r/N3KSRQ9

## 📚 Resources

* Yesterday's presentation 1: https://github.com/escience-academy/2021-02-15-LIACS-code-refine/blob/gh-pages/files/SoftwareEngineering.pdf
* Yesterday's presentation 2: https://github.com/coderefinery/modular-code-development/blob/master/modular-code.svg
* An introduction to .rst files: https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html
* Generating doc automatically form code: https://www.sphinx-doc.org/en/master/usage/extensions/autodoc.html
* Follow [these instructions](https://docs.gitlab.com/ee/user/project/pages/getting_started/pages_forked_sample_project.html) for creating a gitlab pages website
* [The bare minimum of best practices every software project should do](https://guide.esciencecenter.nl/#/best_practices/checklist)


## :question: Q&A

* We discussed different types of documentation (As in: Tutorials -- How-to Guides -- Explanation -- Reference). Which type of documentation would you use `sphinx-doc` for? (and why?)
    * You can use Sphinx for all four types! The reference documentation can be auto-generated from the docstrings in your code, and you can write rst files for tutorials, how-to-guides and explanations.
* And more generally: why are we using `sphinx`?
    * `sphinx` has many built-in features for making nice and interactive HTML documentation for code, while only having to write fairly plain text (=.rst) files, and is currently the most popular documentation framework for Python.
    * Even if you have automated documentation with `doxygen`, you have to go through `sphinx` to get it on readthedocs (see e.g., [this explanation](https://stackoverflow.com/questions/36064976/using-doxygen-in-read-the-docs)).
* Can a link to todays presentations also be provided?

## ✅ Post Workshop Survey
https://www.surveymonkey.com/r/N3KSRQ9
